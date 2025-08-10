<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>كوريا بالعربي | أول موقع احترافي لتعلم اللغة الكورية</title>
  <meta name="description" content="تعلم اللغة الكورية بالعربية بأسلوب عصري، فيديوهات، قواعد، مفردات، وتمارين تفاعلية." />
  <meta name="keywords" content="تعلم الكورية, قواعد اللغة الكورية, مفردات كورية, كوريا بالعربي, تعليم كوريا جيل زد" />
  <meta name="author" content="كوريا بالعربي" />
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo&display=swap');

    * {
      box-sizing: border-box;
      margin: 0; padding: 0;
    }
    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(135deg, #74ebd5 0%, #ACB6E5 100%);
      color: #222;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    header {
      background: #1e3c72;
      color: #fff;
      padding: 25px 20px;
      text-align: center;
      font-size: 2.5rem;
      font-weight: 900;
      letter-spacing: 3px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      user-select: none;
    }
    nav {
      background: #112d4e;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px 0;
      box-shadow: inset 0 -3px 5px rgba(0,0,0,0.3);
    }
    nav a {
      color: #f0f0f0;
      text-decoration: none;
      font-size: 1.2rem;
      padding: 8px 20px;
      border-radius: 12px;
      font-weight: 600;
      transition: background-color 0.3s ease, color 0.3s ease;
    }
    nav a:hover {
      background-color: #f9a825;
      color: #000;
      cursor: pointer;
      box-shadow: 0 0 8px #f9a825;
    }
    main {
      flex-grow: 1;
      max-width: 1100px;
      margin: 40px auto 80px;
      background: #fff;
      border-radius: 20px;
      padding: 40px 30px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      animation: fadeIn 1s ease forwards;
    }
    main h1 {
      font-size: 2.7rem;
      color: #1e3c72;
      margin-bottom: 25px;
      letter-spacing: 1.5px;
    }
    main p {
      font-size: 1.15rem;
      line-height: 1.7;
      color: #444;
      margin-bottom: 35px;
      max-width: 800px;
      user-select: text;
    }
    .btn {
      display: inline-block;
      background: #f9a825;
      color: #000;
      font-weight: 700;
      padding: 15px 35px;
      font-size: 1.2rem;
      border-radius: 30px;
      text-decoration: none;
      box-shadow: 0 5px 12px rgba(249,168,37,0.5);
      transition: background-color 0.3s ease;
      user-select: none;
    }
    .btn:hover {
      background: #fbc02d;
      box-shadow: 0 8px 20px rgba(251,192,45,0.7);
      cursor: pointer;
    }
    section.features {
      display: flex;
      justify-content: space-around;
      gap: 25px;
      margin-top: 40px;
      flex-wrap: wrap;
    }
    section.features .feature-box {
      background: #f0f4f8;
      border-radius: 18px;
      padding: 25px 20px;
      flex: 1 1 300px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.07);
      transition: transform 0.3s ease;
      user-select: none;
    }
    section.features .feature-box:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.12);
    }
    section.features h3 {
      font-size: 1.5rem;
      color: #1e3c72;
      margin-bottom: 15px;
      text-align: center;
    }
    section.features p {
      font-size: 1rem;
      color: #555;
      text-align: center;
      line-height: 1.5;
    }
    footer {
      background: #1e3c72;
      color: #fff;
      text-align: center;
      padding: 18px 15px;
      font-size: 0.9rem;
      user-select: none;
      box-shadow: 0 -3px 10px rgba(0,0,0,0.2);
      position: fixed;
      width: 100%;
      bottom: 0;
    }

    /* انيميشن دخول */
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(15px);}
      to {opacity: 1; transform: translateY(0);}
    }

    /* Responsive */
    @media (max-width: 800px) {
      main {
        margin: 30px 15px 90px;
        padding: 30px 20px;
      }
      section.features {
        flex-direction: column;
        gap: 20px;
      }
    }
  </style>
</head>
<body>

<header>كوريا بالعربي 🇰🇷 | أول موقع احترافي لتعلم الكورية بالعربية</header>

<nav>
  <a href="#home" onclick="navigate(event, 'home')">الرئيسية</a>
  <a href="#grammar" onclick="navigate(event, 'grammar')">قواعد اللغة</a>
  <a href="#vocab" onclick="navigate(event, 'vocab')">المفردات</a>
  <a href="#zterms" onclick="navigate(event, 'zterms')">مصطلحات جيل Z</a>
</nav>

<main>
  <section id="home-section">
    <h1>مرحباً بك في كوريا بالعربي!</h1>
    <p>اكتشف جمال اللغة الكورية بأسلوب عصري وممتع مع دروس سهلة، فيديوهات تعليمية، وتمارين تفاعلية تناسب جميع المستويات. هنا مكانك لتبدأ رحلتك مع كوريا من الصفر إلى الاحتراف!</p>
    <a href="#grammar" class="btn" onclick="navigate(event, 'grammar')">ابدأ التعلم الآن</a>

    <section class="features" aria-label="ميزات الموقع">
      <div class="feature-box">
        <h3>قواعد اللغة ببساطة</h3>
        <p>شرح مبسط للقواعد مع أمثلة سهلة تقدر تفهمها بسرعة وتبدأ تستخدمها.</p>
      </div>
      <div class="feature-box">
        <h3>مفردات يومية</h3>
        <p>تعلم كلمات وعبارات مستخدمة يومياً تساعدك في محادثاتك اليومية.</p>
      </div>
      <div class="feature-box">
        <h3>مصطلحات جيل Z</h3>
        <p>اكتشف أحدث التعبيرات والمصطلحات التي يستخدمها الشباب الكوري لتكون على تواصل معهم.</p>
      </div>
    </section>
  </section>

  <section id="grammar-section" style="display:none;">
    <h2>قواعد اللغة الكورية</h2>
    <ul>
      <li><strong>ترتيب الجملة:</strong> الفعل دائماً في نهاية الجملة.</li>
      <li><strong>الجسيمات (Particles):</strong> 은/는، 을/를، 이/가.</li>
      <li><strong>تصريف الأفعال:</strong> حسب الزمن والاحترام.</li>
      <li><strong>الضمائر:</strong> تختلف حسب الموقف الاجتماعي.</li>
    </ul>
    <p>مثال: 저는 한국어를 공부해요. (أنا أدرس اللغة الكورية)</p>
  </section>

  <section id="vocab-section" style="display:none;">
    <h2>المفردات الشائعة</h2>
    <ul>
      <li>안녕하세요 (أن-ني-هونغ-ها-سي-يو) - مرحباً</li>
      <li>감사합니다 (كام-سا-هم-ني-دا) - شكراً</li>
      <li>사랑해요 (سا-رانغ-هي-يو) - أحبك</li>
      <li>친구 (تشين-غو) - صديق</li>
      <li>학교 (هاك-كيو) - مدرسة</li>
    </ul>
  </section>

  <section id="zterms-section" style="display:none;">
    <h2>مصطلحات جيل Z</h2>
    <ul>
      <li><strong>대박 (ديباب):</strong> رائع، مذهل.</li>
      <li><strong>꿀잼 (كول-جيم):</strong> ممتع جداً.</li>
      <li><strong>헐 (هول):</strong> تعجب أو صدمة.</li>
      <li><strong>소확행 (سو-هواك-هيونغ):</strong> سعادة صغيرة مؤكدة.</li>
      <li><strong>인싸 (إن-سا):</strong> شخص اجتماعي.</li>
      <li><strong>아싸 (آ-سا):</strong> شخص منعزل.</li>
    </ul>
  </section>
</main>

<footer>حقوق النشر &copy; 2025 | كوريا بالعربي</footer>

<script>
  function navigate(event, section) {
    event.preventDefault();
    const sections = ['home', 'grammar', 'vocab', 'zterms'];
    sections.forEach(sec => {
      const el = document.getElementById(sec + '-section');
      if (sec === section) {
        el.style.display = 'block';
        window.location.hash = sec;
      } else {
        el.style.display = 'none';
      }
    });
  }
  // اظهار الصفحة الافتراضية عند تحميل الموقع
  window.onload = () => {
    const hash = window.location.hash.replace('#', '');
    const validSections = ['home', 'grammar', 'vocab', 'zterms'];
    if(validSections.includes(hash)){
      navigate(new Event('load'), hash);
    } else {
      navigate(new Event('load'), 'home');
    }
  };
</script>

</body>
</html>

