!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Beauty</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff69b4, #00b7eb);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }
        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.imgur.com/8Q8z8Xg.png') repeat;
            opacity: 0.5;
            z-index: -1;
            animation: twinkle 5s infinite;
        }
        @keyframes twinkle {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 0.8; }
        }
        .header {
            padding: 40px;
            font-size: 2.5em;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }
        .section {
            padding: 50px;
            margin: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            transition: transform 0.3s;
        }
        .section:hover {
            transform: scale(1.05);
        }
        img {
            max-width: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
    </style>
</head>
<body>
    <div class="stars"></div>
    <div class="header">Global Beauty</div>
    
    <div class="section">
        <h2>Trang Điểm</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300?text=Makeup+1" alt="Trang điểm 1">
            <img src="https://via.placeholder.com/300?text=Makeup+2" alt="Trang điểm 2">
        </div>
    </div>
    
    <div class="section">
        <h2>Phong Cảnh & Biển</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300?text=Beach" alt="Biển">
            <img src="https://via.placeholder.com/300?text=Landscape" alt="Phong cảnh">
        </div>
    </div>
    
    <div class="section">
        <h2>Phong Cách Sống</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300?text=Home" alt="Nhà ở">
            <img src="https://via.placeholder.com/300?text=Lifestyle" alt="Sống đẹp">
        </div>
    </div>
    
    <div class="section">
        <h2>Cơ Thể Năng Lượng</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300?text=Fitness" alt="Thể thao">
            <img src="https://via.placeholder.com/300?text=Energy" alt="Năng lượng">
        </div>
    </div>
    
    <div class="section">
        <h2>Nhân Đạo</h2><p>Chia sẻ những điều đẹp đẽ nhất vì Trái Đất.</p>
        <div class="gallery">
            <img src="https://via.placeholder.com/300?text=Humanity" alt="Nhân đạo">
        </div>
    </div>
</body>
</html>
