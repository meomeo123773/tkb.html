
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Đồ Dùng Học Tập</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .container {
            width: 90%;
            margin: 20px auto;
        }

        h2 {
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 15px 0;
            font-size: 18px;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        img {
            width: 150px;
            height: auto;
            margin-top: 10px;
            display: block;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            text-align: center;
            padding: 10px;
        }

        th {
            background-color: #4CAF50;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <header>
        <h1>Đồ Dùng Học Tập và Thời Khóa Biểu</h1>
    </header>

    <div class="container">
        <h2>Danh Sách Đồ Dùng Học Tập</h2>
        <ul>
            <li>
                <strong>Sách Giáo Khoa</strong>
                <a href="https://shopee.vn/" target="_blank">Mua trên Shopee</a>
                <img src="https://via.placeholder.com/150" alt="Hình Sách Giáo Khoa">
            </li>
            <li>
                <strong>Bút Bi</strong>
                <a href="https://shopee.vn/" target="_blank">Mua trên Shopee</a>
                <img src="https://via.placeholder.com/150" alt="Hình Bút Bi">
            </li>
            <li>
                <strong>Vở Ghi Chép</strong>
                <a href="https://shopee.vn/" target="_blank">Mua trên Shopee</a>
                <img src="https://via.placeholder.com/150" alt="Hình Vở Ghi Chép">
            </li>
            <li>
                <strong>Hộp Bút</strong>
                <a href="https://shopee.vn/" target="_blank">Mua trên Shopee</a>
                <img src="https://via.placeholder.com/150" alt="Hình Hộp Bút">
            </li>
        </ul>

        <h2>Thời Khóa Biểu</h2>
        <table>
            <tr>
                <th>Thứ</th>
                <th>Buổi Sáng</th>
                <th>Buổi Chiều</th>
            </tr>
            <tr>
                <td>Thứ Hai</td>
                <td>Toán, Văn</td>
                <td>Hóa, Sinh</td>
            </tr>
            <tr>
                <td>Thứ Ba</td>
                <td>Lý, Anh</td>
                <td>Sử, Địa</td>
            </tr>
            <tr>
                <td>Thứ Tư</td>
                <td>Toán, Tin</td>
                <td>Thể dục, Văn</td>
            </tr>
            <tr>
                <td>Thứ Năm</td>
                <td>Hóa, Sinh</td>
                <td>Lý, Anh</td>
            </tr>
            <tr>
                <td>Thứ Sáu</td>
                <td>Toán, Văn</td>
                <td>GDCD, Tin</td>
            </tr>
        </table>
    </div>
</body>
</html>
