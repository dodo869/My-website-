# My-website-
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>صفحة الهبوط</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
      direction: rtl;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 15px 0;
      text-align: center;
    }
    .container {
      width: 90%;
      margin: auto;
      overflow: hidden;
    }
    .product-card {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      margin: 10px 0;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .product-card img {
      max-width: 100%;
      border-radius: 10px;
    }
    .product-info {
      padding: 10px 0;
    }
    .form-section {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <header>
    <h1>مرحبًا بكم في متجرنا</h1>
    <p>اكتشف أفضل المنتجات بأسعار مذهلة</p>
  </header>

  <div class="container">
    <!-- قسم المنتجات -->
    <div class="product-card">
      <img src="https://via.placeholder.com/300" alt="صورة المنتج">
      <div class="product-info">
        <h2>اسم المنتج</h2>
        <p>وصف مختصر للمنتج هنا.</p>
        <p>السعر: 1500 دج</p>
      </div>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/300" alt="صورة المنتج">
      <div class="product-info">
        <h2>اسم المنتج</h2>
        <p>وصف مختصر للمنتج هنا.</p>
        <p>السعر: 2500 دج</p>
      </div>
    </div>

    <!-- قسم نموذج المعلومات -->
    <div class="form-section">
      <h2>اطلب الآن</h2>
      <form action="#" method="POST">
        <label for="name">الاسم:</label>
        <input type="text" id="name" name="name" required>

        <label for="surname">اللقب:</label>
        <input type="text" id="surname" name="surname" required>

        <label for="phone">رقم الهاتف:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="state">الولاية:</label>
        <select id="state" name="state" required>
          <option value="">اختر الولاية</option>
          <option value="algiers">الجزائر</option>
          <option value="oran">وهران</option>
          <!-- أضف المزيد من الولايات هنا -->
        </select>

        <label for="city">البلدية:</label>
        <input type="text" id="city" name="city" required>

        <label for="message">ملاحظات إضافية:</label>
        <textarea id="message" name="message" rows="4"></textarea>

        <button type="submit">إرسال الطلب</button>
      </form>
    </div>
  </div>
</body>
</html>
