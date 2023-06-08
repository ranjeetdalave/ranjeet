# Personal Portfolio
//code for this
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="icon" href="./assets/img/h1.png" />
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="./package.json">

  <link href="https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css" rel="stylesheet" />
  
  <title>Ranjeet Dalave</title>
</head>

<body>
  <!--===== HEADER =====-->
  <header class="l-header">
    <nav class="nav bd-grid">
      <div>
        <!-- &#60;&#62; -->
        <a href="#home" class="nav-logo"><img src="imgg/h.png" height="70px" alt="H" /></a>
      </div>

      <div class="nav-menu" id="nav-menu">
        <ul class="nav-list">
          <li class="nav-item">
            <a href="#home" class="nav-link home active">Home</a>
          </li>
          <li class="nav-item">
            <a href="#about" class="nav-link about">About</a>
          </li>
          <li class="nav-item">
            <a href="#skills" class="nav-link skills">Skills</a>
          </li>
          <li class="nav-item">
            <a href="#contact" class="nav-link contact">Contact</a>
          </li>
          <li class="nav-item">
          <a href = "#" onclick="myFunction()"> <img src="imgg/sumoon.png" alt="" height="20px" width="20px" style="background-color: transparent;"> </a>
          </li>
        </ul>
      </div>

      <div class="nav-toggle" id="nav-toggle">
        <i class="bx bx-menu"></i>
      </div>
    </nav>
  </header>

  <main class="l-main">
    <!--===== HOME =====-->
    <section class="home bd-grid section" id="home">
      <div class="home-data">
        <h2 class="home-title">
          Hi 👋,<br />I'am <span class="home-title-color">Ranjeet Dalave</span><br />
         <span id="jobTitle" >Full Stack Developer</span> 
        </h2>

        <a href="https://drive.google.com/file/d/1XCH9jGAQBlfk5x-4vvr47pz8dOcodPj_/view?usp=drive_link" target="_blank"
          class="button">Resume</a>

      </div>
      <span id="hm" >
        <h2>Hire Me</h2>
      </span>

      <div class="home-social">
        <a href="https://www.linkedin.com/in/gaurav-kawade-35000a249/" target="_blank" class="home-social-icon"><i
            class="bx bxl-linkedin"></i></a>
        <a href="https://github.com/vatsaru" target="_blank" class="home-social-icon"><i
            class="bx bxl-github"></i></a>
      </div>

      <div class="home-img">
        <img src="imgg/profile.gif" alt="" />
      </div>
    </section>

    <!--===== ABOUT =====-->
    <section class="about section" id="about">
      <h2 class="section-title">About</h2>

      <div class="about-container bd-grid">
        <div class="about-img">
          <img src="./profile photo.jpg"  height="50px" width="50px" alt="" />
        </div>

        <div style="text-align: center">
          <h2 class="about-subtitle">I'am Ranjeet Dalave</h2>
          <p class="about-text">
            Quick learner and an aspiring full-stack web developer with core
            knowledge of FrontEnd . Looking forward to applying
            and enhancing my skills and knowledge as a developer.
          </p>
          <br />
          
          <p>
            Drop a mail ranjeetdalave474@gmail.com
            <i style="color: #4070f4; font-size: 1.2rem; cursor: pointer" class="bx bx-copy" id="copy"></i>
          </p>
        </div>
      </div>
    </section>


    <!---========Education ======--->
    <section class="education section" id="education">
      <h2 class="section-title">Education</h2>
      <div class="education-container bd-grid">
    
        <div class="education-data">
          <div class="education-names">
            <!-- <i class="bx bxl-html5 skills-icon"></i> -->
            <span class="education-name">Full Stack Web Development</span> 
            <p class="education-platform ">Qspider Institute</p>
            <p class="education-duration ">feb 2023- Present</p>

          </div>
        </div>
        </div>
      <div class="education-container bd-grid">
    
    <div class="education-data">
      <div class="education-names">
        <!-- <i class="bx bxl-html5 skills-icon"></i> -->
        <span class="education-name">B.E(Mechanical)</span>
        <p class="education-platform ">Savitribai Phule University,Pune</p>
        <p class="education-duration ">August 2018- May 2022</p>

      </div>
    </div>
    </div>

    <!--===== SKILLS =====-->
    <section class="skills section" id="skills">
      <h2 class="section-title">Skills</h2>

      <div class="skills-container bd-grid">
        <div>
          <!-- <h2 class="skills-subtitle">Front-end Skills</h2> -->
          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/html_png.png" alt="" />
              <span class="skills-name">HTML</span>
            </div>
            <!-- <div class="skills-bar skills-html"></div> 
             <div>
                <span class="skills-percentage">75%</span>
              </div>  -->
          </div>
          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/css_png.png" alt="" />
              <span class="skills-name">CSS</span>
            </div>
             <!-- <div class="skills-bar skills-css"></div>  -->
            <!-- <div>
                <span class="skills-percentage">70%</span>
              </div>  -->
          </div>
          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/java.png" alt="" />
              <span class="skills-name">Java</span>
            </div>
          </div>

          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/js_png.png" alt="" />
              <span class="skills-name">JavaScript</span>
            </div>
            <div>
              </div> 

          </div>
          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/react_png.png" alt="" />
              <span class="skills-name">React</span>
            </div>
            <div>
              </div>
          </div>
          

          
        </div>
        <div>
          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/dsa.png" alt="" />
              <span class="skills-name">Associate cloud</span>
            </div>

          </div> 


          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/sql-server.png" alt="" />
              <span class="skills-name">SQL</span>
            </div>
            <div>
              </div> 
          </div>

          <div class="skills-data">
            <div class="skills-names">
              <img class="skills-icon" src="imgg/codechef_pngbig.png" alt="" />
              <span class="skills-name">CodeChef</span>
            </div>
            <div>
              </div> 
          </div>
          <div>
             <div class="skills-data">
              <div class="skills-names">
                <img class="skills-icon" src="imgg/github.png" alt="" />
                  

                <span class="skills-name" >GitHub</span>
              </div>
            </div>
            <div class="skills-data">
              <div class="skills-names">
                <img class="skills-icon" src="imgg/leetcode1.png" alt="" />
                <span class="skills-name">LeetCode</span>
              </div>

            </div>
            
          </div>
        </div>
    </section>

    
  <footer class="footer section" id="contact">
    <h2 class="section-title">Get in Touch</h2>
    <p class="footer-title">Ranjeet Dalave</p>
    <div class="footer-social">
      <a href="https://www.linkedin.com/in/ranjeet-dalave-83337b16a" target="_blank" class="footer-icon"><i
          class="bx bxl-linkedin">
          <br />
          LinkedIn</i></a>
      <a href="" target="_blank" class="footer-icon"><i class="bx bxl-twitter">
          <br />
          Twitter</i></a>
      <a href="mailto:ranjeetdalave474@gmail.com" target="_blank" class="footer-icon"><i class="bx bx-mail-send">
          <br />
          E-mail</i></a>
      <a href="tel:+91 9766066474" target="_blank" class="footer-icon"><i class="bx bx-phone">
          <br />
          Phone</i></a>
      <a href="https://github.com/ranjeetdalave" target="_blank" class="footer-icon"><i
            class="bx bxl-github">
          <br />
          GitHub
          </i></a>
    </div>
    <p>&#169; 2023 copyright all right reserved</p>
  </footer>

  <!--===== MAIN JS =====-->
  <script>
    function myFunction(){
    var element = document.body;
    element.classList.toggle("dark-mode")
  }
  </script>
</body>

</html>
