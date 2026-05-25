<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - <!-- GANTI INI: Nama Lu --></title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { 
      font-family: system-ui, sans-serif; 
      line-height: 1.6; 
      color: #1f2937;
      background: #f9fafb;
    }
    .container { max-width: 800px; margin: 0 auto; padding: 40px 20px; }
    .hero { text-align: center; margin-bottom: 60px; }
    .hero img { 
      width: 120px; height: 120px; 
      border-radius: 50%; 
      object-fit: cover; 
      margin-bottom: 20px;
      border: 4px solid #2563eb;
    }
    h1 { font-size: 2.5rem; margin-bottom: 10px; color: #111827; }
    .subtitle { font-size: 1.2rem; color: #6b7280; margin-bottom: 20px; }
    .btn { 
      display: inline-block; 
      padding: 12px 24px; 
      background: #2563eb; 
      color: white; 
      text-decoration: none; 
      border-radius: 8px;
      margin: 5px;
    }
    .btn:hover { background: #1d4ed8; }
    .section { margin-bottom: 50px; }
    h2 { font-size: 1.8rem; margin-bottom: 20px; color: #111827; }
    .skills { display: flex; flex-wrap: wrap; gap: 10px; }
    .skill { 
      background: #e0e7ff; 
      color: #3730a3; 
      padding: 8px 16px; 
      border-radius: 20px;
      font-size: 0.9rem;
    }
    .project { 
      background: white; 
      padding: 20px; 
      border-radius: 12px; 
      margin-bottom: 15px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    }
    footer { text-align: center; color: #6b7280; margin-top: 60px; }
  </style>
</head>
<body>
  <div class="container">
    
    <!-- HERO SECTION -->
    <div class="hero">
      <img src="<!-- GANTI INI: link foto lu atau ./foto.jpg -->" alt="Foto Profile">
      <h1><!-- GANTI INI: Nama Lu --></h1>
      <p class="subtitle"><!-- GANTI INI: Job/Role lu, contoh: Web Developer & Designer --></p>
      <a href="mailto:<!-- GANTI INI: email lu -->" class="btn">Contact Me</a>
      <a href="<!-- GANTI INI: link github -->" class="btn">GitHub</a>
    </div>

    <!-- ABOUT SECTION -->
    <div class="section">
      <h2>Tentang Saya</h2>
      <p><!-- GANTI INI: Tulis 2-3 kalimat tentang diri lu, skill, dan apa yang lu kerjain --></p>
    </div>

    <!-- SKILLS SECTION -->
    <div class="section">
      <h2>Skills</h2>
      <div class="skills">
        <span class="skill">HTML</span>
        <span class="skill">CSS</span>
        <span class="skill">JavaScript</span>
        <span class="skill"><!-- GANTI INI: tambah skill lu --></span>
      </div>
    </div>

    <!-- PROJECTS SECTION -->
    <div class="section">
      <h2>Project</h2>
      <div class="project">
        <h3><!-- GANTI INI: Nama Project 1 --></h3>
        <p><!-- GANTI INI: Deskripsi singkat project --></p>
        <a href="<!-- GANTI INI: link project -->" target="_blank">Lihat Project →</a>
      </div>
      <div class="project">
        <h3><!-- GANTI INI: Nama Project 2 --></h3>
        <p><!-- GANTI INI: Deskripsi singkat project --></p>
        <a href="<!-- GANTI INI: link project -->" target="_blank">Lihat Project →</a>
      </div>
    </div>

    <footer>
      <p>© 2025 <!-- GANTI INI: Nama Lu -->. Dibuat pakai Termux</p>
    </footer>

  </div>
</body>
</html>
