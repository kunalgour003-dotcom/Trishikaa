# Trishikaa 
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trishika | Magazine Style Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fafafa;
      color: #222;
    }
    header {
      padding: 30px 20px;
      text-align: center;
      background: #000;
      color: white;
      font-size: 32px;
      letter-spacing: 2px;
    }
    .hero {
      width: 100%;
      height: 60vh;
      background: url('https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e') center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 40px;
      font-weight: bold;
      text-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }
    .section-title {
      margin: 40px 0 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 0 20px 40px;
    }
    .card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 15px;
    }
    .card-title {
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 8px;
    }
    .card-text {
      font-size: 14px;
      opacity: 0.7;
      line-height: 1.5;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    TRISHIKA — OFFICIAL MAGAZINE
  </header>  <div class="hero">Elegance. Confidence. Trishika.</div>  <h2 class="section-title">Featured Moments</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c" alt="pic1">
      <div class="card-content">
        <div class="card-title">Aesthetic Vibes</div>
        <div class="card-text">Capturing the grace and glow of Trishika’s natural beauty.</div>
      </div>
    </div><div class="card">
  <img src="https://images.unsplash.com/photo-1487412912498-0447578fcca8" alt="pic2">
  <div class="card-content">
    <div class="card-title">Classic Elegance</div>
    <div class="card-text">Soft, serene, and timelessly charming — just like her.</div>
  </div>
</div>

<div class="card">
  <img src="https://images.unsplash.com/photo-1530023367847-a683933f4172" alt="pic3">
  <div class="card-content">
    <div class="card-title">Chic & Confident</div>
    <div class="card-text">A modern queen with a bold personality and warm heart.</div>
  </div>
</div>

  </div>  <footer>
    © 2025 Trishika Magazine — Made with ❤
  </footer>
</body>
</html>
