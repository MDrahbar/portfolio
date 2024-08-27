# portfolio


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
  <script src="https://kit.fontawesome.com/c1a483f58e.js" crossorigin="anonymous"></script>
</head>
<body>
    <header>
        <nav class="container">
            <div class="logo">Portfolio</div>
            <p class="datetime" id="datetime"></p>
    
            <script>
                function updateDateTime() {
                    const now = new Date();
                    const options = { year: 'numeric', month: 'long', day: 'numeric', hour: '2-digit', minute: '2-digit', second: '2-digit', hour12: true };
                    const dateTimeString = now.toLocaleDateString('en-US', options);
                    document.getElementById('datetime').textContent = `Current Date and Time: ${dateTimeString}`;
                }
                
                updateDateTime();
                // Update the time every second
                setInterval(updateDateTime, 1000);
            </script>
            <ul>
                <a href="#hero">
                    <li>Home</li>
                </a>
                <a href="#project">
                    <li>Project</li>
                </a>
                <a href="#contact">
                    <li>Contact</li>
                </a>
            
            </ul>
        </nav>
    </header>
    <main>
        <section id="hero">
            <div class="container">
                <div class="hero_image animate__animated animate__bounceInLeft" >
                    <img src="./images/my-image.jpg" alt="hero image" />
                </div>
                <div class="hero_content">
                    
                    <h1>
                        <span class="hi_text">Hi</span>, I am
                        <span class="name_text">Md Rahbar</span>
                    </h1>
                    <h2>Frontend Developer</h2>
                </div>
            </div>
        </section>
        <section id="project">
            <h2>
                Projects
            </h2>
            <div class="container">
                <div class="project_container">
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project1.png" alt="project1" />
                            <div class="card_content">
                                <h3>Tribute Website</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/Project2.png" alt="project1" />
                            <div class="card_content">
                                <h3>Job Application</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project3.png" alt="project1" />
                            <div class="card_content">
                                <h3>Parallax Website</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project4.png" alt="project1" />
                            <div class="card_content">
                                <h3>Landing Page</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project5.png" alt="project1" />
                            <div class="card_content">
                                <h3>Food Website</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project6.png" alt="project1" />
                            <div class="card_content">
                                <h3>Music Website</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project7.png" alt="project1" />
                            <div class="card_content">
                                <h3>YouTube Clone</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project8.png" alt="project1" />
                            <div class="card_content">
                                <h3>Documentation Website</h3>
                            </div>
                        </div>
                    </div>
                    <div class="grid_item">
                        <div class="card">
                            <img src="images/project9.png" alt="project1" />
                            <div class="card_content">
                                <h3>Blog Website</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="contact">
            <div class="container">
                <h2>Let's Work Together...</h2>
                <div class="top_contact">
                    <div class="contact_way">
                        <i class="fab fa-linkedin"></i>
                        <h3>Linkedin</h3>
                    </div>
                    <div class="contact_way">
                        <i class="fab fa-twitter"></i>
                        <h3>Twitter</h3>
                    </div>
                    <div class="contact_way">
                        <h3>@ Send mail</h3>
                    </div>
                </div>
                <div class="bottom_contact">
                    <div class="contact_way">
                        <i class="fab fa-github"></i>
                        <h3>Github</h3>
                    </div>
                    <div class="contact_way">
                        <i class="fab fa-mobile"></i>
                        <h3>Mobile</h3>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">Created by Hussain</div>
    </footer>
</body>
</html>
