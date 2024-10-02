<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RaspberryWorld</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            text-align: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
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
            border-radius: 5px;
        }
        .product h3 {
            color: #ff6347;
        }
        .product p {
            font-size: 14px;
            color: #555;
        }
        .product button {
            background-color: #ff6347;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #ff7f50;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .top-up {
            background-color: white;
            padding: 20px;
            margin: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .top-up select, .top-up input {
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 80%;
        }
        .top-up button {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .top-up button:hover {
            background-color: #218838;
        }
        .provider {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>RaspberryWorld</h1>
</header>

<nav>
    <a href="#">Trang Chủ</a>
    <a href="#">Sản Phẩm</a>
    <a href="#">Liên Hệ</a>
</nav>

<div class="container">
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm 1">
        <h3>Sản phẩm 1</h3>
        <p>Giá: 50.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm 2">
        <h3>Sản phẩm 2</h3>
        <p>Giá: 100.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm 3">
        <h3>Sản phẩm 3</h3>
        <p>Giá: 150.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm 4">
        <h3>Sản phẩm 4</h3>
        <p>Giá: 200.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản phẩm 5">
        <h3>Sản phẩm 5</h3>
        <p>Giá: 250.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
</div>

<div class="top-up">
    <h2>Nạp Tiền</h2>
    <h3>Nạp thẻ cào</h3>
    <div class="provider">
        <label for="provider">Nhà cung cấp:</label>
        <select id="provider">
            <option value="viettel">VIETTEL</option>
            <option value="vinaphone">VINAPHONE</option>
            <option value="mobifone">MOBIFONE</option>
            <option value="garena">GARENA</option>
            <option value="zing">ZING</option>
            <option value="vcoin">VCOIN</option>
            <option value="gate">GATE</option>
        </select>
    </div>
    <div class="provider">
        <label for="denomination">Chọn mệnh giá:</label>
        <select id="denomination">
            <option value="10000">10,000 VNĐ (Nhận 100%)</option>
            <option value="20000">20,000 VNĐ (Nhận 100%)</option>
            <option value="30000">30,000 VNĐ (Nhận 100%)</option>
            <option value="50000">50,000 VNĐ (Nhận 100%)</option>
            <option value="100000">100,000 VNĐ (Nhận 100%)</option>
            <option value="200000">200,000 VNĐ (Nhận 100%)</option>
            <option value="500000">500,000 VNĐ (Nhận 100%)</option>
            <option value="1000000">1,000,000 VNĐ (Nhận 100%)</option>
            <option value="300000">300,000 VNĐ (Nhận 100%)</option>
        </select>
    </div>
    <p><strong>*Chú ý:</strong> Nạp thẻ sai mệnh giá mất 100% giá trị thẻ.</p>
    <input type="text" placeholder="Mã số thẻ" required>
    <input type="text" placeholder="Số sê-ri" required>
    <input type="text" placeholder="Mã bảo vệ" required>
    <button>Nạp Ngay</button>
</div>

<footer>
    <p>&copy; 2024 RaspberryWorld. Tất cả quyền được bảo lưu.</p>
</footer>

</body>
</html>
