# ifa
#Html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/eb08ed2151.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="name.png">
        
                <ul>
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#My Work">My Work</a></li>
                    <li><a href="#contact">Contact</a></li>
                    
                </ul>
            
            </nav>
            <div class="header-text">
                <p>UI/UX Designer</p>
                <h1>Hi, I'm <span>Shrawan</span> <br> Thing From Nepal</h1>
            </div>
        </div>

    </div>
   <!-- --------about---------- -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="shrawan2.jpg">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>I am an IT student with a strong passion for web development, 
                        aiming to carve out a successful career in this dynamic field.
                        I am proficient in various programming languages and frameworks
                         essential for front-end and back-end development.My love for traveling
                            allows me to explore new cultures and destinations,  enriching my 
                            perspective and creativity. Football keeps me active and is a great
                             way to bond with friends and fellow enthusiasts.By integrating my interests into my 
                             professional life, such as creating travel blogs or sports-related 
                             websites,  I aim to develop innovative projects that showcase my 
                             skills and passion.</p>
                             <div class="tab-titles">
                                <p class="tab-links active-link" onclick="opentab('skills')">skills</p>
                                <p class="tab-links" onclick="opentab('experience')">Experience</p>
                                <p class="tab-links" onclick="opentab('education')">Education</p>
                                <div class="tab-contents active-tab" id="skills">
                                    <ul>
                                        <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                                        <li><span>Web Developement</span><br>Web app Developement</li>
                                    </ul>
                                </div>
                                <div class="tab-contents" id="experience">
                                    <ul>
                                        <li><span>2023 - current</span><br>UI/UX Design Training at ET Institute.</li>
                                        <li><span>2022 - 2023</span><br>Making project on HTML and CSS.</li>
                                    </ul>
                                </div>
                                <div class="tab-contents" id="education">
                                    <ul>
                                        <li><span>2019</span><br>UI/UX Design Training at ET Institute.</li>
                                        <li><span>2019</span><br>Computer Science in +2</li>
                                    
                                    </ul>
                                </div>

                             </div>
                </div>
            </div>
        </div>
    </div>
    <!-- --------------services------------- -->
     <div id="services">
        <div class="container">
            <h1 class="sub-title">My services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Design</h2>
                    <p>If you want to develop your web then contact me.</p>
                    <a href="#">Lern more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop"></i>
                    <h2>UI/UX Design</h2>
                    <p>If you want to design your web then contact me.</p>
                    <a href="#">Lern more</a>
                </div>

            </div>
        </div>
     </div>
     <!-- -----------My Work------------- -->
      <div id="My Work">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
            <div class="work">
                <img src="work-2.png">
                <div class="layer">
                    <h3>Social Media App</h3>
                    <p>The app connects you to the talented people around the world.
                        Download it from play store.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-3.png">
                <div class="layer">
                    <h3>Music App</h3>
                    <p>The app connects you to the talented people around the world.
                        Download it from play store.
                    </p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-1.png">
                <div class="layer">
                    <h3>Online Shopping App</h3>
                    <p>The app connects you to the talented people around the world.
                        Download it from play store.
                    </p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
      </div>
      <!-- ------------contact------------- -->
       <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p> <i class="fa-solid fa-paper-plane"></i>thingshrawanthing@gmail.com</p>
                    <p><i class="fa-solid fa-square-phone"></i>9702086963</p>
                    <div class="social-icons">
                        <a href="https://www.facebook.com/shrawan.theeng.9?mibextid=ZbWKwL"><i class="fa-brands fa-square-facebook"></i></a>
                        <a href=""><i class="fa-brands fa-x-twitter"></i></a>
                        <a href="https://www.instagram.com/shrawanthing?igsh=aGVsd3NnYmd2YW9u"><i class="fa-brands fa-square-instagram"></i></a>
                        <a href=""><i class="fa-brands fa-linkedin"></i></a>

                    </div>
                    <a href="my-cv.pdf" download class="btn btn2">Download CV</a>
                </div>
                    <div class="contact-right">
                        <form>
                            <input type="text" name="Name" placeholder="Your Name" required>
                            <input type="email" name="email" placeholder="Your Email" required>
                            <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                            <button type="submit" class="btn btn2">Submit</button>
                        </form>
                    </div>
                
            </div>
        </div>
        <div class="copyright">
            <p>Copyright $ Shrawan. Follow for <i class="fa-solid fa-heart"></i> connect with me</p>
        </div>
       </div>

    
<script>
    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contenets");
    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");
    }
</script>

</body>
</html>
