<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة ABC - تسجيل ساعات العمل</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 700px;
            margin: 50px auto;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 30px;
        }
        h1 {
            text-align: center;
            color: #007bff;
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>شركة ABC - تسجيل ساعات العمل</h1>
        <form action="submit_hours.php" method="POST">
            <div class="mb-3">
                <label for="employee-id" class="form-label">رقم الموظف:</label>
                <input type="text" id="employee-id" name="employee_id" class="form-control" placeholder="أدخل رقم الموظف" required>
            </div>

            <div class="mb-3">
                <label for="date" class="form-label">التاريخ:</label>
                <input type="date" id="date" name="date" class="form-control" required>
            </div>

            <div class="mb-3">
                <label for="start-time" class="form-label">وقت البدء:</label>
                <input type="time" id="start-time" name="start_time" class="form-control" required>
            </div>

            <div class="mb-3">
                <label for="end-time" class="form-label">وقت الانتهاء:</label>
                <input type="time" id="end-time" name="end_time" class="form-control" required>
            </div>

            <button type="submit" class="btn btn-primary w-100">تسجيل</button>
        </form>
    </div>
    <footer>
        &copy; 2024 شركة ABC. جميع الحقوق محفوظة.
    </footer>
</body>
</html>

