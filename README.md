<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>تعلم اللغة الكورية - موقع تعليمي</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f0f8ff;
      color: #333;
      margin: 0; padding: 0;
      direction: rtl;
    }
    header {
      background-color: #4a90e2;
      padding: 20px;
      text-align: center;
      color: white;
      font-weight: bold;
      font-size: 24px;
      letter-spacing: 2px;
      box-shadow: 0 4px 8px rgba(74,144,226,0.4);
    }
    nav {
      display: flex;
      justify-content: center;
      background: #1e5799; /* أزرق داكن */
      gap: 15px;
      padding: 10px 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
      padding: 8px 15px;
      border-radius: 8px;
      transition: background 0.3s ease;
    }
    nav a:hover {
      background-color: #7db9e8;
      color: #000;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 15px 40px 15px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    h1, h2 {
      color: #0f3b8a;
      margin-bottom: 15px;
    }
    p {
      line-height: 1.6;
      font-size: 17px;
    }
    ul {
      margin: 15px 0 30px 0;
      padding-inline-start: 20px;
    }
    footer {
      background: #4a90e2;
      color: white;
      text-align: center;
      padding: 15px 0;
      position: fixed;
      width: 100%;
      bottom: 0;
      font-size: 14px;
      letter-spacing: 1px;
    }
    /* زر التبديل بين الصفحات */
    .hidden {
      display: none;
    }
    /* تنسيق القوائم */
    .list-word {
      margin-bottom: 10px;
      background: #e8f0fe;
      padding: 10px;
      border-radius: 8px;
      font-weight: 600;
    }
    .term {
      font-weight: bold;
      color: #2a2a72;
    }
    /* تصميم بسيط للمصطلحات */
    .z-term {
      background: #ffe4e1;
      margin-bottom: 12px;
      padding: 12px 15px;
      border-radius: 12px;
      font-size: 18px;
      box-shadow: 2px 2px 8px rgba(255, 99, 71, 0.2);
      cursor: default;
      user-select: none;
      transition: transform 0.15s ease-in-out;
    }
    .z-term:hover {
      transform: scale(1.05);
      box-shadow: 3px 3px 12px rgba(255, 99, 71, 0.4);
    }
  </style>
</head>
<body>

<header>تعلم اللغة الكورية بالعربية 🇰🇷✨</header>

<nav>
  <a href="#" onclick="showPage('home')">الرئيسية</a>
  <a href="#" onclick="showPage('grammar')">قواعد اللغة</a>
  <a href="#" onclick="showPage('vocab')">المفردات</a>
  <a href="#" onclick="showPage('zterms')">مصطلحات جيل Z</a>
</nav>

<main>
  <section id="home">
    <h1>مرحباً بك في عالم اللغة الكورية!</h1>
    <p>هنا ستبدأ رحلتك الممتعة لتعلم اللغة الكورية بطريقة مبسطة وسلسة، مع تركيز خاص على القواعد، المفردات، وأحدث مصطلحات جيل Z.</p>
    <p>ابدأ باختيار أحد الأقسام أعلاه لتكتشف المزيد.</p>
  </section>

  <section id="grammar" class="hidden">
    <h2>قواعد اللغة الكورية</h2>
    <ul>
      <li><strong>الترتيب في الجملة:</strong> في الكورية، الفعل دائماً يأتي في نهاية الجملة.</li>
      <li><strong>الجسيمات (Particles):</strong> مثل 은/는 (للموضوع)، 을/를 (للمفعول به)، 이/가 (للفاعل).</li>
      <li><strong>تصريف الأفعال:</strong> يعتمد على الاحترام والزمن، مثل الماضي، الحاضر، والمستقبل.</li>
      <li><strong>الضمائر:</strong> تختلف حسب المستوى الاجتماعي، وهناك ضمائر غير مستخدمة كثيراً.</li>
    </ul>
    <p>مثال: أنا أدرس اللغة الكورية = 저는 한국어를 공부해요.</p>
  </section>

  <section id="vocab" class="hidden">
    <h2>مفردات شائعة</h2>
    <div class="list-word">안녕하세요 (أن-ني-هونغ-ها-سي-يو) - مرحباً</div>
    <div class="list-word">감사합니다 (كام-سا-هم-ني-دا) - شكراً</div>
    <div class="list-word">사랑해요 (سا-رانغ-هي-يو) - أحبك</div>
    <div class="list-word">친구 (تشين-غو) - صديق</div>
    <div class="list-word">학교 (هاك-كيو) - مدرسة</div>
  </section>

  <section id="zterms" class="hidden">
    <h2>مصطلحات جيل Z الكورية</h2>
    <div class="z-term"><span class="term">대박 (ديباب)</span>: تعبير يعني "رائع" أو "مذهل".</div>
    <div class="z-term"><span class="term">꿀잼 (كول-جيم)</span>: تعني "ممتع جداً" أو "شيء ممتع".</div>
    <div class="z-term"><span class="term">헐 (هول)</span>: تعبير عن الصدمة أو التعجب، يشبه "يا إلهي".</div>
    <div class="z-term"><span class="term">소확행 (سو-هواك-هيونغ)</span>: تعني "سعادة صغيرة مؤكدة"، الأشياء البسيطة التي تجلب السعادة.</div>
    <div class="z-term"><span class="term">인싸 (إن-سا)</span>: الشخص الاجتماعي أو المتفاعل بشدة مع المجتمع.</div>
    <div class="z-term"><span class="term">아싸 (آ-سا)</span>: العكس، الشخص المنعزل أو غير الاجتماعي.</div>
  </section>
</main>

<footer>حقوق النشر &copy; 2025 | موقع تعلم اللغة الكورية بالعربية</footer>

<script>
  function showPage(pageId) {
    // إخفاء جميع الصفحات
    const sections = document.querySelectorAll('main > section');
    sections.forEach(section => {
      if(section.id === pageId){
        section.classList.remove('hidden');
      } else {
        section.classList.add('hidden');
      }
    });
  }
</script>

</body>
</html>
