---
layout: default
title: Harryl Jo Guevara
---

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;400&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

<style>
body {
    font-family: 'Roboto', Arial, sans-serif;
    background: linear-gradient(135deg, #a1c4fd, #c2e9fb 100%);
    color: #222;
    margin: 0;
    padding: 0;
}
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: #fff;
    text-align: center;
    padding: 60px 20px 40px 20px;
    border-radius: 0 0 30px 30px;
    box-shadow: 0 6px 32px rgba(118,75,162,0.11);
}
.hero img {
    width: 160px;
    border-radius: 50%;
    border: 5px solid #fff;
    box-shadow: 0 6px 20px rgba(0,0,0,0.12);
    margin-bottom: 16px;
}
.hero h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 2.6em;
    margin: 0 0 8px 0;
}
.hero p {
    font-size: 1.25em;
    font-weight: 500;
    margin: 0 0 16px 0;
    letter-spacing: 1px;
}

.section-title {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.7em;
    color: #4c2885;
    margin-top: 40px;
    margin-bottom: 18px;
    letter-spacing: 1px;
}

.card-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 28px;
    justify-content: center;
}

.card {
    background: #fff;
    border-radius: 15px;
    box-shadow: 0 6px 24px rgba(70,80,120,0.09);
    padding: 28px 22px;
    margin-bottom: 20px;
    min-width: 250px;
    max-width: 320px;
    flex: 1 1 300px;
    transition: transform 0.18s, box-shadow 0.18s;
}
.card:hover {
    transform: translateY(-6px) scale(1.03);
    box-shadow: 0 14px 32px rgba(76,40,133,0.17);
}
.card h3 {
    margin-top: 0;
    color: #764ba2;
}
.card p {
    color: #444;
}

.skills-list, .contact-list {
    display: flex;
    flex-wrap: wrap;
    gap: 18px;
    margin: 0;
    padding: 0;
    list-style: none;
}
.skills-list li, .contact-list li {
    background: #f4f1fa;
    color: #4c2885;
    padding: 9px 18px;
    border-radius: 22px;
    font-weight: 500;
    font-size: 1.08em;
    box-shadow: 0 2px 8px rgba(76,40,133,0.06);
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    gap: 7px;
}
.contact-list a {
    color: #667eea;
    text-decoration: none;
    transition: color 0.18s;
}
.contact-list a:hover {
    color: #764ba2;
}
@media (max-width: 700px) {
    .card-grid { flex-direction: column; align-items: center; }
}
</style>

<div class="hero">
    <img src="profile.jpg" alt="Harryl Jo Guevara">
    <h1>Harryl Jo Guevara</h1>
    <p>Computer Engineering Student @ University of Bohol</p>
    <div style="font-size: 1.5em; margin-top: 10px;">
        <a href="https://github.com/Nifty2005" title="GitHub" style="color: #fff; margin: 0 12px;"><i class="fab fa-github"></i> GitHub</a>
        <a href="https://facebook.com/Harryl%20Guevara" title="Facebook" style="color: #fff; margin: 0 12px;"><i class="fab fa-facebook"></i> Facebook</a>
    </div>
</div>

<!-- About Me -->
<h2 class="section-title">🧑‍💻 About Me</h2>
<div class="card">
    <p>
        Hello! I'm a passionate technology enthusiast who loves hands-on projects and creative problem-solving.<br>
        <br>
        <b>What I do:</b>
        <ul>
            <li>Build POS systems for cafes</li>
            <li>Develop PC building websites</li>
            <li>Engineer robots (Sumobots!) for competitions</li>
        </ul>
        <b>For fun:</b>
        <ul>
            <li>Edit photos & videos</li>
            <li>Play online games</li>
            <li>Troubleshoot computers</li>
        </ul>
    </p>
</div>

<!-- Skills -->
<h2 class="section-title">🛠️ Skills</h2>
<ul class="skills-list">
    <li>🎥 Video & Photo Editing</li>
    <li>🛠️ Computer Troubleshooting</li>
    <li>🎮 Online Gaming Strategy</li>
</ul>

<!-- Certifications -->
<h2 class="section-title">📜 Certifications</h2>
<ul class="skills-list">
    <li>🤖 Sumobot Seminar</li>
    <li>🔌 PCB Design Seminar</li>
    <li>💻 ICT Congress Seminar</li>
    <li>🔷 Arduino Seminar</li>
</ul>

<!-- Projects -->
<h2 class="section-title">🚀 Projects</h2>
<div class="card-grid">
    <div class="card">
        <h3>🧾 Cafe POS System</h3>
        <p>A point-of-sale system designed for seamless and efficient cafe transactions.</p>
    </div>
    <div class="card">
        <h3>🖥️ PC Builder Website</h3>
        <p>An interactive website that assists users in configuring and planning custom PC builds.</p>
    </div>
    <div class="card">
        <h3>🤖 Sumobot</h3>
        <p>A self-engineered robot built for competitive robotics challenges.</p>
    </div>
</div>

<!-- Contact -->
<h2 class="section-title">🔗 Connect with Me</h2>
<ul class="contact-list">
    <li><a href="https://github.com/Nifty2005"><i class="fab fa-github"></i> GitHub</a></li>
    <li><a href="https://facebook.com/Harryl%20Guevara"><i class="fab fa-facebook"></i> Facebook</a></li>
</ul>

<!-- FontAwesome for icons (optional, online use only) -->
<script src="https://kit.fontawesome.com/0a1d7e7a44.js" crossorigin="anonymous"></script>
