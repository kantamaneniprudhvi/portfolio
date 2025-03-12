<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prudhvi's Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Poppins", sans-serif;
        }

        html {
            font-size: 62.5%;
        }

        body {
            width: 100%;
            height: 100vh;
            overflow-x: hidden;
            background-color: #000;
            color: #f5deb3;
        }

        header {
            margin-top: 20px;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 1rem 9%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: rgba(5, 13, 249, 0.8);
            z-index: 100;
        }

        .logo {
            font-size: 3rem;
            font-weight: bold;
            color: #ff0000;
            cursor: pointer;
            transition: 0.5s ease;
        }
        .logo:hover {
                transform: scale(1.1);
        }
        nav ul {
            display: flex;
            list-style: none;
        }

        nav a {
            font-size: 1.8rem;
            margin-left: 3rem;
            color: #ed0707;
            font-weight: 600;
            text-decoration: none;
            transition: color 0.3s ease, border-bottom 0.3s ease;
            border-bottom: 3px solid transparent;
        }

        nav a:hover,
        nav a.active {
            color: #e8350d;
            border-bottom: 3px solid #f7f3f3;
        }

        /* Home Section */
        .home {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            height: 100vh;
            padding-top: 8rem;
            gap: 8rem;
            background-color: #000;
        }

        .home-content h1 {
            font-size: 5rem;
        }

        .home-content h3 {
            font-size: 2.5rem;
            margin-top: 1rem;
        }

        .social-icons {
            display: flex;
            gap: 2rem;
        }

        .social-icons a {
            display: inline-flex;
            justify-content: center;
            align-items: center;
            width: 4rem;
            height: 4rem;
            border: 2px solid #fff;
            border-radius: 50%;
            color: #ffffff;
            transition: transform 0.3s, background-color 0.3s, box-shadow 0.3s;
        }

        .social-icons a:hover {
            transform: scale(1.2);
            background-color: #1224ef;
            box-shadow: 0 0 20px #b74b4b;
        }

        .btn {
            display: inline-block;
            font-size: 1.8rem;
            color: #fff;
            background-color: #ff0000;
            padding: 1rem 2rem;
            margin-top: 2rem;
            border-radius: 0.5rem;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.3s, background-color 0.3s;
        }

        .btn:hover {
            transform: scale(1.1);
            background-color: #b74b4b;
        }

        img {
            max-width: 50%;
            border-radius: 1.5rem;
        }
    </style>
</head>
<body>
    <header>
        <a href= "#"class="logo">Prudhvi</a>
        <nav>
            <ul>
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="D:\23481A0597\me skills.html">Skills</a></li>
                <li><a href="D:\23481A0597\colgroup.html">Qualification</a></li>
                <li><a href="D:/23481A0597/my%20experience.html">Experience</a></li>
                <li><a href="D:\23481A0597\example of mobile num.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home" class="home">
            <div class="image">
                <img src="D:\23481A0597\WhatsApp Image 2025-01-11 at 12.09.07_e6d94282.jpg"alt="Prudhvi" style="max-width:20%; height 1; border-radius: 0cqmin;">
            <div class="home-content">
                <h1>Hi, I'm <span>Prudhvi</span></h1>
                <h3 class="typing-txt">I'm a <span class="txt">Developer</span></h3>
                <div class="social-icons">
                    <a href="https://www.linkedin.com/in/prudhvi-chowdary-91ab33317" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="https://www.instagram.com/kantamaneniprudhvi" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="https://github.com/kantamaneniprudhvi" target="_blank"><i class="fab fa-github"></i></a>
                </div>
                <a href="D:/23481A0597/contact.html" class="btn">Hire Me</a>
            </div>
        </section>
    </main>
</body>
</html>
