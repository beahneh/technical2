# technical2
personal portfolio

<!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" >
  <style>




    
    .animated {
      animation-duration: 1s;
      animation-fill-mode: both;
    }

    .animated.fadeIn {
      animation-name: fadeIn;
    }

    .animated.fadeInUp {
      animation-name: fadeInUp;
    }

    .animated.fadeInDown {
      animation-name: fadeInDown;
    }

    .animated.fadeInLeft {
      animation-name: fadeInLeft;
    }

    .animated.fadeInRight {
      animation-name: fadeInRight;
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    @keyframes fadeInUp {
      0% {
        transform: translate3d(0, 40px, 0);
        opacity: 0;
      }
      100% {
        transform: translate3d(0, 0, 0);
        opacity: 1;
      }
    }

    @keyframes fadeInDown {
      0% {
        transform: translate3d(0, -40px, 0);
        opacity: 0;
      }
      100% {
        transform: translate3d(0, 0, 0);
        opacity: 1;
      }
    }

    @keyframes fadeInLeft {
      0% {
        transform: translate3d(-40px, 0, 0);
        opacity: 0;
      }
      100% {
        transform: translate3d(0, 0, 0);
        opacity: 1;
      }
    }

    @keyframes fadeInRight {
      0% {
        transform: translate3d(40px, 0, 0);
        opacity: 0;
      }
      100% {
        transform: translate3d(0, 0, 0);
        opacity: 1;
      }
    }



  </style>
</head>
<body>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">My Portfolio</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
  <section id="hero">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h1 class="animated fadeIn">Hello, I'm Aquixa Sab</h1>
          <h2 class="animated fadeIn">Software Engineer</h2>
          <p class="animated fadeIn">Welcome to my portfolio website. Here you can find information about me, my projects, and how to reach me.</p>
        </div>
      </div>
    </div>
  </section>
  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>I'm Aquixa Sab, a passionate and experienced software engineer with a strong foundation in full-stack web development and a knack for problem-solving. With a Bachelor's degree in Computer Science and over five years of professional experience, I've had the opportunity to work on a variety of projects spanning different industries. My journey in programming began with a fascination for technology, and it has evolved into a fulfilling career where I constantly strive to learn and innovate.</p>
    </div>


<section id="about">
    <div class="container">
      <h2>Technical Expertise</h2>
      <p>Technical Expertise:

Languages: Proficient in Java, Python, JavaScript, and SQL.
Frameworks & Technologies: Experienced with Spring Boot, React.js, Node.js, and Django.
Database Systems: Skilled in MySQL, PostgreSQL, and MongoDB.
Tools & Platforms: Familiar with Git, Docker, AWS, and Heroku.</p>
    </div>



  </section>
  <section id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Personal Website (HTML, CSS, JavaScript):</h5>
              <p class="card-text">Designed and developed a personal website to showcase my portfolio, skills, and blog posts. Implemented responsive design principles for optimal viewing across devices and integrated custom animations for a polished look.</p>
              <a href="#" class="btn btn-primary">View Project</a>
            </div>
          </div>
        </div>


        </section>
  <section id="projects">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Algorithm Visualizer (Python, Flask):</h5>
              <p class="card-text">Created a web-based tool for visualizing sorting algorithms, allowing users to interactively observe algorithmic behaviors. Implemented backend logic in Python with Flask framework and utilized JavaScript for dynamic frontend updates.</p>
              <a href="#" class="btn btn-primary">View Project</a>
            </div>
          </div>
        </div>


      

        




        <!-- Add more projects here -->
      </div>
    </div>
  </section>
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form>
        

         <section id="contact">
        <div class="footer">
            
            <p>Email: aquixa.sab@gmail.com</p>
            <p>Phone: +1234567890</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/aquixasab/">Aquixa Sab</a></p>
        </div>
    </section>
