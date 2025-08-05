<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>دار المؤمنات | التسجيل</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #fdfaf5;
      color: #4b3e2b;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #e8d8c3;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    main {
      padding: 30px;
      max-width: 600px;
      margin: auto;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    label {
      font-weight: bold;
    }
    input, select, textarea, button {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }
    button {
      background-color: #a3825e;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #8a6a4f;
    }
    footer {
      margin-top: 40px;
      text-align: center;
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>دار المؤمنات - التسجيل في الدورة</h1>
  </header>
  <main>
    <form action="https://formsubmit.co/your-email@example.com" method="POST">
      <label for="name">الاسم الكامل:</label>
      <input type="text" id="name" name="name" required><label for="age">العمر:</label>
  <input type="number" id="age" name="age" required>

  <label for="phone">رقم الجوال:</label>
  <input type="tel" id="phone" name="phone" required>

  <label for="email">البريد الإلكتروني:</label>
  <input type="email" id="email" name="email" required>

  <label for="course">الدورة المطلوبة:</label>
  <select id="course" name="course" required>
    <option value="">-- اختاري --</option>
    <option value="الفقه">الفقه</option>
    <option value="العقيدة">العقيدة</option>
    <option value="تفسير">تفسير</option>
    <option value="سيرة">السيرة النبوية</option>
  </select>

  <label for="note">ملاحظات إضافية:</label>
  <textarea id="note" name="note" rows="3"></textarea>

  <!-- إعدادات مخفية لـ FormSubmit -->
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_next" value="https://daralmuminat.com/thanks">

  <button type="submit">إرسال التسجيل</button>
</form>
<footer>
  <p>جميع الحقوق محفوظة &copy; دار المؤمنات 2025</p>
</footer>

  </main>
</body>
</html>
ahmme614@example.com
