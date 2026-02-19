<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Velmor</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: "Inter", sans-serif; }
    body { background: #0f1115; color: #e5e7eb; line-height: 1.6; }

    header {
      position: sticky; top: 0;
      background: rgba(15,17,21,0.9);
      backdrop-filter: blur(10px);
      display: flex; justify-content: space-between; align-items: center;
      padding: 16px 40px; border-bottom: 1px solid #1f2933;
    }
    .logo { font-weight: 800; letter-spacing: 1px; }
    nav a { color: #9ca3af; margin-left: 20px; text-decoration: none; transition: .2s; }
    nav a:hover { color: #fff; }

    .hero {
      min-height: 80vh; display: flex; flex-direction: column;
      justify-content: center; align-items: center; text-align: center;
      padding: 0 16px;
    }
    .hero h1 { font-size: 64px; letter-spacing: 2px; }
    .hero p { margin-top: 12px; color: #9ca3af; max-width: 640px; }

    .section { padding: 80px 8%; }
    .section h2 { font-size: 32px; margin-bottom: 24px; }
    .dark { background: #0b0d12; }

    .cards, .fonts {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }
    .card, .font-card {
      background: #141720; padding: 24px; border-radius: 12px; border: 1px solid #1f2933;
    }

    .gallery {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 16px;
    }
    .gallery img {
      width: 100%; border-radius: 12px; border: 1px solid #1f2933;
      background: #0f1115;
    }

    .font-card a {
      display: inline-block; margin-top: 12px; color: #fff; text-decoration: none;
      padding: 8px 14px; border: 1px solid #374151; border-radius: 6px;
    }
    .font-card a:hover { background: #1f2933; }

    footer {
      text-align: center; padding: 30px; color: #9ca3af; border-top: 1px solid #1f2933;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Velmor</div>
    <nav>
      <a href="#philosophy">Philosophy</a>
      <a href="#art">Art</a>
      <a href="#fonts">Fonts</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Velmor</h1>
    <p>A quiet place for philosophy, ancient art, and timeless design.</p>
  </section>

  <section id="philosophy" class="section">
    <h2>Philosophy</h2>
    <div class="cards">
      <div class="card"><h3>Greek Thought</h3><p>Reason, virtue, and the search for truth.</p></div>
      <div class="card"><h3>Indian Thought</h3><p>Inner peace, detachment, and self-knowledge.</p></div>
      <div class="card"><h3>Roman Thought</h3><p>Discipline and calm strength in chaos.</p></div>
      <div class="card"><h3>Persian Thought</h3><p>Poetry, mysticism, love, and meaning.</p></div>
    </div>
  </section>

  <section id="art" class="section dark">
    <h2>Ancient Art Gallery</h2>
    <div class="gallery">
      <img alt="Add your image here">
      <img alt="Add your image here">
      <img alt="Add your image here">
      <img alt="Add your image here">
    </div>
    <p style="margin-top:12px;color:#9ca3af;font-size:14px;">You can replace these with your own images later.</p>
  </section>

  <section id="fonts" class="section">
    <h2>Font Downloads</h2>
    <div class="fonts">
      <div class="font-card">
        <h3>Velmor Serif</h3>
        <p>Elegant serif for philosophy quotes.</p>
        <a href="#" onclick="alert('Add your font file link later')">Download</a>
      </div>
      <div class="font-card">
        <h3>Velmor Sans</h3>
        <p>Clean modern font for minimal websites.</p>
        <a href="#" onclick="alert('Add your font file link later')">Download</a>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2026 Velmor.</p>
  </footer>
</body>
</html>
