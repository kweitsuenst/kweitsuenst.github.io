<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <meta property="og:image" content="https://misai.wuaze.com/MISAIPROJECTS1.jpg" />
    <title>AI Lessons with Ernest Positive</title>
    
       <style>
        /* -----------------------------------
           GLOBAL RESPONSIVE FONT SCALING
        -----------------------------------*/
        html {
            font-size: clamp(14px, 2vw, 22px);
        }

        h1 {
            font-size: clamp(24px, 5vw, 48px);
        }

        h2 {
            font-size: clamp(20px, 4vw, 36px);
        }

        p, li, a, button {
            font-size: clamp(14px, 2vw, 20px);
        }

        /* -----------------------------------
           BASE STYLES
        -----------------------------------*/
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            background: url('https://images.unsplash.com/photo-1535223289827-42f1e9919769?auto=format&fit=crop&w=1500&q=80')
                        center/cover no-repeat fixed;
            color: #333;
            line-height: 1.6;
        }

        /* -----------------------------------
           HEADER
        -----------------------------------*/


        header {
            background: #0073e6cc;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            backdrop-filter: blur(3px);
        }

        .logo { width: 80px; margin-bottom: 1rem; }

        nav { margin-top: 1rem; }
        .nav-links {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            list-style: none;
        }
        .nav-links a {
            text-decoration: none;
            color: #fff;
            background: #005bb5;
            padding: 10px 15px;
            border-radius: 5px;
        }

        main {
         }
        .card {

            background: white;
            padding: 2rem;
            border-radius: 1px;
            box-shadow: 0 0 0px rgba(0,0,0,0.1);


            padding-bottom: !important;
        }
        .btn {
            display: inline-block;
            margin: px;
            padding: 10px 15px;
            background-color: #0073e6;
            color: white;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            cursor: pointer;
            max-width: 900px;
        }
        .btn:hover { background-color: #005bb5; }

        footer {
            background: white ;
            color: #0073e6cc;
            text-align: center;
        }

        .hidden { display: none; }

         /* -----------------------------------
           AI & ETHICS AD SECTION
        -----------------------------------*/
        .ad-section {
            background: url('https://images.unsplash.com/photo-1535223289827-42f1e9919769?auto=format&fit=crop&w=1500&q=80')
                        center/cover no-repeat fixed;
            color: white;
            padding: 50px 20px;
            text-align: center;
            border-bottom: 4px solid white;
            animation: fadeIn 1.2s ease-out;
            backdrop-filter: brightness(0.6);
        }

        .ad-title { font-size: 2.7rem; animation: pop 1.2s infinite alternate; }
        .ad-button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: white;
            color: #0f62fe;
            font-weight: bold;
            border-radius: 50px;
            text-decoration: none;
        }

       
    </style>
</head>

<body>

    



    <!-- -----------------------------------
         WEBSITE CONTENT CONTINUES BELOW
    ----------------------------------- -->

    <header>
        <img src="mis logo.jpg" alt="" width="100" />
        <h1>Welcome to MIS AI</h1>
        <p>Empowering students to learn AI, code, and solve problems creatively.</p>
        <nav>
            <ul class="nav-links">
                <li><a href="#curriculum">Curriculum</a></li>
                <li><a href="#resources">Resources</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#quizzes">Quizzes</a></li>
                <li><a href="#exams">Exams</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#login">Login</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>


        <!-- 🔹 AI & ETHICS ADVERTISING (NOW BELOW FIRST SECTION) -->
        <section id="you-and-ai" class="ad-section">
            <div class="ad-container">
                <h2 class="ad-title">YOU and AI</h2>
                <p class="ad-text">
                    AI is shaping the future — but how we use it matters.
                    Learn <strong>how AI works</strong>, use it <b>responsibly</b>, and explore <strong>AI ethics</strong> to make the world better!
                </p>
                <ul class="ad-benefits">
                    <li>🤖 Use AI to learn faster & smarter</li>
                    <li>🧠 Build critical thinking & problem-solving skills</li>
                    <li>⚖ Understand AI ethics: fairness, honesty & safety</li>
                    <li>💡 Create AI projects that help people</li>
                </ul>
                <a href="#curriculum" class="ad-button">Explore AI & Ethics</a>
            </div>
        </section>

            <!-- 🔹 FIRST SECTION -->
        <section id="curriculum" class="card">
            <h2>AI Curriculum</h2>
            <p>Explore our curriculum organized by grade level.</p>
            <a class="btn" href="Mission_International_School_Coding_AI_Curriculum.pdf" target="_blank">Download PDF</a>
        </section>

        <!-- 🔹 REST OF CONTENT BELOW -->
        <section id="resources" class="card">
            <h2>AI Resources</h2>
            <p>Books, videos, and tools for each grade:</p>
            <div>
                <a class="btn" >Grade 3</a>
                <a class="btn" >Grade 4</a>
                <a class="btn" >Grade 5</a>
                <a class="btn" >Grade 6</a>
                <a class="btn" >Grade 7</a>
                <a class="btn" >Grade 8</a>
            </div>
        </section>

        <section id="projects" class="card">
            <h2>Student Projects</h2>
            <p>See what our students are creating!</p>
            <img src="dance@misaiproject.PNG" alt="Dancing sprite project" width="300" />
            <video controls width="350">
                <source src="dance@misaiprojects.mp4" type="video/mp4" />
                Your browser does not support the video tag.
            </video>
        </section>

        <!-- Remaining sections stay the same -->
            <section id="quizzes" class="card">
            <h2>AI Quizzes</h2>
            <p>Test your knowledge with short quizzes.</p>
            <button class="btn" onclick="document.getElementById('quiz-area').classList.toggle('hidden')">Take a Quiz</button>
            <div id="quiz-area" class="hidden">
                <p>What does AI stand for?</p>
                <button class="btn" onclick="alert('Correct!')">Artificial Intelligence</button>
                <button class="btn" onclick="alert('Incorrect!')">Automated Input</button>
            </div>
        </section>

        <section id="exams" class="card">
            <h2>Term Exams</h2>
            <p>Choose your class to begin:</p>
            <div>
                <a class="btn" href="1quiz3.html">Basic 3</a>
                <a class="btn" href="1quiz4.html">Basic 4</a>
                <a class="btn" href="1quiz5.html">Basic 5</a>
                <a class="btn" href="1quiz6.html">Basic 6</a>
                <a class="btn" href="pquiz7.html">Basic 7</a>
                <a class="btn" href="pquiz8.html">Basic 8</a>
            </div>
        </section>

        <section id="blog" class="card">
            <h2>AI Blog</h2>
            <p>Insights from the world of AI:</p>
            <a href="https://youtube.com/shorts/OK0YhF3NMpQ?si=yhkqNgM3JLovhTxx" target="_blank">
                What ChatGPT’s founder says kids should be learning
            </a>
        </section>

        <section id="login" class="card">
            <h2>Student Login</h2>
            <p>Access assignments and progress tracking.</p>
        </section>

        <section id="contact" class="card">
            <h2>Contact</h2>
            <p>Have questions? Contact us:</p>
            <a href="https://wa.me/+233551758061" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" width="40"/>
            </a>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Ernest Positive. All Rights Reserved.</p>
    </footer>
</body>
</html>
