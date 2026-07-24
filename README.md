# Ex01 Portfolio
## Date:

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
~~~

HTML

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Balasurya S | Portfolio</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <main class="container">
      <header class="hero">
        <div class="hero-content">
          <div class="hero-info">
            <h1>Balasurya S</h1>
            <p>2nd Year B.E. Cyber Security Student</p>
            <p>Saveetha Engineering College</p>
          </div>

          <img class="profile-photo" src="profile.png" alt="Profile photo of Balasurya S" />
        </div>
      </header>

      <section class="intro">
        <h2>About Me</h2>
        <p>
          I am studying 2nd year B.E. Cyber Security at Saveetha Engineering
          College. I have a strong interest in cyber security, networking, and
          penetration testing.
        </p>
      </section>

      <section class="contact">
        <h2>Contact</h2>
        <p><strong>Email:</strong> <a href="mailto:balasurya.offcl@gmail.com">balasurya.offcl@gmail.com</a></p>
        <p><strong>Mobile:</strong> 9080591837</p>
        <p><strong>Location:</strong> Chennai</p>
      </section>

      <section class="skills">
        <h2>Skills</h2>
        <ul>
          <li>Cyber Security</li>
          <li>Networking</li>
          <li>Penetration Testing</li>
          <li>Security Analysis</li>
          <li>Ethical Hacking</li>
          <li>Network Defense</li>
        </ul>
      </section>

      <section class="goals">
        <h2>My Goals</h2>
        <p>
          I aim to build practical skills in security analysis, ethical hacking,
          and network defense so I can contribute to safer systems and help
          organizations protect their digital assets.
        </p>
      </section>
    </main>
  </body>
</html>

CSS

:root {
  color-scheme: light;
  color: #0f172a;
  background: #f3e8d0;
  font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  background: #f3e8d0;
  color: #0f172a;
}

.container {
  max-width: 900px;
  margin: 0 auto;
  padding: 48px 24px;
}

.hero {
  padding: 32px 28px;
  border: 1px solid rgba(15, 23, 42, 0.08);
  border-radius: 24px;
  background: #ffffff;
  box-shadow: 0 20px 45px rgba(15, 23, 42, 0.08);
}

.hero-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 32px;
  flex-wrap: wrap;
}

.hero-info {
  flex: 1 1 320px;
}

.profile-photo {
  width: 160px;
  height: 160px;
  border-radius: 0;
  object-fit: cover;
  border: 4px solid #0f172a;
  flex-shrink: 0;
}

.hero h1 {
  margin: 0;
  font-size: clamp(2.5rem, 4vw, 4rem);
  letter-spacing: -0.04em;
  color: #0f172a;
}

.hero p {
  margin: 12px 0 0;
  color: #334155;
  line-height: 1.6;
}

section {
  margin-top: 32px;
  padding: 28px 26px;
  border-radius: 24px;
  background: #fff9f0;
  border: 1px solid rgba(15, 23, 42, 0.08);
}

h2 {
  margin-top: 0;
  color: #0f172a;
}

a {
  color: #0f172a;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

ul {
  margin: 0;
  padding-left: 1.3rem;
}

li {
  margin: 0.5rem 0;
}

p {
  color: #334155;
  line-height: 1.8;
}

~~~

## OUTPUT

<img width="1920" height="1028" alt="Screenshot 2026-07-24 220923" src="https://github.com/user-attachments/assets/94868345-0982-4cf2-93d8-8132013ebd3d" />

<img width="1920" height="1017" alt="Screenshot 2026-07-24 220938" src="https://github.com/user-attachments/assets/2bcd1c53-0ddd-4fee-9353-ff7986efde99" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
