<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dexter Macaraeg | Portfolio</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Background (stars) */
    body {
      background: radial-gradient(ellipse at bottom, #0D1117 0%, #000000 100%);
      overflow-x: hidden;
      font-family: 'Fira Code', monospace;
      color: #C9D1D9;
      min-height: 100vh;
      position: relative;
    }

    /* Parallax Stars */
    .stars {
      width: 100%;
      height: 100%;
      background: transparent url('https://raw.githubusercontent.com/VincentGarreau/particles.js/master/demo/media/starfield.png') repeat top center;
      background-size: cover;
      position: absolute;
      top: 0;
      left: 0;
      z-index: 0;
      animation: moveStars 100s linear infinite;
    }

    @keyframes moveStars {
      from {background-position: 0 0;}
      to {background-position: 0 2000px;}
    }

    /* Content */
    .content {
      position: relative;
      z-index: 1;
      text-align: center;
      padding: 100px 20px;
    }

    h1 {
      font-size: 48px;
      margin-bottom: 10px;
      color: #58A6FF;
    }

    h3 {
      font-size: 24px;
      margin-bottom: 20px;
      color: #8B949E;
    }

    p {
      font-size: 18px;
      max-width: 600px;
      margin: 20px auto;
      line-height: 1.6;
    }

    hr {
      border: none;
      height: 1px;
      background: #30363D;
      margin: 40px auto;
      width: 80%;
    }

    .badges img {
      margin: 5px;
    }

    a {
      text-decoration: none;
    }

    footer {
      margin-top: 50px;
      font-size: 14px;
      color: #6E7681;
    }
  </style>
</head>

<body>

<div class="stars"></div>

<div class="content">

  <h1>Dexter Macaraeg</h1>
  <h3>UI/UX Designer | Creative Technologist</h3>

  <p>Designing Tomorrow's Digital Experiences with Purpose and Clarity.</p>

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hello%2C+I'm+Dexter!;UI%2FUX+Designer+and+Creative+Technologist." alt="Typing SVG" />

  <hr/>

  <h2>🧠 About Me</h2>
  <p>
    I'm a passionate <b>UI/UX Designer</b> focused on human-centered digital products.<br>
    I design with <b>clarity, empathy</b> and <b>purpose</b> — crafting intuitive, meaningful experiences.
  </p>

  <hr/>

  <h2>🛠 Skills & Tools</h2>

  <div class="badges">
    <img src="https://img.shields.io/badge/Figma-0D1117?style=for-the-badge&logo=figma&logoColor=F24E1E" />
    <img src="https://img.shields.io/badge/Framer-0D1117?style=for-the-badge&logo=framer&logoColor=white" />
    <img src="https://img.shields.io/badge/Canva-0D1117?style=for-the-badge&logo=canva&logoColor=00C4CC" />
    <img src="https://img.shields.io/badge/Dribbble-0D1117?style=for-the-badge&logo=dribbble&logoColor=EA4C89" />
  </div>

  <hr/>

  <h2>🤝 Let's Connect!</h2>

  <div class="badges">
    <a href="https://linkedin.com/in/dextermacaraeg">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="https://dribbble.com/dextermacaraeg">
      <img src="https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white" />
    </a>
    <a href="https://yourportfolio.com">
      <img src="https://img.shields.io/badge/Portfolio-FF6D00?style=for-the-badge&logo=web&logoColor=white" />
    </a>
  </div>

  <footer>
    © 2025 Dexter Macaraeg. All rights reserved.
  </footer>

</div>

</body>
</html>
