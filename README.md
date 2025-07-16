<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>پنکه دو قلو فندکی خودرو | قیمت 798 تومان</title>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary: #2c3e50;
      --secondary: #34495e;
      --accent: #e74c3c;
      --text: #2c3e50;
      --light: #ecf0f1;
      --border: #bdc3c7;
    }
    
    body {
      font-family: 'Vazirmatn', sans-serif;
      background-color: var(--light);
      margin: 0;
      padding: 0;
      color: var(--text);
      direction: rtl;
      line-height: 1.6;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 0 15px;
    }

    /* Header Styles */
    .header {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: white;
      padding: 25px 20px;
      text-align: center;
      border-radius: 0 0 20px 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .header h1 {
      font-size: 1.4rem;
      font-weight: 500;
      margin: 0 0 8px;
    }

    .header p {
      font-size: 0.95rem;
      margin: 0;
      opacity: 0.9;
    }

    /* Product Card */
    .product-card {
      background: white;
      border-radius: 15px;
      margin: 25px 0;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      border: 1px solid var(--border);
    }

    /* Slideshow */
    .slideshow-container {
      position: relative;
      height: 280px;
      background: #f1f3f5;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .slide {
      position: absolute;
      width: 100%;
      height: 100%;
      opacity: 0;
      transition: opacity 0.5s;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
      box-sizing: border-box;
    }

    .slide.active { opacity: 1; }

    .slide img {
      max-width: 100%;
      max-height: 100%;
      object-fit: contain;
      border-radius: 8px;
    }

    .slide-nav {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      width: 36px;
      height: 36px;
      background: rgba(255,255,255,0.9);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      z-index: 10;
      font-size: 1rem;
      color: var(--text);
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: all 0.3s;
    }

    .slide-nav:hover {
      background: white;
      transform: translateY(-50%) scale(1.1);
    }

    .slide-nav.prev { right: 15px; }
    .slide-nav.next { left: 15px; }

    .slide-dots {
      position: absolute;
      bottom: 15px;
      width: 100%;
      display: flex;
      justify-content: center;
      gap: 8px;
    }

    .dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: rgba(255,255,255,0.5);
      cursor: pointer;
      transition: all 0.3s;
    }

    .dot.active {
      background: white;
      transform: scale(1.2);
    }

    /* Product Info */
    .product-info {
      padding: 20px;
    }

    .product-title {
      font-size: 1.4rem;
      font-weight: 500;
      text-align: center;
      color: var(--text);
      margin: 0 0 10px;
      position: relative;
      padding-bottom: 15px;
    }

    .product-title:after {
      content: '';
      position: absolute;
      bottom: 0;
      right: 50%;
      transform: translateX(50%);
      width: 60px;
      height: 2px;
      background: linear-gradient(to right, var(--primary), var(--secondary));
    }

    .product-subtitle {
      font-size: 1rem;
      text-align: center;
      color: var(--accent);
      margin: 0 0 20px;
    }

    /* Features */
    .features {
      margin: 25px 0;
      display: grid;
      grid-template-columns: 1fr;
      gap: 12px;
    }

    .feature-item {
      display: flex;
      align-items: center;
      padding: 12px;
      background: rgba(44, 62, 80, 0.03);
      border-radius: 8px;
      border-right: 2px solid var(--accent);
    }

    .feature-icon {
      margin-left: 10px;
      color: var(--accent);
      font-size: 1.1rem;
      min-width: 25px;
      text-align: center;
    }

    .feature-text {
      font-size: 0.9rem;
    }

    /* Price */
    .price-container {
      background: var(--light);
      padding: 15px;
      border-radius: 10px;
      margin: 25px 0;
      text-align: center;
      border: 1px dashed var(--accent);
    }

    .price {
      font-size: 1.2rem;
      color: var(--accent);
      font-weight: 500;
      margin: 5px 0;
    }

    .price:after {
      content: 'تومان';
      font-size: 1rem;
      margin-right: 5px;
    }

    .price-note {
      font-size: 0.85rem;
      color: #7f8c8d;
    }

    /* Order Button */
    .btn-order {
      display: block;
      background: linear-gradient(135deg, #e74c3c, #c0392b);
      color: white;
      padding: 15px;
      font-size: 1.1rem;
      font-weight: 500;
      border-radius: 10px;
      text-align: center;
      text-decoration: none;
      transition: all 0.3s;
      margin: 25px 0;
      box-shadow: 0 4px 15px rgba(231, 76, 60, 0.3);
    }

    .btn-order:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(231, 76, 60, 0.4);
      background: linear-gradient(135deg, #c0392b, #e74c3c);
    }

    /* Guarantee */
    .guarantee {
      background: white;
      border-radius: 10px;
      padding: 15px;
      margin: 20px 0;
      border: 1px solid var(--border);
    }

    .guarantee-item {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .guarantee-icon {
      margin-left: 10px;
      color: var(--accent);
      font-size: 1.1rem;
    }

    .guarantee-text {
      font-size: 0.9rem;
    }

    /* Footer */
    .footer {
      text-align: center;
      padding: 15px;
      font-size: 0.8rem;
      color: #7f8c8d;
    }

    /* Responsive */
    @media (max-width: 480px) {
      .header h1 {
        font-size: 1.2rem;
      }
      
      .slideshow-container {
        height: 250px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>پنکه دو قلو فندکی خودرو</h1>
      <p>راه حلی ساده برای تهویه بهتر هوای خودرو</p>
    </div>

    <div class="product-card">
      <div class="slideshow-container">
        <div class="slide active">
          <img src="https://biaupload.com/do.php?imgf=org-7fd9fe9095c31.jpg" alt="پنکه دو قلو فندکی خودرو">
        </div>
        <div class="slide">
          <img src="https://biaupload.com/do.php?imgf=org-f556ee5780d81.jpg" alt="پنکه دو قلو فندکی خودرو">
        </div>
        <div class="slide">
          <img src="https://biaupload.com/do.php?imgf=org-d4f376f279053.jpg" alt="پنکه دو قلو فندکی خودرو">
        </div>
        
        <div class="slide-nav prev"><i class="fas fa-chevron-right"></i></div>
        <div class="slide-nav next"><i class="fas fa-chevron-left"></i></div>
        
        <div class="slide-dots">
          <div class="dot active"></div>
          <div class="dot"></div>
          <div class="dot"></div>
        </div>
      </div>

      <div class="product-info">
        <h2 class="product-title">پنکه دو قلو فندکی خودرو</h2>
        <div class="product-subtitle">مناسب برای بهبود جریان هوا در خودرو</div>

        <div class="features">
          <div class="feature-item">
            <span class="feature-icon"><i class="fas fa-arrows-alt"></i></span>
            <span class="feature-text">قابلیت تنظیم زاویه هر پنکه</span>
          </div>
          
          <div class="feature-item">
            <span class="feature-icon"><i class="fas fa-plug"></i></span>
            <span class="feature-text">اتصال از طریق فندکی خودرو</span>
          </div>
          
          <div class="feature-item">
            <span class="feature-icon"><i class="fas fa-tachometer-alt"></i></span>
            <span class="feature-text">دارای دو سرعت مختلف</span>
          </div>
          
          <div class="feature-item">
            <span class="feature-icon"><i class="fas fa-thumbtack"></i></span>
            <span class="feature-text">قابل نصب روی داشبورد</span>
          </div>
        </div>

        <div class="price-container">
          <div class="price">۷۹۸</div>
          <div class="price-note">پرداخت در محل پس از دریافت</div>
        </div>

        <a href="https://de.mihanstore.net/fcartmob.php?id=1845" class="btn-order" target="_blank">
          ✅ ثبت سریع و آسان 🚀💪
        </a>

        <div class="guarantee">
          <div class="guarantee-item">
            <span class="guarantee-icon"><i class="fas fa-truck"></i></span>
            <span class="guarantee-text">ارسال به تمام نقاط ایران</span>
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
    </div>
  </div>

  <script>
    // Slideshow functionality
    let currentSlide = 0;
    const slides = document.querySelectorAll('.slide');
    const dots = document.querySelectorAll('.dot');
    const prevBtn = document.querySelector('.prev');
    const nextBtn = document.querySelector('.next');

    function showSlide(n) {
      slides.forEach(slide => slide.classList.remove('active'));
      dots.forEach(dot => dot.classList.remove('active'));
      
      currentSlide = (n + slides.length) % slides.length;
      slides[currentSlide].classList.add('active');
      dots[currentSlide].classList.add('active');
    }

    function nextSlide() {
      showSlide(currentSlide + 1);
    }

    function prevSlide() {
      showSlide(currentSlide - 1);
    }

    // Auto slide change
    let slideInterval = setInterval(nextSlide, 5000);

    // Pause on hover
    const slideshow = document.querySelector('.slideshow-container');
    slideshow.addEventListener('mouseenter', () => clearInterval(slideInterval));
    slideshow.addEventListener('mouseleave', () => {
      clearInterval(slideInterval);
      slideInterval = setInterval(nextSlide, 5000);
    });

    // Navigation buttons
    nextBtn.addEventListener('click', () => {
      nextSlide();
      clearInterval(slideInterval);
      slideInterval = setInterval(nextSlide, 5000);
    });

    prevBtn.addEventListener('click', () => {
      prevSlide();
      clearInterval(slideInterval);
      slideInterval = setInterval(nextSlide, 5000);
    });

    // Dot navigation
    dots.forEach((dot, index) => {
      dot.addEventListener('click', () => {
        showSlide(index);
        clearInterval(slideInterval);
        slideInterval = setInterval(nextSlide, 5000);
      });
    });
  </script>
</body>
</html>
