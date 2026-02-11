 <h1>Hi </h1> 
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio | Your Name</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:Arial, Helvetica, sans-serif}
    body{line-height:1.6;background:#f5f7fb;color:#333}
    header{background:#111;color:#fff;padding:20px 0}
    .container{width:90%;max-width:1100px;margin:auto}
    nav{display:flex;justify-content:space-between;align-items:center}
    nav h1{font-size:24px}
    nav ul{display:flex;list-style:none}
    nav ul li{margin-left:20px}
    nav ul li a{color:#fff;text-decoration:none;font-size:16px}

    .hero{padding:60px 0;text-align:center}
    .hero img{width:150px;height:150px;border-radius:50%;object-fit:cover;border:5px solid #111}
    .hero h2{margin-top:20px;font-size:32px}
    .hero p{margin-top:10px;color:#555}

    .section{padding:50px 0}
    .section h2{text-align:center;margin-bottom:30px;font-size:28px}

    .skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:20px}
    .card{background:#fff;padding:20px;border-radius:10px;text-align:center;box-shadow:0 4px 10px rgba(0,0,0,0.08)}

    .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px}

    footer{background:#111;color:#fff;text-align:center;padding:20px;margin-top:40px}

    @media(max-width:600px){
      nav ul{display:none}
      .hero h2{font-size:24px}
    }
  </style>
</head>
<body>

<header>
  <div class="container">
    <nav>
      <h1>My Portfolio</h1>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<section class="hero">
  <div class="container">
    <img src="https://via.placeholder.com/150" alt="profile" />
    <h2>Your Name</h2>
    <p>AI/ML & Data Science Enthusiast | Web Developer</p>
  </div>
</section>

<section id="about" class="section">
  <div class="container">
    <h2>About Me</h2>
    <p style="text-align:center;max-width:700px;margin:auto">
      I am passionate about Artificial Intelligence, Machine Learning, and Web Development. I love building modern, responsive, and user‑friendly applications.
    </p>
  </div>
</section>

<section id="skills" class="section">
  <div class="container">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">JavaScript</div>
      <div class="card">Python</div>
      <div class="card">Machine Learning</div>
      <div class="card">Node.js</div>
    </div>
  </div>
</section>

<section id="projects" class="section">
  <div class="container">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>AI Chatbot</h3>
        <p>Smart chatbot using NLP and Python.</p>
      </div>
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>Responsive personal portfolio using HTML & CSS.</p>
      </div>
      <div class="card">
        <h3>ML Prediction App</h3>
        <p>Machine learning web application.</p>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="section">
  <div class="container">
    <h2>Contact</h2>
    <p style="text-align:center">
      Email: your@email.com <br />
      GitHub: github.com/yourusername
    </p>
  </div>
</section>

<footer>
  <p>© 2026 Your Name | All Rights Reserved</p>
</footer>

</body>
</html>

<!-- <h1 align="center">Hi 👋, I'm Abhay Chintamwar</h1>
<h3 align="center">Software Engineer</h3>

<!-- <p align="left"> <img src="https://komarev.com/ghpvc/?username=abhaymadhukarchintamwar&label=Profile%20views&color=0e75b6&style=flat" alt="abhaymadhukarchintamwar" /> </p>

<p align="left"> <a href="[https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=abhaymadhukarchintamwa](https://media.licdn.com/dms/image/v2/D5603AQF_XHGb6eeJpA/profile-displayphoto-scale_200_200/B56ZwPGFU_JIAY-/0/1769779883767?e=1772668800&v=beta&t=0ZLBP84ByjewG4A_5EaHZt_VSO8_enFfgE8ePEcZlfc)r" alt="abhaymadhukarchintamwar" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=abhaymadhukarchintamwar&show_icons=true&locale=en&layout=compact" alt="abhaymadhukarchintamwar" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=abhaymadhukarchintamwar&show_icons=true&locale=en" alt="abhaymadhukarchintamwar" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=abhaymadhukarchintamwar&" alt="abhaymadhukarchintamwar" /></p> --> -->
