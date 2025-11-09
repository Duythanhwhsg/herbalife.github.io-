<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu bản thân - Nguyễn Duy Thanh</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            animation: fadeIn 1s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .container {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 30px;
            max-width: 600px;
            text-align: center;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            animation: slideUp 1s ease-out;
        }

        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #ff0000; /* Khung ảnh màu đỏ */
            object-fit: cover;
            margin-bottom: 20px;
            transition: transform 0.3s ease;
        }

        .profile-img:hover {
            transform: scale(1.1);
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .info {
            font-size: 1.2em;
            margin: 10px 0;
        }

        .links {
            margin-top: 20px;
        }

        .links a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px 20px;
            background: #ff0000;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s ease, transform 0.3s ease;
        }

        .links a:hover {
            background: #cc0000;
            transform: translateY(-5px);
        }

        .phone {
            font-size: 1.1em;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="c:\Users\Admin\Pictures\Screenshots\z7142935492401_b7cb386e4c3316510deafc812233180d.jpg" alt="Ảnh đại diện" class="profile-img">
        <h1 style="color: #00f2fe;">Nguyễn Duy Thanh</h1>
        <div class="info">
            <p style="color: #cc0000;" ><strong>Sinh ngày:</strong> 20/11/2005</p>
            <p style="color: #cc0000;"><strong>Nơi sống:</strong> Thanh Hóa</p>
            <p style="color: #cc0000;"><strong>Nghề nghiệp:</strong> Sinh viên IT Công nghệ Thông tin Đại Học HỒNG Đức </p>
        </div>
        <div class="links">
            <a href="https://www.facebook.com/share/17pj4CvnLR/?mibextid=wwXIfr" target="_blank">Facebook</a>
            <a href="https://www.tiktok.com/@thanhdeptrai315?_r=1&_t=ZS-91FJodt83JV" target="_blank">TikTok</a>
        </div>
        <div class="phone">
            <p style="color: #00f2fe;"><strong>Số điện thoại:</strong> <a href="tel:0866890005" style="color: #fff;">0866890005</a></p>
        </div>
    </div>
</body>
</html>
