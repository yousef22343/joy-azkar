<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>أذكار المسلم - By Youssef Sayed</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f7f9fc;
      color: #333;
      margin: 0;
      padding: 0;
      transition: background-color 0.3s, color 0.3s;
    }
    header {
      background-color: #4a6fa5;
      color: white;
      padding: 1rem;
      text-align: center;
      font-size: 1.8rem;
      font-weight: bold;
    }
    .container {
      padding: 1rem;
      max-width: 800px;
      margin: auto;
    }
    .section {
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
      padding: 1rem;
    }
    .section h2 {
      color: #4a6fa5;
      margin-bottom: 0.5rem;
      font-size: 1.4rem;
    }
    .azkar {
      line-height: 1.8;
      font-size: 1.1rem;
      color: #222;
    }
    .azkar p {
      margin-bottom: 1rem;
    }
    .counter-section {
      text-align: center;
      padding: 1rem;
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .counter-display {
      font-size: 2rem;
      margin: 1rem 0;
      color: #4a6fa5;
    }
    .counter-buttons button {
      margin: 0.5rem;
      padding: 0.7rem 1.2rem;
      font-size: 1rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      background-color: #4a6fa5;
      color: white;
      transition: background-color 0.3s;
    }
    .counter-buttons button:hover {
      background-color: #3b5f8c;
    }
    .toggle-btn {
      position: fixed;
      top: 10px;
      left: 10px;
      background-color: #4a6fa5;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      z-index: 1000;
    }
    /* الوضع الليلي */
    .dark-mode {
      background-color: #1e1e2f;
      color: #eee;
    }
    .dark-mode header {
      background-color: #2c3e50;
    }
    .dark-mode .section,
    .dark-mode .counter-section {
      background-color: #2a2a3d;
      color: #eee;
    }
    .dark-mode .section h2 {
      color: #64b5f6;
    }
    .dark-mode .azkar p {
      color: #e0e0e0;
    }
    .dark-mode .counter-display {
      color: #64b5f6;
    }
    .dark-mode .counter-buttons button {
      background-color: #3b5f8c;
    }
    .dark-mode .counter-buttons button:hover {
      background-color: #2c4a6e;
    }
    .dark-mode .toggle-btn {
      background-color: #3b5f8c;
    }
  </style>
</head>
<body>
  <button class="toggle-btn" onclick="toggleDarkMode()">الوضع الليلي</button>
  <header>📿 أذكار المسلم - By Youssef Sayed</header>
  <div class="container">
    <!-- Morning Azkar -->
    <div class="section">
      <h2>🌅 أذكار الصباح</h2>
      <div class="azkar">
        <p>أصبحنا وأصبح الملك لله، والحمد لله، لا إله إلا الله وحده لا شريك له، له الملك وله الحمد وهو على كل شيء قدير...</p>
        <p>اللهم بك أصبحنا، وبك أمسينا، وبك نحيا، وبك نموت، وإليك النشور.</p>
        <p>اللهم إني أصبحت أشهدك، وأشهد حملة عرشك، وملائكتك، وجميع خلقك أنك أنت الله لا إله إلا أنت وحدك لا شريك لك، وأن محمداً عبدك ورسولك. (ثلاث مرات)</p>
        <p>رضيت بالله رباً، وبالإسلام ديناً، وبمحمد ﷺ نبياً. (ثلاث مرات)</p>
        <p>اللهم ما أصبح بي من نعمة أو بأحد من خلقك، فمنك وحدك لا شريك لك، فلك الحمد ولك الشكر.</p>
        <p>حسبي الله لا إله إلا هو عليه توكلت وهو رب العرش العظيم. (سبع مرات)</p>
        <p>اللهم عافني في بدني، اللهم عافني في سمعي، اللهم عافني في بصري، لا إله إلا أنت. (ثلاث مرات)</p>
        <p>اللهم إني أعوذ بك من الكفر والفقر، وأعوذ بك من عذاب القبر، لا إله إلا أنت. (ثلاث مرات)</p>
        <p>اللهم إني أسألك العفو والعافية في الدنيا والآخرة...</p>
        <p>اللهم إني أسألك علماً نافعاً، ورزقاً طيباً، وعملاً متقبلاً.</p>
        <p>أستغفر الله العظيم وأتوب إليه. (مائة مرة)</p>
      </div>
    </div>
    
    <!-- Evening Azkar -->
    <div class="section">
      <h2>🌇 أذكار المساء</h2>
      <div class="azkar">
        <p>أمسينا وأمسى الملك لله، والحمد لله، لا إله إلا الله وحده لا شريك له، له الملك وله الحمد وهو على كل شيء قدير...</p>
        <p>اللهم بك أمسينا، وبك أصبحنا، وبك نحيا، وبك نموت، وإليك المصير.</p>
        <p>اللهم إني أمسيت أشهدك، وأشهد حملة عرشك، وملائكتك، وجميع خلقك أنك أنت الله لا إله إلا أنت وحدك لا شريك لك، وأن محمداً عبدك ورسولك. (ثلاث مرات)</p>
        <p>رضيت بالله رباً، وبالإسلام ديناً، وبمحمد ﷺ نبياً. (ثلاث مرات)</p>
        <p>اللهم ما أمسى بي من نعمة أو بأحد من خلقك، فمنك وحدك لا شريك لك، فلك الحمد ولك الشكر.</p>
        <p>حسبي الله لا إله إلا هو عليه توكلت وهو رب العرش العظيم. (سبع مرات)</p>
        <p>اللهم عافني في بدني، اللهم عافني في سمعي، اللهم عافني في بصري، لا إله إلا أنت. (ثلاث مرات)</p>
        <p>اللهم إني أعوذ بك من الكفر والفقر، وأعوذ بك من عذاب القبر، لا إله إلا أنت. (ثلاث مرات)</p>
        <p>اللهم إني أسألك العفو والعافية في الدنيا والآخرة...</p>
        <p>اللهم إني أسألك علماً نافعاً، ورزقاً طيباً، وعملاً متقبلاً.</p>
        <p>أستغفر الله العظيم وأتوب إليه. (مائة مرة)</p>
      </div>
    </div>
    
    <!-- Sleep Azkar -->
    <div class="section">
      <h2>🌙 أذكار النوم</h2>
      <div class="azkar">
        <p>باسمك اللهم أموت وأحيا.</p>
        <p>اللهم قني عذابك يوم تبعث عبادك.</p>
        <p>اللهم باسمك وضعت جنبي، وبك أرفعه، فإن أمسكت نفسي فارحمها، وإن أرسلتها فاحفظها بما تحفظ به عبادك الصالحين.</p>
        <p>اللهم إني أسلمت نفسي إليك، وفوضت أمري إليك، وألجأت ظهري إليك، رغبة ورهبة إليك، لا ملجأ ولا منجى منك إلا إليك...</p>
        <p>سبحان الله (33)، الحمد لله (33)، الله أكبر (34).</p>
        <p>آية الكرسي: الله لا إله إلا هو الحي القيوم...</p>
        <p>آخر آيتين من سورة البقرة: آمن الرسول بما أنزل إليه من ربه...</p>
      </div>
    </div>
    
    <!-- Tasbeeh Counter -->
    <div class="section counter-section">
      <h2>🔢 عداد التسبيح</h2>
      <select id="phraseSelector" onchange="changePhrase()">
        <option value="سبحان الله">سبحان الله</option>
        <option value="الحمد لله">الحمد لله</option>
        <option value="الله أكبر">الله أكبر</option>
        <option value="لا إله إلا الله">لا إله إلا الله</option>
        <option value="لا حول ولا قوة إلا بالله">لا حول ولا قوة إلا بالله</option>
        <option value="أستغفر الله">أستغفر الله</option>
        <option value="سبحان الله وبحمده">سبحان الله وبحمده</option>
        <option value="سبحان الله العظيم">سبحان الله العظيم</option>
      </select>
      <div class="phrase" id="currentPhrase">سبحان الله</div>
      <div class="count" id="counter">0</div>
      <div class="counter-buttons">
        <button onclick="increment()">تسبيح</button>
        <button onclick="resetCounter()">إعادة</button>
      </div>
    </div>
  </div>
  <script>
    // دالة تفعيل الوضع الليلي
    function toggleDarkMode() {
      document.body.classList.toggle('dark-mode');
      
      // حفظ حالة الوضع الليلي في التخزين المحلي
      if (document.body.classList.contains('dark-mode')) {
        localStorage.setItem('darkMode', 'enabled');
        document.querySelector('.toggle-btn').textContent = 'الوضع النهاري';
      } else {
        localStorage.setItem('darkMode', 'disabled');
        document.querySelector('.toggle-btn').textContent = 'الوضع الليلي';
      }
    }
    
    // عند تحميل الصفحة، تحقق من تفضيل الوضع الليلي
    document.addEventListener('DOMContentLoaded', function() {
      if (localStorage.getItem('darkMode') === 'enabled') {
        document.body.classList.add('dark-mode');
        document.querySelector('.toggle-btn').textContent = 'الوضع النهاري';
      }
    });
    
    // كود عداد التسبيح
    let count = 0;
    let phrase = document.getElementById("phraseSelector").value;
    
    function increment() {
      count++;
      document.getElementById("counter").textContent = count;
      if (navigator.vibrate) navigator.vibrate(100);
    }
    
    function resetCounter() {
      count = 0;
      document.getElementById("counter").textContent = count;
    }
    
    function changePhrase() {
      phrase = document.getElementById("phraseSelector").value;
      document.getElementById("currentPhrase").textContent = phrase;
      resetCounter();
    }
  </script>
</body>
</html>
