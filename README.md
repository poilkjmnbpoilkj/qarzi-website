<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>درب و پنجره‌سازی قارزی | آلومینیوم و UPVC</title>
  <meta name="description"
        content="درب و پنجره‌سازی قارزی در ورامین و پیشوا - ساخت انواع درب و پنجره آلومینیومی و UPVC">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: Tahoma, Arial, sans-serif;
      background: #f5f7fa;
      color: #222;
      line-height: 1.8;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    .container {
      width: 92%;
      max-width: 1100px;
      margin: auto;
    }
    /* هدر */
    header {
      background: #ffffff;
      border-bottom: 1px solid #e5e7eb;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .nav {
      min-height: 72px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }
    .logo {
      font-size: 21px;
      font-weight: bold;
      color: #0f172a;
      white-space: nowrap;
    }
    .logo span {
      color: #d97706;
    }
    .menu {
      display: flex;
      gap: 25px;
      list-style: none;
    }
    .menu a {
      color: #334155;
      font-size: 15px;
      transition: 0.2s;
    }
    .menu a:hover {
      color: #d97706;
    }
    .menu-btn {
      display: none;
      border: none;
      background: #0f172a;
      color: white;
      padding: 9px 13px;
      border-radius: 8px;
      font-size: 18px;
      cursor: pointer;
    }
    /* صفحه اصلی */
    .hero {
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      padding: 85px 0;
    }
    .hero-content {
      max-width: 800px;
    }
    .hero h1 {
      font-size: 42px;
      line-height: 1.5;
      margin-bottom: 18px;
    }
    .hero h1 span {
      color: #f59e0b;
    }
    .hero p {
      color: #dbe3ed;
      font-size: 18px;
      margin-bottom: 30px;
    }
    .buttons {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }
    .btn {
      display: inline-block;
      padding: 12px 22px;
      border-radius: 9px;
      font-weight: bold;
      transition: 0.2s;
    }
    .btn-primary {
      background: #f59e0b;
      color: #111827;
    }
    .btn-primary:hover {
      background: #fbbf24;
    }
    .btn-outline {
      border: 1px solid #64748b;
      color: white;
    }
    .btn-outline:hover {
      background: white;
      color: #0f172a;
    }
    /* بخش‌ها */
    section {
      padding: 70px 0;
    }
    .section-title {
      text-align: center;
      margin-bottom: 40px;
    }
    .section-title h2 {
      font-size: 30px;
      color: #0f172a;
      margin-bottom: 8px;
    }
    .section-title p {
      color: #64748b;
    }
    /* خدمات */
    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 14px;
      padding: 28px;
      border: 1px solid #e5e7eb;
      box-shadow: 0 5px 18px rgba(15, 23, 42, 0.05);
      transition: 0.25s;
    }
    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 25px rgba(15, 23, 42, 0.09);
    }
    .icon {
      width: 52px;
      height: 52px;
      border-radius: 12px;
      background: #fff7ed;
      color: #d97706;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 25px;
      margin-bottom: 18px;
    }
    .card h3 {
      color: #0f172a;
      margin-bottom: 10px;
      font-size: 19px;
    }
    .card p {
      color: #64748b;
      font-size: 14px;
    }
    /* نمونه کار بدون عکس */
    .projects {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }
    .project {
      background: white;
      border: 1px solid #e5e7eb;
      border-radius: 14px;
      padding: 30px 20px;
      text-align: center;
    }
    .project-icon {
      font-size: 42px;
      margin-bottom: 15px;
    }
    .project h3 {
      margin-bottom: 8px;
      color: #0f172a;
    }
    .project p {
      color: #64748b;
      font-size: 14px;
    }
    /* درباره ما */
    .about {
      background: white;
    }
    .about-box {
      max-width: 850px;
      margin: auto;
      text-align: center;
    }
    .about-box p {
      color: #475569;
      font-size: 17px;
    }
    /* اطلاعات تماس */
    .contact {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 25px;
    }
    .contact-info {
      background: #0f172a;
      color: white;
      border-radius: 14px;
      padding: 30px;
    }
    .contact-info h3 {
      font-size: 24px;
      margin-bottom: 20px;
    }
    .contact-item {
      padding: 13px 0;
      border-bottom: 1px solid #334155;
    }
    .contact-item:last-child {
      border-bottom: none;
    }
    .contact-item strong {
      color: #f59e0b;
    }
    .contact-form {
      background: white;
      border-radius: 14px;
      padding: 30px;
      border: 1px solid #e5e7eb;
    }
    .contact-form h3 {
      margin-bottom: 20px;
      color: #0f172a;
    }
    input,
    textarea {
      width: 100%;
      padding: 13px;
      border: 1px solid #cbd5e1;
      border-radius: 8px;
      margin-bottom: 13px;
      font-family: inherit;
      font-size: 14px;
      outline: none;
    }
    input:focus,
    textarea:focus {
      border-color: #f59e0b;
    }
    textarea {
      min-height: 120px;
      resize: vertical;
    }
    .submit-btn {
      width: 100%;
      border: none;
      cursor: pointer;
      background: #16a34a;
      color: white;
      padding: 13px;
      border-radius: 8px;
      font-family: inherit;
      font-size: 15px;
      font-weight: bold;
    }
    .submit-btn:hover {
      background: #15803d;
    }
    /* فوتر */
    footer {
      background: #020617;
      color: #94a3b8;
      text-align: center;
      padding: 25px 0;
      font-size: 13px;
    }
    footer strong {
      color: white;
    }
    /* واتساپ */
    .whatsapp {
      position: fixed;
      left: 20px;
      bottom: 20px;
      width: 55px;
      height: 55px;
      border-radius: 50%;
      background: #25d366;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 27px;
      z-index: 2000;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }
    .whatsapp:hover {
      transform: scale(1.05);
    }
    /* موبایل */
    @media (max-width: 800px) {
      .menu-btn {
        display: block;
      }
      .menu {
        display: none;
        position: absolute;
        top: 72px;
        right: 0;
        left: 0;
        background: white;
        flex-direction: column;
        padding: 20px 7%;
        gap: 15px;
        border-bottom: 1px solid #e5e7eb;
      }
      .menu.active {
        display: flex;
      }
      .hero {
        padding: 65px 0;
      }
      .hero h1 {
        font-size: 30px;
      }
      .hero p {
        font-size: 16px;
      }
      .services,
      .projects,
      .contact {
        grid-template-columns: 1fr;
      }
      .section-title h2 {
        font-size: 25px;
      }
      .logo {
        font-size: 17px;
      }
    }
  </style>
</head>
<body>
  <!-- هدر -->
  <header>
    <div class="container nav">
      <div class="logo">
        درب و پنجره‌سازی <span>قارزی</span>
      </div>
      <button class="menu-btn" onclick="toggleMenu()">
        ☰
      </button>
      <ul class="menu" id="menu">
        <li><a href="#home">خانه</a></li>
        <li><a href="#services">خدمات</a></li>
        <li><a href="#projects">نمونه کارها</a></li>
        <li><a href="#about">درباره ما</a></li>
        <li><a href="#contact">تماس با ما</a></li>
      </ul>
    </div>
  </header>
  <!-- صفحه اصلی -->
  <section class="hero" id="home">
    <div class="container">
      <div class="hero-content">
        <h1>
          درب و پنجره‌سازی
          <span>قارزی</span>
        </h1>
        <p>
          ساخت انواع درب و پنجره آلومینیومی و UPVC
          با اجرای دقیق و کیفیت مناسب
          در ورامین و پیشوا
        </p>
        <div class="buttons">
          <a class="btn btn-primary" href="tel:09127264397">
            📞 تماس مستقیم
          </a>
          <a class="btn btn-outline"
             href="https://wa.me/989307261397"
             target="_blank">
            💬 واتساپ
          </a>
        </div>
      </div>
    </div>
  </section>
  <!-- خدمات -->
  <section id="services">
    <div class="container">
      <div class="section-title">
        <h2>خدمات ما</h2>
        <p>انواع خدمات ساخت و اجرای درب و پنجره</p>
      </div>
      <div class="services">
        <div class="card">
          <div class="icon">🏠</div>
          <h3>درب و پنجره آلومینیومی</h3>
          <p>
            ساخت انواع درب و پنجره آلومینیومی
            مناسب ساختمان‌های مسکونی و تجاری.
          </p>
        </div>
        <div class="card">
          <div class="icon">🪟</div>
          <h3>درب و پنجره UPVC</h3>
          <p>
            ساخت و اجرای پنجره‌های UPVC
            با طراحی مناسب و عایق‌بندی مطلوب.
          </p>
        </div>
        <div class="card">
          <div class="icon">🔧</div>
          <h3>اندازه‌گیری و نصب</h3>
          <p>
            اندازه‌گیری، ساخت و نصب درب و پنجره
            با دقت و اجرای اصولی.
          </p>
        </div>
      </div>
    </div>
  </section>
  <!-- نمونه کارها -->
  <section id="projects" style="background:#eef2f7;">
    <div class="container">
      <div class="section-title">
        <h2>نمونه کارها</h2>
        <p>
          نمونه‌هایی از خدمات قابل اجرا توسط مجموعه قارزی
        </p>
      </div>
      <div class="projects">
        <div class="project">
          <div class="project-icon">🪟</div>
          <h3>پنجره آلومینیومی</h3>
          <p>
            طراحی و ساخت انواع پنجره آلومینیومی
          </p>
        </div>
        <div class="project">
          <div class="project-icon">🏠</div>
          <h3>پنجره UPVC</h3>
          <p>
            ساخت و نصب پنجره‌های UPVC
          </p>
        </div>
        <div class="project">
          <div class="project-icon">🚪</div>
          <h3>درب آلومینیومی</h3>
          <p>
            ساخت انواع درب آلومینیومی
            برای ساختمان و فروشگاه
          </p>
        </div>
      </div>
    </div>
  </section>
  <!-- درباره ما -->
  <section class="about" id="about">
    <div class="container">
      <div class="section-title">
        <h2>درباره ما</h2>
      </div>
      <div class="about-box">
        <p>
          <strong>درب و پنجره‌سازی قارزی</strong>
          ارائه‌دهنده خدمات ساخت انواع درب و پنجره
          آلومینیومی و UPVC در محدوده
          <strong>ورامین و پیشوا</strong> است.
          هدف ما ارائه کار با کیفیت، اجرای دقیق
          و پاسخگویی مناسب به مشتریان است.
        </p>
      </div>
    </div>
  </section>
  <!-- تماس -->
  <section id="contact">
    <div class="container">
      <div class="section-title">
        <h2>تماس با ما</h2>
        <p>برای مشاوره و دریافت قیمت با ما در تماس باشید</p>
      </div>
      <div class="contact">
        <div class="contact-info">
          <h3>اطلاعات تماس</h3>
          <div class="contact-item">
            <strong>📞 تلفن:</strong>
            <a href="tel:09127264397">
              09127264397
            </a>
          </div>
          <div class="contact-item">
            <strong>💬 واتساپ:</strong>
            <a href="https://wa.me/989307261397"
               target="_blank">
              09307261397
            </a>
          </div>
          <div class="contact-item">
            <strong>📍 محدوده فعالیت:</strong>
            ورامین - پیشوا
          </div>
          <div class="contact-item">
            <strong>🕘 ساعت کاری:</strong>
            هر روز از ۹ صبح تا ۹ شب
          </div>
        </div>
        <div class="contact-form">
          <h3>درخواست مشاوره و قیمت</h3>
          <input
            type="text"
            id="name"
            placeholder="نام شما">
          <input
            type="tel"
            id="phone"
            placeholder="شماره تماس">
          <textarea
            id="message"
            placeholder="توضیحات یا نوع کار مورد نظر"></textarea>
          <button
            class="submit-btn"
            onclick="sendWhatsApp()">
            ارسال درخواست در واتساپ
          </button>
        </div>
      </div>
    </div>
  </section>
  <!-- فوتر -->
  <footer>
    <div class="container">
      <p>
        © 2026
        <strong>درب و پنجره‌سازی قارزی</strong>
        - تمامی حقوق محفوظ است.
      </p>
    </div>
  </footer>
  <!-- دکمه شناور واتساپ -->
  <a
    class="whatsapp"
    href="https://wa.me/989307261397"
    target="_blank"
    aria-label="واتساپ">
    💬
  </a>
  <script>
    /* منوی موبایل */
    function toggleMenu() {
      const menu = document.getElementById("menu");
      menu.classList.toggle("active");
    }
    /* ارسال فرم به واتساپ */
    function sendWhatsApp() {
      const name =
        document.getElementById("name").value;
      const phone =
        document.getElementById("phone").value;
      const message =
        document.getElementById("message").value;
      const text =
        "سلام، از طریق سایت درب و پنجره‌سازی قارزی پیام می‌دهم.%0A%0A" +
        "نام: " + encodeURIComponent(name) + "%0A" +
        "شماره تماس: " + encodeURIComponent(phone) + "%0A" +
        "توضیحات: " + encodeURIComponent(message);
      window.open(
        "https://wa.me/989307261397?text=" + text,
        "_blank"
      );
    }
  </script>
</body>
</html>
