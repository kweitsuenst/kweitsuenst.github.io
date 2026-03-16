<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 3 Artificial Intelligence Test</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
html { font-size: clamp(14px, 2vw, 22px); }
h1 { font-size: clamp(24px, 5vw, 48px); }
h2 { font-size: clamp(20px, 4vw, 36px); }
p, li, a, button { font-size: clamp(14px, 2vw, 20px); }
body {
    font-family: 'Segoe UI', sans-serif;
    background: #123544;
    color: white;
    padding: 30px 20px;
    animation: fadeIn 1.2s ease-out;
}
</style>
<body>
<h1>Class 4 Artificial Intelligence Test</h1>
<form id="quizForm">
<label for="name">Your Name:</label>
<input type="text" id="name" name="name" required><br><br>
<label for="class">Select Your Class:</label>
<select id="class" name="class" required>
<option value="">--Select Class--</option>
<option value="4A">Class 4A</option>
<option value="4B">Class 4B</option>
<option value="4C">Class 4C</option>
</select><br><br>

<!-- 25 Questions with a, b, c values -->

        <p>1. What is a smart home?<br>
            <input type="radio" name="q1" value="a">A house with many rooms<br>
            <input type="radio" name="q1" value="b">A home that uses AI and technology to automate tasks<br>
            <input type="radio" name="q1" value="c">A house with colorful lights<br>
            <input type="radio" name="q1" value="d">A home built with expensive materials<br>
        </p>

        <p>2. Which device is commonly used in AI-powered smart homes?<br>
            <input type="radio" name="q2" value="a">Smart speakers<br>
            <input type="radio" name="q2" value="b">Televisions only<br>
            <input type="radio" name="q2" value="c">Typewriters<br>
            <input type="radio" name="q2" value="d">Chalkboards<br>
        </p>

        <p>3. What does a smart thermostat do?<br>
            <input type="radio" name="q3" value="a">Cooks food<br>
            <input type="radio" name="q3" value="b">Controls room temperature automatically<br>
            <input type="radio" name="q3" value="c">Plays music<br>
            <input type="radio" name="q3" value="d">Opens doors<br>
        </p>

        <p>4. AI in smart homes can help save ______.<br>
            <input type="radio" name="q4" value="a">Money and energy<br>
            <input type="radio" name="q4" value="b">Homework<br>
            <input type="radio" name="q4" value="c">Games<br>
            <input type="radio" name="q4" value="d">Shoes<br>
        </p>

        <p>5. Which AI assistant is used in many smart homes?<br>
            <input type="radio" name="q5" value="a">Siri<br>
            <input type="radio" name="q5" value="b">Robots in movies<br>
            <input type="radio" name="q5" value="c">Toy cars<br>
            <input type="radio" name="q5" value="d">Desktop wallpaper<br>
        </p>

        <p>6. Smart security cameras can ______.<br>
            <input type="radio" name="q6" value="a">Wash clothes<br>
            <input type="radio" name="q6" value="b">Detect movement and send alerts<br>
            <input type="radio" name="q6" value="c">Change wall colors<br>
            <input type="radio" name="q6" value="d">Bake food<br>
        </p>

        <p>7. What is voice recognition?<br>
            <input type="radio" name="q7" value="a">AI reading your mind<br>
            <input type="radio" name="q7" value="b">AI understanding and responding to speech<br>
            <input type="radio" name="q7" value="c">AI controlling your phone<br>
            <input type="radio" name="q7" value="d">AI turning off your device<br>
        </p>

        <p>8. Why are smart lights useful?<br>
            <input type="radio" name="q8" value="a">They taste good<br>
            <input type="radio" name="q8" value="b">They can change color and be controlled automatically<br>
            <input type="radio" name="q8" value="c">They clean floors<br>
            <input type="radio" name="q8" value="d">They play music<br>
        </p>

        <p>9. What does a smart door lock allow you to do?<br>
            <input type="radio" name="q9" value="a">Fly a drone<br>
            <input type="radio" name="q9" value="b">Lock or unlock your door remotely<br>
            <input type="radio" name="q9" value="c">Paint the wall<br>
            <input type="radio" name="q9" value="d">Watch cartoons<br>
        </p>

        <p>10. Which of these is an example of automation?<br>
            <input type="radio" name="q10" value="a">Lights turning on when motion is detected<br>
            <input type="radio" name="q10" value="b">Someone turning on the lights manually<br>
            <input type="radio" name="q10" value="c">Cooking food yourself<br>
            <input type="radio" name="q10" value="d">Washing dishes by hand<br>
        </p>

        <p>11. What does AI learn from in a smart home?<br>
            <input type="radio" name="q11" value="a">Magic<br>
            <input type="radio" name="q11" value="b">Patterns and user behaviour<br>
            <input type="radio" name="q11" value="c">Loud noises<br>
            <input type="radio" name="q11" value="d">Broken devices<br>
        </p>

        <p>12. A smart fridge can ______.<br>
            <input type="radio" name="q12" value="a">Play football<br>
            <input type="radio" name="q12" value="b">Tell you when food is running out<br>
            <input type="radio" name="q12" value="c">Fly like a drone<br>
            <input type="radio" name="q12" value="d">Drive a car<br>
        </p>

        <p>13. Why do smart homes improve safety?<br>
            <input type="radio" name="q13" value="a">AI makes loud noises<br>
            <input type="radio" name="q13" value="b">AI can detect dangerous situations<br>
            <input type="radio" name="q13" value="c">AI removes furniture<br>
            <input type="radio" name="q13" value="d">AI hides objects<br>
        </p>

        <p>14. What helps smart home devices connect and communicate?<br>
            <input type="radio" name="q14" value="a">Wi-Fi<br>
            <input type="radio" name="q14" value="b">Pencils<br>
            <input type="radio" name="q14" value="c">Paper<br>
            <input type="radio" name="q14" value="d">String<br>
        </p>

        <p>15. What is a benefit of using AI in smart homes?<br>
            <input type="radio" name="q15" value="a">More manual work<br>
            <input type="radio" name="q15" value="b">Convenience and comfort<br>
            <input type="radio" name="q15" value="c">No electricity<br>
            <input type="radio" name="q15" value="d">Dirty rooms<br>
        </p>

        <p>16. What is a smart speaker used for?<br>
            <input type="radio" name="q16" value="a">Watering plants<br>
            <input type="radio" name="q16" value="b">Giving voice commands and playing music<br>
            <input type="radio" name="q16" value="c">Washing clothes<br>
            <input type="radio" name="q16" value="d">Studying for exams<br>
        </p>

        <p>17. Which device uses AI to clean floors automatically?<br>
            <input type="radio" name="q17" value="a">Washing machine<br>
            <input type="radio" name="q17" value="b">Blender<br>
            <input type="radio" name="q17" value="c">Robot vacuum<br>
            <input type="radio" name="q17" value="d">Smart TV<br>
        </p>

        <p>18. Smart home AI can adjust lights based on ______.<br>
            <input type="radio" name="q18" value="a">Weather<br>
            <input type="radio" name="q18" value="b">Mood and activity<br>
            <input type="radio" name="q18" value="c">Random guessing<br>
            <input type="radio" name="q18" value="d">Coin tosses<br>
        </p>

        <p>19. Which word describes devices that connect together in a home?<br>
            <input type="radio" name="q19" value="a">Internet of Things (IoT)<br>
            <input type="radio" name="q19" value="b">Laundry<br>
            <input type="radio" name="q19" value="c">Wallpapers<br>
            <input type="radio" name="q19" value="d">Cartoons<br>
        </p>

        <p>20. What can a smart smoke detector do?<br>
            <input type="radio" name="q20" value="a">Dance<br>
            <input type="radio" name="q20" value="b">Send alerts when smoke is detected<br>
            <input type="radio" name="q20" value="c">Boil water<br>
            <input type="radio" name="q20" value="d">Draw pictures<br>
        </p>

        <p>21. Why is privacy important in smart homes?<br>
            <input type="radio" name="q21" value="a">Devices may store personal data<br>
            <input type="radio" name="q21" value="b">Lights become too bright<br>
            <input type="radio" name="q21" value="c">AI refuses to work<br>
            <input type="radio" name="q21" value="d">Doors won't open<br>
        </p>

        <p>22. AI in smart homes helps people who are ______.<br>
            <input type="radio" name="q22" value="a">Lazy only<br>
            <input type="radio" name="q22" value="b">Busy, elderly, or disabled<br>
            <input type="radio" name="q22" value="c">Tall<br>
            <input type="radio" name="q22" value="d">Good at sports<br>
        </p>

        <p>23. Smart home AI improves energy efficiency by ______.<br>
            <input type="radio" name="q23" value="a">Leaving devices on<br>
            <input type="radio" name="q23" value="b">Turning devices off when not needed<br>
            <input type="radio" name="q23" value="c">Adding more devices<br>
            <input type="radio" name="q23" value="d">Breaking appliances<br>
        </p>

        <p>24. What is the role of sensors in smart homes?<br>
            <input type="radio" name="q24" value="a">To sense danger, movement, or temperature<br>
            <input type="radio" name="q24" value="b">To make noise<br>
            <input type="radio" name="q24" value="c">To show videos<br>
            <input type="radio" name="q24" value="d">To clean windows<br>
        </p>

        <p>25. AI-powered home assistants can NOT do which of these?<br>
            <input type="radio" name="q25" value="a">Set reminders<br>
            <input type="radio" name="q25" value="b">Answer questions<br>
            <input type="radio" name="q25" value="c">Control smart devices<br>
            <input type="radio" name="q25" value="d">Replace your parents<br>
        </p>

        <button type="submit">Submit</button>
    </form>

    <h2 id="result" style="display: none;"></h2>
    <h3 id="correctAnswers" style="display: none;"></h3>

    <script>
        document.getElementById("quizForm").addEventListener("submit", async function(event) {
            event.preventDefault();

            const form = event.target;
            const name = form.name.value.trim().toLowerCase().replace(/\s+/g, "_");
            const studentClass = form.class.value;
            const uniqueKey = `submission_${name}_${studentClass}`;

            if (localStorage.getItem(uniqueKey)) {
                alert("You have already submitted this exam. Only one attempt is allowed.");
                return;
            }

            localStorage.setItem(uniqueKey, "submitted");

            const submitBtn = form.querySelector("button[type='submit']");
            submitBtn.disabled = true;

            const formData = new FormData(form);

            /* Updated correct answers */
            const correctAnswers = {
                q1: "b",
                q2: "a",
                q3: "b",
                q4: "a",
                q5: "a",
                q6: "b",
                q7: "b",
                q8: "b",
                q9: "b",
                q10: "a",
                q11: "b",
                q12: "b",
                q13: "b",
                q14: "a",
                q15: "b",
                q16: "b",
                q17: "c",
                q18: "b",
                q19: "a",
                q20: "b",
                q21: "a",
                q22: "b",
                q23: "b",
                q24: "a",
                q25: "d"
            };

            let score = 0;
            let totalQuestions = Object.keys(correctAnswers).length*2;
            let feedback = "<h3>Correct Answers:</h3><ul>";

            let submissionData = {
                name: formData.get("name"),
                studentClass: formData.get("class"),
                answers: {},
                score: 0
            };

            for (let key in correctAnswers) {
                const userAnswer = formData.get(key);
                submissionData.answers[key] = userAnswer;

                if (userAnswer === correctAnswers[key]) {
                    score += 2;
                    feedback += `<li><b>Question ${key.slice(1)}:</b> ✅ ${correctAnswers[key]}</li>`;
                } else {
                    feedback += `<li><b>Question ${key.slice(1)}:</b> ❌ Correct: ${correctAnswers[key]} | Your Answer: ${userAnswer || "No answer"}</li>`;
                }
            }

            feedback += "</ul>";
            submissionData.score = score;

            try {
                const response = await fetch("https://kweitsuenst.pythonanywhere.com//submit_quiz", {
                    method: "POST",
                    headers: { "Content-Type": "application/json" },
                    body: JSON.stringify(submissionData)
                });

                if (!response.ok) throw new Error(`Server error: ${response.statusText}`);

                const resJson = await response.json();
                alert(`Submission successful! Message from server: ${resJson.message}`);
            } catch (error) {
                console.error("Error submitting quiz:", error);
                alert("There was a problem submitting your quiz. Please make sure the server is running.");
            } finally {
                submitBtn.disabled = false;
            }

            document.getElementById("result").innerHTML = `Your Score: ${score} / ${totalQuestions}`;
            document.getElementById("result").style.display = "block";
            document.getElementById("correctAnswers").innerHTML = feedback;
            document.getElementById("correctAnswers").style.display = "block";
        });
    </script>
</body>
</html>
