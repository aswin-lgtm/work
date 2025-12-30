<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aswin | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background: #f4f6f8;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #0a2540;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
        }

        header p {
            margin-top: 10px;
            font-size: 1.1rem;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            margin-bottom: 20px;
            color: #0a2540;
            border-bottom: 2px solid #0a2540;
            display: inline-block;
        }

        .about p {
            margin-top: 10px;
        }

        .skills ul {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            list-style: none;
            margin-top: 20px;
        }

        .skills li {
            background: #fff;
            padding: 15px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .projects .card {
            background: #fff;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .contact p {
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #0a2540;
            color: #fff;
            margin-top: 40px;
        }

        @media(max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Aswin</h1>
    <p>Chemical Engineering Graduate | Technology & Innovation Enthusiast</p>
</header>

<section class="about">
    <h2>About Me</h2>
    <p>
        I am a B.Tech Chemical Engineering graduate (2025) with a strong interest in
        sustainable technologies, process engineering, and innovation.
        I enjoy learning new technical skills and applying them to real-world problems.
    </p>
</section>

<section class="skills">
    <h2>Skills</h2>
    <ul>
        <li>Chemical Process Fundamentals</li>
        <li>Mass Transfer & Thermodynamics</li>
        <li>CFD (Basics)</li>
        <li>Arduino & IoT Projects</li>
        <li>HTML, CSS (Basic)</li>
        <li>Video Editing & Content Creation</li>
    </ul>
</section>

<section class="projects">
    <h2>Projects</h2>

    <div class="card">
        <h3>Sustainable Ammonium Nitrate Synthesis</h3>
        <p>
            Final year project focused on producing ammonium nitrate using
            biomass-derived nitric acid for sustainable fertilizer production.
        </p>
    </div>

    <div class="card">
        <h3>Arduino Safety & Automation Projects</h3>
        <p>
            Developed basic automation systems using Arduino, ultrasonic sensors,
            servo motors, and buzzers.
        </p>
    </div>

</section>

<section class="contact">
    <h2>Contact</h2>
    <p>Email: aswin@example.com</p>
    <p>Phone: +91 XXXXX XXXXX</p>
    <p>LinkedIn: linkedin.com/in/aswin</p>
</section>

<footer>
    <p>© 2025 Aswin | Portfolio</p>
</footer>

</body>
</html>
