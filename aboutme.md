---
layout: default
---

#  [About me](./aboutme.html) | [Home](./index.html) | [Contact](./contactinfo.html) | [Resources](./resources.html) | [Projects](./projects.html)


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Typewriter Effect</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      padding: 20px;
    }
    .typewriter-container {
      display: inline-block;
      overflow: hidden;
      white-space: pre-wrap; /* Preserve formatting for line breaks */
      border-right: 3px solid #000;
      animation: blink 0.7s step-end infinite;
      font-size: 18px;
      font-weight: bold;
    }
    @keyframes blink {
      from, to { border-color: transparent; }
      50% { border-color: black; }
    }
  </style>
</head>
<body>
  <h1># About Me</h1>
  <div id="typewriter" class="typewriter-container"></div>

  <script>
    const text = `
**Hi there! I'm Shane**, an IT professional with over a decade and a half of experience spanning various domains in technology. My journey in IT has allowed me to develop a broad skill set, ranging from network and system administration to cybersecurity and web development.

### Current Focus
I am currently pivoting towards becoming a **Security Operations Analyst**, with plans to transition into **Threat Intelligence** and **Penetration Testing**. My motivation is driven by a passion for protecting and securing digital infrastructures.

### Professional Background
I’ve evolved from working as a mobile, computer, and network technician to becoming deeply immersed in the world of cybersecurity. My journey has been shaped by various roles, including working as a Digital Specialist and Projectionist, where I managed both technical operations and digital systems. These experiences have honed my ability to tackle complex technical problems with creative solutions.

### Personal Interests
Outside of work, I’m an avid photographer, audiophile, and gamer. I enjoy exploring digital landscapes and honing my strategic thinking through gaming.

### Lifelong Learning
I believe that learning is a lifelong adventure. Whether I’m delving into the nuances of network security, experimenting with new culinary recipes, or exploring the latest photography techniques, my curiosity is the driving force behind all my endeavors.

### Commitment to Innovation
Beyond security, I’m dedicated to staying at the forefront of **tech innovation**. My ability to engineer high-quality prompts has led me to dive deep into AI and automation workflows, helping businesses and individuals optimize and secure their technology stacks.
    `;

    let i = 0;
    const speed = 50; // typing speed in milliseconds
    const container = document.getElementById('typewriter');

    function typeWriter() {
      if (i < text.length) {
        // Convert newline characters to <br> dynamically
        if (text.charAt(i) === '\n') {
          container.innerHTML += '<br>';
        } else {
          container.innerHTML += text.charAt(i);
        }
        i++;
        setTimeout(typeWriter, speed);
      }
    }

    typeWriter();
  </script>
</body>
</html>

