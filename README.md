<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./styles.css"/>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <title>Alfred L. Kashuru - Portfolio</title>
  </head>
  <body>
    <nav>
      <header>
        <h3>ALFRED LEWA KASHURU</h3>
        <div class="nav-links">
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#resume">Resume</a>
          <a href="#Hobbies">Hobbies</a>
          <a href="#contacts">Contacts</a>
          
        </div>
      </header>
    </nav>

    <section id="home" class="home-content">
      <img src="./live-session/DSC_3349.JPG" alt="" />
      <div class="home-desc">
        <h3>Hello world, I’m Alfred L. Kashuru</h3>
        <p>
          Hi there! I am Alfred! I am an objective oriented person committed to 
          success with excellent communication skills, leadership skills, 
          outgoing and aspiring to gain experience through interaction, 
           research and learning. A team member with analytical and interpersonal skills
            and a sound working knowledge in my area of specialization.
        </p>
        <a href="#contact"><button>Contacts</button></a>
      </div>
    </section>

    <section id="about" class="about-content">
      <div class="about-desc">
        <h3>Get To Know Me</h3>
        <p>
          Hi there! I am Alfred! To develop successful career with an organization<br> 
          that offers me an opportunity for career advancement and to be translated<br>
           into improvement growth and profitability. To work in a high energy level <br>
           and ability to make decisions and provision of proper and efficient<br>
            leadership ability in my area of specialization.
        </p>
      </div>
      <h3>About Me</h3>
    </section>

    <section id="resume" class="about-content">
      <h3>Resume</h3>
      <div class="resume-desc">
        <h3>Education</h3>
        <p>
          Hi there! I am Alfred! You might also know me as Javascript Developer.
          I've been programming for about 3months now as a Junior Stack developer.
          I've been working both with startups and individuals to help build & scale
          their businesses.
        </p> 
        <h3>Computer Skills</h3>
        <p>
          Hi there! I am Alfred! I have knowledge on computer packages 
          having fully completed at Mombasa Rifkins Business College and 
          awarded a certificate (Ms Word, Ms, Excel, Ms Access, Ms PowerPoint,
           Ms Dos, Publisher, Picture Manager, Outlook, keyboarding, Print, E-mail).
        </p>
        <h3>Other Skills</h3>
        <li>Javascript</li>
        <li>Typescript</li>
           
      </section>

      <section id="Hobbies" class="Hobbies-content">
        <div class="Hobbies-desc">
          <h3>Hobbies</h3>
          <p></p>Hi there! I love doing the 
           following during my free time<p></p>
          
            <li>Watching movies</li>      
            <li>Reading Novels</li>
            <li> Research</li>
            <li>Playing Volleyball</li>
            <li> Making friends</li>
          
        </div>
      </section>
    

    <section id="contacts" class="contact-content">
      <h3>Contact Me</h3>
      <div class="contact-desc">
        <p>Get in touch with me and grow your skills and business!</p>

        <form action="https://formspree.io/f/xoqgawvj"
        method="POST">
              
        <label for ="Name"> First Name:</label>
        <input type="text" id="name" name="name" required /> <br>

        <label for ="Name"> Second Name:</label>
        <input type="text" id="name" name="name" /> <br>

        <label for ="Name"> Last Name:</label>
        <input type="text" id="name" name="name" required /> <br>

        <label for ="email"> Email:</label> 
        <input type="text" id="email" name="Email" required /> <br> <br>

        <label for ="subject"> SUBJECT:</label>
        <input type="text" id="subject" name="subject" required /> <br>
       
            
        <textarea id="Message" name="message"
        placeholder="Message"></textarea><br>
                      
          <button>CLICK TO SUBMIT</button>
        </form>
      </div>
    </section>

    <section class="footer">
      <div class="footer-content">
        <div class="social-media">
          <a href=""><i class="fa fa-facebook"></i></a>
          <a href=""><i class="fa fa-linkedin"></i></a>
          <a href=""><i class="fa fa-instagram"></i></a>
          <a href=""><i class="fa fa-pinterest"></i></a>
          <a href=""><i class="fa fa-youtube"></i></a>
          <a href=""><i class="fa fa-whatsapp"></i></a>
          <a href=""><i class="fa fa-skype"></i></a>
        
        </div>
        <p>Built by Alfred L. Kashuru</p>
      </div>
    </section>
  </body>
</html>
