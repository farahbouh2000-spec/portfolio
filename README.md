# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>

<body>

    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>I'm a young web developer learning and building projects with HTML.</p>

        <hr>

        <nav>
            <a href="#about">About Me</a> |
            <a href="#skills">Skills</a> |
            <a href="#projects">Projects</a> |
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <hr>

    <main>

        <section id="about">
            <h2>About Me</h2>

            <p>
                Hello! My name is Faty. I'm a young person interested in
                web development and technology.
            </p>

            <p>
                I'm currently learning how websites are created and
                experimenting with HTML. My goal is to improve my skills
                and create useful and beautiful websites.
            </p>
        </section>

        <hr>

        <section id="skills">
            <h2>My Skills</h2>

            <ul>
                <li>HTML</li>
                <li>Web Development</li>
                <li>Website Design</li>
                <li>Creative Ideas</li>
                <li>Learning New Technologies</li>
            </ul>
        </section>

        <hr>

        <section id="projects">
            <h2>My Projects</h2>

            <article>
                <h3>Personal Portfolio</h3>
                <p>
                    A simple personal portfolio website created using
                    only HTML.
                </p>
            </article>

            <article>
                <h3>Appointment Website</h3>
                <p>
                    I'm working on a website where visitors can fill out
                    a form to request an appointment.
                </p>
            </article>

            <article>
                <h3>Ikram 48</h3>
                <p>
                    A creative project involving food, branding,
                    menus, prices and promotional designs.
                </p>
            </article>
        </section>

        <hr>

        <section>
            <h2>My Goal</h2>

            <p>
                My goal is to continue learning web development,
                build more projects, and eventually work in the web
                development field.
            </p>
        </section>

        <hr>

        <section id="contact">
            <h2>Contact Me</h2>

            <p>
                If you would like to contact me, you can send me a message.
            </p>

            <form>
                <label for="name">Your Name:</label>
                <br>
                <input type="text" id="name" name="name">
                <br><br>

                <label for="email">Your Email:</label>
                <br>
                <input type="email" id="email" name="email">
                <br><br>

                <label for="message">Your Message:</label>
                <br>
                <textarea id="message" name="message" rows="6" cols="30"></textarea>
                <br><br>

                <button type="submit">Send Message</button>
            </form>
        </section>

    </main>

    <hr>

    <footer>
        <p>© 2026 My Portfolio</p>
        <p>Built with HTML ❤️</p>
    </footer>

</body>
</html>
