# index.html
No description 
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Của Tôi</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
        body { background: #f0f8ff; color: #333; line-height: 1.6; }
        header { background: #2c3e50; color: white; padding: 2rem; text-align: center; }
        h1 { font-size: 2rem; margin-bottom: 0.5rem; }
        section { max-width: 800px; margin: 2rem auto; padding: 0 1rem; }
        .card { background: white; padding: 2rem; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.1); margin-bottom: 1.5rem; }
        h2 { color: #2c3e50; margin-bottom: 1rem; }
        p { margin-bottom: 1rem; }
        button { background: #3498db; color: white; border: none; padding: 0.8rem 2rem; border-radius: 8px; font-size: 1rem; cursor: pointer; transition: 0.3s; }
        button:hover { background: #2980b9; transform: scale(1.05); }
        footer { background: #2c3e50; color: white; text-align: center; padding: 1.5rem; margin-top: 2rem; }
    </style>
</head>
<body>
    <header>
        <h1>Chào Mừng Đến Với Website Của Tôi �</h1>
        <p>Đơn giản, đẹp và dễ dùng</p>
    </header>

    <section>
        <div class="card">
            <h2>Giới Thiệu</h2>
            <p>Đây là website đơn giản mình tạo cho bạn. Bạn có thể thay đổi nội dung, màu sắc, chữ viết theo ý muốn nhé!</p>
            <button onclick="thongBao()">Nhấn Vào Tôi</button>
        </div>

        <div class="card">
            <h2>Nội Dung Chính</h2>
            <p>Bạn có thể viết gì ở đây: giới thiệu bản thân, dự án, hình ảnh, liên kết... Tất cả đều dễ chỉnh sửa!</p>
        </div>
    </section>

    <footer>
        <p>© 2025 Website Của Tôi — Tạo bởi Dola</p>
    </footer>

    <script>
        function thongBao() {
            alert('Chào bạn! Website đang hoạt động tốt ✅');
        }
    </script>
</body>
</html>
