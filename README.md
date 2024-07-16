<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <style>
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blinkCaret {
            from, to { border-color: transparent; }
            50% { border-color: #0f0; }
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            animation: fadeIn 2s ease-in;
        }

        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            max-width: 800px;
            width: 100%;
            text-align: center;
            animation: slideIn 1s ease-out;
        }

        .container h1 {
            font-size: 22px;
            margin-bottom: 20px;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid #333;
            width: fit-content;
            margin: 0 auto;
            animation: typing 8s steps(30, end), blinkCaret 0.75s step-end infinite;
        }

        .stat {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 10px;
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease-in;
        }

        h4 {
            font-size: 18px;
            color: #333;
            margin: 10px 0;
            font-family: 'Trebuchet MS', sans-serif;
        }

        h4 span {
            color: #0077B5; /* LinkedIn blue for emphasis */
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            animation: bounce 2s infinite;
        }

        .social-links a {
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
        }

        .social-links .linkedin { background-color: #0077B5; }
        .social-links .instagram { background-color: #E1306C; }

        .code-snippet {
            background-color: #000;
            color: #0f0;
            padding: 10px;
            border-radius: 10px;
            text-align: left;
            white-space: pre;
            overflow: hidden;
            position: relative;
            width: fit-content;
            margin: 0 auto;
        }

        .code-snippet::after {
            content: "";
            background: black;
            position: absolute;
            right: 0;
            width: 10px;
            height: 100%;
            border-right: 2px solid #0f0;
            animation: typing 4s steps(44) infinite, blink-caret 0.75s step-end infinite;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi!👋My name is Sejal Waman and I'm a Software Developer from India.</h1>
        <div class="stat">
            <h4>Hi, I'm <span>@sejal-waman</span></h4>
            <h4>👩‍💻 I'm interested in doing coding</h4>
            <h4>🎓 I'm currently pursuing a master's degree in computer applications from Ajeenkya DY Patil University, Pune</h4>
            <h4>💞️ I'm looking to collaborate on open source projects and innovative software development</h4>
            <h4>📫 How to reach me: sejalwaman@gmail.com | <a href="https://www.linkedin.com/in/sejal-waman-397449252?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a> | <a href="https://www.instagram.com/_._sejuuu_._?utm_source=qr&igshid=MTdza25oOWx3eDU2aw==">Instagram</a></h4>
            <h4>🌟 Pronouns: She/Her</h4>
        </div>

        <div class="code-snippet">
            (function repeat() {<br>
            &nbsp;&nbsp;eat();<br>
            &nbsp;&nbsp;sleep();<br>
            &nbsp;&nbsp;code();<br>
            &nbsp;&nbsp;repeat();<br>
            })();
        </div>
    </div>
</body>
</html>


<!---
sejal-waman/sejal-waman is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
