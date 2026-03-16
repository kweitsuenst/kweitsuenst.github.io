
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mission International School</title>
<style>
html { font-size: clamp(14px, 2vw, 22px); }
h1 { font-size: clamp(24px, 5vw, 48px); }
h2, h3 { font-size: clamp(18px, 4vw, 28px); }
body{ font-family:'Segoe UI',sans-serif; background:#123544; color:white; padding:30px 20px; }
input, select, button{ padding:10px; margin-top:5px; margin-bottom:15px; width:100%; max-width:400px; border-radius:5px; border:none; }
button{ background:#2ecc71; color:white; cursor:pointer; }
button:hover{ background:#27ae60; }
</style>
</head>
<body>

<h1>Mission International School</h1>
<h2>Upload your file with your name and respective class</h2>
<h3>Class 3–5: .sb3 file (PictoBlox)</h3>
<h3>Class 6: .py file (Python)</h3>

<form id="quizForm" enctype="multipart/form-data">
<label>Your Name:</label>
<input type="text" name="name" required>
<br></br>
<label>Select Class:</label>
<select name="class" id="class" required>
<option value="">--Select Class--</option>
<option value="3A">Class 3A</option>
<option value="3B">Class 3B</option>
<option value="3C">Class 3C</option>
<option value="4A">Class 4A</option>
<option value="4B">Class 4B</option>
<option value="4C">Class 4C</option>
<option value="5A">Class 5A</option>
<option value="5B">Class 5B</option>
<option value="5C">Class 5C</option>
<option value="6A">Class 6A</option>
<option value="6B">Class 6B</option>
<option value="6C">Class 6C</option>
</select>
<br></br>
<label>Upload File:</label>
<input type="file" id="file" name="file" required>
<br></br>
<button type="submit">Submit</button>
</form>

<p id="message"></p>

<script>
document.getElementById("quizForm").addEventListener("submit", async function(event){
    event.preventDefault();
    const form = event.target;
    const fileInput = document.getElementById("file");
    const selectedClass = form.class.value;
    const file = fileInput.files[0];

    if(!file){
        alert("Please select a file.");
        return;
    }

    const fileName = file.name.toLowerCase();
    const classNumber = selectedClass.charAt(0);

    // Validate file type
    if(classNumber === "6" && !fileName.endsWith(".py")){
        alert("Class 6 must upload a Python (.py) file.");
        return;
    } else if(["3","4","5"].includes(classNumber) && !fileName.endsWith(".sb3")){
        alert("Classes 3–5 must upload a PictoBlox (.sb3) file.");
        return;
    }

    const name = form.name.value.trim().toLowerCase().replace(/\s+/g,"_");
    const uniqueKey = `submission_${name}_${selectedClass}`;

    if(localStorage.getItem(uniqueKey)){
        alert("You have already submitted. Only one submission allowed.");
        return;
    }

    const submitBtn = form.querySelector("button");
    submitBtn.disabled = true;

    const formData = new FormData(form);

    try{
        const response = await fetch("https://kweitsuenst.pythonanywhere.com/submit_quiz", {
            method: "POST",
            body: formData
        });
        const result = await response.json();

        if(!response.ok){
            throw new Error(result.error || "Server error");
        }

        localStorage.setItem(uniqueKey,"submitted");
        document.getElementById("message").innerHTML = "✅ Submission successful!";
        form.reset();

    } catch(error){
        console.error(error);
        document.getElementById("message").innerHTML = "❌ Submission failed. Check console or server logs.";
    }

    submitBtn.disabled = false;
});
</script>

</body>
</html>
