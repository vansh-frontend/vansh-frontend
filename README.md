<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vansh Dhalor | Frontend & Web Developer</title>
  <style>
    :root {
      --bg: #0D1117;
      --text: #FFFFFF;
      --accent: #A855F7;
      --secondary: #00D9FF;
      --border-radius: 10px;
    }
    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }
    h2, h3, h4 {
      color: var(--accent);
      margin-bottom: 10px;
    }
    p {
      margin: 10px 0;
    }
    .wave {
      animation: wave 2s infinite;
    }
    @keyframes wave {
      0%, 100% { transform: rotate(0deg); }
      25% { transform: rotate(15deg); }
      75% { transform: rotate(-15deg); }
    }
    .about, .skills, .portfolio, .stats, .achievements, .connect {
      background-color: rgba(255, 255, 255, 0.05);
      border-radius: var(--border-radius);
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }
    .skills img, .connect img {
      margin: 5px;
    }
    .stats img, .achievements img {
      margin: 10px;
    }
    .footer {
      text-align: center;
      margin-top: 30px;
      color: var(--secondary);
    }
    a {
      color: var(--secondary);
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2 align="center">Hey there <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30" class="wave"/>, I'm Vansh Dhalor</h2>
    <p align="center">
      <b>Frontend & Web Developer</b> | BCA Student | <b>Building Amazing Digital Experiences ✨</b>
    </p>

    <div class="about">
      <h3>💡 About Me</h3>
      <ul style="text-align:left; max-width: 600px; margin: auto;">
        <li>💻 Passionate about responsive, modern UI & interaction design</li>
        <li>🌱 Exploring advanced <b>React</b>, <b>Tailwind</b>, and cloud technologies like Firebase & Supabase</li>
        <li>⚡ Always up for creative web builds & collaborating on innovative projects</li>
        <li>🎓 Pursuing BCA at Chandigarh University (2022 – 2025)</li>
      </ul>
    </div>

    <div class="skills">
      <h3>🚀 Skills & Tools</h3>
      <p align="center">
        <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
        <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
        <img alt="JavaScript" src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
        <img alt="React" src="https://img.shields.io/badge/REACT-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
        <img alt="Tailwind CSS" src="https://img.shields.io/badge/TAILWIND_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
        <img alt="EJS" src="https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black"/>
        <img alt="Firebase" src="https://img.shields.io/badge/FIREBASE-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
        <img alt="Supabase" src="https://img.shields.io/badge/SUPABASE-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
        <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
        <br>
        <img alt="Git" src="https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white"/>
        <img alt="GitHub" src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white"/>
        <img alt="Vercel" src="https://img.shields.io/badge/VERCEL-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
        <img alt="Netlify" src="https://img.shields.io/badge/NETLIFY-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>
        <img alt="Google Sheets" src="https://img.shields.io/badge/GOOGLE_SHEETS-34A853?style=for-the-badge&logo=google-sheets&logoColor=white"/>
        <img alt="Microsoft Excel" src="https://img.shields.io/badge/EXCEL-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
      </p>
    </div>

    <div class="portfolio">
      <h3>🌍 My Portfolio</h3>
      <p align="center">
        🎨 Explore my projects and experiments →  
        <a href="https://vanshdhalor.vercel.app" target="_blank" rel="noopener noreferrer">vanshdhalor.vercel.app</a>
      </p>
    </div>

    <div class="stats">
      <h3>📊 GitHub Stats & Activity</h3>
      <div align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=vansh-frontend&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10&bg_color=0D1117&title_color=A855F7&icon_color=00D9FF&text_color=FFFFFF" alt="Vansh Dhalor GitHub Stats" />
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vansh-frontend&layout=compact&theme=tokyonight&hide_border=true&border_radius=10&bg_color=0D1117&title_color=A855F7&text_color=FFFFFF" alt="Vansh Dhalor GitHub Top Languages" />
        <img src="https://streak-stats.demolab.com?user=vansh-frontend&theme=tokyonight&hide_border=true&border_radius=10" alt="Vansh Dhalor GitHub Streak" />
      </div>
    </div>

    <div class="achievements">
      <h3>🏆 Achievements</h3>
      <div align="center">
        <img src="https://github-profile-trophy.vercel.app/?username=vansh-frontend&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&column=4"/>
      </div>
    </div>

    <div class="connect">
      <h3>📬 Connect With Me</h3>
      <p align="center">
        <a href="mailto:vanshdhalor4@gmail.com">
          <img alt="Email" src="https://img.shields.io/badge/Email-vanshdhalor4@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
        </a>
        <a href="https://linkedin.com/in/vanshdhalor" target="_blank" rel="noopener noreferrer">
          <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-vanshdhalor-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
        </a>
        <a href="https://github.com/vansh-frontend" target="_blank" rel="noopener noreferrer">
          <img alt="GitHub" src="https://img.shields.io/badge/GitHub-vansh--frontend-181717?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
        <a href="https://vanshdhalor.vercel.app" target="_blank" rel="noopener noreferrer">
          <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-vanshdhalor-580cd9?style=for-the-badge&logo=vercel&logoColor=white"/>
        </a>
      </p>
    </div>

    <div class="footer">
      <h4>⭐ Thanks for visiting my profile ⭐</h4>
      <p>Made with ❤️ by <a href="https://github.com/vansh-frontend" target="_blank" rel="noopener noreferrer">Vansh Dhalor</a></p>
    </div>
  </div>
</body>
</html>
