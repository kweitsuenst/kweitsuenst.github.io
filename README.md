
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Lessons with Ernest Positive</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #0073e6;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
            margin: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #0073e6;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to MIS AI page </h1>
        <nav>
            <ul>
                <li><a href="#curriculum">Curriculum</a></li>
                <li><a href="#resources">Resources</a></li>
                <li><a href="#assignments">Assignments</a></li>
                <li><a href="#quizzes">Quizzes</a></li>
                <li><a href="#exams">Exams</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#login">Student Login</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="curriculum">
        <h2>AI Curriculum</h2>
        <p>Explore AI topics by grade level.</p>
    </section>

    <section id="resources">
        <h2>AI Resources</h2>
        <p>Find articles, videos, and tools to enhance your learning.</p>
    </section>

    <section id="assignments">
        <h2>Assignments</h2>
        <p>Complete exercises and challenges to test your AI skills.</p>
    </section>

    <section id="quizzes">
        <h2>Quizzes</h2>
        <p>Take interactive quizzes to assess your understanding of AI.</p>
        <button onclick="showQuiz()">Start Quiz</button>
        <div id="quiz-section" class="hidden">
            <p>What does AI stand for?</p>
            <button onclick="checkAnswer('correct')">Artificial Intelligence</button>
            <button onclick="checkAnswer('wrong')">Automated Input</button>
            <p id="quiz-result"></p>
        </div>
    </section>

    <section id="exams">
        <h2>Exams</h2>
        <p>Select your class to take the End of Term AI exams.</p>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdj8xaR9eqr--6e8JLUjdSuyuO5GRWOpVsc1NzLPTxZ2sBN6A/viewform?usp=header">
        <button type="button">Basic Three (3) </button>
        </a><a href="https://docs.google.com/forms/d/e/1FAIpQLSdj8xaR9eqr--6e8JLUjdSuyuO5GRWOpVsc1NzLPTxZ2sBN6A/viewform?usp=header">
        <button type="button">Basic Four (4) </button>
        </a><a href="https://docs.google.com/forms/d/e/1FAIpQLSdj8xaR9eqr--6e8JLUjdSuyuO5GRWOpVsc1NzLPTxZ2sBN6A/viewform?usp=header">
        <button type="button">Basic Five (5) </button>
        </a>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdj8xaR9eqr--6e8JLUjdSuyuO5GRWOpVsc1NzLPTxZ2sBN6A/viewform?usp=header">
        <button type="button">Basic Six (6) </button>
        </a>
        <a href="quiz7.html">
        <button type="button">Basic Seven (7) </button>
        </a><a href="https://docs.google.com/forms/d/e/1FAIpQLSdj8xaR9eqr--6e8JLUjdSuyuO5GRWOpVsc1NzLPTxZ2sBN6A/viewform?usp=header">
        <button type="button">Basic Eight (8) </button>
        </a>


    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>Stay updated with AI news and insights.</p>
    </section>

    <section id="login">
        <h2>Student Login</h2>
        <p>Access your assignments and track your progress.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Reach out with any questions or feedback.</p>

        <a href="https://wa.me/+233551758061" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Icon" width="50" height="50">
    </a>
    </section>

    <footer>
        <p>&copy; 2025 Ernest Positive. All Rights Reserved.</p>
    </footer>

    <script>
        function showQuiz() {
            document.getElementById('quiz-section').classList.remove('hidden');
        }
        function checkAnswer(answer) {
            if (answer === 'correct') {
                document.getElementById('quiz-result').innerText = 'Correct! Well done!';
            } else {
                document.getElementById('quiz-result').innerText = 'Incorrect. Try again!';
            }
        }
    </script>
</body>
</html>
