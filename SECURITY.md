<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <title>Restorant PIZZA NINJA</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #fff8f0;
      color: #333;
    }

    header {
      background-color: #e65100;
      padding: 20px;
      text-align: center;
      color: white;
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
    }

    section {
      margin-bottom: 40px;
      background-color: #fff3e0;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #ccc;
    }

    h2 {
      color: #d84315;
    }

    .item {
      margin-bottom: 20px;
    }

    .item img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      box-shadow: 0 0 5px #999;
    }

    footer {
      background-color: #e65100;
      color: white;
      text-align: center;
      padding: 10px;
    }

    button {
      padding: 10px 20px;
      background-color: #ff6f00;
      color: white;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background-color: #e64a19;
    }

    input, select {
      padding: 10px;
      width: 100%;
      margin: 5px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    label {
      display: block;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Restorant PIZZA NINJA 🍕🥷</h1>
    <nav>
      <a href="#pizza">بيتزا</a>
      <a href="#sweet-pizza">بيتزا حلو</a>
      <a href="#crepe">كريب</a>
      <a href="#calzone">كازوني</a>
      <a href="#bomb">قمبلة</a>
      <a href="#order">اطلب</a>
    </nav>
  </header>

  <main>
    <section id="pizza">
      <h2>🍕 أنواع البيتزا</h2>
      <div class="item">
        <h3>بيتزا مارجريتا</h3>
        <img src="https://i.imgur.com/1ZQZ1Zf.jpg" alt="مارجريتا" />
      </div>
      <div class="item">
        <h3>بيتزا فراخ باربكيو</h3>
        <img src="https://i.imgur.com/1da8Q5D.jpg" alt="باربكيو" />
      </div>
    </section>

    <section id="sweet-pizza">
      <h2>🍫 بيتزا حلو</h2>
      <div class="item">
        <h3>بيتزا نوتيلا</h3>
        <img src="https://i.imgur.com/CJhYMFZ.jpg" alt="نوتيلا" />
      </div>
    </section>

    <section id="crepe">
      <h2>🥞 كريب</h2>
      <div class="item">
        <h3>كريب نوتيلا</h3>
        <img src="https://i.imgur.com/z7wqU3C.jpg" alt="كريب نوتيلا" />
      </div>
      <div class="item">
        <h3>كريب فراخ</h3>
        <img src="https://i.imgur.com/8vqgkpc.jpg" alt="كريب فراخ" />
      </div>
    </section>

    <section id="calzone">
      <h2>🫓 كازوني</h2>
      <div class="item">
        <h3>كازوني جبن</h3>
        <img src="https://i.imgur.com/MhKRZ3q.jpg" alt="كازوني" />
      </div>
    </section>

    <section id="bomb">
      <h2>💣 قمبلة</h2>
      <div class="item">
        <h3>قمبلة لحوم</h3>
        <img src="https://i.imgur.com/5gOq7Zb.jpg" alt="قمبلة" />
      </div>
    </section>

    <section id="order">
      <h2>📬 اطلب دلوقتي</h2>
      <form action="https://formsubmit.co/suhaib.obdullah2012@gmail.com" method="POST">
        <input type="hidden" name="_subject" value="طلب جديد من موقع PIZZA NINJA">
        <input type="hidden" name="_template" value="table">
        <input type="hidden" name="_captcha" value="false">

        <label>الاسم:</label>
        <input type="text" name="name" required />

        <label>العنوان:</label>
        <input type="text" name="address" required />

        <label>الطلب:</label>
        <select name="order">
          <option value="بيتزا مارجريتا">بيتزا مارجريتا</option>
          <option value="بيتزا نوتيلا">بيتزا نوتيلا</option>
          <option value="كريب نوتيلا">كريب نوتيلا</option>
          <option value="قمبلة لحوم">قمبلة لحوم</option>
        </select>

        <label>ملاحظات:</label>
        <input type="text" name="notes" placeholder="مثلاً: بدون جبنة زيادة" />

        <button type="submit">إرسال الطلب</button>
      </form>
    </section>
  </main>

  <footer>
    <p>جميع الحقوق محفوظة © Restorant PIZZA NINJA – صهيب 2025</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <title>Restorant PIZZA NINJA</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #fff8f0;
      color: #333;
    }

    header {
      background-color: #e65100;
      padding: 20px;
      text-align: center;
      color: white;
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
    }

    section {
      margin-bottom: 40px;
      background-color: #fff3e0;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #ccc;
    }

    h2 {
      color: #d84315;
    }

    .item {
      margin-bottom: 20px;
    }

    .item img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      box-shadow: 0 0 5px #999;
    }

    footer {
      background-color: #e65100;
      color: white;
      text-align: center;
      padding: 10px;
    }

    button {
      padding: 10px 20px;
      background-color: #ff6f00;
      color: white;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background-color: #e64a19;
    }

    input, select {
      padding: 10px;
      width: 100%;
      margin: 5px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    label {
      display: block;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Restorant PIZZA NINJA 🍕🥷</h1>
    <nav>
      <a href="#pizza">بيتزا</a>
      <a href="#sweet-pizza">بيتزا حلو</a>
      <a href="#crepe">كريب</a>
      <a href="#calzone">كازوني</a>
      <a href="#bomb">قمبلة</a>
      <a href="#order">اطلب</a>
    </nav>
  </header>

  <main>
    <section id="pizza">
      <h2>🍕 أنواع البيتزا</h2>
      <div class="item">
        <h3>بيتزا مارجريتا</h3>
        <img src="https://i.imgur.com/1ZQZ1Zf.jpg" alt="مارجريتا" />
      </div>
      <div class="item">
        <h3>بيتزا فراخ باربكيو</h3>
        <img src="https://i.imgur.com/1da8Q5D.jpg" alt="باربكيو" />
      </div>
    </section>

    <section id="sweet-pizza">
      <h2>🍫 بيتزا حلو</h2>
      <div class="item">
        <h3>بيتزا نوتيلا</h3>
        <img src="https://i.imgur.com/CJhYMFZ.jpg" alt="نوتيلا" />
      </div>
    </section>

    <section id="crepe">
      <h2>🥞 كريب</h2>
      <div class="item">
        <h3>كريب نوتيلا</h3>
        <img src="https://i.imgur.com/z7wqU3C.jpg" alt="كريب نوتيلا" />
      </div>
      <div class="item">
        <h3>كريب فراخ</h3>
        <img src="https://i.imgur.com/8vqgkpc.jpg" alt="كريب فراخ" />
      </div>
    </section>

    <section id="calzone">
      <h2>🫓 كازوني</h2>
      <div class="item">
        <h3>كازوني جبن</h3>
        <img src="https://i.imgur.com/MhKRZ3q.jpg" alt="كازوني" />
      </div>
    </section>

    <section id="bomb">
      <h2>💣 قمبلة</h2>
      <div class="item">
        <h3>قمبلة لحوم</h3>
        <img src="https://i.imgur.com/5gOq7Zb.jpg" alt="قمبلة" />
      </div>
    </section>

    <section id="order">
      <h2>📬 اطلب دلوقتي</h2>
      <form action="https://formsubmit.co/suhaib.obdullah2012@gmail.com" method="POST">
        <input type="hidden" name="_subject" value="طلب جديد من موقع PIZZA NINJA">
        <input type="hidden" name="_template" value="table">
        <input type="hidden" name="_captcha" value="false">

        <label>الاسم:</label>
        <input type="text" name="name" required />

        <label>العنوان:</label>
        <input type="text" name="address" required />

        <label>الطلب:</label>
        <select name="order">
          <option value="بيتزا مارجريتا">بيتزا مارجريتا</option>
          <option value="بيتزا نوتيلا">بيتزا نوتيلا</option>
          <option value="كريب نوتيلا">كريب نوتيلا</option>
          <option value="قمبلة لحوم">قمبلة لحوم</option>
        </select>

        <label>ملاحظات:</label>
        <input type="text" name="notes" placeholder="مثلاً: بدون جبنة زيادة" />

        <button type="submit">إرسال الطلب</button>
      </form>
    </section>
  </main>

  <footer>
    <p>جميع الحقوق محفوظة © Restorant PIZZA NINJA – صهيب 2025</p>
  </footer>
</body>
</html>
