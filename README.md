<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Getachew Tadesse - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
</head>
<body>
   <header>
    <nav>
        <div class="first">GT</div>
        <ul class="links">
           <li><a href="#home">Home</a></li>
           <li><a href="#about">About</a></li>
           <li><a href="#project">Projects</a></li>
           <li><a href="#contact">Contact</a></li> 
        </ul>
    </nav>
   </header>

   <section id="home" class="live">
    <div class="hero-container">
        <!-- Profile Picture Section -->
        <div class="profile-img-container">
            <img src="geach.jp3.jpg" alt="Getachew Tadesse Profile" class="profile-img">
        </div>
        
        <div class="my-histry"> 
            <h1> I'm Getachew Tadesse</h1>
            <p>I am a passionate developer creating amazing web experiences.</p>
            <a href="#about" class="link">Learn More</a>     
        </div>
    </div>
   </section>

   <section id="about" class="aboutes">
    <h2>About Me</h2>
    <p>My name is Getachew Tadesse, and I am a third-year Computer Science student.<br> Currently, I have experience with HTML and CSS, and I plan to build interactive web applications in the future.<br> Additionally, we have group projects that we are working on, and I am excited to build collaborative solutions!</p>
   </section>

   <section id="project" class="project">
    <h2>My Projects</h2>
    <div class="project-grid">
        <div class="project-card">
            <img src="app.jp1.jfif" alt="To-Do List App">
            <h3>To-Do List App</h3>
            <p>A simple and efficient task management web app to help users organize daily activities and keep track of daily goals.</p>
        </div>
        <div class="project-card">
            <img src="imag.jp3.jfif" alt="Student Study Resource">
            <h3>Student Study Resource Exchange Portal</h3>
            <p>A collaborative web platform designed for students to easily share, discover, and download verified academic notes, past papers, and study resources.</p>
        </div>
    </div>
   </section>

   <section id="contact" class="contact">
    <h2>My Contact</h2>
    <form id="contact-form">
        <input type="text" id="name" placeholder="Username" required>
        <input type="email" id="email" placeholder="Email" required> 
        <textarea id="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Your Message</button>
    </form>
   </section>

 <footer>
    <p>&copy; 2026 My Portfolio. All rights reserved.</p>
    <div class="midea-link">
      
        <a href="https://github.com/gach" target="_blank"><i class="fab fa-github"></i></a>
        
       
        <a href="https://www.linkedin.com/in/gach" target="_blank"><i class="fab fa-linkedin"></i></a>
        
       
        <a href="https://twitter.com/gach" target="_blank"><i class="fab fa-twitter"></i></a>
        
        
        <a href="https://t.me/gach" target="_blank"><i class="fab fa-telegram"></i></a>
    </div>
</footer>

    <script src="scripts.js"></script>
</body>
</html>
