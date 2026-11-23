# My-project-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EBCO School</title>
  <style>
    * { box-sizing: border-box; }
    body { margin: 0; font-family: Arial, sans-serif; color: #243044; background: #f4f7fb; }
    header { background: #123b66; color: white; padding: 22px 8%; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; }
    header h1 { margin: 0; font-size: 25px; }
    nav a { color: white; text-decoration: none; margin-left: 20px; font-weight: bold; }
    .hero { background: linear-gradient(120deg, #e5f1ff, #ffffff); text-align: center; padding: 55px 20px; }
    .hero h2 { color: #123b66; font-size: 34px; margin: 0 0 12px; }
    main { max-width: 900px; margin: 30px auto; padding: 0 20px; }
    section { background: white; padding: 28px; margin-bottom: 22px; border-radius: 12px; box-shadow: 0 4px 16px rgba(0,0,0,.06); }
    h3 { color: #123b66; margin-top: 0; }
    .school-art { display: block; width: 100%; max-width: 520px; height: auto; margin: 18px auto 0; border-radius: 10px; }
    footer { text-align: center; background: #123b66; color: white; padding: 20px; margin-top: 35px; }
    @media (max-width: 520px) { header { gap: 14px; } nav a { margin: 0 12px 0 0; } .hero h2 { font-size: 28px; } }
  </style>
</head>
<body>
  <header>
    <h1>EBCO School</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact Us</a>
    </nav>
  </header>

  <div class="hero" id="home">
    <h2>Welcome to EBCO School</h2>
    <p>Learning today, leading tomorrow.</p>
  </div>

  <main>
    <section id="about">
      <h3>About EBCO School</h3>
      <p>EBCO School is a learning community committed to providing students with knowledge, useful skills, good character and confidence. The school encourages hard work, discipline, creativity and respect, helping learners prepare for a brighter future.</p>
      <p><strong>Our aim:</strong> To support every student in learning, growing and achieving their potential.</p>

      <svg class="school-art" viewBox="0 0 640 300" role="img" aria-label="Illustration of a school building">
        <rect width="640" height="300" fill="#e7f3ff"/>
        <circle cx="530" cy="58" r="28" fill="#ffd166"/>
        <path d="M70 255 L570 255" stroke="#6b8e5a" stroke-width="8"/>
        <rect x="170" y="115" width="300" height="140" rx="5" fill="#ffffff" stroke="#123b66" stroke-width="5"/>
        <path d="M145 120 L320 35 L495 120 Z" fill="#d95d39" stroke="#123b66" stroke-width="5"/>
        <rect x="290" y="175" width="60" height="80" fill="#8bb7df" stroke="#123b66" stroke-width="4"/>
        <g fill="#b9dcf5" stroke="#123b66" stroke-width="4">
          <rect x="195" y="145" width="48" height="42"/><rect x="397" y="145" width="48" height="42"/>
        </g>
        <path d="M219 145 V187 M195 166 H243 M421 145 V187 M397 166 H445" stroke="#123b66" stroke-width="3"/>
        <text x="320" y="105" text-anchor="middle" font-size="24" font-family="Arial" font-weight="bold" fill="#123b66">EBCO</text>
        <path d="M110 255 V190 M95 205 Q110 170 125 205 M510 255 V195 M495 210 Q510 175 525 210" stroke="#477b4a" stroke-width="7" fill="none" stroke-linecap="round"/>
      </svg>
    </section>

    <section id="contact">
      <h3>Contact Us</h3>
      <p>For enquiries about EBCO School, please contact the school office.</p>
    </section>
  </main>

  <footer>
    <p>Designed by: Your Name</p>
    <p>&copy; 2026 EBCO School</p>
  </footer>
</body>
</html>
