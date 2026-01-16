<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أكاديمية المهارات الإدارية | 2026</title>
    
    <!-- مكتبة الأيقونات والخطوط -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <link href="https://fonts.googleapis.com" rel="stylesheet">
    
    <style>
        :root {
            --primary: #1a2a6c;
            --secondary: #b21f1f;
            --accent: #fdbb2d;
            --white: #ffffff;
            --bg-light: #f8f9fa;
        }

        * {
            margin: 0; padding: 0; box-sizing: border-box;
            font-family: 'Almarai', sans-serif;
        }

        body { background-color: var(--bg-light); color: #333; line-height: 1.6; }

        /* الهيدر */
        header {
            background: var(--primary);
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            position: sticky; top: 0; z-index: 1000;
        }

        .logo {
            color: var(--accent);
            font-size: 1.4rem;
            font-weight: 800;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            margin-right: 20px;
            font-weight: 700;
            transition: 0.3s;
        }

        nav a:hover { color: var(--accent); }

        /* القسم الرئيسي */
        .hero {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: white;
            padding: 100px 5%;
            text-align: center;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .hero h1 { font-size: 3rem; margin-bottom: 20px; }

        /* قسم الدورات */
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            padding: 50px 5%;
        }

        .service-card {
            background: var(--white);
            padding: 25px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            transition: 0.4s;
            border-bottom: 5px solid var(--accent);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .service-card:hover { transform: translateY(-10px); }

        .video-container {
            border-radius: 15px;
            overflow: hidden;
            margin-bottom: 15px;
            background: #000;
            aspect-ratio: 16/9;
        }

        .service-card i { font-size: 2.5rem; color: var(--primary); margin-bottom: 15px; }
        
        .course-features {
            text-align: right;
            margin: 15px 0;
            font-size: 0.9rem;
        }

        .course-features li {
            list-style: none;
            margin-bottom: 8px;
            color: #555;
        }

        .course-features li i {
            font-size: 1rem;
            color: #27ae60;
            margin-left: 8px;
        }

        .price-tag {
            font-size: 1.4rem;
            font-weight: 800;
            color: var(--secondary);
            margin: 15px 0;
        }

        .btn-booking {
            background: var(--accent);
            color: var(--primary);
            padding: 12px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 800;
            transition: 0.3s;
            display: block;
        }

        .btn-booking:hover { background: var(--primary); color: white; }

        .contact-section {
            background: var(--primary);
            color: white;
            padding: 60px 5%;
            text-align: center;
        }

        footer { background: #111; color: white; padding: 20px; text-align: center; }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo">
            <i class="fas fa-graduation-cap"></i>
            أكاديمية المهارات الإدارية
        </a>
        <nav>
            <a href="#home">الرئيسية</a>
            <a href="#courses">الدورات</a>
            <a href="https://wa.me" target="_blank">تواصل معنا</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>انطلق نحو الاحتراف 2026</h1>
        <p>دورات تدريبية معتمدة لتطوير مهاراتك القيادية والتقنية</p>
        <a href="#courses" class="btn-booking" style="width: 200px; margin: 20px auto;">اكتشف الدورات</a>
    </section>

    <section class="services" id="courses">
        
        <!-- دورة PMP -->
        <div class="service-card">
            <div class="video-container">
                <iframe width="100%" height="100%" src="https://www.youtube.com" frameborder="0" allowfullscreen></iframe>
            </div>
            <i class="fas fa-project-diagram"></i>
            <h3>إدارة المشاريع الاحترافية (PMP)</h3>
            <ul class="course-features">
                <li><i class="fas fa-check-circle"></i> 35 ساعة تدريبية معتمدة</li>
                <li><i class="fas fa-check-circle"></i> التحضير للاختبار الدولي</li>
                <li><i class="fas fa-check-circle"></i> شرح منهجية Agile</li>
            </ul>
            <div class="price-tag">1500 ريال</div>
            <a href="https://wa.me?text=أرغب%20في%20التسجيل%20بدورة%20PMP" class="btn-booking">احجز عبر واتساب</a>
        </div>

        <!-- دورة القيادة -->
        <div class="service-card">
            <div class="video-container">
                <iframe width="100%" height="100%" src="https://www.youtube.com" frameborder="0" allowfullscreen></iframe>
            </div>
            <i class="fas fa-users"></i>
            <h3>القيادة الإبداعية والفعالة</h3>
            <ul class="course-features">
                <li><i class="fas fa-check-circle"></i> مهارات التأثير والتفاوض</li>
                <li><i class="fas fa-check-circle"></i> بناء فرق العمل الناجحة</li>
                <li><i class="fas fa-check-circle"></i> شهادة حضور معتمدة</li>
            </ul>
            <div class="price-tag">950 ريال</div>
            <a href="https://wa.me?text=أرغب%20في%20التسجيل%20بدورة%20القيادة" class="btn-booking">احجز عبر واتساب</a>
        </div>

        <!-- دورة التحول الرقمي -->
        <div class="service-card">
            <div class="video-container">
                <iframe width="100%" height="100%" src="https://www.youtube.com" frameborder="0" allowfullscreen></iframe>
            </div>
            <i class="fas fa-laptop-code"></i>
            <h3>التحول الرقمي و AI</h3>
            <ul class="course-features">
                <li><i class="fas fa-check-circle"></i> أساسيات الذكاء الاصطناعي</li>
                <li><i class="fas fa-check-circle"></i> تطبيقات عملية في العمل</li>
                <li><i class="fas fa-check-circle"></i> مواكبة رؤية 2030</li>
            </ul>
            <div class="price-tag">1200 ريال</div>
            <a href="https://wa.me?text=أرغب%20في%20التسجيل%20بدورة%20التحول%20الرقمي" class="btn-booking">احجز عبر واتساب</a>
        </div>

    </section>

    <section class="contact-section">
        <h2>هل لديك استفسار؟</h2>
        <p style="margin: 15px 0;">نحن متاحون لخدمتك على مدار الساعة</p>
        <p><i class="fab fa-whatsapp"></i> واتساب: 966533936881+</p>
        <p><i class="fas fa-envelope"></i> ايميل: awaad852@gmail.com</p>
    </section>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2026 | أكاديمية المهارات الإدارية</p>
    </footer>

</body>
</html>
