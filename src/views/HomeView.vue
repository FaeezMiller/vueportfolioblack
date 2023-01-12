<template>
  <head>
  <title>Portfolio</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous"> -->
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
  <link rel="shortcut icon" href="https://i.postimg.cc/4NhTzjcV/smiley-PNG10.png" type="image/x-icon">
  
  <link rel="stylesheet" href="./styles/styles.css">


</head>



  <!-- Icon Bar (Sidebar - hidden on small screens) -->
  <nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
    <!-- Avatar image in top left corner -->
    <img src="https://i.postimg.cc/0j6Ss9NY/mr-robot.jpg" class="mrrobot" style="width:100% 
    ">


    <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa fa-home w3-xxlarge"></i>
      <h3>HOME</h3>
    </a>
    <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa fa-user w3-xxlarge"></i>
      <h3>ABOUT</h3>
    </a>
    <a href="#testimonials" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa-solid fa-comments w3-xxlarge"></i>
      <h3>TESTIMONIALS</h3>
    </a>
    <a href="#projects" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa-solid fa-briefcase w3-xxlarge"></i>
      <h3>PROJECTS</h3>
    </a>
    <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa-solid fa-image w3-xxlarge"></i>
      <h3>PHOTOS</h3>
    </a>
    <a href="#resume" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa fa-envelope w3-xxlarge"></i>
      <h3>RESUME</h3>
    </a>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-black">
      <i class="fa fa-envelope w3-xxlarge"></i>
      <h3>CONTACT</h3>
    </a>
  
  </nav>

  <!-- Navbar -->
  <div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
    <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
      <a href="#home" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
      <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
      <a href="#testimonials" class="w3-bar-item w3-button" style="width:25% !important">TESTIMONIALS</a>
      <a href="#projects" class="w3-bar-item w3-button" style="width:25% !important">PROJECTS</a>
      <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
      <a href="#resume" class="w3-bar-item w3-button" style="width:25% !important">RESUME</a>
      <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
    </div>
  </div>

  <body class="w3-black">
  <!-- Page Content -->
  <div class="w3-padding-large" id="main">
    <!-- Header/Home -->
    <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
      <h3>Im a </h3>
      <h1 class="w3-jumbo"><span class="w3-hide-small"></span>Moegamad Faeez Miller</h1>
       
      
     
      
      <img src="https://i.postimg.cc/wMyzQmwh/33f78851-dc97-4d4d-8b3e-7801158d376a.jpg" alt="Avatar" class="picture"
        style="height: 550px; width: 550px;">
       
    </header>


   
    

    
    <div class="-padding-64 w3-content w3-text-light-grey" id="about">
    </div>
    <h2 class="w3-padding-16 w3-text-light-grey">About</h2>
    <hr style="width:150px" class="w3-opacity">
      

        <p>I am an enthusiastic, self-motivated, reliable, responsible and hard working person. I am a mature team
          worker and adaptable to all challenging situations. I am able to work well both in a team environment as well
          as using own initiative. I am able to work well under pressure and adhere to strict deadlines. I am a hard
          working, honest individual. I am a good timekeeper, always willing to learn new skills. I am friendly, helpful
          and polite, have a good sense of humour. I am able to work independently in busy environments and also within
          a team setting. I am outgoing and tactful, and able to listen effectively when solving problems.I am a
          dedicated, organized and methodical individual. I have good interpersonal skills, am an excellent team worker
          and am keen and very willing to learn and develop new skills. I am reliable and dependable and often seek new
          responsibilities within a wide range of employment areas. I have an active and dynamic approach to work and
          getting things done. I am determined and decisive.</p>
      </div>
        
      

      <h2 class="w3-padding-16 w3-text-light-grey">My Skills</h2>
      <hr style="width:150px" class="w3-opacity">
      <!--skill bars-->
     
      <p class="w3-wide">CSS<i class="fa-brands fa-css3-alt"></i></p>
      <div class="w3-white">
        <div class="w3-dark-grey" style="height:28px;width:65%"></div>
      </div>
      <br>
      <p class="w3-wide">BOOTSTRAP<i class="fa-brands fa-bootstrap"></i></p>
      <div class="w3-white">
        <div class="w3-dark-grey" style="height:28px;width:60%"></div>
      </div>
      <br>
      <p class="w3-wide">JAVASCRIPT<i class="fa-brands fa-css3-alt"></i></p>
      <div class="w3-white">
        <div class="w3-dark-grey" style="height:28px;width:40%"></div>
      </div>
      
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">6+</span><br>
        Projects Done
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">2+</span><br>
        Happy Clients
      </div>
      <br>


      <!-- <a href="./assets/resume/Resume.png">
        <button class="w3-button w3-light-grey w3-padding-large w3-section">
          <i class="fa fa-download"></i>
          Download Resume
        </button>
      </a> -->


 
      <br>
      <br>
      <br>
      <div class="-padding-64 w3-content w3-text-light-grey" id="testimonials">
    </div>
      <h2 class="w3-padding-16 w3-text-light-grey">Testimonials</h2>
      <hr style="width:155px" class="w3-opacity">




          <img
          src="https://i.postimg.cc/kGsfxbhN/profile-1.jpg"
            alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
          <p><span class="w3-large w3-margin-right">@Camryn Herandien</span> Web developer </p>
          <p>Faeez Miller is a down to earth, kind ,creative mature colleague. Having somebody like him on your team
            makes tasks a whole lot easier and less stressful. I highly admire his work ethic and passion. </p><br>

          <img src="https://i.postimg.cc/rFCxLGbs/deno-720.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right"
            style="width:80px">
          <p><span class="w3-large w3-margin-right">@Deno Rautenbach</span> Web developer </p>
          <p>Faeez is hardworking, meticulous. Having been on a team with him I can proudly say his approach towards
            work is always steadfast and rigorous, which gets the task done without wasting time.</p><br>

          <img src="https://i.postimg.cc/bvM2RmGC/download-13.jpg" alt="Avatar"
            class="w3-left w3-circle w3-margin-right" style="width:80px">
          <p><span class="w3-large w3-margin-right">@Mu-een Slamat</span> Web developer </p>
          <p>Faeez is a funny and chilled guy. He is reliable and never hesitates to help out the next person. He always
            tries to learn a new way of doing things. He truly has a heart of gold.</p><br>

          <img src="https://i.postimg.cc/hvB77hwp/profile-pic1-720.jpg" alt="Avatar"
            class="w3-left w3-circle w3-margin-right" style="width:80px">
          <p><span class="w3-large w3-margin-right">@Matthew Thomas</span> Web developer </p>
          <p>Faeez is attentive in his ability to Listen to other's and asses what can be done, regarding Projects or
            Team Issues.<br>He is attentive in his ability to Listen to other's and asses what can be done.
          </p><br>

          <img src="https://i.postimg.cc/TPRC1h4r/DSC-3567.jpg" alt="Avatar"
          class="w3-left w3-circle w3-margin-right" style="width:80px">
            <p><span class="w3-large w3-margin-right">@John Noad</span> Web developer </p>
          <p>Faeez is a hardworking, focused individual. He is always busy, and is not afraid to put in the time and effort required to get the results he is looking for. I have a deep respect for his work ethic, and the dynamic he brings into the workplace, keeps it interesting to say the least.</p><br>
          <br>
          <br>
          <br>



          
          
          
    <div class="-padding-64 w3-content w3-text-light-grey" id="projects">
    </div>
    <h2 class="w3-padding-16 w3-text-light-grey">Projects</h2>
    <hr style="width:120px" class="w3-opacity">
           
            <div class="row">
              
              <div class="col">
                <div class="card bg-dark text-white" style="width: 18rem ;">
                  <img src="https://i.postimg.cc/C1qcBkqd/8f7687531ae2dc2d2436d157cbae5657.jpg" class="nasa" alt="...">
                  <div class="card-body">
                    <center>
                      <h5 class="card-title">NASAtrips</h5>
                    </center>
                    <p class="card-text"></p>
                    <center><a class="btn btn-dark" href="https://nasatrips.netlify.app" role="button" target="_blank">Live <i
                          class="fa-brands fa-internet-explorer"></i></a></center>
                    <center><a class="btn btn-dark" href="https://github.com/FaeezMiller/NASA.git"
                        role="button" target="_blank">GitHub <i class="fa-brands fa-github"></i></a></center>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card bg-dark text-white" style="width: 18rem ;">
                  <img src="https://i.postimg.cc/x1K3Y6Yx/f992f7f35b6f383625254680b659c6a2.jpg" class="vansltd" alt="...">
                  <div class="card-body">
                    <center>
                      <h5 class="card-title">VansLtdEdition</h5>
                    </center>
                    <p class="card-text"></p>
                    <center><a class="btn btn-dark" href="https://vansltdeomp.netlify.app" role="button" target="_blank">Live <i
                          class="fa-brands fa-internet-explorer"></i></a></center>
                    <center><a class="btn btn-dark" href="https://github.com/FaeezMiller/VANS-JSEOMP.git"
                        role="button" target="_blank">GitHub <i class="fa-brands fa-github"></i></a></center>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card bg-dark text-white" style="width: 18rem  ;">
                  <img src="https://i.postimg.cc/L4Tb4G42/images.jpg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <center>
                      <h5 class="card-title">NetflixClone</h5>
                    </center>
                    <p class="card-text"></p>
                    <center><a class="btn btn-dark" href="https://netflixreprint.netlify.app/" role="button" target="_blank">Live <i
                          class="fa-brands fa-internet-explorer"></i></a></center>
                    <center><a class="btn btn-dark" href="https://github.com/FaeezMiller/NetFLIX" role="button" target="_blank">GitHub
                        <i class="fa-brands fa-github"></i></a></center>
                  </div>
                </div>
              </div>

              <div class="col">
                <div class="card bg-dark text-white" style="width: 18rem ;">
                  <img src="https://i.postimg.cc/jqgPyLRh/Screenshot-2023-01-10-161916.png" class="port" alt="...">
                  <div class="card-body">
                    <center>
                      <h5 class="card-title">Portfolio</h5>
                    </center>
                    <p class="card-text"></p>
                    <center><a class="btn btn-dark" href="https://faeezbootstrapportfolio.netlify.app" role="button" target="_blank">Live <i
                          class="fa-brands fa-internet-explorer"></i></a></center>
                    <center><a class="btn btn-dark" href="https://github.com/FaeezMiller/Portfolio"
                        role="button" target="_blank">GitHub <i class="fa-brands fa-github"></i></a></center>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card bg-dark text-white" style="width: 18rem ;">
                  <img src="https://i.postimg.cc/C1x1fW8k/mr-robot-hackerman.jpg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <center>
                      <h5 class="card-title">MrRobot</h5>
                    </center>
                    <p class="card-text"></p>
                    <center><a class="btn btn-dark" href="https://hellofriendmrrobot.netlify.app/" role="button" target="_blank">Live <i
                          class="fa-brands fa-internet-explorer"></i></a></center>
                    <center><a class="btn btn-dark" href="https://github.com/FaeezMiller/MrRobot" role="button" target="_blank">GitHub
                        <i class="fa-brands fa-github"></i></a></center>
                  </div>
                </div>
              </div>

              

              <div class="col">
                <div class="card bg-dark text-white" style="width: 18rem ;">
                  <img src="https://i.postimg.cc/4d8GBLDp/Shelby-Company-LTD.jpg" class="shelby" alt="...">
                  <div class="card-body">
                    <center>
                      <h5 class="card-title">ShelbyLtd</h5>
                    </center>
                    <p class="card-text"></p>
                    <center><a class="btn btn-dark" href="https://shelbyltd.netlify.app/" role="button" target="_blank">Live <i
                      class="fa-brands fa-internet-explorer"></i></a></center>
                    <center><a class="btn btn-dark" href="https://github.com/FaeezMiller/ShelbyLtd.git"
                        role="button" target="_blank">GitHub <i class="fa-brands fa-github"></i></a></center>
                  </div>
                </div>
              </div>

              
            </div>
            <br>


            <!-- Portfolio Section -->
            <br>
            <br>
            <div class="-padding-64 w3-content w3-text-light-grey" id="photos">
    </div>
    <h2 class="w3-padding-16 w3-text-light-grey">Photos</h2>
    <hr style="width:120px" class="w3-opacity">

            
          
          <div class="row">
              <div class="col">
                <center><img src="https://i.postimg.cc/vmQ8JXYh/00601cce-130b-4021-88ec-eb1c01403738.jpg"
                    class="picture2"></center>
              </div>

              <div class="col">
                <center><img src="https://i.postimg.cc/6QFFNpw0/6d0137ac-dea9-4fbf-b9f2-9f3feb3c1fb6.jpg"
                    class="picture3"></center>
              </div>
          </div>

    <div class="-padding-64 w3-content w3-text-light-grey" id="resume">
    </div>
    <h2 class="w3-padding-16 w3-text-light-grey">Resume</h2>
    <hr style="width:120px" class="w3-opacity">

    <div class="container">
    <div class="row">
        <div class="col-md-12">
            <div class="main-timeline">
                <div class="timeline">
                    <x href="#" class="timeline-content">
                        <div class="timeline-year">2021</div>
                        <h3 class="title">NATIONAL SENIOR CERTIFICATE (NSC)</h3>
                        <p class="description">
                          Admission Points Score(APS)-29 |
                          BACHELOR'S DEGREE PASS
                          <br>
                          <br>
                        </p>
                    </x>
                </div>
                <div class="timeline">
                    <x href="#" class="timeline-content">
                        <div class="timeline-year">2022</div>
                        <h3 class="title">Web Development using HTML & CSS</h3>
                        <p class="description">
                          HTML/CSS Overview |
                          TEXT FORMATTING & ANCHOR LINKS |
                          CSS SPECIFICITY TYPOGRAPHY |
                          Media Queries and Animation |
                          Building responsive layouts in HTML & CSS
                        </p>
                    </x>
                </div>
                <div class="timeline">
                    <x href="#" class="timeline-content">
                        <div class="timeline-year">2022</div>
                        <h3 class="title">Bootstrap5</h3>
                        <p class="description">
                          BOOTSTRAP OUTLINE |
                          LAYOUT & GRIDS |
                          COMPONENTS |
                          UTILITIES |
                          SYNTAX |
                          Responsive development in BOOTSTRAP5
                        </p>
                    </x>
                </div>
                <div class="timeline">
                    <x href="#" class="timeline-content">
                        <div class="timeline-year">2022</div>
                        <h3 class="title">JAVASCRIPT</h3>
                        <p class="description">
                          FUNCTIONS |
                          OPERATORS-(Ternary/Logical & Precedence) |
                          CONDITIONALS |  
                          The Fetch API
                        </p>
                    </x>
                </div>
                <div class="timeline">
                    <x href="#" class="timeline-content">
                        <div class="timeline-year">2023</div>
                        <h3 class="title">VUEJS</h3>
                        <p class="description">
                          COMPUTED PROPERTIES |
                          COMPONENTS |
                          TEMPLATES |
                          ROUTING |
                          Reactivity Complexity
                        </p>
                    </x>
                </div>
            </div>
        </div>
    </div>
</div>






              <!-- Contact Section -->
              <div id="contact">
                
                <h2 class="-text-light-grey">Contact Me</h2>
                <hr style="width:180px" class="w3-opacity">

                <div class="-section">
                  <p><i class="fa fa-map-marker"></i> Location: Cape Town,SA</p>
                  <p><i class="fa fa-phone"></i> Phone: 074-7222-180</p>
                  <p><i class="fa fa-envelope"></i> Email: faeezmiller8@gmail.com</p>



                </div><br>
                <p>Let's get in touch. Send me a message:</p>

                <form action="https://formspree.io/f/mnqrglaw" method="POST" target="_blank">
                  <p><input class="-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
                  <p><input class="-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
                  <p><input class="-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
                  <p><input class="-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
                  <p>
                    <button class="w3-button w3-light-grey w3-padding-large" type="submit">
                      <i class="fa fa-paper-plane"></i> SEND MESSAGE
                    </button>
                  </p>
                </form>
              </div>

              <center>
                <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
                  <i class="fa fa-facebook-official w3-hover-opacity"></i>
                  <i class="fa fa-instagram w3-hover-opacity"></i>
                  <i class="fa fa-snapchat w3-hover-opacity"></i>
                  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
                  <i class="fa fa-twitter w3-hover-opacity"></i>
                  <i class="fa fa-linkedin w3-hover-opacity"></i>
                </footer>
              </center>

              

            </body >
          </template>

  <style>
  .mrrobot{
    height: 235px;
  }
  .picture2{
    height: 600px;
    width: 550px;
  }
  .picture3{
    height: 600px;
    width: 550px;
  }
  .port{
    height:150px ;
  }
  .vansltd{
    height:150px;
  }
  .shelby{
    height: 150px;
  }
  .nasa{
    height: 150px;
  }
  .w3-black{
    padding-left:  15%;
  }
  .w3-sidebar{
    padding: px;
    background-color: black;
  }
    body,
    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
      font-family: "Montserrat", "sans-serif"
    }
  
    .w3-row-padding img {
      margin-bottom: 12px
    }
  
    /* Set the width of the sidebar to 120px */
    .w3-sidebar {
      width: 110px;
      height: 100%;
      background: #222;
    }
  
    /* Add a left margin to the "page content" that matches the width of the sidebar (120px)
    #main {
      margin-left: 120px
    } */
  
    /* Remove margins from "page content" on small screens */
    @media only screen and (max-width: 600px) {
      #main {
        margin-left: 0
      }
    }
    
    
.main-timeline:after{
    display: block;
    clear: both;
}
.main-timeline .timeline{
    width: calc(50% + 58px);
    border-top: 2px solid white;
    float: left;
    position: relative;
    z-index: 1;
}
.main-timeline .timeline:before{
    background: white;
    width: 10px;
    height: 10px;
    border-radius: 50px;
    position: absolute;
    top: -5px;
    right: 0;
}
.main-timeline .timeline-content{
    color: white;
    text-align: center;
    padding: 15px 80px 15px 10px;
    display: block;
    position: relative;
}
.main-timeline .timeline-content:hover{ text-decoration: none; }
.main-timeline .timeline-content:before{
    content: "";
    background: #00a6f9;
    width: 15px;
    height: 100%;
    position: absolute;
    top: 0;
    right: 50px;
}
.main-timeline .timeline-year{
    font-size: 35px;
    line-height: 35px;
    font-weight: 700;
    transform: translateY(-50%) rotate(90deg);
    position: absolute;
    top: 50%;
    right: -15px;
}
.main-timeline .title{
    font-size: 22px;
    font-weight: 600;
    letter-spacing: 0.5px;
    text-transform: uppercase;
    margin: 0 0 8px;
}
.main-timeline .description{
    font-size: 16px;
    margin: 0;
}
.main-timeline .timeline:nth-child(even){ float: right; }
.main-timeline .timeline:nth-child(even):before{
    right: auto;
    left: 0;
}
.main-timeline .timeline:nth-child(even) .timeline-content{
    padding: 15px 10px 15px 80px;
}
.main-timeline .timeline:nth-child(even) .timeline-content:before{
    right: auto;
    left: 51px;
}
.main-timeline .timeline:nth-child(even) .timeline-year{
    right: auto;
    left: -15px;
}
.main-timeline .timeline:nth-child(4n+2) .timeline-content:before{ background: #ff3e7c; }
.main-timeline .timeline:nth-child(4n+3) .timeline-content:before{ background: #7438be; }
.main-timeline .timeline:nth-child(4n+4) .timeline-content:before{ background: #bdc203; }
@media screen and (max-width:767px){
    .main-timeline .timeline{ width: 100%; }
}
  </style>





