<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website - Easy Tutorials</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/c4254e24a8.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <img src="images/logo.png" class="logo">
            <ul id="sidemenu">
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                <i class="fas fa-times" onclick="closemenu()"></i>
            </ul>
            <i class="fas fa-bars" onclick="openmenu()"></i>
        </nav>
        <div class="header-text">
            <p>UI/UX Designer</p>
            <h1>Hi, I'm <span>Kevin</span><br>Jen From Australia</h1>
        </div>
    </div>
</div>
<!-- -----------about---------- -->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/user.png">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh, tincidunt sit amet sapien quis, elementum molestie tellus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris eleifend magna id ante convallis mattis. Quisque in sem tristique, dictum sapien et, accumsan libero.</p>

                <div class="tab-titles">
                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('experience')">Experience</p>
                    <p class="tab-links" onclick="opentab('education')">Education</p>
                </div>
                <div class="tab-contents active-tab" id="skills">
                    <ul>
                        <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                        <li><span>Web Development</span><br>Web app Development</li>
                        <li><span>App Development</span><br>Building Android/iOS apps</li>
                    </ul>
                </div>
                <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>2021 - Current</span><br>UI/UX Design Training at ET Institute</li>
                        <li><span>2019 - 2021</span><br>Team lead at StarApp LLC.</li>
                        <li><span>2017 - 2019</span><br>UI/UX Design Executive at Coin Digital Ltd.</li>
                        <li><span>2016 - 2017</span><br>Internship at ekart eCommerce.</li>
                    </ul>
                </div>
                <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2016</span><br>UI/UX Design Training at ET Institute</li>
                        <li><span>2016</span><br>MBA from MIT Bangalore.</li>
                        <li><span>2014</span><br>BBA from ISM Bangalore.</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- ---------services---------------- -->
<div id="services">
    <div class="container">
        <h1 class="sub-title">My Services</h1>
        <div class="services-list">
            <div>
                <i class="fas fa-code"></i>
                <h2>Web Design</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh, tincidunt sit amet sapien quis.</p>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fas fa-crop-alt"></i>
                <h2>UI/UX Design</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh, tincidunt sit amet sapien quis.</p>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fab fa-app-store"></i>
                <h2>App Design</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla nibh, tincidunt sit amet sapien quis.</p>
                <a href="#">Learn more</a>
            </div>
        </div>
    </div>
</div>
<!-- ----------portfolio------------ -->
<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3>Social Media App</h3>
                    <p>The app connects you yo the talented people around the world. Download it from play store.</p>
                    <a href="#"><i class="fas fa-external-link-alt"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3>Music App</h3>
                    <p>The app connects you yo the talented people around the world. Download it from play store.</p>
                    <a href="#"><i class="fas fa-external-link-alt"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>Online Shopping App</h3>
                    <p>The app connects you yo the talented people around the world. Download it from play store.</p>
                    <a href="#"><i class="fas fa-external-link-alt"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See more</a>
    </div>
</div>
<!-- ----------contact------------- -->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fas fa-paper-plane"></i> contact@example.com</p>
                <p><i class="fas fa-phone-square-alt"></i> 0123456789</p>
                <div class="social-icons">
                    <a href="https://facebook.com/"><i class="fab fa-facebook"></i></a>
                    <a href=""><i class="fab fa-twitter-square"></i></a>
                    <a href=""><i class="fab fa-instagram"></i></a>
                    <a href=""><i class="fab fa-linkedin"></i></a>
                </div>
                <a href="images/my-cv.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your Email" required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright © Kevin. Made wtih <i class="fas fa-heart"></i> by <a href="https://www.youtube.com/channel/UCkjoHfkLEy7ZT4bA2myJ8xA?sub_confirmation=1">Easy Tutorials</a></p>
    </div>
</div>



<script>

    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");

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

<script>

    var sidemeu = document.getElementById("sidemenu");

    function openmenu(){
        sidemeu.style.right = "0";
    }
    function closemenu(){
        sidemeu.style.right = "-200px";
    }

</script>
<script>
    const scriptURL = '< add you own link here >' // add your own app script link here
    const form = document.forms['submit-to-google-sheet']
    const msg = document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML = "Message sent successfully"
            setTimeout(function(){
                msg.innerHTML = ""
            },5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>
</body>
</html>
