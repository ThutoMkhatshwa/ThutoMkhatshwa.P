# ThutoMkhatshwa.P
I am a System Support professional currently working at Gimsoi across Data Analytics Engineering, Business Development and Frontend Development. I have experience as an Audio Visual Technician at the University of Johannesburg (UJ) and skills in JavaScript and C++. I value troubleshooting, problem-solving and learning new technologies continuously.

const app = document.getElementById("app");

document.title = "Thuto Mkhatshwa | Portfolio";

// Portfolio styling
const style = document.createElement("style");

style.textContent = `
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #f7f9fc;
  color: #253247;
  line-height: 1.7;
}

header {
  background: white;
  padding: 20px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 10;
  box-shadow: 0 2px 12px #0000000c;
}

.logo {
  color: #163b68;
  font-size: 20px;
  font-weight: bold;
}

nav {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

nav a {
  color: #253247;
  text-decoration: none;
  font-size: 14px;
  font-weight: 600;
}

nav a:hover {
  color: #2478c5;
}

.hero {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 65px;
  padding: 90px 8%;
  background: white;
  flex-wrap: wrap;
}

.profile {
  width: 270px;
  height: 320px;
  object-fit: cover;
  object-position: center 25%;
  border-radius: 15px;
  border: 5px solid #e8f0fa;
  box-shadow: 0 10px 30px #163b6820;
}

.hero-content {
  max-width: 570px;
}

.intro {
  color: #2478c5;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 13px;
}

h1 {
  font-size: 43px;
  color: #163b68;
  margin: 10px 0;
  line-height: 1.2;
}

.hero h3 {
  color: #2478c5;
  margin-bottom: 15px;
}

p {
  margin-bottom: 14px;
  color: #58677a;
}

.button {
  display: inline-block;
  background: #1769aa;
  color: white;
  padding: 12px 25px;
  border-radius: 6px;
  text-decoration: none;
  margin-top: 12px;
}

.button:hover {
  background: #124d80;
}

section {
  padding: 70px 9%;
}

.section-title {
  color: #163b68;
  font-size: 29px;
  margin-bottom: 25px;
}

.card {
  background: white;
  padding: 25px;
  margin-bottom: 18px;
  border-radius: 10px;
  border: 1px solid #e5eaf1;
  box-shadow: 0 4px 15px #00000008;
}

.card h3 {
  color: #1769aa;
  margin-bottom: 8px;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.skill {
  background: #e9f2fc;
  color: #174f83;
  padding: 10px 18px;
  border-radius: 6px;
  font-weight: bold;
}

.contact a {
  color: #1769aa;
}

footer {
  text-align: center;
  background: #163b68;
  color: white;
  padding: 25px;
}

footer p {
  color: white;
}

@media(max-width: 700px) {
  header {
    flex-direction: column;
    gap: 15px;
  }

  nav {
    justify-content: center;
    gap: 12px;
  }

  .hero {
    text-align: center;
    gap: 30px;
    padding: 55px 6%;
  }

  h1 {
    font-size: 34px;
  }

  .profile {
    width: 220px;
    height: 260px;
  }

  section {
    padding: 50px 6%;
  }
}
`;

document.head.appendChild(style);

// Website content
app.innerHTML = `
<header>
  <div class="logo">THUTO MKHATSHWA</div>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#education">Education</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero">
  <img class="profile"
       src="profile.jpg"
       alt="Thuto Mkhatshwa professional photograph">

  <div class="hero-content">
    <div class="intro">WELCOME TO MY PORTFOLIO</div>

    <h1>Thuto Mkhatshwa</h1>

    <h3>System Support | Data Analytics | Front-End Development</h3>

    <p>
      I am a technology professional currently working at
      Gimsoi, contributing to Data Analytics Engineering,
      Business Development and Front-End Development.
      I am passionate about technology, problem-solving
      and creating practical digital solutions.
    </p>

    <a class="button" href="#contact">Contact Me</a>
  </div>
</div>

<section id="about">
  <h2 class="section-title">About Me</h2>

  <div class="card">
    <p>
      I am a System Support professional with an interest
      in technology, data analytics and digital innovation.
      I enjoy learning new technologies, supporting users,
      troubleshooting technical problems and contributing
      to business solutions.
    </p>

    <p>
      My professional journey includes experience in
      technical support, audio-visual technology,
      administration and customer service. I am committed
      to continuous learning and professional development.
    </p>
  </div>
</section>

<section id="skills">
  <h2 class="section-title">Technical Skills</h2>

  <div class="card">
    <div class="skills">
      <span class="skill">Python</span>
      <span class="skill">JavaScript</span>
      <span class="skill">C++</span>
      <span class="skill">Java</span>
      <span class="skill">HTML</span>
      <span class="skill">CSS</span>
      <span class="skill">System Support</span>
      <span class="skill">Data Analytics</span>
      <span class="skill">Troubleshooting</span>
      <span class="skill">Microsoft Office</span>
    </div>
  </div>
</section>

<section id="experience">
  <h2 class="section-title">Professional Experience</h2>

  <div class="card">
    <h3>Gimsoi — Current Position</h3>
    <p>
      Working across Data Analytics Engineering,
      Business Development and Front-End Development.
    </p>
  </div>

  <div class="card">
    <h3>University of Johannesburg — Audio Visual Technician</h3>
    <p>January 2025 – August 2025</p>
    <p>
      Set up, operated and maintained audio-visual equipment,
      provided technical assistance and supported events.
    </p>
  </div>

  <div class="card">
    <h3>M Sibuyi Attorneys — Office Administrator</h3>
    <p>
      Administrative support, document management,
      client information and office coordination.
    </p>
  </div>

  <div class="card">
    <h3>Tourvest Destination Retail — Retail Assistant</h3>
    <p>
      Customer service, sales support, stock management
      and handling customer queries.
    </p>
  </div>

  <div class="card">
    <h3>Auction Nation — Receptionist</h3>
    <p>
      Reception duties, visitor assistance, buyer registration
      and administrative support.
    </p>
  </div>
</section>

<section id="education">
  <h2 class="section-title">Education</h2>

  <div class="card">
    <h3>NQF Level 5 — System Support</h3>
    <p>Dynamic DNA | Currently studying</p>
  </div>

  <div class="card">
    <h3>NQF Level 4 — System Development</h3>
    <p>Dynamic DNA | 2024–2025</p>
  </div>

  <div class="card">
    <h3>BSc Animal Production</h3>
    <p>University of Limpopo | Studies not completed</p>
  </div>
</section>

<section id="contact">
  <h2 class="section-title">Get In Touch</h2>

  <div class="card contact">
    <p>Email:
      <a href="mailto:thutomachane@gmail.com">
        thutomachane@gmail.com
      </a>
    </p>

    <p>GitHub:
      <a href="https://github.com/ThutoMkhatshwa"
         target="_blank" rel="noopener noreferrer">
        ThutoMkhatshwa
      </a>
    </p>
  </div>
</section>

<footer>
  <p>
    © ${new Date().getFullYear()} Thuto Mkhatshwa.
    All rights reserved.
  </p>
</footer>
`;
