<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" />
    <title>Engr Soweto's Portfolio</title>
</head>
<body>
    <header class="site_header">
        <div class="wrapper_inner">
            <nav class="site_header_nav">
                <ul role="list" class="flex flex_center">
                    <li><a href="#0">HOME</a></li>
                    <li><a href="#skills">SKILLS</a></li>
                    <li><a href="#about">ABOUT</a></li>
                    <li><a href="#contact">CONTACT</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section id="hero">
            <div class="wrapper">
                <div class="wrapper_inner">
                    <div class="text_center hero_content">
                        <h1 class="h2">Official Soweto</h1>
                        <p class="h5">ARCHITECT & MECHANICAL ENGINEER</p>
                    </div>
                </div>
                <ul role="list" class="flex flex_between hero_social">
                    <address>Lagos, Abuja Nigeria</address>
                    <ul role="list" class="flex">
                        <li>find me online</li>
                        <li>
                            <a href="https://linkedin.com/soweto1of1" target="_blank">
                                <img src="/images/linkedin.JPG" alt="linkedin" width="40" height="20" />
                            </a>
                        </li>
                        <li>
                            <a href="https://x.com/soweto1of1" target="_blank">
                                <img src="images/twitter.PNG" alt="Twitter" width="40" height="20" />
                            </a>
                        </li>
                    </ul>
                </ul>
            </div>
        </section>
    </main>
        <section id="about">
            <div class="wrapper">
                <div class="text_center">
                    <h2>
                        I am an architecture and intrigiung mechanical Engineer. I help industries provide top-notch services to humanity.
                    </h2>
                </div>
                <div class="wrapper_inner">
                    <div class="about_content flex flex_around">
                        <figure class="about_figure text_center">
                            <img width="400px" height="200px" src="/images/soweto1of1.jpg" alt="Engineer" class="about_img" />
                            <figcaption class="about_caption">Soweto</figcaption>
                        </figure>
                        <p class="h5">
                            Born in Transamadi Portharcourt, I've spent 6+ years in college studying Engineering. I assist companies deliver amazing services to mankind and bring more peace to humanity.
                        </p>
                    </div>
                </div>
            </div>
        </section>
        <section id="work">
            <div class="wrapper_inner">
                <div class="text_center">
                    <h4 class="h5">
                        With delibrate efforts i have helped 7+ firms develop amazing technologies, renovate their engineering abilities and projects.
                    </h4>
                    <ul role="list" class="work_logos flex flex_center">
                        <li>
                            <img 
                            src="/images/haliburton.jpg" 
                            alt="Haliburton Corp" width
                            width="800"
                            height="400" 
                            />
                        </li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="contact">
            <div class="wrapper">
                <div class="text_left">
                    <p>
                        Wish to work together? <br />
                        Would be pleased hearing from you.
                    </p>
                </div>

                <div class="wrapper_inner">
                    <h5 class="h3">Contact Me</h5>
                    <form action="" method="post" class="contact_form">
                        <div class="flex">
                            <div class="form_group">
                                <label for="name">NAME</label>
                                <input type="text" id="name" name="name" />
                            </div>
                            <div class="form_group">
                                <label for="email">EMAIL</label>
                                <input type="email" id="email" name="email" />
                            </div>
                        </div>
                        <div class="form_group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message"></textarea>
                        </div>
                        <button type="submit">SEND MESSAGE</button>
                    </form>
                </div>
            </div>
        </section>
</body>
<footer>
    <section id="footer">
        <div class="wrapper">
            <div class="text_right">
                <p>&copy; 2026 Engr Soweto</p>
            </div>
        </div>
    </section>
</footer>
</html>
