<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ian Mutugi | Portfolio</title>

<!-- External CSS Link Added -->
<link rel="stylesheet" href="styles.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body{
    font-family: 'Roboto', sans-serif; /* Google Font */
    font-size: 16px;                   /* Base font size */
    line-height: 1.6;                  /* Line spacing */
    color:#4c02f9;                    /* Text color */
    background-color: #9ba917;         /* Background color */
}
    
h1, h2, h3, h4, h5, h6 {
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: 650;
}   
/* NAVBAR */
nav{
    background:#111;
    color:white;
    padding:20px 50px;
    position:fixed;
    width:100%;
    top:0;
}

.nav-container{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav ul{
    list-style:none;
    display:flex;
    gap:25px;
}

nav a{
    text-decoration:none;
    color:white;
    font-weight:bold;
}

nav a:hover{
    color:#00adb5;
}

/* ABOUT SECTION */
#about{
    display:flex;
    justify-content:center;
    align-items:center;
    gap:60px;
    padding:150px 50px 80px 50px;
    flex-wrap:wrap;
    background:white;
}

#about img{
    width:250px;
    height:250px;
    object-fit:cover;
    border-radius:50%;
    border:5px solid #00adb5;
}

.about-text{
    max-width:500px;
}

.about-text h2{
    font-size:32px;
    margin-bottom:10px;
}

.about-text p{
    margin-bottom:15px;
}

/* SKILLS SECTION */
#skills{
    padding:80px 50px;
    text-align:center;
}

#skills h2{
    margin-bottom:40px;
    font-size:28px;
}

.skills-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(220px,1fr));
    gap:25px;
}

.skill{
    background:white;
    padding:30px;
    border-radius:10px;
    transition:0.3s;
}

.skill:hover{
    transform:translateY(-10px);
    box-shadow:0 10px 20px rgba(0,0,0,0.1);
}

.icon{
    font-size:40px;
    margin-bottom:15px;
}

/* CONTACT SECTION */
#contact{
    padding:80px 50px;
    background:white;
    text-align:center;
}

form{
    max-width:400px;
    margin:auto;
    display:flex;
    flex-direction:column;
    gap:15px;
}

input, textarea{
    padding:12px;
    border-radius:6px;
    border:1px solid #ccc;
}

button{
    padding:12px;
    border:none;
    background:#00adb5;
    color:white;
    border-radius:6px;
    font-weight:bold;
    cursor:pointer;
}

button:hover{
    background:#008b92;
}

/* FOOTER */
footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>
<body>

<!-- NAVIGATION -->
<nav>
    <div class="nav-container">
        <h1> Ian Mutugi</h1>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
</nav>

<!-- ABOUT -->
<section id="about">
<div class="profile-container">
    <img 
        src="https://avatars.githubusercontent.com/u/260180402?s=400&u=2eb0bcdf4034cf5d9333761d4e851b8356862baa&v=4" 
        alt="My Profile Picture"
        class="profile-pic">
</div>
        <div class="about-text">
        <h2>Hi, I'm Ian Mutugi👋</h2>
        <p><strong>Junior Web Developer</strong></p>
        <p>
            I am a passionate web developer based in Mombasa, Kenya.
            I love building innovative websites and learning emerging AI technologies.
        </p>
        <p>
            Currently improving my skills in JavaScript, Git, GitHub, HTML, CSS and Python.
        </p>
    </div>
</section>

<!-- SKILLS -->
<section id="skills">
    <h2>My Skills</h2>

    <div class="skills-grid">

        <div class="skill">
            <div class="icon">🌐</div>
            <h3>HTML</h3>
            <p>Semantic structure and clean markup</p>
        </div>

        <div class="skill">
            <div class="icon">🎨</div>
            <h3>CSS</h3>
            <p>Styling, layout, and responsive design</p>
        </div>

        <div class="skill">
            <div class="icon">⚡</div>
            <h4>JavaScript</h4>
            <p>Interactive and dynamic web features</p>
        </div>

        <div class="skill">
            <div class="icon">📱</div>
            <h5>Responsive Design</h5>
            <p>Mobile-friendly modern websites</p>
        </div>

    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Me</h2>

    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="5" placeholder="Write your message." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<!-- FOOTER -->
<footer>
    © 2026 Ian mutugi | Built with HTML & CSS
</footer>

</body>
</html>
