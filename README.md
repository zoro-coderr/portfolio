<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aman Kumar - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPKB9WWgQlnU6T+0YlQl5nTvNW27hVQxv9g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>

    <header class="new-header">
        <nav class="container new-nav">
            <div class="logo">AK</div> <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#" class="button primary-button">Resume</a></li> </ul>
        </nav>
        <div class="container hero">
            <div class="hero-content">
                <h5 class="hero-subtitle">HI THERE, I'M</h5>
                <h1 class="hero-title">Aman Kumar</h1>
                <p class="hero-description">Web Developer & Programmer</p>
                <a href="#contact" class="button primary-button">Get In Touch</a>
            </div>
            <div class="hero-image">
                <img src="zorosmiles.jpeg" alt="Your Profile Image"> </div>
        </div>
    </header>

    <main>
        <section id="about">
            <div class="container">
                <div class="about-content">
                    <h2>About Me</h2>
                    <p>Hi, I'm Aman Kumar, a passionate web developer and programmer dedicated to crafting clean, efficient, and user-friendly web solutions. With a strong foundation in front-end and back-end technologies, I'm constantly seeking opportunities to learn and grow in the ever-evolving tech landscape. My enthusiasm for problem-solving and my commitment to creating impactful digital experiences drive me in every project I undertake.</p>
                    <p>I'm currently pursuing my B.Tech and actively building my skills through personal projects and continuous learning. I'm eager to contribute my abilities and passion to exciting and challenging projects.</p>
                </div>
            </div>
        </section>

        <section id="skills">
            <div class="container">
                <h2>Skills</h2>
                <ul class="skills-list">
                    <li><span class="skill-tag">HTML</span></li>
                    <li><span class="skill-tag">CSS</span></li>
                    <li><span class="skill-tag">JavaScript</span></li>
                    <li><span class="skill-tag">React</span></li>
                    <li><span class="skill-tag">Node.js</span></li>
                    <li><span class="skill-tag">Git</span></li>
                    <li><span class="skill-tag">Responsive Design</span></li>
                    <li><span class="skill-tag">Basic UI/UX</span></li>
                    <li><span class="skill-tag">Problem Solving</span></li>
                    <li><span class="skill-tag">Continuous Learning</span></li>
                </ul>
            </div>
        </section>

        <section id="projects">
            <div class="container">
                <h2>Projects</h2>
                <div class="projects-container">
                    <div class="project-card">
                        <div class="project-image">
                            <img src="todolist.jpg" alt="To-Do List Project">
                        </div>
                        <div class="project-info">
                            <h3>Simple To-Do List</h3>
                            <p>A user-friendly web application built with HTML, CSS, and JavaScript to help users manage their daily tasks effectively. Features include adding, deleting, and marking tasks as complete. This project focused on DOM manipulation and local storage implementation.</p>
                            <a href="#" class="button secondary-button" target="_blank">View Project</a>
                            <a href="https://github.com/zoro-coderr/simple-todo-list" class="button github-button" target="_blank"><i class="fab fa-github"></i> GitHub</a>
                        </div>
                    </div>

                    <div class="project-card">
                        <div class="project-image">
                            <img src="calc.png" alt="Basic Calculator Project">
                        </div>
                        <div class="project-info">
                            <h3>Basic Calculator</h3>
                            <p>An interactive online calculator developed using HTML, CSS, and JavaScript. This project allows users to perform fundamental arithmetic operations. It emphasizes event handling and basic mathematical logic in JavaScript.</p>
                            <a href="#" class="button secondary-button" target="_blank">View Project</a>
                            <a href="https://github.com/zoro-coderr/basic-calculator" class="button github-button" target="_blank"><i class="fab fa-github"></i> GitHub</a>
                        </div>
                    </div>

                    <div class="project-card">
                        <div class="project-image">
                            <img src="landing.webp" alt="Static Landing Page Project">
                        </div>
                        <div class="project-info">
                            <h3>Static Landing Page</h3>
                            <p>A visually appealing and responsive landing page created with HTML and CSS. This project demonstrates understanding of layout design, responsive principles, and semantic HTML structure. It could be used to showcase a product, service, or personal profile.</p>
                            <a href="#" class="button secondary-button" target="_blank">View Project</a>
                            <a href="https://github.com/zoro-coderr/static-landing-page" class="button github-button" target="_blank"><i class="fab fa-github"></i> GitHub</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="education">
            <div class="container">
                <h2>Education</h2>
                <div class="education-list">
                    <div class="education-item">
                        <img src="gu.jpeg" alt="Galgotias University Logo" class="institution-logo">
                        <div class="institution-info">
                            <h3>Galgotias University</h3>
                            <p><strong>B.Tech</strong> - Currently in 4th Semester (as of 2023)</p>
                        </div>
                    </div>
                    <div class="education-item">
                        <img src="dav.jpeg" alt="DAV Public School Logo" class="institution-logo">
                        <div class="institution-info">
                            <h3>DAV Public School, Hehal, Ranchi</h3>
                            <p><strong>12th Grade:</strong> 77%</p>
                            <p><strong>10th Grade:</strong> 85.68%</p>
                        </div>
                    </div>
                    </div>
            </div>
        </section>

        <section id="contact">
            <div class="container">
                <h2>Contact</h2>
                <p class="contact-intro">Feel free to reach out for collaborations, opportunities, or just a friendly chat!</p>
                <div class="contact-details">
                    <p><i class="fas fa-envelope"></i> Email: <a href="mailto:amankr.21797@gmail.com">amankr.21797@gmail.com</a></p>
                    <p><i class="fab fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/aman-kumar-660836274/" target="_blank">Aman Kumar</a></p>
                    <p><i class="fab fa-github"></i> GitHub: <a href="https://github.com/zoro-coderr" target="_blank">zoro-coderr</a></p>
                    <p><i class="fab fa-twitter"></i> Twitter: <a href="https://x.com/amankr21797" target="_blank">@amankr21797</a></p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Aman Kumar. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // The animated title script can likely be removed or adjusted for the new header style
        // For now, I'll comment it out.
        // const animatedTitle = document.querySelector('.animated-title');
        // const text = "Hi, I'm Aman Kumar";
        // let index = 0;

        // function typeWriter() {
        //     if (index < text.length) {
        //         animatedTitle.textContent += text.charAt(index);
        //         index++;
        //         setTimeout(typeWriter, 100); // Adjust speed as needed
        //     }
        // }

        // typeWriter();
    </script>

</body>
</html># portfolio
