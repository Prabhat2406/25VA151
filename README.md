# 25VA151<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instamart Basic</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #eef2ff;
        }
        .navbar {
            background: #4f46e5;
            padding: 15px;
            color: #fff;
            font-size: 22px;
            font-weight: bold;
            text-align: center;
        }
        .hero {
            background: white;
            padding: 40px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            border-bottom: 4px solid #4f46e5;
        }
        .search-box input {
            width: 70%;
            padding: 12px;
            border: 2px solid #4f46e5;
            border-radius: 8px;
            font-size: 16px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 3px 7px rgba(0,0,0,0.1);
            border-left: 5px solid #4f46e5;
        }
        .card h3 {
            margin: 0 0 10px;
            font-size: 18px;
            color: #333;
        }
        .card button {
            background: #4f46e5;
            border: none;
            color: white;
            padding: 10px;
            width: 100%;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
        }
        .card button:hover {
            background: #3730a3;
        }
    </style>
</head>
<body>
    <div class="navbar">Instamart</div>

    <div class="hero">
        <h2>Groceries delivered in minutes</h2>
        <div class="search-box">
            <input type="text" placeholder="Search for milk, bread, fruits...">
        </div>
    </div>

    <div class="products">
        <div class="card">
            <h3>Milk 1L</h3>
            <p>₹55</p>
            <button>Add</button>
        </div>
        <div class="card">
            <h3>Bananas (1 Dozen)</h3>
            <p>₹40</p>
            <button>Add</button>
        </div>
        <div class="card">
            <h3>Bread</h3>
            <p>₹35</p>
            <button>Add</button>
        </div>
        <div class="card">
            <h3>Eggs (6 pack)</h3>
            <p>₹60</p>
            <button>Add</button>
        </div>
    </div>
</body>
</html>
