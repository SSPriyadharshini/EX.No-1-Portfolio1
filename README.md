# Ex01 Portfolio
## Date:29-08-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portfolio</title>
  <meta name="description" content="Personal portfolio – projects, skills, and contact." />
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #fce4ec, #e0f7fa);
      color: #333;
      text-align: center;
    }
    header {
      background: linear-gradient(90deg, #b39ddb, #80deea);
      color: white;
      padding: 20px 0;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: transform 0.3s, color 0.3s;
    }
    nav a:hover {
      color: #ffecb3;
      transform: scale(1.1);
    }
    .container {
      width: 80%;
      margin: auto;
      padding: 20px 0;
    }
    section {
      background: rgba(255, 255, 255, 0.9);
      padding: 20px;
      margin: 20px auto;
      border-radius: 15px;
      box-shadow: 0 8px 15px rgba(0,0,0,0.1);
      backdrop-filter: blur(8px);
      transition: transform 0.3s;
    }
    section:hover {
      transform: translateY(-5px);
    }
    h2 {
      color: #6a1b9a;
      margin-bottom: 15px;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      background: linear-gradient(90deg, #ffe0f0, #e0f7fa);
      margin: 10px auto;
      padding: 10px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: inline-block;
      width: 80%;
      font-weight: bold;
    }
    .skills {
      display: flex;
      justify-content: center;
      gap: 10px;
      flex-wrap: wrap;
    }
    .pill {
      background: linear-gradient(90deg, #ba68c8, #4dd0e1);
      color: white;
      padding: 10px 20px;
      border-radius: 25px;
      font-weight: bold;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .pill:hover {
      transform: scale(1.1);
    }
    .contact a {
      color: #6a1b9a;
      text-decoration: none;
    }
    .contact a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: linear-gradient(90deg, #b39ddb, #80deea);
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Portfolio</h1>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero" id="home">
      <h2>ASPIRING LEARNER</h2>
      <p>Hi, I'm  AATHI.S , an aspiring learner exploring the world of web development.</p>
      <p>I am passionate about creating simple and effective digital experiences. I can create a webpage, a portfolio, and a personal blog.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <p>Here are a few of the projects I've worked on:</p>
      <ul>
        <li>Personal Portfolio Website</li>
        <li>Recipe Book</li>
        <li>Contact Form</li>
      </ul>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skills">
        <div class="pill">Python</div>
        <div class="pill">Figma</div>
        <div class="pill">Django</div>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:aathi61521@gmail.com">aathi61521@gmail.com</a></p>
      <p>Phone: 9344522370</p>
      <p>Location: Chennai, India</p>
    </section>
  </main>

  <footer>
    © <span id="year"></span> AATHI All rights reserved
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

```
## OUTPUT
<img width="1544" height="834" alt="image" src="https://github.com/user-attachments/assets/a9a824b0-b7a4-4ebf-8869-05a26fb1b9a5" />
<img width="1720" height="625" alt="image" src="https://github.com/user-attachments/assets/4e7108ad-ec62-426d-a18d-0e62f62fd1cb" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
