<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Far Jes's Personal Page</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Main Font and Colors */
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f3eb; /* Light background */
            color: #5c4e3b; /* Dark coffee color */
            line-height: 1.6;
        }

        /* Header and Navigation */
        header {
            background-color: #a2896d; /* Warm beige */
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav a {
            color: #f7f3eb;
            font-weight: bold;
            text-decoration: none;
            padding: 8px 15px;
            border-radius: 5px;
        }

        nav a:hover {
            background-color: #5c4e3b; /* Dark coffee color */
        }

        /* Main Content Section */
        section {
            padding: 50px;
            max-width: 800px;
            margin: 20px auto;
            text-align: center;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            color: #5c4e3b;
        }

        h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 28px;
            margin-bottom: 20px;
            position: relative;
            display: inline-block;
        }

        /* Underline Animation for Headings */
        h2::after {
            content: '';
            display: block;
            width: 50%;
            height: 3px;
            background: #5c4e3b;
            margin: 5px auto 0;
            transition: width 0.3s ease;
        }

        h2:hover::after {
            width: 80%;
        }

        p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .contact-info {
            font-weight: bold;
            color: #5c4e3b;
        }

        .hobbies {
            font-style: italic;
            color: #6d5b3b;
        }

        /* Contact Button */
        .contact-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #5c4e3b;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
            font-weight: bold;
        }

        .contact-button:hover {
            background-color: #a2896d;
        }

        /* Footer */
        footer {
            background-color: #a2896d;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Far Jes's Personal Page</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi, my name is Far Jes. I enjoy learning new things and engaging in activities that challenge me.</p>
        <p class="hobbies">Hobbies: I love playing chess in my free time!</p>
    </section>

    <section id="contact">
        <h2>Contact Information</h2>
        <p class="contact-info">Phone: 065625836448</p>
        <p>If you'd like to reach out, feel free to contact me at the number above.</p>
        <a href="tel:065625836448" class="contact-button">Contact Me</a>
    </section>

    <footer>
        <p>Thank you for visiting my page! Feel free to connect with me anytime.</p>
    </footer>

</body>
</html>
