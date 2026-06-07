<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Markniel Vituallia | Social Media Manager</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f8fafc;
    color:#1e293b;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    background:white;
    position:sticky;
    top:0;
    box-shadow:0 2px 10px rgba(0,0,0,.05);
    z-index:100;
}

.logo{
    font-size:24px;
    font-weight:700;
    color:#2563eb;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav a{
    text-decoration:none;
    color:#334155;
    font-weight:500;
}

.hero{
    min-height:90vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:40px;
    background:linear-gradient(135deg,#2563eb,#7c3aed);
    color:white;
}

.hero-content{
    max-width:800px;
}

.hero h1{
    font-size:55px;
    margin-bottom:15px;
}

.hero p{
    font-size:20px;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:14px 28px;
    background:white;
    color:#2563eb;
    border-radius:50px;
    text-decoration:none;
    font-weight:600;
}

section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    font-size:36px;
    margin-bottom:50px;
}

.about{
    text-align:center;
    max-width:800px;
    margin:auto;
    line-height:1.8;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    margin-bottom:15px;
    color:#2563eb;
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.stat-box{
    background:white;
    padding:30px;
    text-align:center;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.stat-box h2{
    color:#2563eb;
    font-size:40px;
}

.testimonial{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
    max-width:800px;
    margin:auto;
    text-align:center;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
}

footer{
    background:#0f172a;
    color:white;
    text-align:center;
    padding:25px;
}
</style>
</head>

<body>

<nav>
    <div class="logo">Markniel</div>

    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#results">Results</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section class="hero">
    <div class="hero-content">
        <h1>Helping Brands Grow Through Social Media</h1>
        <p>
            Social Media Manager specializing in content creation,
            engagement, community management, and growth strategies.
        </p>

        <a href="#contact" class="btn">Let's Work Together</a>
    </div>
</section>

<section id="about">
    <h2 class="section-title">About Me</h2>

    <div class="about">
        <p>
            Hi, I'm Markniel. I help businesses build a stronger online
            presence through strategic content, audience engagement,
            and consistent brand messaging. My goal is to help brands
            attract customers, increase engagement, and grow their communities.
        </p>
    </div>
</section>

<section id="services">
    <h2 class="section-title">My Services</h2>

    <div class="services">

        <div class="card">
            <h3>Content Creation</h3>
            <p>Create engaging posts, reels, captions, and graphics.</p>
        </div>

        <div class="card">
            <h3>Content Scheduling</h3>
            <p>Plan and manage posting calendars for consistency.</p>
        </div>

        <div class="card">
            <h3>Community Management</h3>
            <p>Respond to comments, messages, and customer inquiries.</p>
        </div>

        <div class="card">
            <h3>Analytics Reporting</h3>
            <p>Track growth, engagement, and campaign performance.</p>
        </div>

    </div>
</section>

<section id="results">
    <h2 class="section-title">Results</h2>

    <div class="stats">

        <div class="stat-box">
            <h2>50K+</h2>
            <p>Audience Reached</p>
        </div>

        <div class="stat-box">
            <h2>300%</h2>
            <p>Engagement Growth</p>
        </div>

        <div class="stat-box">
            <h2>100+</h2>
            <p>Content Pieces Created</p>
        </div>

    </div>
</section>

<section>
    <h2 class="section-title">Client Feedback</h2>

    <div class="testimonial">
        <p>
            "Professional, responsive, and creative. Our engagement
            improved significantly after working together."
        </p>
        <br>
        <strong>- Client Testimonial</strong>
    </div>
</section>

<section id="contact" class="contact">
    <h2 class="section-title">Contact Me</h2>

    <p>Email: macnielvitualla@gmail.com</p>
    <p>Facebook: facebook.com/yourprofile</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>

    <br>

    <a href="mailto:macnielvitualla@gmail.com" class="btn">
        Send an Email
    </a>
</section>

<footer>
    © 2026 Markniel Vitualla | Social Media Manager
</footer>

</body>
</html>
