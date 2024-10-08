<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل دخول شبكة العامري</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
            text-align: center;
            padding: 50px;
            margin: 0;
        }

        .login-container {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            max-width: 400px;
            margin: auto;
            color: #333;
        }

        h2 {
            color: #444;
            font-size: 24px;
        }

        .input-field {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            color: #333;
            background-color: #f1f1f1;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        select {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 8px;
            font-size: 16px;
            color: #333;
            border: none;
            background-color: #f1f1f1;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .remember {
            margin: 20px 0;
        }

        input[type="submit"] {
            background-color: #28a745;
            color: white;
            padding: 14px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 18px;
            width: 100%;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        input[type="submit"]:hover {
            background-color: #218838;
        }

        .footer {
            margin-top: 20px;
            font-size: 12px;
            color: #f1f1f1;
        }

        /* شريط التمرير للإعلان */
        .marquee {
            margin: 20px 0;
            background-color: #333;
            color: #fff;
            padding: 10px;
            border-radius: 8px;
            font-size: 14px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        .marquee-text {
            animation: scroll 10s linear infinite;
            white-space: nowrap;
        }

        @keyframes scroll {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }

        /* تنسيق الرقم للتواصل */
        .contact {
            margin-top: 20px;
            font-size: 14px;
            color: #444;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>تسجيل دخول شبكة العامري</h2>
        
        <div class="marquee">
            <div class="marquee-text">شبكة العامري نت - أفضل اتصال وأفضل خدمات - أهلاً وسهلاً بكم</div>
        </div>

        <form action="login.php" method="POST">
            <input type="text" class="input-field" name="username" placeholder="اسم المستخدم" required>
            <input type="password" class="input-field" name="password" placeholder="كلمة المرور" required>
            
            <select name="speed" required>
                <option value="" disabled selected>اختيار السرعة المناسبة</option>
                <option value="500KB">500 كيلو بايت</option>
                <option value="1MB">1 ميجا بايت</option>
                <option value="5MB">5 ميجا بايت</option>
            </select>
            
            <div class="remember">
                <label>
                    <input type="checkbox" name="remember_card"> تذكر الكرت
                </label>
            </div>
            
            <input type="submit" value="تسجيل الدخول">
        </form>
        
        <div class="contact">
            للتواصل مع الإدارة: 73747141
        </div>

        <div class="footer">جميع الحقوق محفوظة © 2024 شبكة العامري</div>
    </div>
</body>
</html>
