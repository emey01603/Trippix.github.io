<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trippix Smart Transportation</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", "Cairo", sans-serif;
      background-color: #f9fafb;
      color: #222;
    }
    header {
      background-color: #0b2c57;
      color: white;
      padding: 1.2rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
    }
    nav button {
      background: none;
      border: 1px solid white;
      color: white;
      padding: 0.4rem 1rem;
      border-radius: 20px;
      cursor: pointer;
      font-size: 0.9rem;
    }
    nav button:hover {
      background-color: white;
      color: #0b2c57;
    }
    section {
      max-width: 900px;
      margin: 3rem auto;
      padding: 0 1rem;
    }
    h2 {
      color: #0b2c57;
      text-align: center;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .service-card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1.5rem;
      width: 250px;
      text-align: center;
    }
    footer {
      background-color: #0b2c57;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
    .arabic {
      direction: rtl;
      text-align: right;
      font-family: "Cairo", sans-serif;
    }
  </style>
</head>
<body>
  <header>
    <h1>Trippix Smart Transportation</h1>
    <nav>
      <button onclick="switchLang()">عربي / English</button>
    </nav>
  </header>

  <!-- English Content -->
  <section id="en">
    <h2>About Us</h2>
    <p>
      Trippix Smart Transportation provides modern, efficient, and reliable
      employee and student transportation services across Egypt. We combine
      smart route planning and punctual fleet operations to deliver the highest
      level of comfort and safety.
    </p>

    <h2>Our Services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Corporate Transportation</h3>
        <p>Reliable daily transportation solutions for company employees.</p>
      </div>
      <div class="service-card">
        <h3>School Transportation</h3>
        <p>Safe and punctual rides for students and school staff.</p>
      </div>
      <div class="service-card">
        <h3>Staff Shuttle Management</h3>
        <p>Customized transport operations for outsourcing and call centers.</p>
      </div>
    </div>

    <h2>Contact Us</h2>
    <p style="text-align:center;">
      📧 info@trippix.eg<br />
      📞 +20 1005669888
    </p>
  </section>

  <!-- Arabic Content -->
  <section id="ar" class="arabic" style="display:none;">
    <h2>من نحن</h2>
    <p>
      تقدم شركة تريبكس للنقل الذكي حلول نقل حديثة وفعالة وآمنة لموظفي الشركات وطلاب المدارس في جميع أنحاء مصر. نعتمد على أنظمة ذكية لتخطيط المسارات وضمان الدقة في المواعيد وجودة الخدمة.
    </p>

    <h2>خدماتنا</h2>
    <div class="services">
      <div class="service-card">
        <h3>نقل الموظفين</h3>
        <p>خدمة نقل يومية آمنة وموثوقة لموظفي الشركات والمؤسسات.</p>
      </div>
      <div class="service-card">
        <h3>نقل المدارس</h3>
        <p>رحلات آمنة ومنظمة للطلاب وأعضاء هيئة التدريس.</p>
      </div>
      <div class="service-card">
        <h3>إدارة خطوط النقل</h3>
        <p>حلول مخصصة لشركات التعهيد ومراكز الاتصال.</p>
      </div>
    </div>

    <h2>تواصل معنا</h2>
    <p style="text-align:center;">
      📧 info@trippix.eg<br />
      📞 +20 1005669888
    </p>
  </section>

  <footer>
    © 2025 Trippix Smart Transportation. All Rights Reserved.
  </footer>

  <script>
    function switchLang() {
      const en = document.getElementById("en");
      const ar = document.getElementById("ar");
      if (en.style.display === "none") {
        en.style.display = "block";
        ar.style.display = "none";
      } else {
        en.style.display = "none";
        ar.style.display = "block";
      }
    }
  </script>
</body>
</html>

