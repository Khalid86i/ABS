<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة ABC - إنشاء حساب الموظفين</title>
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
        <h1>شركة ABC - إنشاء حساب الموظفين</h1>
        <form action="register.php" method="POST">
            <div class="mb-3">
                <label for="employee-id" class="form-label">رقم الموظف:</label>
                <input type="text" id="employee-id" name="employee_id" class="form-control" placeholder="أدخل رقم الموظف" required>
            </div>

            <div class="mb-3">
                <label for="username" class="form-label">اسم المستخدم:</label>
                <input type="text" id="username" name="username" class="form-control" placeholder="أدخل اسم المستخدم" required>
            </div>

            <div class="mb-3">
                <label for="email" class="form-label">البريد الإلكتروني:</label>
                <input type="email" id="email" name="email" class="form-control" placeholder="أدخل البريد الإلكتروني" required>
            </div>

            <div class="mb-3">
                <label for="password" class="form-label">كلمة المرور:</label>
                <input type="password" id="password" name="password" class="form-control" placeholder="أدخل كلمة المرور" required>
            </div>

            <div class="mb-3">
                <label for="confirm-password" class="form-label">تأكيد كلمة المرور:</label>
                <input type="password" id="confirm-password" name="confirm_password" class="form-control" placeholder="أعد إدخال كلمة المرور" required>
            </div>

            <button type="submit" class="btn btn-success w-100">إنشاء الحساب</button>
        </form>
    </div>
    <footer>
        &copy; 2024 شركة ABC. جميع الحقوق محفوظة.
    </footer>
</body>
</html>
