<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>تعلم اللغة العربية</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>مرحبًا بك في موقع تعلم اللغة العربية</h1>
  </header>
  <main>
    <section>
      <h2>المفردات</h2><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>الدروس - تعلم اللغة العربية</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f5f5f5;
      direction: rtl;
      color: #333;
    }
    header {
      background-color: #008080;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav {
      background: #004d4d;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 30px;
    }
    section {
      background: white;
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 30px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }
    section h2 {
      color: #00695c;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      padding: 5px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>الدروس التعليمية</h1>
    <p>مفردات - حوار - قراءة - نحو</p>
  </header>
  <nav>
    <a href="index.html">الرئيسية</a>
    <a href="lessons.html">الدروس</a>
    <a href="latihan.html">التمارين</a><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>التمارين والتصحيح</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #008080;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 30px;
    }
    h2 {
      color: #00695c;
    }
    .exercise {
      background: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .exercise input[type="text"] {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .btn {
      padding: 10px 20px;
      background: #008080;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    .feedback {
      margin-top: 10px;
      color: green;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>التمارين والتصحيح</h1>
    <p>قم بحل التمارين التالية ثم تحقق من إجاباتك</p>
  </header>

  <main>
    <section class="exercise" id="ex1">
      <h2>١. أكمل الكلمة الناقصة:</h2>
      <p>المدرسة ______ كبيرة.</p>
      <input type="text" id="answer1" placeholder="أدخل الكلمة هنا">
      <button class="btn" onclick="checkAnswer1()">تحقق</button>
      <div class="feedback" id="feedback1"></div>
    </section>

    <section class="exercise" id="ex2">
      <h2>٢. ترجم الكلمة إلى العربية: (Teacher)</h2>
      <input type="text" id="answer2" placeholder="أدخل الترجمة هنا">
      <button class="btn" onclick="checkAnswer2()">تحقق</button>
      <div class="feedback" id="feedback2"></div>
    </section>

    <section class="exercise" id="ex3">
      <h2>٣. حدد نوع الكلمة: "يكتبُ"</h2>
      <input type="text" id="answer3" placeholder="اسم / فعل / حرف">
      <button class="btn" onclick="checkAnswer3()">تحقق</button>
      <div class="feedback" id="feedback3"></div>
    </section>
  </main>

  <script>
    function checkAnswer1() {
      const ans = document.getElementById('answer1').value.trim();
      const feedback = document.getElementById('feedback1');
      if (ans === "كبيرة") {
        feedback.innerText = "إجابة صحيحة ✔️";
        feedback.style.color = 'green';
      } else {
        feedback.innerText = "حاول مرة أخرى ❌";
        feedback.style.color = 'red';
      }
    }

    function checkAnswer2() {
      const ans = document.getElementById('answer2').value.trim();
      const feedback = document.getElementById('feedback2');
      if (ans === "معلم" || ans === "المعلم") {
        feedback.innerText = "أحسنت! الإجابة صحيحة ✔️";
        feedback.style.color = 'green';
      } else {
        feedback.innerText = "خطأ، جرّب مرة أخرى ❌";
        feedback.style.color = 'red';
      }
    }

    function checkAnswer3() {
      const ans = document.getElementById('answer3').value.trim();
      const feedback = document.getElementById('feedback3');
      if (ans === "فعل") {
        feedback.innerText = "صحيح! إنها فعل ✔️";
        feedback.style.color = 'green';
      } else {
        feedback.innerText = "خطأ، الكلمة فعل ❌";
        feedback.style.color = 'red';
      }
    }
  </script>
</body>
</html>
    <a href="quiz.html">الاختبار</a>
    <a href="videos.html">الفيديو</a>
  </nav>
  <main>
    <section>
      <h2>📘 المفردات</h2>
      <ul>
        <li>المدرسة - الطالب - الكتاب - الفصل - السبورة</li>
        <li>الأب - الأم - الأخ - الأخت - العائلة</li>
        <li>اليوم - الغد - الأمس - ساعة - دقيقة</li>
      </ul>
    <section>
      <h2>💬 الحوار</h2>
      <p><strong>علي:</strong> السلام عليكم<br>
      <strong>أحمد:</strong> وعليكم السلام<br>
      <strong>علي:</strong> أين الكتاب؟<br>
      <strong>أحمد:</strong> الكتاب على المكتب.</p>
    </section>

    <section>
      <h2>📖 القراءة</h2>
      <p><strong>جدولي اليومي:</strong><br>
      أستيقظ في الساعة السادسة صباحًا، وأذهب إلى المدرسة في الساعة السابعة، وأعود إلى البيت في الساعة الثانية.</p>
    <section>
      <h2>✍️ النحو</h2>
      <ul>
        <li><strong>المبتدأ والخبر:</strong> الطالبُ مجتهدٌ.</li>
        <li><strong>أسماء الإشارة:</strong> هذا كتاب - هذه معلمة - هؤلاء طلاب</li>
        <li><strong>الفعل الماضي والمضارع:</strong> كتبَ - يكتبُ / أكلَ - يأكلُ</li>
      </ul>
    </section>
  </main>
</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>الدروس - تعلم اللغة العربية</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f5f5f5;
      direction: rtl;
      color: #333;
    }
    header {
      background-color: #008080;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav {
      background: #004d4d;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 30px;
    }
    section {
      background: white;
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 30px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }
    section h2 {
      color: #00695c;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      padding: 5px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>الدروس التعليمية</h1>
    <p>مفردات - حوار - قراءة - نحو</p>
  </header>

  <nav>
    <a href="index.html">الرئيسية</a>
    <a href="lessons.html">الدروس</a>
    <a href="latihan.html">التمارين</a>
    <a href="quiz.html">الاختبار</a>
    <a href="videos.html">الفيديو</a>
  </nav>
<main>
    <section>
      <h2>📘 المفردات</h2>
      <ul>
        <li>المدرسة - الطالب - الكتاب - الفصل - السبورة</li>
        <li>الأب - الأم - الأخ - الأخت - العائلة</li>
        <li>اليوم - الغد - الأمس - ساعة - دقيقة</li>
      </ul>
  <section>
      <h2>💬 الحوار</h2>
      <p><strong>علي:</strong> السلام عليكم<br>
      <strong>أحمد:</strong> وعليكم السلام<br>
      <strong>علي:</strong> أين الكتاب؟<br>
      <strong>أحمد:</strong> الكتاب على المكتب.</p>
    </section>

    <section>
      <h2>📖 القراءة</h2>
      <p><strong>جدولي اليومي:</strong><br>
      أستيقظ في الساعة السادسة صباحًا، وأذهب إلى المدرسة في الساعة السابعة، وأعود إلى البيت في الساعة الثانية.</p>
    </section>

    <section>
      <h2>✍️ النحو</h2>
      <ul>
        <li><strong>المبتدأ والخبر:</strong> الطالبُ مجتهدٌ.</li>
        <li><strong>أسماء الإشارة:</strong> هذا كتاب - هذه معلمة - هؤلاء طلاب</li>
        <li><strong>الفعل الماضي والمضارع:</strong> كتبَ - يكتبُ / أكلَ - يأكلُ</li>
      </ul>
    </section>
      <p>تعلم كلمات جديدة يوميًا.</p>
    </section>
    <section>
      <h2>الحوار</h2>
      <p>استمع وتمرن على المحادثات.</p>
    </section>
    <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>اختبار المفردات</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f9f9f9;
      color: #333;
      padding: 20px;
    }
    h1 {
      text-align: center;
      color: #008080;
    }
    .quiz-container {
      max-width: 600px;
      margin: 0 auto;
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    .question {
      margin-bottom: 20px;
    }
    .question h2 {
      font-size: 20px;
      margin-bottom: 10px;
    }
    .options label {
      display: block;
      margin-bottom: 10px;
      cursor: pointer;
    }
    button {
      padding: 10px 20px;
      background: #008080;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .result {
      margin-top: 20px;
      font-size: 18px;
      font-weight: bold;
      text-align: center;
      color: #00695c;
    }
  </style>
</head>
<body>
  <h1>اختبار المفردات</h1>
  <div class="quiz-container">
    <form id="quizForm">
      <div class="question">
        <h2>١. ما معنى كلمة "المدرسة"؟</h2>
        <div class="options">
          <label><input type="radio" name="q1" value="0"> المسجد</label>
          <label><input type="radio" name="q1" value="1"> المدرسة</label>
          <label><input type="radio" name="q1" value="0"> السوق</label>
          <label><input type="radio" name="q1" value="0"> المكتب</label>
        </div>
      </div>
      <div class="question">
        <h2>٢. ما معنى كلمة "الكتاب"؟</h2>
        <div class="options">
          <label><input type="radio" name="q2" value="1"> الكتاب</label>
          <label><input type="radio" name="q2" value="0"> الباب</label>
          <label><input type="radio" name="q2" value="0"> النافذة</label>
          <label><input type="radio" name="q2" value="0"> الحقيبة</label>
        </div>
      </div>
      <div class="question">
        <h2>٣. ما معنى كلمة "المعلم"؟</h2>
        <div class="options">
          <label><input type="radio" name="q3" value="1"> المعلم</label>
          <label><input type="radio" name="q3" value="0"> الطالب</label>
          <label><input type="radio" name="q3" value="0"> المدير</label>
          <label><input type="radio" name="q3" value="0"> الحارس</label>
        </div>
      </div>
      <div style="text-align: center;">
        <button type="button" onclick="checkAnswers()">تحقق من الإجابات</button>
      </div>
    </form>
    <div class="result" id="result"></div>
  </div>

  <script>
    function checkAnswers() {
      const form = document.forms['quizForm'];
      let score = 0;
      for (let i = 1; i <= 3; i++) {
        const q = form[`q${i}`];
        for (let j = 0; j < q.length; j++) {
          if (q[j].checked && q[j].value === "1") {
            score++;
          }
        }
      }
      document.getElementById('result').textContent = `نتيجتك: ${score} من 3`;
    }
  </script>
</body><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>فيديوهات تعليمية</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
      direction: rtl;
    }
    header, footer {
      background-color: #008080;
      color: white;
      text-align: center;
      padding: 15px;
    }
    h1 {
      margin: 0;
    }
    main {
      padding: 30px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .video-card {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      padding: 15px;
    }
    .video-card iframe {
      width: 100%;
      height: 200px;
      border-radius: 8px;
    }
    .video-card h3 {
      margin: 10px 0 5px;
      font-size: 18px;
      color: #00695c;
    }
    .video-card p {
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>فيديوهات تعليم اللغة العربية</h1>
    <p>استمتع بمقاطع الفيديو التعليمية المتنوعة لدعم تعلمك</p>
  </header>

  <main>
    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/v1v5J4NQYXg" frameborder="0" allowfullscreen></iframe>
      <h3>مفردات المدرسة</h3>
      <p>تعلم أهم كلمات الصف والمدرسة بالصوت والصورة.</p>
    </div>

    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/OGiR9qE_K4s" frameborder="0" allowfullscreen></iframe>
      <h3>حوار يومي في المنزل</h3>
      <p>مشاهدة حوار سهل بين أفراد العائلة باللغة العربية.</p>
    </div>

    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VBGU_m8LnsU" frameborder="0" allowfullscreen></iframe>
      <h3>قواعد اللغة: الجملة الاسمية</h3>
      <p>فهم المبتدأ والخبر مع أمثلة مرئية ومبسطة.</p>
    </div>

    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/mGMJ0gMaN4M" frameborder="0" allowfullscreen></iframe>
      <h3>قراءة نصوص بسيطة</h3>
      <p>نص عربي مع قراءة صوتية وأسئلة لفهم المقروء.</p>
    </div>
  </main>

  <footer>
    &copy; 2025 منصة تعلم العربية | تصميم: نيار رمضانى
  </footer>
</body>
</html>

</html>
  </main>
  <footer>
    <p>&copy; 2025 تصميم: Niar Ramadhani</p>
  </footer>
</body>
