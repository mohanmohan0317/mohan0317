<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mohan0317 - My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background: #f4f4f9;
        }

        header {
            background: #4CAF50;
            color: #fff;
            padding: 1em 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
        }

        #home {
            background: #8BC34A;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }

        #about, #projects, #contact {
            background: #fff;
            margin: 20px 0;
        }

        .project {
            border: 1px solid #ddd;
            padding: 10px;
            margin-bottom: 10px;
            background: #e7f7df;
        }

        footer {
            background: #4CAF50;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .logo {
            width: 50px;
            vertical-align: middle;
            margin-right: 10px;
        }

        .about-photo {
            max-width: 200px;
            border-radius: 50%;
            display: block;
            margin: 0 auto;
        }

        .about-details {
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h1>Welcome to My Portfolio</h1>
        <h2>R MOHANVENKATADASU</h2>
    </section>
    
    <section id="about">
        <h2>About Me</h2>
        <img src="IMG-20230708-WA0123.jpg" alt="R MOHANVENKATADASU" class="about-photo">
        <div class="about-details">
            <p>Hi, I'm R MOHANVENKATADASU, currently pursuing my B.Tech in Electronics and Communication Engineering at Usha Rama College of Engineering and Technology, Andhra Pradesh.</p>
            <h3>Education</h3>
            <div>
                <img src="path_to_srichaitanya_logo.png" alt="Sri Chaitanya" class="logo">
                <p>High School at Sri Chaitanya E.M School, Andhra Pradesh (01/2019 - 07/2021) - GPA: 9.7/10</p>
            </div>
            <div>
                <img src="path_to_narayana_logo.png" alt="Narayana" class="logo">
                <p>Intermediate at Narayana</p>
            </div>
            <div>
                <img src="path_to_usharama_logo.png" alt="Usha Rama College" class="logo">
                <p>Pursuing Engineering at Usha Rama College of Engineering and Technology (10/2021 - 2025), Andhra Pradesh</p>
            </div>
        </div>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title 1</h3>
            <p>Project description goes here.</p>
        </div>
        <div class="project">
            <h3>Project Title 2</h3>
            <p>Project description goes here.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Phone: 9951715588</p>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 mohan0317 - My Portfolio</p>
    </footer>
    
    <script>
        document.getElementById('contact-form').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Thank you for your message!');
            // Add further form submission handling here
        });
    </script>
</body>
</html>
