<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Học Tập</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
        }
        section {
            background: white;
            width: 60%;
            margin: 20px auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px gray;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        img {
            width: 300px;
            margin-top: 10px;
        }
        input, select, textarea {
            width: 90%;
            padding: 8px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <!-- Danh Sách Môn Học -->
    <section>
        <h2>Danh Sách Môn Học</h2>
        <ul>
            <li>Toán</li>
            <li>Vật Lý</li>
            <li>Hóa Học</li>
            <li>Ngữ Văn</li>
            <li>Tiếng Anh</li>
            <li>Sinh Học</li>
        </ul>
    </section>

    <!-- Thời Khóa Biểu -->
    <section>
        <h2>Thời Khóa Biểu</h2>
        <table>
            <tr>
                <th>Thứ</th>
                <th>Tiết 1</th>
                <th>Tiết 2</th>
                <th>Tiết 3</th>
            </tr>
            <tr>
                <td>Thứ Hai</td>
                <td>Toán</td>
                <td>Vật Lý</td>
                <td>Hóa Học</td>
            </tr>
            <tr>
                <td>Thứ Ba</td>
                <td>Ngữ Văn</td>
                <td>Tiếng Anh</td>
                <td>Sinh Học</td>
            </tr>
        </table>
    </section>

    <!-- Hình Ảnh Minh Họa -->
    <section>
        <h2>Hình Ảnh Minh Họa</h2>
        <img src="https://images.app.goo.gl/RXMRTdotrGZsLsnYA " alt="Hình ảnh minh họa">
    </section>

    <!-- Liên Kết Học Tập -->
    <section>
        <h2>Liên Kết Học Tập</h2>
        <p>Truy cập <a href="https://www.khanacademy.org" target="_blank">Khan Academy</a> để học tập miễn phí!</p>
    </section>

    <!-- Biểu Mẫu Đăng Ký Câu Lạc Bộ Toán -->
    <section>
        <h2>Đăng Ký Tham Gia Câu Lạc Bộ Toán</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Họ và Tên:</label><br>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>

            <label for="phone">Số Điện Thoại:</label><br>
            <input type="tel" id="phone" name="phone" required><br>

            <label for="class">Lớp Học:</label><br>
            <select id="class" name="class">
                <option value="10">Lớp 10</option>
                <option value="11">Lớp 11</option>
                <option value="12">Lớp 12</option>
            </select><br>

            <label for="level">Bạn yêu thích môn Toán mức nào?</label><br>
            <input type="radio" id="high" name="level" value="high" checked> Rất thích  
            <input type="radio" id="medium" name="level" value="medium"> Bình thường  
            <input type="radio" id="low" name="level" value="low"> Ít thích<br>

            <label for="reason">Lý do bạn muốn tham gia?</label><br>
            <textarea id="reason" name="reason" rows="4" required></textarea><br>

            <button type="submit">Gửi Đăng Ký</button>
        </form>
    </section>

</body>
</html>

