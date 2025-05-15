<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>আমার ই-কমার্স</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #ff6600;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: white;
    }
    header h1 {
      margin: 0;
    }
    .top-buttons button {
      margin-left: 10px;
      padding: 6px 12px;
      border: none;
      background-color: white;
      color: #ff6600;
      border-radius: 4px;
      cursor: pointer;
    }
    nav {
      background-color: #333;
      display: flex;
      justify-content: space-between;
      padding: 10px 20px;
      align-items: center;
    }
    nav .menu a {
      color: white;
      margin-right: 20px;
      text-decoration: none;
    }
    nav .search input {
      padding: 5px;
      width: 200px;
    }
    nav .search button {
      padding: 5px 10px;
      background-color: #ff6600;
      border: none;
      color: white;
      cursor: pointer;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      padding: 10px;
      border-radius: 5px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product p {
      margin: 5px 0;
    }
    .product button {
      background-color: #ff6600;
      color: white;
      border: none;
      padding: 8px 12px;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 15px 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>আমার ই-কমার্স</h1>
    <div class="top-buttons">
      <button>লগইন</button>
      <button>রেজিস্টার</button>
      <button>কার্ট (0)</button>
    </div>
  </header>

  <nav>
    <div class="menu">
      <a href="#">হোম</a>
      <a href="#">সকল পণ্য</a>
      <a href="#">ডিলস</a>
      <a href="#">যোগাযোগ</a>
    </div>
    <div class="search">
      <input type="text" placeholder="পণ্য খুঁজুন...">
      <button>সার্চ</button>
    </div>
  </nav>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product">
      <h3>পণ্য ১</h3>
      <p>৳৫০০</p>
      <button>কার্টে যোগ করুন</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product">
      <h3>পণ্য ২</h3>
      <p>৳৭৫০</p>
      <button>কার্টে যোগ করুন</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product">
      <h3>পণ্য ৩</h3>
      <p>৳১২০০</p>
      <button>কার্টে যোগ করুন</button>
    </div>
  </section>

  <footer>
    <p>&copy; ২০২৫ আমার ই-কমার্স. সর্বস্বত্ব সংরক্ষিত।</p>
    <p>যোগাযোগ: ০১৭xxxxxxxx | info@amarshop.com</p>
  </footer>

</body>
</html>
