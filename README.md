<!-- 🌸 Embedded Portfolio (Like Adobe/CodePen Embed) -->
<iframe 
  srcdoc="
  <!DOCTYPE html>
  <html lang='en'>
  <head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <title>Ved's Portfolio</title>
    <link href='https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Raleway:wght@400;600&display=swap' rel='stylesheet'>
    <style>
      * { margin:0; padding:0; box-sizing:border-box; }
      body {
        max-width: 100vw;
        font-family: 'Raleway', sans-serif;
        background: linear-gradient(to bottom, #ff6fa1, #fff0f5);
        color: #4a004e;
        text-align: center;
        padding-bottom: 2rem;
      }
      .static-header {
        display:flex;
        justify-content:space-between;
        align-items:center;
        padding:0.8rem 2rem;
        font-family:'Playfair Display',serif;
        font-size:1.8rem;
        color:#fff7ff;
        font-style:italic;
        border-radius:1rem;
      }
      .container {
        display:flex;
        max-width:900px;
        background:#fff;
        border-radius:1.2rem;
        box-shadow:0 6px 30px rgba(0,0,0,0.15);
        overflow:hidden;
        margin:2rem auto;
        gap:2rem;
        padding:2rem;
      }
      .left-column {
        flex:1;
        display:flex;
        flex-direction:column;
        align-items:center;
        gap:1rem;
        border-right:2px solid #ffd6e8;
        padding-right:1.5rem;
      }
      .profile-img {
        width:140px; height:140px;
        border-radius:50%;
        object-fit:cover;
      }
      .name {
        font-family:'Playfair Display',serif;
        font-size:2.5rem;
        color:#e67394;
        font-weight:bold;
      }
      .title { font-style:italic; font-size:1.1rem; color:#6d2b50; }
      .right-column { flex:2; display:flex; flex-direction:column; gap:1rem; text-align:left; }
      .section {
        background:#fff0f4;
        border-radius:0.8rem;
        padding:1rem 1.5rem;
      }
      .section h2 {
        font-family:'Playfair Display',serif;
        font-size:1.5rem;
        color:#e94b77;
        margin-bottom:0.5rem;
      }
      ul { list-style:none; padding:0; }
      li::before { content:'• '; color:#e94b77; }
      .softwares { display:flex; flex-wrap:wrap; gap:0.5rem; }
      .software-icon {
        background:white;
        padding:0.4rem 0.6rem;
        border-radius:0.4rem;
        box-shadow:0 2px 6px rgba(0,0,0,0.1);
        font-size:0.85rem;
      }
      .projects {
        max-width:700px;
        margin:2rem auto;
        text-align:left;
        padding:1rem 1.5rem;
        background:#fff0f4;
        border-radius:1rem;
        box-shadow:0 4px 15px rgba(0,0,0,0.08);
      }
      .project-list a {
        display:block;
        margin:0.6rem 0;
        padding:0.8rem 1rem;
        background:#ffd3e6;
        color:#4a004e;
        border-radius:0.8rem;
        text-decoration:none;
        font-weight:bold;
        transition:background 0.3s ease, transform 0.3s ease;
      }
      .project-list a:hover { background:#ff92b3; color:white; transform:translateX(5px); }
      footer { margin:2rem 0; font-size:0.9rem; color:#6d2b50; }
      @media (max-width:800px) {
        .container { flex-direction:column; text-align:center; padding:1.5rem; }
        .left-column { border-right:none; border-bottom:2px solid #ffd6e8; padding-bottom:1rem; }
        .right-column { text-align:center; }
        .static-header { font-size:1rem; padding:0.6rem 1rem; }
      }
    </style>
  </head>
  <body>
    <div class='static-header'>
      <span>/Illustrator/</span><span>/Graphic Design/</span><span>/Ved V/</span>
    </div>
    <div class='container'>
      <div class='left-column'>
        <img src='7751b0cb-f3ec-40ea-90d1-796dd1a5c7b6-removebg-preview.png' alt='profile' class='profile-img'>
        <h1 class='name'>Ved</h1>
        <p class='title'>✨Electrical Engineering Student ✨<br>✨ Developer ✨</p>
      </div>
      <div class='right-column'>
        <div class='section'>
          <h2>About Me</h2>
          <p>Hi! I'm Ved! I love blending design and software together. Currently focused on building aesthetic, responsive web apps ✨</p>
        </div>
        <div class='section'>
          <h2>Education</h2>
          <ul>
            <li>B.Tech Electrical Engineering - NIT Trichy</li>
            <li>GPA: 7.5/10</li>
          </ul>
        </div>
        <div class='section'>
          <h2>Experience</h2>
          <ul>
            <li>Freelance Web Development & UI/UX Projects</li>
          </ul>
        </div>
        <div class='section'>
          <h2>Software</h2>
          <div class='softwares'>
            <span class='software-icon'>ReactJs</span>
            <span class='software-icon'>Html</span>
            <span class='software-icon'>GitHub</span>
            <span class='software-icon'>CSS</span>
            <span class='software-icon'>Python</span>
            <span class='software-icon'>Illustrator</span>
            <span class='software-icon'>Photoshop</span>
            <span class='software-icon'>Figma</span>
          </div>
        </div>
      </div>
    </div>
    <section class='projects'>
      <h2>Featured Projects</h2>
      <ul class='project-list'>
        <a href='https://github.com/heyimvm/yougamain.git'>YOUGA – Real-time Body Movement Detection</a>
        <a href='#'>Portfolio Website</a>
        <a href='https://github.com/heyimvm/fixmydrive.git'>Fix My Drive</a>
        <a href='https://github.com/heyimvm/SIPVED.git'>Student Internship Portal E-Cell</a>
      </ul>
    </section>
    <footer>
      <p>Made with 💖 by Ved | <a href='mailto:Vedavarshiniv2@gmail.com'>Contact Me</a></p>
    </footer>
  </body>
  </html>" 
  width="100%" 
  height="800" 
  style="border: 1px solid #ccc; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.15);" 
  loading="lazy">
</iframe>

