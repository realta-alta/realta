


<h1>Hi, I'm <span style="color:#e91e63;">Realta Krasniqi</span> 👋</h1>
<img align="right" src="https://i.pinimg.com/originals/82/0d/43/820d430a62d360cf71c4a46f1d305f9c.gif" width="120"/>

✨ About Me

I'm a Computer Science and Engineering graduate, specialized in Computer Graphics and Multimedia.This specialization allowed me to blend creativity with technology — something I’m truly passionate about.I love building digital experiences that are both functional and visually engaging. From designing interactive websites to experimenting with 2D/3D visuals and games.I enjoy building beautiful, interactive, and meaningful digital experiences — from web designs to small games.



---
- 🌱 Currently learning: React ,Blender, Three.js
- 🤝 Open to: Collaborations & creative coding projects
- 🎨 Outside tech: Figma, digital art, design tools
- 📬 Contact: realtakrasniqi009@gmail.com



  ✨ Fun Facts About Me

- 🎬 I love animated movies and Pixar-style 3D visuals.  
- ✈️ I dream of working abroad as a creative developer.  
- 🍫 I function best with coffee and chocolate.


---
🛠 My Skills Include

 Languages
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /> 
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
</p>

 Tools & Technologies
<p>
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white" />
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" />
</p>





---

📊 GitHub Stats


<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=realta-alta&show_icons=true&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=realta-alta&theme=radical&date_format=M%20j%5B%2C%20Y%5D" />
  <br/>

</p>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Simple Form</title>
</head>
<body>

<h2>Contact Form</h2>

<form id="contactForm">
  <label for="fname">First Name:</label><br />
  <input type="text" id="fname" name="firstname" required /><br /><br />
  
  <label for="lname">Last Name:</label><br />
  <input type="text" id="lname" name="lastname" required /><br /><br />
  
  <label for="email">Email:</label><br />
  <input type="email" id="email" name="email" required /><br /><br />
  
  <input type="submit" value="Submit" />
</form>

<script>
  document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();

    const firstName = document.getElementById('fname').value.trim();
    const lastName = document.getElementById('lname').value.trim();
    const email = document.getElementById('email').value.trim();

    if (!firstName || !lastName || !email) {
      alert('Please fill in all fields.');
      return;
    }

    alert(`Thank you, ${firstName} ${lastName}! We received your email: ${email}`);
    
    // Pas alert, mund ta pastroni formën nëse dëshironi:
    this.reset();
  });
</script>

</body>
</html>











  

