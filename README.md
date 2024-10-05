<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RaspberryWorld - Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            padding: 20px;
            text-align: center;
            color: white;
        }
        nav {
            display: flex;
            justify-content: space-between;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
        }
        .search-bar {
            display: flex;
            justify-content: space-between;
            padding: 10px;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .search-bar input {
            width: 80%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .search-bar button {
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }
        .product {
            background-color: white;
            width: 220px;
            margin: 10px;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            color: #007bff;
        }
        .product p {
            color: #333;
        }
        .product button {
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #218838;
        }
        .btn-nap-tien {
            background-color: #ffc107;
            color: black;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-left: auto;
        }
        .btn-nap-tien:hover {
            background-color: #e0a800;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>RaspberryWorld Shop</h1>
</header>

<nav>
    <div>
        <a href="#">Sản phẩm hot</a>
        <a href="#">Acc giá rẻ</a>
        <a href="#">Mã giảm giá</a>
        <a href="#">Minigame hấp dẫn</a>
    </div>
    <a class="btn-nap-tien" href="#nap-tien">Nạp Tiền</a>
</nav>

<div class="search-bar">
    <input type="text" placeholder="Tìm kiếm sản phẩm...">
    <button>Tìm kiếm</button>
</div>

<section class="product-list">
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm">
        <h3>Bán Gems - Unit</h3>
        <p>Giao dịch: 683</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm">
        <h3>Bán Item Arm Wrestle</h3>
        <p>Giao dịch: 938</p>
        <button>Mua ngay</button>
    </div>
</section>

<section id="nap-tien">
    <h2>Nạp Tiền</h2>
    <label for="provider">Nhà cung cấp:</label>
    <select id="provider">
        <option value="viettel">VIETTEL</option>
        <option value="vinaphone">VINAPHONE</option>
        <option value="mobifone">MOBIFONE</option>
        <option value="garena">GARENA</option>
        <option value="zing">ZING</option>
    </select>

    <label for="amount">Chọn mệnh giá:</label>
    <select id="amount">
        <option value="10000">10,000 VND - Nhận 100%</option>
        <option value="20000">20,000 VND - Nhận 100%</option>
        <option value="50000">50,000 VND - Nhận 100%</option>
    </select>

    <br>
    <label for="card-number">Mã số thẻ:</label>
    <input type="text" id="card-number" placeholder="Nhập mã số thẻ">
    <br>
    <label for="serial">Số sê-ri:</label>
    <input type="text" id="serial" placeholder="Nhập số sê-ri">
    <br>
    <button>Nạp Ngay</button>
</section>

<footer>
    <p>&copy; 2024 RaspberryWorld. Tất cả quyền được bảo lưu.</p>
</footer>

</body>
</html>
