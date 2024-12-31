# mywebsite
<!DOCTYPE html>  
<html lang="fa">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>فروشگاه حرزکریمه اهل بیت</title>  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            margin: 0;  
            padding: 0;  
            background-color: #f4f4f4;  
            color: #333;  
        }  
        header {  
            background-color: #4CAF50;  
            color: white;  
            padding: 15px;  
            text-align: center;  
        }  
        nav {  
            margin: 0;  
            padding: 10px;  
            background-color: #333;  
        }  
        nav a {  
            color: white;  
            padding: 14px 20px;  
            text-decoration: none;  
            text-align: center;  
        }  
        nav a:hover {  
            background-color: #ddd;  
            color: black;  
        }  
        .container {  
            width: 80%;  
            margin: 20px auto;  
            display: flex;  
            flex-wrap: wrap;  
        }  
        .product {  
            background: white;  
            border-radius: 5px;  
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);  
            margin: 20px;  
            flex: 1 1 calc(33% - 40px);  
            padding: 20px;  
            transition: transform 0.2s;  
        }  
        .product:hover {  
            transform: scale(1.05);  
        }  
        .product img {  
            max-width: 100%;  
            border-radius: 5px;  
        }  
        .product h2 {  
            font-size: 18px;  
            margin: 10px 0;  
        }  
        .product p {  
            margin: 10px 0;  
        }  
        .price {  
            font-size: 20px;  
            color: #4CAF50;  
            margin: 10px 0;  
        }  
        .buy-btn {  
            background-color: #4CAF50;  
            color: white;  
            border: none;  
            padding: 10px;  
            cursor: pointer;  
            border-radius: 5px;  
            transition: background-color 0.3s;  
        }  
        .buy-btn:hover {  
            background-color: #45a049;  
        }  
        footer {  
            text-align: center;  
            padding: 20px;  
            background-color: #333;  
            color: white;  
            position: relative;  
            bottom: 0;  
            width: 100%;  
        }  
    </style>  
</head>  
<body>  

<header>  
    <h1>فروشگاه حرز کریمه اهل بیت /مرتضوی</h1>  
    <p>حرز امام جواد روی پوست آهو</p>  
</header>  

<nav>  
    <a href="#">خانه</a>  
    <a href="#">محصولات</a>  
    <a href="#">درباره ما</a>  
    <a href="#">تماس با ما</a>  
</nav>  

<div class="container">  
    <div class="product">  
        <img src="https://via.placeholder.com/300" alt="حرز پوست آهو ۱">  
        <h2>حرز *****</h2>  
        <p>حرز تابلویی</p>  
        <p class="price">قیمت: ۵۰۰,۰۰۰ تومان</p>  
        <button class="buy-btn">خرید</button>  
    </div>  
    <div class="product">  
        <img src="https://via.placeholder.com/300" alt="حرز طلایی ۲">  
        <h2>حرز طلایی ۲</h2>  
        <p>حرز لوکس با بهترین کیفیت.</p>  
        <p class="price">قیمت: ۷۰۰,۰۰۰ تومان</p>  
        <button class="buy-btn">خرید</button>  
    </div>  
    <div class="product">  
        <img src="https://via.placeholder.com/300" alt="حرز طلایی ۳">  
        <h2>حرز طلایی ۳</h2>  
        <p>حرز با طراحی مدرن و زیبا.</p>  
        <p class="price">قیمت: ۶۰۰,۰۰۰ تومان</p>  
        <button class="buy-btn">خرید</button>  
    </div>  
</div>  

<footer>  
    <p>&copy; 2024 فروشگاه حرز. تمامی حقوق محفوظ است.</p>  
</footer>  

</body>  
</html>
