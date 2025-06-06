# <!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Sewa tanah premium di Nusa Penida untuk investasi atau pembangunan villa mewah dengan pemandangan laut spektakuler">
  <title>Sewa Tanah Premium di Nusa Penida | Investasi Strategis</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    :root {
      --primary: #2c3e50;
      --secondary: #C9A86B;
      --accent: #27ae60;
      --light: #ffffff;
      --dark: #1a1a1a;
      --text: #2c3e50;
      --text-light: #f8f9fa;
      --shadow: 0 8px 16px rgba(0,0,0,0.15);
      --transition: all 0.3s ease;
      --border-radius: 15px;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(135deg, #f5f7fa 0%, #e4e8eb 100%);
      color: var(--text);
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* Header Styles */
    header {
      position: relative;
      background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
                  url('https://png.pngtree.com/thumb_back/fw800/background/20240715/pngtree-leaves-of-banana-abstract-green-dark-texture-nature-background-tropical-leaf-image_16003764.jpg') center/cover no-repeat;
      height: 100vh;
      min-height: 600px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: var(--text-light);
      overflow: hidden;
    }

    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: linear-gradient(135deg, rgba(44,62,80,0.7) 0%, rgba(0,0,0,0.7) 100%);
      z-index: 1;
    }

    header .overlay {
      position: relative;
      z-index: 2;
      padding: 0 1.5rem;
      max-width: 800px;
      animation: fadeInUp 1s ease-out;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2.5rem, 5vw, 4rem);
      margin-bottom: 1.5rem;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
      line-height: 1.2;
    }

    header p {
      font-size: clamp(1rem, 2vw, 1.3rem);
      margin-bottom: 2.5rem;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
    }

    /* Button Styles */
    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
      background-color: var(--secondary);
      color: var(--light);
      padding: 0.9rem 2rem;
      border: none;
      border-radius: 50px;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: var(--transition);
      text-decoration: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    .btn:hover {
      background-color: #b28d58;
      transform: translateY(-3px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.25);
    }

    .btn i {
      font-size: 1.2rem;
    }

    /* Container Styles */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 1.5rem;
    }

    /* Section Styles */
    section {
      padding: 4rem 0;
      position: relative;
    }

    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.8rem, 3vw, 2.5rem);
      margin-bottom: 2rem;
      text-align: center;
      color: var(--primary);
      position: relative;
    }

    .section-title::after {
      content: '';
      display: block;
      width: 80px;
      height: 3px;
      background: var(--secondary);
      margin: 1rem auto;
    }

    /* Description Section */
    .description {
      text-align: center;
      margin-bottom: 3rem;
      position: relative;
      padding: 3rem;
      border-radius: var(--border-radius);
      box-shadow: var(--shadow);
    }

    .description::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(255, 255, 255, 0.85);
      border-radius: var(--border-radius);
      z-index: 0;
    }

    .description h2,
    .description p {
      position: relative;
      z-index: 1;
    }

    .description p {
      font-size: 1.1rem;
      color: #555;
      max-width: 800px;
      margin: 0 auto 2rem;
    }

    /* Cleaner Features Grid */
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      margin: 3rem 0;
    }

    .feature-card {
      background: var(--light);
      border-radius: var(--border-radius);
      padding: 2rem;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      transition: var(--transition);
      border: 1px solid rgba(0,0,0,0.05);
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .feature-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 24px rgba(0,0,0,0.12);
    }

    .feature-icon {
      font-size: 2rem;
      color: var(--secondary);
      margin-bottom: 1.5rem;
      width: 70px;
      height: 70px;
      background: rgba(201, 168, 107, 0.1);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: var(--transition);
    }

    .feature-card:hover .feature-icon {
      background: rgba(201, 168, 107, 0.2);
      transform: scale(1.1);
    }

    .feature-card h3 {
      font-family: 'Playfair Display', serif;
      margin-bottom: 1rem;
      color: var(--primary);
      font-size: 1.25rem;
    }

    .feature-card p {
      color: #555;
      font-size: 0.95rem;
      line-height: 1.6;
      margin-top: auto;
    }

    /* Video Gallery */
    .videos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      margin: 3rem 0;
    }

    .video-preview {
      position: relative;
      overflow: hidden;
      border-radius: var(--border-radius);
      box-shadow: var(--shadow);
      aspect-ratio: 4/3;
      background: #000;
    }

    .video-preview video {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: var(--transition);
    }

    .video-preview:hover video {
      transform: scale(1.05);
      opacity: 0.9;
    }

    .video-overlay {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: linear-gradient(to top, rgba(0,0,0,0.7), transparent);
      color: white;
      padding: 1rem;
      transform: translateY(100%);
      transition: var(--transition);
    }

    .video-preview:hover .video-overlay {
      transform: translateY(0);
    }

    .play-button {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 60px;
      height: 60px;
      background: rgba(255,255,255,0.2);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: var(--transition);
      pointer-events: none;
    }

    .video-preview:hover .play-button {
      background: rgba(201, 168, 107, 0.7);
      transform: translate(-50%, -50%) scale(1.1);
    }

    .play-button i {
      color: white;
      font-size: 1.5rem;
      margin-left: 5px;
    }

    /* Main Video Section */
    .video-container {
      position: relative;
      width: 100%;
      max-width: 800px;
      margin: 0 auto;
      border-radius: var(--border-radius);
      overflow: hidden;
      box-shadow: var(--shadow);
    }

    .video-container video {
      width: 100%;
      display: block;
    }

    /* Map Section */
    .map-container {
      width: 100%;
      height: 450px;
      border-radius: var(--border-radius);
      overflow: hidden;
      box-shadow: var(--shadow);
    }

    .map-container iframe {
      width: 100%;
      height: 100%;
      border: 0;
    }

    /* CTA Section */
    .cta {
      background: linear-gradient(135deg, var(--secondary), #b28d58);
      color: var(--light);
      text-align: center;
      padding: 4rem 0;
    }

    .cta h2 {
      margin-bottom: 2rem;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
    }

    .cta .btn {
      background: var(--primary);
      font-size: 1.1rem;
      padding: 1rem 2.5rem;
    }

    .cta .btn:hover {
      background: #1a2635;
    }

    /* Footer */
    footer {
      background: linear-gradient(135deg, var(--primary), #1a2635);
      color: var(--text-light);
      padding: 4rem 0 2rem;
      text-align: center;
      width: 100%;
    }

    .footer-wrapper {
      background: linear-gradient(135deg, var(--primary), #1a2635);
      padding: 4rem 0 2rem;
    }

    .footer-content {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-bottom: 2rem;
      text-align: left;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 1.5rem;
    }

    .footer-column h3 {
      font-family: 'Playfair Display', serif;
      margin-bottom: 1.5rem;
      color: var(--secondary);
    }

    .footer-column ul {
      list-style: none;
    }

    .footer-column li {
      margin-bottom: 0.8rem;
    }

    .footer-column a {
      color: var(--text-light);
      text-decoration: none;
      transition: var(--transition);
    }

    .footer-column a:hover {
      color: var(--secondary);
    }

    .social-links {
      display: flex;
      gap: 1rem;
      margin-top: 1rem;
    }

    .social-links a {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 40px;
      height: 40px;
      background: rgba(255,255,255,0.1);
      border-radius: 50%;
      transition: var(--transition);
    }

    .social-links a:hover {
      background: var(--secondary);
      transform: translateY(-3px);
    }

    .copyright {
      border-top: 1px solid rgba(255,255,255,0.1);
      padding-top: 1.5rem;
      font-size: 0.9rem;
      opacity: 0.8;
      max-width: 1200px;
      margin: 0 auto;
    }

    /* Ornament Styles */
    .ornament {
      position: absolute;
      z-index: 0;
      opacity: 0.1;
      width: 120px;
      pointer-events: none;
    }

    .ornament.leaf-top-left {
      top: 20px;
      left: 20px;
      transform: rotate(-15deg);
    }

    .ornament.leaf-bottom-right {
      bottom: 20px;
      right: 20px;
      transform: rotate(30deg);
    }

    /* Wave Divider */
    .wave-divider {
      position: relative;
      height: 100px;
      overflow: hidden;
    }

    .wave-divider svg {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive Adjustments */
    @media (max-width: 768px) {
      header {
        height: 80vh;
      }
      
      .videos {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      }
      
      section {
        padding: 3rem 0;
      }
      
      .description {
        padding: 2rem 1.5rem;
      }
      
      .features {
        grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
        gap: 1.5rem;
      }
      
      .feature-card {
        padding: 1.5rem;
      }
      
      .feature-icon {
        width: 60px;
        height: 60px;
        font-size: 1.8rem;
      }
    }

    @media (max-width: 480px) {
      header {
        height: 70vh;
      }
      
      .btn {
        padding: 0.8rem 1.5rem;
      }
      
      .features {
        grid-template-columns: 1fr;
        gap: 1.2rem;
      }
      
      .description {
        padding: 1.5rem 1rem;
      }
      
      .feature-card {
        padding: 1.5rem 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="overlay">
      <h1>Sewa Tanah Premium</h1>
      <p>Investasi Tanah Strategis di Surga Tropis Nusa Penida dengan Pemandangan Laut Spektakuler</p>
      <a href="https://wa.me/6281805465944?text=Hello%2C%20I%27m%20interested%20in%20the%20land%20you%20advertised" class="btn">
        <i class="fab fa-whatsapp"></i> Hubungi Kami
      </a>
    </div>
  </header>

  <!-- Ornamen Daun -->
  <img src="leaf.svg" class="ornament leaf-top-left" alt="Daun Ornamen">
  <img src="leaf.svg" class="ornament leaf-bottom-right" alt="Daun Ornamen">

  <!-- Gelombang -->
  <div class="wave-divider">
    <svg viewBox="0 0 1440 150" xmlns="http://www.w3.org/2000/svg"><path fill="#ffffff" fill-opacity="1" d="M0,96L60,90.7C120,85,240,75,360,101.3C480,128,600,192,720,213.3C840,235,960,213,1080,192C1200,171,1320,149,1380,138.7L1440,128L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path></svg>
  </div>

  <div class="container">
    <section class="description">
      <h2 class="section-title">Tentang Tanah Ini</h2>
      <p>Terletak di kawasan premium Nusa Penida, tanah seluas 42 are (4,200 m²) ini menawarkan lokasi yang tenang dan privat dengan akses satu pintu. Dengan pemandangan laut dari bukit yang memukau, lokasi strategis dekat Pantai Diamond dan Atuh, serta berdekatan dengan Cactus Club dan area wisata populer.</p>
    </section>

    <section>
      <h2 class="section-title">Fasilitas & Keunggulan</h2>
      <div class="features">
        <div class="feature-card">
          <div class="feature-icon">
            <i class="fas fa-lock"></i>
          </div>
          <h3>Area Privat</h3>
          <p>Lokasi yang tenang dan eksklusif dengan akses satu pintu untuk keamanan dan kenyamanan</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <i class="fas fa-water"></i>
          </div>
          <h3>Pemandangan Laut</h3>
          <p>Pemandangan panorama laut spektakuler dari bukit dengan sudut pandang 180°</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <i class="fas fa-bolt"></i>
          </div>
          <h3>Infrastruktur Lengkap</h3>
          <p>Sudah tersedia akses listrik dan sumber air bersih di lokasi tanah</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <i class="fas fa-map-marked-alt"></i>
          </div>
          <h3>Lokasi Strategis</h3>
          <p>Berdekatan dengan Pantai Diamond, Atuh Beach, dan Cactus Club di jantung area wisata</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <i class="fas fa-certificate"></i>
          </div>
          <h3>Sertifikat Lengkap</h3>
          <p>Sertifikat Hak Milik (SHM) yang sah dan sudah melalui proses notaris</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <i class="fas fa-expand"></i>
          </div>
          <h3>Luas Tanah</h3>
          <p>Luas tanah 42 are (4,200 m²) dengan potensi pengembangan yang sangat besar</p>
        </div>
      </div>
    </section>
  </div>
  <!-- Enhanced Full Tour Video Section -->
   
  <div class="full-tour-section">
    <section class="full-tour-container">
         <div class="tour-description">
            <div class="description-content">
              <span class="tag">Virtual Experience</span>
              <h2 class="fancy-heading"> 
                Explore Our Property in Virtual Tour</h2>
              <p class="animated-text">Enjoy a full virtual tour of our rental land in Nusa Penida. This video will take you around the entire 4,200 m² area, showcasing the sea view, road access, and property development potential.
              </p>
              <div class="tour-features">
                <div class="tour-feature pulse">
                  <i class="fas fa-clock"></i>
                  <span>7 Min Experience</span>
                </div>
                <div class="tour-feature pulse">
                  <i class="fas fa-expand"></i>
                  <span>Resolusi 1080p</span>
                </div>
                <div class="tour-feature pulse">
                  <i class="fas fa-map-marked-alt"></i>
                  <span>Panduan Lokasi</span>
                </div>
              </div>
              
              <button class="btn tour-cta" id="scheduleTourBtn">
                <i class="fas fa-calendar-alt"></i> Schedule a Live Tour

              </button>
              
              <script>
                document.getElementById('scheduleTourBtn').addEventListener('click', function() {
                  // 1. Proper number format (62 without leading 0)
                  const phone = '6281805465944';
                  
                  // 2. Safely encoded message
                  const text = encodeURIComponent("Saya tertarik untuk jadwalkan tur langsung tanah di Nusa Penida");
                  
                  // 3. Device-appropriate URL
                  const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
                  const whatsappUrl = `https://${isMobile ? 'api' : 'web'}.whatsapp.com/send?phone=${phone}&text=${text}`;
                  
                  // 4. Reliable opening method
                  try {
                    window.location.href = whatsappUrl;
                  } catch (e) {
                    window.open(whatsappUrl, '_blank');
                  }
                });
              </script>
            </div>
          </div>

          

          <div class="tour-video">
  <div class="video-frame">
    <div class="video-container">
      <iframe 
        src="https://www.youtube.com/embed/pnIWh0MhKhY?enablejsapi=1&controls=0" 
        id="player"
        frameborder="0" 
        allowfullscreen
        allow="autoplay; fullscreen; accelerometer; gyroscope"
        style="z-index: 2;">
      </iframe>
      
      <div class="video-overlay" style="pointer-events: none;">
        <button class="play-button" style="pointer-events: auto;">
          <i class="fas fa-play"></i>
        </button>
      </div>
    </div>
  </div>
</div>

<script>
document.querySelector('.play-button').addEventListener('click', function() {
  const iframe = document.getElementById('player');
  iframe.src += "&autoplay=1";
  document.querySelector('.video-overlay').style.opacity = 0;
});
</script>
          
          <style>
            /* Responsive video container */
            .video-container {
              position: relative;
              padding-bottom: 56.25%; /* 16:9 aspect ratio */
              height: 0;
              overflow: hidden;
            }
            
            .video-container iframe {
              position: absolute;
              top: 0;
              left: 0;
              width: 100%;
              height: 100%;
              border: none;
            }
            
            /* Maintain your existing overlay styles */
            .video-overlay {
              position: absolute;
              top: 0;
              left: 0;
              right: 0;
              bottom: 0;
              display: flex;
              flex-direction: column;
              align-items: center;
              justify-content: center;
              background: rgba(0,0,0,0.3);
              z-index: 2;
            }
            
          </style>
              <div class="video-badge">
                <i class="fas fa-video"></i> Tur Virtual
              </div>
            </div>
          </div>
        </section>
        
      
      <style>
        /* Enhanced Styles for Fancy Tour Section */
        .full-tour-section {
          padding: 4rem 0;
          background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
          position: relative;
          overflow: hidden;
        }
        
        .full-tour-section::before {
          content: "";
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          background: url('texture.png') repeat;
          opacity: 0.03;
          pointer-events: none;
        }
        
        .fancy-title {
          position: relative;
          margin-bottom: 3rem;
        }
        
        .fancy-title span {
          position: relative;
          display: inline-block;
          padding: 0 1.5rem;
        }
        
        .fancy-title span::before,
        .fancy-title span::after {
          content: "";
          position: absolute;
          top: 50%;
          width: 50px;
          height: 3px;
          background: linear-gradient(90deg, var(--secondary), transparent);
        }
        
        .fancy-title span::before {
          left: -50px;
        }
        
        .fancy-title span::after {
          right: -50px;
          background: linear-gradient(270deg, var(--secondary), transparent);
        }
        
        .full-tour-container {
          display: flex;
          gap: 3rem;
          margin: 0 auto;
          max-width: 1200px;
          background: white;
          border-radius: 15px;
          box-shadow: 0 20px 40px rgba(0,0,0,0.1);
          overflow: hidden;
          transform: translateY(0);
          transition: transform 0.5s ease, box-shadow 0.5s ease;
          position: relative;
        }
        
        .full-tour-container:hover {
          transform: translateY(-10px);
          box-shadow: 0 25px 50px rgba(0,0,0,0.15);
        }
        
        .tour-description {
          flex: 1;
          padding: 3rem;
          display: flex;
          flex-direction: column;
          justify-content: center;
          position: relative;
          z-index: 1;
        }
        
        .description-content {
          max-width: 500px;
        }
        
        .tag {
          display: inline-block;
          background: var(--secondary);
          color: white;
          padding: 0.3rem 1rem;
          border-radius: 50px;
          font-size: 0.8rem;
          font-weight: 600;
          margin-bottom: 1.5rem;
          text-transform: uppercase;
          letter-spacing: 1px;
        }
        
        .fancy-heading {
          font-family: 'Playfair Display', serif;
          font-size: 2.2rem;
          color: var(--primary);
          margin-bottom: 1.5rem;
          line-height: 1.3;
        }
        
        .highlight {
          background: linear-gradient(120deg, rgba(201,168,107,0.3) 0%, rgba(201,168,107,0) 80%);
          padding: 0 0.5rem;
          border-radius: 5px;
        }
        
        .animated-text {
          color: #555;
          margin-bottom: 2rem;
          line-height: 1.7;
          position: relative;
          padding-left: 1.5rem;
        }
        
        .animated-text::before {
          content: "";
          position: absolute;
          left: 0;
          top: 0;
          height: 100%;
          width: 3px;
          background: var(--secondary);
          border-radius: 3px;
        }
        
        .tour-features {
          display: flex;
          gap: 1rem;
          flex-wrap: wrap;
          margin: 2rem 0;
        }
        
        .tour-feature {
          display: flex;
          align-items: center;
          gap: 0.5rem;
          background: rgba(201, 168, 107, 0.1);
          padding: 0.7rem 1.2rem;
          border-radius: 50px;
          font-size: 0.9rem;
          color: var(--primary);
          transition: all 0.3s ease;
          border: 1px solid rgba(201, 168, 107, 0.2);
        }
        
        .tour-feature i {
          color: var(--secondary);
        }
        
        .tour-feature.pulse:hover {
          transform: translateY(-3px);
          box-shadow: 0 5px 15px rgba(201, 168, 107, 0.2);
          background: rgba(201, 168, 107, 0.15);
        }
        
        .tour-cta {
          background: var(--primary);
          color: white;
          padding: 0.8rem 1.5rem;
          border-radius: 50px;
          display: inline-flex;
          align-items: center;
          gap: 0.7rem;
          font-weight: 600;
          transition: all 0.3s ease;
          margin-top: 1rem;
          text-decoration: none;
        }
        
        .tour-cta:hover {
          background: #12261d;
          transform: translateY(-3px);
          box-shadow: 0 10px 20px rgba(26, 58, 39, 0.2);
        }
        
        .tour-video {
          flex: 1.5;
          position: relative;
        }
        
        .video-frame {
          position: relative;
          height: 100%;
          overflow: hidden;
        }
        
        .video-frame::before {
          content: "";
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          background: linear-gradient(45deg, rgba(26,58,39,0.1) 0%, rgba(201,168,107,0.05) 100%);
          z-index: 1;
        }
        
        .video-container {
          width: 100%;
          height: 100%;
          margin: 0;
          max-width: 100%;
          position: relative;
        }
        
        .video-container video {
          width: 100%;
          height: 100%;
          min-height: 500px;
          object-fit: cover;
          display: block;
          transition: transform 0.5s ease;
        }
        
        .video-overlay {
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          bottom: 0;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          background: rgba(0,0,0,0.3);
          opacity: 1;
          transition: all 0.3s ease;
          z-index: 2;
        }
        
        .video-container.playing .video-overlay {
          opacity: 0;
          pointer-events: none;
        }
        
        .play-button {
          width: 80px;
          height: 80px;
          background: rgba(201, 168, 107, 0.9);
          border-radius: 50%;
          display: flex;
          align-items: center;
          justify-content: center;
          color: white;
          font-size: 2rem;
          cursor: pointer;
          transition: all 0.3s ease;
          border: none;
          margin-bottom: 1rem;
        }
        
        .play-button:hover {
          background: var(--secondary);
          transform: scale(1.1);
        }
        
        .overlay-text {
          color: white;
          font-size: 1.2rem;
          font-weight: 500;
          text-shadow: 0 2px 5px rgba(0,0,0,0.3);
        }
        
        .video-badge {
          position: absolute;
          top: 20px;
          right: 20px;
          background: rgba(0,0,0,0.7);
          color: white;
          padding: 0.5rem 1rem;
          border-radius: 50px;
          font-size: 0.8rem;
          display: flex;
          align-items: center;
          gap: 0.5rem;
          z-index: 3;
        }
        
        .video-controls {
          position: absolute;
          bottom: 0;
          left: 0;
          right: 0;
          background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
          padding: 1.2rem;
          display: flex;
          align-items: center;
          gap: 1rem;
          opacity: 0;
          transition: all 0.3s ease;
          z-index: 3;
        }
        
        .video-container:hover .video-controls {
          opacity: 1;
        }
        
        .play-pause-btn, .fullscreen-btn, .volume-btn {
          background: none;
          border: none;
          color: white;
          font-size: 1.2rem;
          cursor: pointer;
          width: 36px;
          height: 36px;
          display: flex;
          align-items: center;
          justify-content: center;
          border-radius: 50%;
          transition: all 0.3s ease;
        }
        
        .play-pause-btn:hover, .fullscreen-btn:hover, .volume-btn:hover {
          background: rgba(255,255,255,0.2);
        }
        
        .progress-bar {
          flex: 1;
          height: 5px;
          background: rgba(255,255,255,0.3);
          border-radius: 3px;
          cursor: pointer;
          position: relative;
        }
        
        .progress {
          height: 100%;
          background: var(--secondary);
          width: 0%;
          border-radius: 3px;
          position: relative;
        }
        
        .progress::after {
          content: "";
          position: absolute;
          right: -5px;
          top: 50%;
          transform: translateY(-50%);
          width: 10px;
          height: 10px;
          background: white;
          border-radius: 50%;
          opacity: 0;
          transition: opacity 0.3s ease;
        }
        
        .progress-bar:hover .progress::after {
          opacity: 1;
        }
        
        .time {
          color: white;
          font-size: 0.9rem;
          min-width: 100px;
          text-align: center;
          font-family: monospace;
        }
        
        .right-controls {
          display: flex;
          gap: 0.5rem;
        }
        
        .tour-360-notice {
          text-align: center;
          margin-top: 1.5rem;
          color: var(--primary);
          font-size: 0.9rem;
          display: flex;
          align-items: center;
          justify-content: center;
          gap: 0.5rem;
          opacity: 0.8;
        }
        
        @media (max-width: 992px) {
          .full-tour-container {
            flex-direction: column;
          }
          
          .tour-description {
            padding: 2rem;
          }
          
          .tour-video video {
            min-height: 400px;
          }
          
          .video-overlay {
            opacity: 1 !important;
          }
          
          .video-controls {
            opacity: 1;
          }
        }
        
        @media (max-width: 576px) {
          .fancy-heading {
            font-size: 1.8rem;
          }
          
          .tour-features {
            gap: 0.7rem;
          }
          
          .tour-feature {
            padding: 0.5rem 1rem;
            font-size: 0.8rem;
          }
          
          .video-badge {
            top: 10px;
            right: 10px;
            font-size: 0.7rem;
          }
        }
      </style>
      
      <script>
        document.addEventListener('DOMContentLoaded', function() {
          const videoContainer = document.querySelector('.video-container');
          const video = document.getElementById('tourVideo');
          const playButton = document.querySelector('.play-button');
          const playPauseBtn = document.querySelector('.play-pause-btn');
          const progressBar = document.querySelector('.progress');
          const progressContainer = document.querySelector('.progress-bar');
          const timeDisplay = document.querySelector('.time');
          const fullscreenBtn = document.querySelector('.fullscreen-btn');
          const volumeBtn = document.querySelector('.volume-btn');
          
          // Play/Pause from big button
          playButton.addEventListener('click', function() {
            video.play();
            videoContainer.classList.add('playing');
            playPauseBtn.innerHTML = '<i class="fas fa-pause"></i>';
          });
          
          // Play/Pause toggle from controls
          playPauseBtn.addEventListener('click', function() {
            if (video.paused) {
              video.play();
              videoContainer.classList.add('playing');
              playPauseBtn.innerHTML = '<i class="fas fa-pause"></i>';
            } else {
              video.pause();
              playPauseBtn.innerHTML = '<i class="fas fa-play"></i>';
            }
          });
          
          // Update progress bar
          video.addEventListener('timeupdate', function() {
            const progress = (video.currentTime / video.duration) * 100;
            progressBar.style.width = progress + '%';
            
            // Update time display
            const currentMins = Math.floor(video.currentTime / 60);
            const currentSecs = Math.floor(video.currentTime % 60).toString().padStart(2, '0');
            const durationMins = Math.floor(video.duration / 60);
            const durationSecs = Math.floor(video.duration % 60).toString().padStart(2, '0');
            
            timeDisplay.textContent = `${currentMins}:${currentSecs} / ${durationMins}:${durationSecs}`;
          });
          
          // Click on progress bar to seek
          progressContainer.addEventListener('click', function(e) {
            const percent = e.offsetX / this.offsetWidth;
            video.currentTime = percent * video.duration;
          });
          
          // Fullscreen toggle
          fullscreenBtn.addEventListener('click', function() {
            if (videoContainer.requestFullscreen) {
              videoContainer.requestFullscreen();
            } else if (videoContainer.webkitRequestFullscreen) {
              videoContainer.webkitRequestFullscreen();
            } else if (videoContainer.msRequestFullscreen) {
              videoContainer.msRequestFullscreen();
            }
          });
          
          // Volume toggle
          let isMuted = false;
          volumeBtn.addEventListener('click', function() {
            isMuted = !isMuted;
            video.muted = isMuted;
            volumeBtn.innerHTML = isMuted ? '<i class="fas fa-volume-mute"></i>' : '<i class="fas fa-volume-up"></i>';
          });
          
          // Update play/pause button when video ends
          video.addEventListener('ended', function() {
            playPauseBtn.innerHTML = '<i class="fas fa-play"></i>';
            videoContainer.classList.remove('playing');
          });
          
          // Add gyroscope effect for 360 video on mobile
          if (window.DeviceOrientationEvent) {
            window.addEventListener('deviceorientation', function(e) {
              if (videoContainer.classList.contains('playing')) {
                const gamma = e.gamma;  // -90 to 90 (left to right)
                const beta = e.beta;    // -180 to 180 (front to back)
                
                // Adjust video rotation based on device orientation
                video.style.transform = `rotateX(${beta * 0.2}deg) rotateY(${gamma * 0.2}deg)`;
              }
            });
          }
        });
      </script>


<section class="map-section">
  <h2 class="section-title">Peta Tanah Sewa</h2>
  <div class="zoom-container">
    <img id="zoomImage" src="master plan_page-0001.jpg" alt="Master Plan Tanah Sewa di Nusa Penida">
  </div>
  <div class="zoom-instructions">
    <small>Klik untuk zoom in/out, pinch untuk zoom, atau geser untuk melihat area lain</small>
  </div>
</section>

<style>
  .map-section {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .zoom-container {
    overflow: hidden;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.15);
    touch-action: none;
    cursor: pointer;
    position: relative;
    background-color: #f5f5f5;
    user-select: none;
    height: 500px; /* Fixed height for better control */
  }
  
  .zoom-container img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    transform-origin: 0 0;
    transition: transform 0.25s ease-out;
    will-change: transform;
  }
  
  .zoom-instructions {
    text-align: center;
    margin-top: 10px;
    color: #666;
    font-size: 0.9em;
  }
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const container = document.querySelector('.zoom-container');
  const image = document.getElementById('zoomImage');
  let scale = 1;
  let posX = 0;
  let posY = 0;
  let isDragging = false;
  let startX, startY;
  
  // Click to toggle zoom
  container.addEventListener('click', function(e) {
    if (e.target === container) {
      if (scale === 1) {
        zoomTo(2, e.clientX, e.clientY);
      } else {
        resetZoom();
      }
    }
  });
  
  // Double click to reset
  container.addEventListener('dblclick', resetZoom);
  
  // Mouse wheel zoom
  container.addEventListener('wheel', function(e) {
    e.preventDefault();
    const delta = -Math.sign(e.deltaY) * 0.1;
    zoomTo(scale + delta, e.clientX, e.clientY);
  }, { passive: false });
  
  // Touch events
  container.addEventListener('touchstart', handleTouchStart, { passive: false });
  container.addEventListener('touchmove', handleTouchMove, { passive: false });
  container.addEventListener('touchend', handleTouchEnd);
  
  // Mouse drag
  container.addEventListener('mousedown', function(e) {
    if (scale > 1) {
      isDragging = true;
      startX = e.clientX - posX;
      startY = e.clientY - posY;
      container.style.cursor = 'grabbing';
    }
  });
  
  document.addEventListener('mousemove', function(e) {
    if (isDragging) {
      posX = e.clientX - startX;
      posY = e.clientY - startY;
      applyTransform();
    }
  });
  
  document.addEventListener('mouseup', function() {
    if (isDragging) {
      isDragging = false;
      container.style.cursor = scale > 1 ? 'grab' : 'pointer';
    }
  });
  
  function zoomTo(newScale, centerX, centerY) {
    const prevScale = scale;
    scale = Math.min(Math.max(1, newScale), 5);
    
    if (scale !== prevScale) {
      // Adjust position to zoom toward pointer
      if (centerX && centerY) {
        const containerRect = container.getBoundingClientRect();
        const relativeX = centerX - containerRect.left;
        const relativeY = centerY - containerRect.top;
        
        posX = relativeX - (relativeX - posX) * (scale / prevScale);
        posY = relativeY - (relativeY - posY) * (scale / prevScale);
      }
      
      applyTransform();
    }
  }
  
  function resetZoom() {
    scale = 1;
    posX = 0;
    posY = 0;
    applyTransform();
    container.style.cursor = 'pointer';
  }
  
  function applyTransform() {
    // Constrain position to keep image within bounds
    const maxX = Math.max(0, (scale - 1) * container.offsetWidth);
    const maxY = Math.max(0, (scale - 1) * container.offsetHeight);
    
    posX = Math.min(0, Math.max(-maxX, posX));
    posY = Math.min(0, Math.max(-maxY, posY));
    
    image.style.transform = `translate(${posX}px, ${posY}px) scale(${scale})`;
  }
  
  // Touch handlers
  let touchStartDistance;
  let touchStartScale;
  
  function handleTouchStart(e) {
    e.preventDefault();
    if (e.touches.length === 2) {
      touchStartDistance = getTouchDistance(e.touches[0], e.touches[1]);
      touchStartScale = scale;
    } else if (e.touches.length === 1) {
      isDragging = true;
      startX = e.touches[0].clientX - posX;
      startY = e.touches[0].clientY - posY;
    }
  }
  
  function handleTouchMove(e) {
    e.preventDefault();
    if (e.touches.length === 2) {
      const currentDistance = getTouchDistance(e.touches[0], e.touches[1]);
      const scaleChange = (currentDistance - touchStartDistance) / 100;
      zoomTo(touchStartScale + scaleChange);
    } else if (e.touches.length === 1 && isDragging) {
      posX = e.touches[0].clientX - startX;
      posY = e.touches[0].clientY - startY;
      applyTransform();
    }
  }
  
  function handleTouchEnd() {
    isDragging = false;
  }
  
  function getTouchDistance(touch1, touch2) {
    return Math.hypot(
      touch2.clientX - touch1.clientX,
      touch2.clientY - touch1.clientY
    );
  }
});
</script>
    
   

    <section>
      <h2 class="section-title">Lokasi Tanah</h2>
      <div class="map-container">
        <iframe src="https://www.google.com/maps/embed?pb=YOUR_GOOGLE_MAPS_EMBED_CODE" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </section>



    <footer>
      <div class="footer-content">
        <div class="footer-column">
          <h3>Kontak</h3>
          <ul>
            <li><i class="fas fa-phone"></i> +62 818-0546-5944</li>
            <li><i class="fas fa-map-marker-alt"></i> Nusa Penida, Bali, Indonesia</li>
          </ul>
       
      <div class="copyright">
        &copy; 2025 Sewa Tanah Nusa Penida. All rights reserved.
      </div>
    </footer>
  </div>

  
