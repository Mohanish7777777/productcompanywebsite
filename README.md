# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta property="og:site_name" content="Hi im Mohanish check my cv site">
<meta property="og:title" content="Mohanish" />
<meta property="og:description" content="Hi I'm Mohanish Founder and Admin of XAdmin a Cyber Security Researcher and Investigator  based in Chennai, India. I run a cyber security consulting company named XAdmin, where my primary responsibility is to identify vulnerabilities in various platforms. To make it a point, I have hacked into Android OS ,Google, Microsoft, Facebook, Snapchat, Upwork and more. My work involves both hacking into these platforms and securing them against potential attacks from malicious attacks." />
<meta property="og:image" itemprop="image" content="assets/images/prof.png">
	<meta property="og:image:width" content="612" />
	<meta property="og:image:height" content="612" />
	<meta property="og:image:type" content="image/png" />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:label1" content="Est. reading time" />
	<meta name="twitter:data1" content="1 minute" />
<meta property="og:type" content="website" />
  <title>Mohanish</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="assets/images/profile.ico" type="image/x-icon">

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="assets/css/style.css">

  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com/">
  <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&amp;display=swap" rel="stylesheet">
</head>

<body>

  <!--
    - #MAIN
  -->

  <main>

    <!--
      - #SIDEBAR
    -->

    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img src="assets/images/prof.png" alt="Mohanish" width="80" style="border-radius: 20px;">
        </figure>

        <div class="info-content">
          <h1 class="name" title="Mohanish">Mohanish</h1>
            <p class="title"> Admin of MohanishX</p>
          <pre>
          </pre>
          <p class="title"> Mentor at SNA</p>
          <pre>
          </pre>
          
        
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>

          <ion-icon name="chevron-down"></ion-icon>
        </button>

      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Email</p>

              <a href="mailto:mohnishkumar7777777@gmail.com" class="contact-link">mohnishkumar7777777@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Phone</p>

              <a href="tel:+917904707229" class="contact-link">+91 7904707229</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Birthday</p>

              <time datetime="2004-04-20">April 20, 2004</time>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Location</p>

              <address>Chennai, Tamil nadu, India</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          <li class="social-item">
            <a href="https://github.com/Mohanish7777777/Mohanish7777777" class="social-link">
              <ion-icon name="logo-github"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://twitter.com/Mohanish007" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://www.instagram.com/_Mohanish_007/" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

        </ul>

      </div>

    </aside>





    <!--
      - #main-content
    -->

    <div class="main-content">

      <!--
        - #NAVBAR
      -->

      <nav class="navbar">

        <ul class="navbar-list">

          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Bots</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>

        </ul>

      </nav>





      <!--
        - #ABOUT
      -->

      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">About me</h2>
        </header>

        <section class="about-text">
          <p>I'm  a Cyber Security Researcher and Investigator  based in Chennai, India. I am Owner of MohanishX services which is running sucessfully on thetimeline of 3 Year.
           
            
          </p>

          <p>
            My job is to make your Hardware/Software safe and secure from Black hat Hackers .
          </p>
           <p class="title">Ethical Hacker</p>
            <p class="title">Cyber Security Researcher</p>
             <p class="title">Penetration Tester</p>
              <p class="title">BugHunter</p>
              <p class="title">Bot Devel0per</p>
        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">What i'm doing</h3>

          <ul class="service-list">

            <li class="service-item">

              <div class="service-icon-box">
                <img src="assets/images/icon-design.svg" alt="design icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web Security</h4>

                <p class="service-item-text">
                  I found more than 150+ Security bugs and Flaws in top MNC's and small startups.
                  Beta Tester For Top Applications Like Meta Services and Google Web Application 
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Cyber Security Tool development</h4>

                <p class="service-item-text">
                 I develop tool for cyber security testing and automation. and writen script to activate the MS-office Services
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Mobile app Pentesting</h4>

                <p class="service-item-text">
                  I do both static and dynamic analysis for android and IoS.
                </p>
              </div>

            </li>

            

          </ul>

        </section>


        <!--
          - testimonials
        -->




  <section class="timeline">

    <div class="title-wrapper">
      <div class="icon-box">
        <ion-icon name="book-outline"></ion-icon>
      </div>

      <h3 class="h3">Computer Timeline </h3>
    </div>

    <ol class="timeline-list">
<li class="timeline-item">

  <h4 class="h4 timeline-item-title">In class 2 i started using computer</h4>

  <span>2012</span>

  <p class="timeline-text">
    Used For Timepass 

</li>
<li class="timeline-item">

  <h4 class="h4 timeline-item-title">In class 3 i started Drawing on it  </h4>

  <span>2013-2015</span>

  <p class="timeline-text">
      

</li>
        <li class="timeline-item">

  <h4 class="h4 timeline-item-title">in class 6 playing games</h4>

  <span>2018</span>

  <p class="timeline-text">
    

</li>
      
<li class="timeline-item">

  <h4 class="h4 timeline-item-title">download the pirated games/software in class 8</h4>

  <span>2019</span>

  <p class="timeline-text">
    sharing games to my friend via pencard even sometime in sdcard because it too cheap then pendrive

</li>
      
<li class="timeline-item">

  <h4 class="h4 timeline-item-title">rewrite the script from the original game script</h4>

  <span>2019</span>

  <p class="timeline-text">
    to modify the game and     

</li>
      
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">Finished class 10</h4>
      
        <span>2020</span>
      
        <p class="timeline-text">
          With Grage of 83%
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">in 11 in choose cs group</h4>
      
        <span>2021</span>
      
        <p class="timeline-text">
          Lockdown Batch
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">SNA Student</h4>
      
        <span>IN lockdown</span>
      
        <p class="timeline-text">
          LATHP BATCH 5 STUDENT
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">SNA Workshop Team Head </h4>
      
        <span>in next 3 month</span>
      
        <p class="timeline-text">
         
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">SNA Youngest Mentor</h4>
      
        <span>DEC 2021</span>
      
        <p class="timeline-text">
          
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">Got Interest in deploying Bot</h4>
      
        <span>2020</span>
      
        <p class="timeline-text">
          Started Learn Things In Bot Depolyment
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">Started A service called MohanishX</h4>
      
        <span>2021</span>
      
        <p class="timeline-text">
          IN node.js bot
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">Whatsapp Cheems Bot Depolyment</h4>
      
        <span>2022</span>
      
        <p class="timeline-text">
          An AIO Bot
      </p>
      </li>  
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">Saveetha College of Arts and Science</h4>
      
        <span>2022 Sep 10</span>
      
        <p class="timeline-text">
          Provided awareness to 150 Students
      
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">Now I Have 7 telegram bots and 3 whatsapp bots</h4>
      
        <span>Now</span>
      
        <p class="timeline-text">
          My Domain is started getting bigger now
      </p>
      </li>
      <li class="timeline-item">
      
        <h4 class="h4 timeline-item-title">and I have Movie Website </h4>
      
        <span>Now</span>
      
        <p class="timeline-text">
          And that is provide all lastest Movies/Ott content in a single platform 
      </p>
      </li>
      
   <p style="color:#FFF;">Username: temp-user
    Password: temp@xadmin</p>
    <button><a href="https://kaipullax.kfakeid9.workers.dev">
      Click Here to Redirect to MohanishX Movies
      <p> 
        
      </p>
 </a></button>
    </ol>
    

  </section><!--
        <section class="testimonials">

          <h3 class="h3 testimonials-title">Testimonials</h3>

          <ul class="testimonials-list has-scrollbar">

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Daniel lewis</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-2.png" alt="Jessica miller" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Jessica miller</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-3.png" alt="Emily evans" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Emily evans</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-4.png" alt="Henry william" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Henry william</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

          </ul>

        </section>


        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container>

          <div class="overlay" data-overlay></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>

              <img src="assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title>Daniel lewis</h4>

              <time datetime="2021-06-14">14 June, 2021</time>

              <div data-modal-text>
                <p>
                  Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                  lot of experience
                  and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                  consectetur adipiscing
                  elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                </p>
              </div>

            </div>

          </section>

        </div>


        <!--
          - clients
        -->

</li>
    <!--<li class="clients-item">
  <a href="#">
    <img src="./assets/images/logo-2-color.png" alt="client logo">
  </a>
</li>
  -->
          </ul>

        </section>

      </article>





      <!--
        - #RESUME
      -->

      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">BMHSS</h4>

              <span>2008 - 2022</span>

              <p class="timeline-text">
                schooling
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">SNA Student</h4>

              <span>2020 - Now</span>

              <p class="timeline-text">
                LATHP 
              </p>

            </li>
            <li class="timeline-item">
            
              <h4 class="h4 timeline-item-title">node.js</h4>
            
              <span>2022</span>
            
              <p class="timeline-text">
                Learn by selfmade
              </p>
            
            </li>
            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Saveetha Engineering College</h4>

              <span>2022 - Now</span>

              <p class="timeline-text">
                SEC 🔥
              </p> 

            </li>
          </ol>

        </section>
        <section class="skill">

          <h3 class="h3 skills-title">My skills</h3>

          <ul class="skills-list content-card">

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Cyber Security Tool development</h5>
                <data value="67">67%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Android Pentesting</h5>
                <data value="82">82%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 82%;"></div>
              </div>

            </li>
            <li class="skills-item">
            
              <div class="title-wrapper">
                <h5 class="h5">IoS Pentesting</h5>
                <data value="55">55%</data>
              </div>
            
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 55%;"></div>
              </div>
            
            </li>
            <li class="skills-item">
            
              <div class="title-wrapper">
                <h5 class="h5">Web Pentesting</h5>
                <data value="85">85%</data>
              </div>
            
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 85%;"></div>
              </div>
            
            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Hardware and IOT</h5>
                <data value="83">83%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 83%;"></div>
              </div>

            </li>
            <li class="skills-item">
            
              <div class="title-wrapper">
                <h5 class="h5">Teaching</h5>
                <data value="99">99%</data>
              </div>
            
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 99%;"></div>
              </div>
            
            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Bot Depolying</h5>
                <data value="93">93%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 93%;"></div>
              </div>

            </li>

          </ul>

        </section>

      </article>





      <!--
        - #PORTFOLIO
      -->

      <article class="" data-page="bots">

        <header>
          <h2 class="h2 article-title">Bots - Mohanish<span style="font-size:40px; color:red; font-weight:bold; font-style:italic;">X</span></h2>
        </header>
        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>

            <li class="filter-item">
              <button class="active1" data-filter-btn>Whatsapp-Bot</button>
            </li>
         

            <li class="filter-item">
              <button class="active2" data-filter-btn>Telegram-Bot</button>
            </li>
            <li class="filter-item">
              <button class="active3" data-filter-btn>MohanishX1 Movies</button>
            </li>
          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-select-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>All</button>
              </li>

              <li class="select-item">
                <button data-select-item>Whatsapp-Bots</button>
              </li>

              <li class="select-item">
                <button data-select-item>Telegram-Bots</button>
              </li>
              <li class="select-item">
                <button data-select-item>MohanishX1 Movies</button>
              </li>
            </ul>

          </div>

          <ul class="project-list">
            <li class="project-item  active" data-filter-item data-category="Whatsapp-Bots">
              <a href="https://github.com/Mohanish7777777/Bot4Mohanish" target="_blank">

                <figure class="project-img">
                  <div class="project-list-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/Bot4Mohanish.png" alt="finance" loading="lazy">
                </figure>
                <h3 class="project-title">Whatsapp Bots</h3>

                <p class="project-category">Bot4Mohanish</p>

              </a>
            </li>

            <li class="project-item  active " data-filter-item data-category="Whatsapp-Bots">
              <a href="https://github.com/Mohanish7777777/Cheems4Mohanish" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/cheems.gif" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">Cheems4Mohanish</h3>

                <p class="project-category">Whatsapp Bot</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/MirrorLeech" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="fundo" loading="lazy">
                </figure>

                <h3 class="project-title">Leecher</h3>

                <p class="project-category">Telegram Bots</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/ChatBot" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="brawlhalla" loading="lazy">
                </figure>

                <h3 class="project-title">ChatGPT</h3>

                <p class="project-category">ChatGPT in Telegram</p>

              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/Torrent-to-GDrive" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="brawlhalla" loading="lazy">
                </figure>

                <h3 class="project-title">Torrent-to-GDrive</h3>

                <p class="project-category">Magent Link Downloader and Auto Upload file in G-drive</p>

              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/Auto-Filter-Bot" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="brawlhalla" loading="lazy">
                </figure>

                <h3 class="project-title">Auto-Filter-Bot</h3>

                <p class="project-category">File Search Bot</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/EvaMaria" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="dsm." loading="lazy">
                </figure>

                <h3 class="project-title">EvaMaria</h3>

                <p class="project-category">Telegram EvaMaria</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/PYRO-RENAME-BOT" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="metaspark" loading="lazy">
                </figure>

                <h3 class="project-title">PYRO-RENAME-BOT</h3>

                <p class="project-category">Renaming Bot</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="Telegram-Bots">
              <a href="https://github.com/Mohanish7777777/All-Url-Uploader" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="summary" loading="lazy">
                </figure>

                <h3 class="project-title">All-Url-Uploader</h3>

                <p class="project-category">All File can upload via Bot</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web-security">
              <a href="https://github.com/Mohanish7777777/MohanishMusicBot" target="_blank">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="assets/images/tele.png" alt="task manager" loading="lazy">
                </figure>

                <h3 class="project-title">MohanishMusicBot</h3>

                <p class="project-category">Music Stream Bot</p>

              </a>
            </li>
          </ul>

        </section>

      </article>


      <!--
        - #CONTACT
      -->

      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <section class="mapbox" data-mapbox>
          <figure>
            <iframe
              src="https://maps.google.com/maps?q=chennai&amp;t=&amp;z=10&amp;ie=UTF8&amp;iwloc=&amp;output=embed"
              width="400" height="300" ></iframe>
          </figure>
        </section>

        <section class="contact-form">

          <h3 class="h3 form-title">Contact Details</h3>

          <ul class="contacts-list">
          
            <li class="contact-item">
          
              <div class="icon-box">
                <ion-icon name="mail-outline"></ion-icon>
              </div>
          
              <div class="contact-info">
                <p class="contact-title">Email</p>
                <a href="mailto:mohnishkumar777777@gmail.com" class="contact-link">contact@Mohanish.com</a>
              </div>
          
            </li>
          
            <li class="contact-item">
          
              <div class="icon-box">
                <ion-icon name="phone-portrait-outline"></ion-icon>
              </div>
          
              <div class="contact-info">
                <p class="contact-title">Phone</p>
          
                <a href="tel:+917904707229" class="contact-link">+91 7904707229</a>
              </div>
          
            </li>
          
            <li class="contact-item">
          
              <div class="icon-box">
                <ion-icon name="calendar-outline"></ion-icon>
              </div>
          
              <div class="contact-info">
                <p class="contact-title">Birthday</p>
          
                <time datetime="2004-20-04">April 20, 2004</time>
              </div>
          
            </li>
          
            <li class="contact-item">
          
              <div class="icon-box">
                <ion-icon src="location-outline"></ion-icon>
                
              </div>
          
              <div class="contact-info">
                <p class="contact-title">Location</p>
          
                <address>Chennai, Tamil nadu, India</address>
              </div>
          
            </li>
          
          </ul>
        </section>

      </article>

    </div>

  </main>






  <!--
    - custom js link
  -->
  <script src="assets/js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="../unpkg.com/ionicons%405.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="../unpkg.com/ionicons%405.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
### CSS CODE:


/*-----------------------------------*\
  #CUSTOM PROPERTY
\*-----------------------------------*/

:root {

  /**
   * colors
   */

  /* gradient */

  --bg-gradient-onyx: linear-gradient(
    to bottom right, 
    hsl(240, 1%, 25%) 3%, 
    hsl(0, 0%, 19%) 97%
  );
  --bg-gradient-jet: linear-gradient(
    to bottom right, 
    hsla(240, 1%, 18%, 0.251) 0%, 
    hsla(240, 2%, 11%, 0) 100%
  ), hsl(240, 2%, 13%);
  --bg-gradient-yellow-1: linear-gradient(
    to bottom right, 
    hsl(282, 100%, 71%) 0%, 
    hsla(36, 100%, 69%, 0) 50%
  );
  --bg-gradient-yellow-2: linear-gradient(
    135deg, 
    hsla(45, 100%, 71%, 0.251) 0%, 
    hsla(35, 100%, 68%, 0) 59.86%
  ), hsl(240, 2%, 13%);
  --border-gradient-onyx: linear-gradient(
    to bottom right, 
    hsl(0, 0%, 25%) 0%, 
    hsla(0, 0%, 25%, 0) 50%
  );
  --text-gradient-yellow: linear-gradient(
    to right, 
    hsl(293, 100%, 50%), 
    hsl(273, 100%, 71%)
  );

  /* solid */

  --jet: hsl(0, 0%, 22%);
  --onyx: hsl(240, 1%, 17%);
  --eerie-black-1: hsl(240, 2%, 13%);
  --eerie-black-2: hsl(240, 2%, 12%);
  --smoky-black: hsl(0, 0%, 7%);
  --white-1: hsl(0, 0%, 100%);
  --white-2: hsl(0, 0%, 98%);
  --orange-yellow-crayola: hsl(275, 100%, 46%);
  /*--orange-yellow-crayola: hsl(45, 100%, 72%);*/
  --vegas-gold: hsl(274, 100%, 50%);
  /*--vegas-gold: hsl(45, 54%, 58%);*/
  --light-gray: hsl(0, 0%, 84%);
  --light-gray-70: hsla(0, 0%, 84%, 0.7);
  --bittersweet-shimmer: hsl(0, 43%, 51%);

  /**
   * typography
   */

  /* font-family */
  --ff-poppins: 'Poppins', sans-serif;

  /* font-size */
  --fs-1: 24px;
  --fs-2: 18px;
  --fs-3: 17px;
  --fs-4: 16px;
  --fs-5: 15px;
  --fs-6: 14px;
  --fs-7: 13px;
  --fs-8: 11px;

  /* font-weight */
  --fw-300: 300;
  --fw-400: 400;
  --fw-500: 500;
  --fw-600: 600;

  /**
   * shadow
   */
  
  --shadow-1: -4px 8px 24px hsla(0, 0%, 0%, 0.25);
  --shadow-2: 0 16px 30px hsla(0, 0%, 0%, 0.25);
  --shadow-3: 0 16px 40px hsla(0, 0%, 0%, 0.25);
  --shadow-4: 0 25px 50px hsla(0, 0%, 0%, 0.15);
  --shadow-5: 0 24px 80px hsla(0, 0%, 0%, 0.25);

  /**
   * transition
   */

  --transition-1: 0.25s ease;
  --transition-2: 0.5s ease-in-out;

}





/*-----------------------------------*\
  #RESET
\*-----------------------------------*/

*, *::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

a { text-decoration: none; }

li { list-style: none; }

img, ion-icon, a, button, time, span { display: block; }

button {
  font: inherit;
  background: none;
  border: none;
  text-align: left;
  cursor: pointer;
}

input, textarea {
  display: block;
  width: 100%;
  background: none;
  font: inherit;
}

::selection {
  background: var(--orange-yellow-crayola);
  color: var(--smoky-black);
}

:focus { outline-color: var(--orange-yellow-crayola); }

html { font-family: var(--ff-poppins); }

body { background: var(--smoky-black); }





/*-----------------------------------*\
  #REUSED STYLE
\*-----------------------------------*/

.sidebar,
article {
  background: var(--eerie-black-2);
  border: 1px solid var(--jet);
  border-radius: 20px;
  padding: 15px;
  box-shadow: var(--shadow-1);
  z-index: 1;
}

.separator {
  width: 100%;
  height: 1px;
  background: var(--jet);
  margin: 16px 0;
}

.icon-box {
  position: relative;
  background: var(--border-gradient-onyx);
  width: 30px;
  height: 30px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 16px;
  color: var(--orange-yellow-crayola);
  box-shadow: var(--shadow-1);
  z-index: 1;
}

.icon-box::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--eerie-black-1);
  border-radius: inherit;
  z-index: -1;
}

.icon-box ion-icon { --ionicon-stroke-width: 35px; }

article { display: none; }

article.active {
  display: block;
  animation: fade 0.5s ease backwards;
}

@keyframes fade {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.h2,
.h3,
.h4,
.h5 {
  color: var(--white-2);
  text-transform: capitalize;
}

.h2 { font-size: var(--fs-1); }

.h3 { font-size: var(--fs-2); }

.h4 { font-size: var(--fs-4); }

.h5 {
  font-size: var(--fs-7);
  font-weight: var(--fw-500);
}

.article-title {
  position: relative;
  padding-bottom: 7px;
}

.article-title::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 30px;
  height: 3px;
  background: var(--text-gradient-yellow);
  border-radius: 3px;
}

.has-scrollbar::-webkit-scrollbar {
  width: 5px; /* for vertical scrollbar */
  height: 5px; /* for horizontal scrollbar */
}

.has-scrollbar::-webkit-scrollbar-track {
  background: var(--onyx);
  border-radius: 5px;
}

.has-scrollbar::-webkit-scrollbar-thumb {
  background: var(--orange-yellow-crayola);
  border-radius: 5px;
}

.has-scrollbar::-webkit-scrollbar-button { width: 20px; }

.content-card {
  position: relative;
  background: var(--border-gradient-onyx);
  padding: 15px;
  padding-top: 45px;
  border-radius: 14px;
  box-shadow: var(--shadow-2);
  cursor: pointer;
  z-index: 1;
}

.content-card::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--bg-gradient-jet);
  border-radius: inherit;
  z-index: -1;
}





/*-----------------------------------*\
  #MAIN
\*-----------------------------------*/

main {
  margin: 15px 12px;
  margin-bottom: 75px;
  min-width: 259px;
}





/*-----------------------------------*\
  #SIDEBAR
\*-----------------------------------*/

.sidebar {
  margin-bottom: 15px;
  max-height: 140px;
  overflow: hidden;
  transition: var(--transition-2);
}

.sidebar.active { max-height: 644px; }

.sidebar-info {
  position: relative;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 15px;
}

.avatar-box {
  background: var(--bg-gradient-onyx);
  border-radius: 20px;
}

.info-content .name {
  color: var(--white-2);
  font-size: var(--fs-3);
  font-weight: var(--fw-500);
  letter-spacing: -0.25px;
  margin-bottom: 10px;
}
.title {
  color: var(--white-1);
  background: var(--onyx);
  font-size: var(--fs-8);
  font-weight: var(--fw-300);
  width: max-content;

  padding: 3px 12px;
  border-radius: 8px;
}

.info-content .title {
  color: var(--white-1);
  background: var(--onyx);
  font-size: var(--fs-8);
  font-weight: var(--fw-300);
  width: max-content;

  padding: 3px 12px;
  border-radius: 8px;
}

.info_more-btn {
  position: absolute;
  top: -15px;
  right: -15px;
  border-radius: 0 15px;
  font-size: 13px;
  color: var(--orange-yellow-crayola);
  background: var(--border-gradient-onyx);
  padding: 10px;
  box-shadow: var(--shadow-2);
  transition: var(--transition-1);
  z-index: 1;
}

.info_more-btn::before {
  content: "";
  position: absolute;
  inset: 1px;
  border-radius: inherit;
  background: var(--bg-gradient-jet);
  transition: var(--transition-1);
  z-index: -1;
}

.info_more-btn:hover,
.info_more-btn:focus { background: var(--bg-gradient-yellow-1); }

.info_more-btn:hover::before,
.info_more-btn:focus::before { background: var(--bg-gradient-yellow-2); }

.info_more-btn span { display: none; }

.sidebar-info_more {
  opacity: 0;
  visibility: hidden;
  transition: var(--transition-2);
}

.sidebar.active .sidebar-info_more {
  opacity: 1;
  visibility: visible;
}

.contacts-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 16px;
}

.contact-item {
  min-width: 100%;
  display: flex;
  align-items: center;
  gap: 16px;
}

.contact-info {
  max-width: calc(100% - 46px);
  width: calc(100% - 46px);
}

.contact-title {
  color: var(--light-gray-70);
  font-size: var(--fs-8);
  text-transform: uppercase;
  margin-bottom: 2px;
}

.contact-info :is(.contact-link, time, address) {
  color: var(--white-2);
  font-size: var(--fs-7);
}

.contact-info address { font-style: normal; }

.social-list {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 15px;
  padding-bottom: 4px;
  padding-left: 7px;
}

.social-item .social-link {
  color: var(--light-gray-70);
  font-size: 18px;
}


.social-item .social-link:hover { color: var(--light-gray); }





/*-----------------------------------*\
  #NAVBAR
\*-----------------------------------*/

.navbar {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background: hsla(240, 1%, 17%, 0.75);
  backdrop-filter: blur(10px);
  border: 1px solid var(--jet);
  border-radius: 12px 12px 0 0;
  box-shadow: var(--shadow-2);
  z-index: 5;
}

.navbar-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding: 0 10px;
}

.navbar-link {
  color: var(--light-gray);
  font-size: var(--fs-8);
  padding: 20px 7px;
  transition: color var(--transition-1);
}

.navbar-link:hover,
.navbar-link:focus { color: var(--light-gray-70); }

.navbar-link.active { color: var(--orange-yellow-crayola); }





/*-----------------------------------*\
  #ABOUT
\*-----------------------------------*/

.about .article-title { margin-bottom: 15px; }

.about-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
}

.about-text p { margin-bottom: 15px; }



/**
 * #service 
 */

.service { margin-bottom: 35px; }

.service-title { margin-bottom: 20px; }

.service-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
}

.service-item {
  position: relative;
  background: var(--border-gradient-onyx);
  padding: 20px;
  border-radius: 14px;
  box-shadow: var(--shadow-2);
  z-index: 1;
}

.service-item::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--bg-gradient-jet);
  border-radius: inherit;
  z-index: -1;
}

.service-icon-box { margin-bottom: 10px; }

.service-icon-box img { margin: auto; }

.service-content-box { text-align: center; }

.service-item-title { margin-bottom: 7px; }

.service-item-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-3);
  line-height: 1.6;
}


/**
 * #testimonials 
 */

.testimonials { margin-bottom: 30px; }

.testimonials-title { margin-bottom: 20px; }

.testimonials-list {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 15px;
  margin: 0 -15px;
  padding: 25px 15px;
  padding-bottom: 35px;
  overflow-x: auto;
  scroll-behavior: smooth;
  overscroll-behavior-inline: contain;
  scroll-snap-type: inline mandatory;
}

.testimonials-item {
  min-width: 100%;
  scroll-snap-align: center;
}

.testimonials-avatar-box {
  position: absolute;
  top: 0;
  left: 0;
  transform: translate(15px, -25px);
  background: var(--bg-gradient-onyx);
  border-radius: 14px;
  box-shadow: var(--shadow-1);
}

.testimonials-item-title { margin-bottom: 7px; }

.testimonials-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
  display: -webkit-box;
  line-clamp: 4;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;
  overflow: hidden;
}


/**
 * #testimonials-modal
 */

.modal-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-y: auto;
  overscroll-behavior: contain;
  z-index: 20;
  pointer-events: none;
  visibility: hidden;
}

.modal-container::-webkit-scrollbar { display: none; }

.modal-container.active {
  pointer-events: all;
  visibility: visible;
}

.overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background: hsl(0, 0%, 5%);
  opacity: 0;
  visibility: hidden;
  pointer-events: none;
  z-index: 1;
  transition: var(--transition-1);
}

.overlay.active {
  opacity: 0.8;
  visibility: visible;
  pointer-events: all;
}

.testimonials-modal {
  background: var(--eerie-black-2);
  position: relative;
  padding: 15px;
  margin: 15px 12px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  box-shadow: var(--shadow-5);
  transform: scale(1.2);
  opacity: 0;
  transition: var(--transition-1);
  z-index: 2;
}

.modal-container.active .testimonials-modal {
  transform: scale(1);
  opacity: 1;
}

.modal-close-btn {
  position: absolute;
  top: 15px;
  right: 15px;
  background: var(--onyx);
  border-radius: 8px;
  width: 32px;
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: var(--white-2);
  font-size: 18px;
  opacity: 0.7;
}

.modal-close-btn:hover,
.modal-close-btn:focus { opacity: 1; }

.modal-close-btn ion-icon { --ionicon-stroke-width: 50px; }

.modal-avatar-box {
  background: var(--bg-gradient-onyx);
  width: max-content;
  border-radius: 14px;
  margin-bottom: 15px;
  box-shadow: var(--shadow-2);
}

.modal-img-wrapper > img { display: none; }

.modal-title { margin-bottom: 4px; }

.modal-content time {
  font-size: var(--fs-6);
  color: var(--light-gray-70);
  font-weight: var(--fw-300);
  margin-bottom: 10px;
}

.modal-content p {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
}
p{
  display: flex;
}

/**
 * #clients 
 */

.clients { margin-bottom: 15px; }

.clients-list {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 15px;
  margin: 0 -15px;
  padding: 25px;
  padding-bottom: 25px;
  overflow-x: auto;
  scroll-behavior: smooth;
  overscroll-behavior-inline: contain;
  scroll-snap-type: inline mandatory;
  scroll-padding-inline: 25px;
}

.clients-item {
  min-width: 50%;
  margin-left: 150px;
  scroll-snap-align: start;
}

.clients-item img {
  width: 100%;
  filter: grayscale(1);
  transition: var(--transition-1);
}

.clients-item img:hover { filter: grayscale(0); }





/*-----------------------------------*\
  #RESUME
\*-----------------------------------*/

.article-title { margin-bottom: 30px; }


/**
 * education and experience 
 */

.timeline { margin-bottom: 30px; }

.timeline .title-wrapper {
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 25px;
}

.timeline-list {
  font-size: var(--fs-6);
  margin-left: 45px;
}

.timeline-item { position: relative; }

.timeline-item:not(:last-child) { margin-bottom: 20px; }

.timeline-item-title {
  font-size: var(--fs-6);
  line-height: 1.3;
  margin-bottom: 7px;
}

.timeline-list span {
  color: var(--vegas-gold);
  font-weight: var(--fw-400);
  line-height: 1.6;
}

.timeline-item:not(:last-child)::before {
  content: "";
  position: absolute;
  top: -25px;
  left: -30px;
  width: 1px;
  height: calc(100% + 50px);
  background: var(--jet);
}

.timeline-item::after {
  content: "";
  position: absolute;
  top: 5px;
  left: -33px;
  height: 6px;
  width: 6px;
  background: var(--text-gradient-yellow);
  border-radius: 50%;
  box-shadow: 0 0 0 4px var(--jet);
}

.timeline-text {
  color: var(--light-gray);
  font-weight: var(--fw-300);
  line-height: 1.6;
}


/**
 * skills 
 */

.skills-title { margin-bottom: 20px; }

.skills-list { padding: 20px; }


.skills-item:not(:last-child) { margin-bottom: 15px; }

.skill .title-wrapper {
  display: flex;
  align-items: center;
  gap: 5px;
  margin-bottom: 8px;
}

.skill .title-wrapper data {
  color: var(--light-gray);
  font-size: var(--fs-7);
  font-weight: var(--fw-300);
}

.skill-progress-bg {
  background: var(--jet);
  width: 100%;
  height: 8px;
  border-radius: 10px;
}

.skill-progress-fill {
  background: var(--text-gradient-yellow);
  height: 100%;
  border-radius: inherit;
}





/*-----------------------------------*\
  #PORTFOLIO
\*-----------------------------------*/

.filter-list { display: none; }

.filter-select-box {
  position: relative;
  margin-bottom: 25px;
}

.filter-select {
  background: var(--eerie-black-2);
  color: var(--light-gray);
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 12px 16px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
}

.filter-select.active .select-icon { transform: rotate(0.5turn); }

.select-list {
  background: var(--eerie-black-2);
  position: absolute;
  top: calc(100% + 6px);
  width: 100%;
  padding: 6px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  z-index: 2;
  opacity: 0;
  visibility: hidden;
  pointer-events: none;
  transition: 0.15s ease-in-out;
}

.filter-select.active + .select-list {
  opacity: 1;
  visibility: visible;
  pointer-events: all;
}

.select-item button {
  background: var(--eerie-black-2);
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  text-transform: capitalize;
  width: 100%;
  padding: 8px 10px;
  border-radius: 8px;
}

.select-item button:hover { --eerie-black-2: hsl(240, 2%, 20%); }

.project-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 30px;
  margin-bottom: 10px;
}

.project-item { display: none; }

.project-item.active {
  display: block;
  animation: scaleUp 0.25s ease forwards;
}

@keyframes scaleUp {
  0% { transform: scale(0.5); }
  100% { transform: scale(1); }
}

.project-item > a { width: 100%; }

.project-img {
  position: relative;
  width: 100%;
  height: 200px;
  border-radius: 16px;
  overflow: hidden;
  margin-bottom: 15px;
}

.project-img::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: transparent;
  z-index: 1;
  transition: var(--transition-1);
}

.project-item > a:hover .project-img::before { background: hsla(0, 0%, 0%, 0.5); }

.project-item-icon-box {
  --scale: 0.8;

  background: var(--jet);
  color: var(--orange-yellow-crayola);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) scale(var(--scale));
  font-size: 20px;
  padding: 18px;
  border-radius: 12px;
  opacity: 0;
  z-index: 1;
  transition: var(--transition-1);
}

.project-item > a:hover .project-item-icon-box {
  --scale: 1;
  opacity: 1;
}

.project-item-icon-box ion-icon { --ionicon-stroke-width: 50px; }

.project-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: var(--transition-1);
}

.project-item > a:hover img { transform: scale(1.1); }

.project-title,
.project-category { margin-left: 10px; }

.project-title {
  color: var(--white-2);
  font-size: var(--fs-5);
  font-weight: var(--fw-400);
  text-transform: capitalize;
  line-height: 1.3;
}

.project-category {
  color: var(--light-gray-70);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
}





/*-----------------------------------*\
  #BLOG
\*-----------------------------------*/

.blog-posts { margin-bottom: 10px; }

.blog-posts-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
}

.blog-post-item > a {
  position: relative;
  background: var(--border-gradient-onyx);
  height: 100%;
  box-shadow: var(--shadow-4);
  border-radius: 16px;
  z-index: 1;
}

.blog-post-item > a::before {
  content: "";
  position: absolute;
  inset: 1px;
  border-radius: inherit;
  background: var(--eerie-black-1);
  z-index: -1;
}

.blog-banner-box {
  width: 100%;
  height: 200px;
  border-radius: 12px;
  overflow: hidden;
}

.blog-banner-box img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: var(--transition-1);
}

.blog-post-item > a:hover .blog-banner-box img { transform: scale(1.1); }

.blog-content { padding: 15px; }

.blog-meta {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 7px;
  margin-bottom: 10px;
}

.blog-meta :is(.blog-category, time) {
  color: var(--light-gray-70);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
}

.blog-meta .dot {
  background: var(--light-gray-70);
  width: 4px;
  height: 4px;
  border-radius: 4px;
}

.blog-item-title {
  margin-bottom: 10px;
  line-height: 1.3;
  transition: var(--transition-1);
}

.blog-post-item > a:hover .blog-item-title { color: var(--orange-yellow-crayola); }

.blog-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
}





/*-----------------------------------*\
  #CONTACT
\*-----------------------------------*/

.mapbox {
  position: relative;
  height: 250px;
  width: 100%;
  border-radius: 16px;
  margin-bottom: 30px;
  border: 1px solid var(--jet);
  overflow: hidden;
}

.mapbox figure { height: 100%; }

.mapbox iframe {
  width: 100%;
  height: 100%;
  border: none;
  filter: grayscale(1) invert(1);
}

.contact-form { margin-bottom: 10px; }

.form-title { margin-bottom: 20px; }

.input-wrapper {
  display: grid;
  grid-template-columns: 1fr;
  gap: 25px;
  margin-bottom: 25px;
}

.form-input {
  color: var(--white-2);
  font-size: var(--fs-6);
  font-weight: var(--fw-400);
  padding: 13px 20px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  outline: none;
}

.form-input::placeholder { font-weight: var(--fw-500); }

.form-input:focus { border-color: var(--orange-yellow-crayola); }

textarea.form-input {
  min-height: 100px;
  height: 120px;
  max-height: 200px;
  resize: vertical;
  margin-bottom: 25px;
}

textarea.form-input::-webkit-resizer { display: none; }

.form-input:focus:invalid { border-color: var(--bittersweet-shimmer); }

.form-btn {
  position: relative;
  width: 100%;
  background: var(--border-gradient-onyx);
  color: var(--orange-yellow-crayola);
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 13px 20px;
  border-radius: 14px;
  font-size: var(--fs-6);
  text-transform: capitalize;
  box-shadow: var(--shadow-3);
  z-index: 1;
  transition: var(--transition-1);
}

.form-btn::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--bg-gradient-jet);
  border-radius: inherit;
  z-index: -1;
  transition: var(--transition-1);
}

.form-btn ion-icon { font-size: 16px; }

.form-btn:hover { background: var(--bg-gradient-yellow-1); }

.form-btn:hover::before { background: var(--bg-gradient-yellow-2); }

.form-btn:disabled {
  opacity: 0.7;
  cursor: not-allowed;
}

.form-btn:disabled:hover { background: var(--border-gradient-onyx); }

.form-btn:disabled:hover::before { background: var(--bg-gradient-jet); }





/*-----------------------------------*\
  #RESPONSIVE
\*-----------------------------------*/

/**
 * responsive larger than 450px screen
 */

@media (min-width: 450px) {

  /**
   * client
   */

  .clients-item { min-width: calc(33.33% - 10px); }



  /**
   * #PORTFOLIO, BLOG 
   */

  .project-img,
  .blog-banner-box { height: auto; }

}





/**
 * responsive larger than 580px screen
 */

@media (min-width: 580px) {

  /**
   * CUSTOM PROPERTY
   */

  :root {

    /**
     * typography
     */

    --fs-1: 32px;
    --fs-2: 24px;
    --fs-3: 26px;
    --fs-4: 18px;
    --fs-6: 15px;
    --fs-7: 15px;
    --fs-8: 12px;

  }



  /**
   * #REUSED STYLE
   */

  .sidebar, article {
    width: 520px;
    margin-inline: auto;
    padding: 30px;
  }

  .article-title {
    font-weight: var(--fw-600);
    padding-bottom: 15px;
  }

  .article-title::after {
    width: 40px;
    height: 5px;
  }

  .icon-box {
    width: 48px;
    height: 48px;
    border-radius: 12px;
    font-size: 18px;
  }



  /**
   * #MAIN
   */

  main {
    margin-top: 60px;
    margin-bottom: 100px;
  }



  /**
   * #SIDEBAR
   */

  .sidebar {
    max-height: 180px;
    margin-bottom: 30px;
  }

  .sidebar.active { max-height: 584px; }

  .sidebar-info { gap: 25px; }

  .avatar-box { border-radius: 30px; }

  .avatar-box img { width: 120px; }

  .info-content .name { margin-bottom: 15px; }

  .info-content .title { padding: 5px 18px; }

  .info_more-btn {
    top: -30px;
    right: -30px;
    padding: 10px 15px;
  }

  .info_more-btn span {
    display: block;
    font-size: var(--fs-8);
  }

  .info_more-btn ion-icon { display: none; }

  .separator { margin: 32px 0; }

  .contacts-list { gap: 20px; }

  .contact-info {
    max-width: calc(100% - 64px);
    width: calc(100% - 64px);
  }



  /**
   * #NAVBAR
   */

  .navbar { border-radius: 20px 20px 0 0; }

  .navbar-list { gap: 20px; }

  .navbar-link { --fs-8: 14px; }



  /**
   * #ABOUT
   */

  .about .article-title { margin-bottom: 20px; }

  .about-text { margin-bottom: 40px; }

  /* service */

  .service-item {
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 18px;
    padding: 30px;
  }

  .service-icon-box {
    margin-bottom: 0;
    margin-top: 5px;
  }

  .service-content-box { text-align: left; }

  /* testimonials */

  .testimonials-title { margin-bottom: 25px; }

  .testimonials-list {
    gap: 30px;
    margin: 0 -30px;
    padding: 30px;
    padding-bottom: 35px;
  }

  .content-card {
    padding: 30px;
    padding-top: 25px;
  }

  .testimonials-avatar-box {
    transform: translate(30px, -30px);
    border-radius: 20px;
  }

  .testimonials-avatar-box img { width: 80px; }

  .testimonials-item-title {
    margin-bottom: 10px;
    margin-left: 95px;
  }

  .testimonials-text {
    line-clamp: 2;
    -webkit-line-clamp: 2;
  }

  /* testimonials modal */

  .modal-container { padding: 20px; }

  .testimonials-modal {
    display: flex;
    justify-content: flex-start;
    align-items: stretch;
    gap: 25px;
    padding: 30px;
    border-radius: 20px;
  }

  .modal-img-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .modal-avatar-box {
    border-radius: 18px;
    margin-bottom: 0;
  }

  .modal-avatar-box img { width: 65px; }

  .modal-img-wrapper > img {
    display: block;
    flex-grow: 1;
    width: 35px;
  }

  /* clients */

  .clients-list {
    gap: 50px;
    margin: 0 -30px;
    padding: 45px;
    scroll-padding-inline: 45px;
  }

  .clients-item { min-width: calc(33.33% - 35px); }



  /**
   * #RESUME
   */

  .timeline-list { margin-left: 65px; }

  .timeline-item:not(:last-child)::before { left: -40px; }

  .timeline-item::after {
    height: 8px;
    width: 8px;
    left: -43px;
  }

  .skills-item:not(:last-child) { margin-bottom: 25px; }



  /**
   * #PORTFOLIO, BLOG
   */

  .project-img, .blog-banner-box { border-radius: 16px; }

  .blog-posts-list { gap: 30px; }

  .blog-content { padding: 25px; }



  /**
   * #CONTACT
   */

  .mapbox {
    height: 380px;
    border-radius: 18px;
  }

  .input-wrapper {
    gap: 30px;
    margin-bottom: 30px;
  }

  .form-input { padding: 15px 20px; }

  textarea.form-input { margin-bottom: 30px; }

  .form-btn {
    --fs-6: 16px;
    padding: 16px 20px;
  }

  .form-btn ion-icon { font-size: 18px; }

}





/**
 * responsive larger than 768px screen
 */

@media (min-width: 768px) {

  /**
   * REUSED STYLE
   */

  .sidebar, article { width: 700px; }

  .has-scrollbar::-webkit-scrollbar-button { width: 100px; }



  /**
   * SIDEBAR
   */

  .contacts-list {
    grid-template-columns: 1fr 1fr;
    gap: 30px 15px;
  }



  /**
   * NAVBAR
   */

  .navbar-link { --fs-8: 15px; }



  /**
   * ABOUT
   */

  /* testimonials modal */

  .testimonials-modal {
    gap: 35px;
    max-width: 680px;
  }

  .modal-avatar-box img { width: 80px; }



  /**
   * PORTFOLIO
   */

  .article-title { padding-bottom: 20px; }

  .filter-select-box { display: none; }

  .filter-list {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 25px;
    padding-left: 5px;
    margin-bottom: 30px;
  }

  .filter-item button {
    color: var(--light-gray);
    font-size: var(--fs-5);
    transition: var(--transition-1);
  }

  .filter-item button:hover { color: var(--light-gray-70); }

  .filter-item button.active { color: var(--orange-yellow-crayola); }

  /* portfolio and blog grid */

  .project-list, .blog-posts-list { grid-template-columns: 1fr 1fr; }



  /**
   * CONTACT
   */

  .input-wrapper { grid-template-columns: 1fr 1fr; }

  .form-btn {
    width: max-content;
    margin-left: auto;
  }
  
}





/**
 * responsive larger than 1024px screen
 */

@media (min-width: 1024px) {

  /**
   * CUSTOM PROPERTY
   */

  :root {

    /**
    * shadow
    */

    --shadow-1: -4px 8px 24px hsla(0, 0%, 0%, 0.125);
    --shadow-2: 0 16px 30px hsla(0, 0%, 0%, 0.125);
    --shadow-3: 0 16px 40px hsla(0, 0%, 0%, 0.125);

  }



  /**
   * REUSED STYLE
   */

  .sidebar, article {
    width: 950px;
    box-shadow: var(--shadow-5);
  }



  /**
   * MAIN 
   */

  main { margin-bottom: 60px; }

  .main-content {
    position: relative;
    width: max-content;
    margin: auto;
  }



  /**
   * NAVBAR
   */

  .navbar {
    position: absolute;
    bottom: auto;
    top: 0;
    left: auto;
    right: 0;
    width: max-content;
    border-radius: 0 20px;
    padding: 0 20px;
    box-shadow: none;
  }

  .navbar-list {
    gap: 30px;
    padding: 0 20px;
  }

  .navbar-link { font-weight: var(--fw-500); }



  /**
   * ABOUT
   */

  /* service */

  .service-list {
    grid-template-columns: 1fr 1fr;
    gap: 20px 25px;
  }

  /* testimonials */

  .testimonials-item { min-width: calc(50% - 15px); }

  /* clients */

  .clients-item { min-width: calc(25% - 38px); }



  /**
   * PORTFOLIO
   */

  .project-list { grid-template-columns: repeat(3, 1fr); }



  /**
   * BLOG
   */

  .blog-banner-box { height: 230px; }

}





/**
 * responsive larger than 1250px screen
 */

@media (min-width: 1250px) {

  /**
   * RESET
   */

  body::-webkit-scrollbar { width: 20px; }

  body::-webkit-scrollbar-track { background: var(--smoky-black); }

  body::-webkit-scrollbar-thumb {
    border: 5px solid var(--smoky-black);
    background: hsla(0, 0%, 100%, 0.1);
    border-radius: 20px;
    box-shadow: inset 1px 1px 0 hsla(0, 0%, 100%, 0.11),
                inset -1px -1px 0 hsla(0, 0%, 100%, 0.11);
  }

  body::-webkit-scrollbar-thumb:hover { background: hsla(0, 0%, 100%, 0.15); }

  body::-webkit-scrollbar-button { height: 60px; }



  /**
   * REUSED STYLE
   */

  .sidebar, article { width: auto; }

  article { min-height: 100%; }



  /**
   * MAIN
   */

  main {
    max-width: 1200px;
    margin-inline: auto;
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
  }

  .main-content {
    min-width: 75%;
    width: 75%;
    margin: 0;
  }



  /**
   * SIDEBAR
   */

  .sidebar {
    position: sticky;
    top: 60px;
    max-height: max-content;
    height: 100%;
    margin-bottom: 0;
    padding-top: 60px;
    z-index: 1;
  }

  .sidebar-info { flex-direction: column; }

  .avatar-box img { width: 150px; }

  .info-content .name {
    white-space: nowrap;
    text-align: center;
  }

  .info-content .title { margin: auto; }

  .info_more-btn { display: none; }

  .sidebar-info_more {
    opacity: 1;
    visibility: visible;
  }

  .contacts-list { grid-template-columns: 1fr; }

  .contact-info :is(.contact-link) {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .contact-info :is(.contact-link, time, address) {
    --fs-7: 14px;
    font-weight: var(--fw-300);
  }

  .separator:last-of-type {
    margin: 15px 0;
    opacity: 0;
  }

  .social-list { justify-content: center; }



  /**
	 * RESUME
	 */

  .timeline-text { max-width: 700px; }

}
### JS 

// element toggle function
const elementToggleFunc = function (elem) { elem.classList.toggle("active"); }



// sidebar variables
const sidebar = document.querySelector("[data-sidebar]");
const sidebarBtn = document.querySelector("[data-sidebar-btn]");

// sidebar toggle functionality for mobile
sidebarBtn.addEventListener("click", function () { elementToggleFunc(sidebar); });



// testimonials variables
const testimonialsItem = document.querySelectorAll("[data-testimonials-item]");
const modalContainer = document.querySelector("[data-modal-container]");
const modalCloseBtn = document.querySelector("[data-modal-close-btn]");
const overlay = document.querySelector("[data-overlay]");

// modal variable
const modalImg = document.querySelector("[data-modal-img]");
const modalTitle = document.querySelector("[data-modal-title]");
const modalText = document.querySelector("[data-modal-text]");

// modal toggle function
const testimonialsModalFunc = function () {
  modalContainer.classList.toggle("active");
  overlay.classList.toggle("active");
}

// add click event to all modal items
for (let i = 0; i < testimonialsItem.length; i++) {

  testimonialsItem[i].addEventListener("click", function () {

    modalImg.src = this.querySelector("[data-testimonials-avatar]").src;
    modalImg.alt = this.querySelector("[data-testimonials-avatar]").alt;
    modalTitle.innerHTML = this.querySelector("[data-testimonials-title]").innerHTML;
    modalText.innerHTML = this.querySelector("[data-testimonials-text]").innerHTML;

    testimonialsModalFunc();

  });

}

// add click event to modal close button
modalCloseBtn.addEventListener("click", testimonialsModalFunc);
overlay.addEventListener("click", testimonialsModalFunc);



// custom select variables
const select = document.querySelector("[data-select]");
const selectItems = document.querySelectorAll("[data-select-item]");
const selectValue = document.querySelector("[data-selecct-value]");
const filterBtn = document.querySelectorAll("[data-filter-btn]");

select.addEventListener("click", function () { elementToggleFunc(this); });

// add event in all select items
for (let i = 0; i < selectItems.length; i++) {
  selectItems[i].addEventListener("click", function () {

    let selectedValue = this.innerText.toLowerCase();
    selectValue.innerText = this.innerText;
    elementToggleFunc(select);
    filterFunc(selectedValue);

  });
}

// filter variables
const filterItems = document.querySelectorAll("[data-filter-item]");

const filterFunc = function (selectedValue) {

  for (let i = 0; i < filterItems.length; i++) {

    if (selectedValue === "all") {
      filterItems[i].classList.add("active");
    } else if (selectedValue === filterItems[i].dataset.category) {
      filterItems[i].classList.add("active");
    } else {
      filterItems[i].classList.remove("active");
    }

  }

}

// add event in all filter button items for large screen
let lastClickedBtn = filterBtn[0];

for (let i = 0; i < filterBtn.length; i++) {

  filterBtn[i].addEventListener("click", function () {

    let selectedValue = this.innerText.toLowerCase();
    console.log(selectedValue);
    selectValue.innerText = this.innerText;
    filterFunc(selectedValue);
    lastClickedBtn.classList.remove("active");
    this.classList.add("active");
    lastClickedBtn = this;

  });

}



// contact form variables
const form = document.querySelector("[data-form]");
const formInputs = document.querySelectorAll("[data-form-input]");
const formBtn = document.querySelector("[data-form-btn]");

// add event to all form input field
for (let i = 0; i < formInputs.length; i++) {
  formInputs[i].addEventListener("input", function () {

    // check form validation
    if (form.checkValidity()) {
      formBtn.removeAttribute("disabled");
    } else {
      formBtn.setAttribute("disabled", "");
    }

  });
}



// page navigation variables
const navigationLinks = document.querySelectorAll("[data-nav-link]");
const pages = document.querySelectorAll("[data-page]");

// add event to all nav link
for (let i = 0; i < navigationLinks.length; i++) {
  navigationLinks[i].addEventListener("click", function () {

    for (let i = 0; i < pages.length; i++) {
      if (this.innerHTML.toLowerCase() === pages[i].dataset.page) {
        pages[i].classList.add("active");
        navigationLinks[i].classList.add("active");
        window.scrollTo(0, 0);
      } else {
        pages[i].classList.remove("active");
        navigationLinks[i].classList.remove("active");
      }
    }

  });
}

## OUTPUT:
![image](https://github.com/Mohanish7777777/productcompanywebsite/assets/111619160/5b26a2a5-21b6-4483-96f2-c34b6bf02746)
![image](https://github.com/Mohanish7777777/productcompanywebsite/assets/111619160/3c9dd0ca-35b4-4830-89b1-9dc96f53fc06)
![image](https://github.com/Mohanish7777777/productcompanywebsite/assets/111619160/547a39d3-4443-46c9-84ea-f9faa71bd026)
![image](https://github.com/Mohanish7777777/productcompanywebsite/assets/111619160/a129a545-358c-4c07-a9fb-15ec7c24a8fe)
![image](https://github.com/Mohanish7777777/productcompanywebsite/assets/111619160/f0357ed1-6e78-46fb-8ea6-39cd53303ea4)
![image](https://github.com/Mohanish7777777/productcompanywebsite/assets/111619160/c07d2dc6-df01-464f-869f-146356b0f8c7)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
