# testrepo
<!DOCTYPE html>
<html>
  <head>
    <title>Joe Lima - Portfolio</title>
    <link rel="stylesheet" href="./style.css"/>
    <script src="./script.js"></script>
  </head>
  <body>
    <!-- Navigation Bar -->
    <nav>
      <div id="home">
        <div class="profile_name">
          Joe Lima
          <div class="contact_info">
            <img src="html_finalprojimages/envelope.png" alt="https://icons8.com/icon/124377/circled-envelope"/>
          jlima@jeemail.com
        </div>
        <div style="clear:both;"></div>
        <div class="contact_info">
          <img src="html_finalprojimages/phone.png" alt="https://icons8.com/icon/124377/circled-envelope"/>
          +13456764598

        </div>
        </div>
        <div class="topdiv">
          <a class="topmenu" href="#about-me">About Me</a>
          <!-- Add the links for Skills, Projects and Recommendation here -->

        </div>
      </div>    
    </nav>

    <!-- About Me -->
    <section id="about-me" class="container">
      <div>
        <img src="ai-generated-8722946_960_720.png" class="profile_image"/>
      </div>

      <div>
          <h1>
            Hi, I'm Joe Lima! <img src="html_finalprojimages/waving-hand.png" width="60px"/>
          </h1>
          <p>
            I am a developer with 1 year of experience in both application and presentation layers.
            I have worked on applications and microservices deployed on IBM Cloud. 
            I am an avid user of IBM Watson Services and have worked on Watson Assistant, NLU, Sentiment analyzer to name a few.
          </p>
      </div>
    </section>
              
    <!-- Skills -->
    <section id="skills">
      <h2>Skills</h2>
      <div style="clear:both;"></div>

      <div class="all_skills">
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>HTML</h6>
          <p>2 years experience</p>
        </div>  

        <div class="skill">
          <img src="html_finalprojimages/js.jpeg"/>
          <h6>JavaScript</h6>
          <p>3 years experience</p>
        </div>  

        <div class="skill">
            <img src="snake-312561_960_720.png"/>
            <h6>Python</h6>
            <p>2 years experience</p>
          </div>  

          <div class="skill">
            <img src="file-7084006_640.png"/>
            <h6>Word</h6>
            <p>9 years experience</p>
          </div>  

          <div class="skill">
            <img src="html5-3384039_640.png"/>
            <h6>Photoshop</h6>
            <p>6 years experience</p>
          </div>  
  
  
        <!-- Add more skills here -->

      </div>
    </section>
          
    <!-- Projects -->
    <section class="projects" id="projects">
      <h2>
        Projects
      </h2>
      <div style="clear:both;"></div>

        <div id="projects-container" class="projects-container">
          <div class="project-card">
            <h3>Honda Bot</h3>
            <ul>
              <li>Developed a talking walking robot  for honda using HTML, CSS, JavaScript and IBM Watson Assistant</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Time Machine</h3>
            <ul>
              <li>Developed and deployed a time Machine for time travel using IBM NLU</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Fashion Model</h3>
            <ul>
              <li>Created a Fashion Model robot for the fashion industry and integrated it with a shopping cart, using stripe for payment gateway</li>
            </ul>
          </div>
    </div>
    </section>
    <div style="clear:both;"></div>

    <!-- Recommendations -->
    <section id="recommendations">
      <h2>Recommendations</h2>
      <div style="clear:both;"></div>
      <div class="all_recommendations" id="all_recommendations">
        <div class="recommendation">
          <span>&#8220;</span>
          Jane is a very quick learner and quickly grasps key concepts of Web development. 
          She got a great attitude & she is an excellent team player. 
          She has a curious mind and asks the right question. 
          She takes initiative within a team and has potentials to lead the team.
          <span>&#8221;</span>
        </div>
        <div class="recommendation">
          <span>&#8220;</span>
          Working with Jane has been an awesome experience. 
          She is highly knowledgable and always goes the extra step to make sure everything is right. 
          For any future projects that need her expertise I would definitely want to work with her again.
          <span>&#8221;</span>
        </div>
        <div class="recommendation">
          <span>&#8220;</span>
          I had worked along with Jane during the initial phase of our venture which needed Web development. 
          She is a committed resource who has in depth knowledge about the domain. 
          She will be an asset for any organisation! 
          <span>&#8221;</span>
        </div>
      </div>
    </section>

    <!-- Recommendation Form -->
    <section id="contact">
      <div class="flex_center">
        <fieldset>
          <legend class="introduction">Leave a Recommendation</legend>          
          <input type="text" placeholder="Name (Optional)"> <br/>
          <textarea id="new_recommendation" cols="500" rows="10" placeholder="Message"></textarea>
          <div class="flex_center">
            <button id="recommend_btn" onclick="addRecommendation()">Submit</button>
          </div>
        </fieldset>
      </div>
    </section>

    <div class="iconbutton">
      <a href="#home">
        <!--Add the code here for the logo to appear and the icon to be actionable-->
      </a>
    </div>

    <div class="popup" id="popup" class="flex_center">
      <img src="html_finalprojimages/checkmark--outline.svg"/>
      <h3><!-- Add appropriate text here--></h3>
      <button onclick="showPopup(false)">Ok</button>
    </div>
  </body>
</html>


