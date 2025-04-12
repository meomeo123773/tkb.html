
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thời Khóa Biểu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            color: #4CAF50;
        }

        table {
            width: 80%;
            margin: 30px auto;
            border-collapse: collapse;
            border: 1px solid #ddd;
            background-color: white;
        }

        table th, table td {
            padding: 10px;
            text-align: center;
            border: 1px solid #ddd;
        }

        table th {
            background-color: #4CAF50;
            color: white;
        }

        a {
            color: #2196F3;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        iframe {
            width: 100%;
            height: 300px;
            border: 1px solid #ddd;
        }

        ul {
            list-style-type: square;
            padding-left: 20px;
        }

        form {
            width: 60%;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
        }

        label {
            font-weight: bold;
            display: block;
            margin: 10px 0 5px;
        }

        input[type="text"], input[type="email"], select, textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ddd;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }

        .container {
            width: 90%;
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            border: 2px solid #ddd;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        .highlight {
            color: #e91e63;
            font-style: italic;
        }

        .background {
            background-color: #fce4ec;
        }

        .priority-1 {
            font-weight: bold;
            color: #ff5722;
        }

        .priority-2 {
            font-weight: bold;
            color: #3f51b5;
        }

        .priority-3 {
            color: #607d8b;
        }

    </style>
</head>
<body>

    <div class="container">
        <h1>Thời Khóa Biểu</h1>
        <p>Chào mừng bạn đến với thời khóa biểu của lớp học!</p>
        <table>
            <tr>
                <th>Thời Gian</th>
                <th>Môn Học</th>
                <th>Giảng Viên</th>
            </tr>
            <tr>
                <td>7:00 - 8:30</td>
                <td>Toán</td>
                <td>Thầy Nam</td>
            </tr>
            <tr>
                <td>8:30 - 10:00</td>
                <td>Lý</td>
                <td>Cô Lan</td>
            </tr>
            <tr>
                <td>10:00 - 11:30</td>
                <td>Hóa</td>
                <td>Thầy Minh</td>
            </tr>
        </table>
        <p><a href="https://example.com/tailieu.pdf" target="_blank">Tải tài liệu học tập</a></p>
        <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="YouTube video player"></iframe>
        <h2>Môn Học</h2>
        <ul>
            <li>Toán</li>
            <li>Lý</li>
            <li>Hóa</li>
            <li>Sinh</li>
        </ul>
        <h2>Đăng Ký</h2>
        <form action="#" method="POST">
            <label for="name">Họ và Tên</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="course">Chọn Môn Học</label>
            <select id="course" name="course">
                <option value="toan">Toán</option>
                <option value="ly">Lý</option>
                <option value="hoa">Hóa</option>
            </select>

            <label for="message">Thông tin thêm</label>
            <textarea id="message" name="message" rows="4"></textarea>

            <input type="submit" value="Gửi Đăng Ký">
        </form>
    </div>

</body>
</html>
        
        
