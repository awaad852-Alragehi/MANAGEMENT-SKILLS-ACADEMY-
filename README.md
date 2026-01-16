<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أكاديمية المهارات الإدارية | 2026</title>
    
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

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Almarai', sans-serif; }
        body { background-color: var(--bg-light); color: #333; line-height: 1.6; }

        header {
            background: var(--primary); padding: 15px 5%;
            display: flex; justify-content: space-between; align-items: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1); position: sticky; top: 0; z-index: 1000;
        }

        .logo { color: var(--accent); font-size: 1.2rem; font-weight: 800; text-decoration: none; display: flex; align-items: center; gap: 10px; }
        nav a { color: var(--white); text-decoration: none; margin-right: 20px; font-weight: 700; }

        .hero {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            background-size: 400% 400%; animation: gradientBG 15s ease infinite;
            color: white; padding: 100px 5%; text-align: center;
        }

        @keyframes gradientBG { 0% { background-position: 0% 50%; } 50% { background-position: 100% 50%; } 100% { background-position: 0% 50%; } }

        /* قسم وصف الأكاديمية */
        .about-section { padding: 60px 10%; text-align: center; background: white; }
        .about-section h2 { color: var(--primary); margin-bottom: 20px; font-size: 2rem; }
        .about-section p { font-size: 1.1rem; color: #555; max-width: 800px; margin: 0 auto; }

        .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; padding: 50px 5%; }

        .service-card {
            background: var(--white); border-radius: 20px; overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1); transition: 0.3s;
            border-bottom: 5px solid var(--accent);
        }
        .service-card:hover { transform: translateY(-10px); }

        /* تنسيق صور الدورات */
        .course-img { width: 100%; height: 200px; object-fit: cover; }

        .card-content { padding: 20px; text-align: right; }
        .card-content h3 { color: var(--primary); margin-bottom: 10px; }
        .card-content .description { font-size: 0.9rem; color: #666; margin-bottom: 15px; height: 60px; overflow: hidden; }

        .video-container { border-radius: 10px; overflow: hidden; margin: 15px 0; position: relative; padding-bottom: 56.25%; height: 0; }
        .video-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }

        .course-features { list-style: none; margin-bottom: 15px; }
        .course-features li { font-size: 0.85rem; margin-bottom: 5px; display: flex; align-items: center; }
        .course-features li i { color: #27ae60; margin-left: 8px; }

        .price-tag { font-size: 1.4rem; font-weight: 800; color: var(--secondary); margin-bottom: 15px; }
        .btn-booking {
            background: var(--accent); color: var(--primary); padding: 12px; border-radius: 50px;
            text-decoration: none; font-weight: 800; display: block; text-align: center; transition: 0.3s;
        }
        .btn-booking:hover { background: var(--primary); color: white; }

        .contact-section { background: var(--primary); color: white; padding: 60px 5%; text-align: center; }
        footer { background: #111; color: white; padding: 20px; text-align: center; }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo"><i class="fas fa-graduation-cap"></i> أكاديمية المهارات الإدارية</a>
        <nav>
            <a href="#about">عن الأكاديمية</a>
            <a href="#courses">الدورات</a>
            <a href="https://wa.me" target="_blank">اتصل بنا</a>
        </nav>
    </header>

    <section class="hero">
        <h1>منصة صناع القادة لعام 2026</h1>
        <p>نؤهلك لاحتراف الإدارة والقيادة بأحدث المعايير الدولية</p>
    </section>

    <!-- قسم وصف نشاط الأكاديمية -->
    <section class="about-section" id="about">
        <h2>عن الأكاديمية</h2>
        <p>
            أكاديمية المهارات الإدارية هي مؤسسة تدريبية رائدة تهدف إلى تمكين الكوادر العربية بالأدوات الإدارية الحديثة. نحن نركز على تقديم محتوى تعليمي تطبيقي يجمع بين المنهجيات الأكاديمية واحتياجات سوق العمل في 2026، مع التركيز على التقنيات الناشئة والذكاء الاصطناعي في الإدارة.
        </p>
    </section>

    <section class="services" id="courses">
        
        <!-- دورة PMP -->
        <div class="service-card">
            <img src="https://images.unsplash.com" alt="PMP" class="course-img">
            <div class="card-content">
                <h3>إدارة المشاريع الاحترافية (PMP)</h3>
                <p class="description">الدورة الأقوى عالمياً لإدارة المشاريع بكفاءة، مصممة لاجتياز اختبار 2026 بنجاح.</p>
                <div class="video-container">
                    <iframe src="https://www.youtube.com" frameborder="0" allowfullscreen></iframe>
                </div>
                <ul class="course-features">
                    <li><i class="fas fa-check-circle"></i> 35 ساعة تدريبية معتمدة</li>
                    <li><i class="fas fa-check-circle"></i> شرح منهجية Agile و Hybrid</li>
                </ul>
                <div class="price-tag">400 ريال</div>
                <a href="https://wa.me?text=أرغب%20في%20دورة%20PMP" class="btn-booking">سجل الآن</a>
            </div>
        </div>

        <!-- دورة القيادة -->
        <div class="service-card">
            <img src="https://images.unsplash.com" alt="Leadership" class="course-img">
            <div class="card-content">
                <h3>القيادة الإبداعية والفعالة</h3>
                <p class="description">تعلم كيف تقود فريقك برؤية ملهمة في عصر التحول الرقمي والعمل عن بعد.</p>
                <ul class="course-features">
                    <li><i class="fas fa-check-circle"></i> مهارات الذكاء العاطفي للقادة</li>
                    <li><i class="fas fa-check-circle"></i> فن اتخاذ القرار الاستراتيجي</li>
                </ul>
                <div class="price-tag">950 ريال</div>
                <a href="https://wa.me?text=أرغب%20في%20دورة%20القيادة" class="btn-booking">سجل الآن</a>
            </div>
        </div>

        <!-- دورة التحول الرقمي -->
        <div class="service-card">
            <img src="https://images.unsplash.com" alt="AI and Digital" class="course-img">
            <div class="card-content">
                <h3>التحول الرقمي و AI 2026</h3>
                <p class="description">استعد للمستقبل وتعلم كيف تدمج الذكاء الاصطناعي في عملياتك الإدارية اليومية.</p>
                <ul class="course-features">
                    <li><i class="fas fa-check-circle"></i> تطبيقات AI لزيادة الإنتاجية</li>
                    <li><i class="fas fa-check-circle"></i> تحليل البيانات الضخمة للمدراء</li>
                </ul>
                <div class="price-tag">1200 ريال</div>
                <a href="https://wa.me?text=أرغب%20في%20دورة%20التحول%20الرقمي" class="btn-booking">سجل الآن</a>
            </div>
        </div>

    </section>

    <section class="contact-section">
        <h2>جاهز لتبدأ رحلتك؟</h2>
        <p>تواصل معنا للحصول على استشارة تدريبية مجانية</p>
        <div style="margin-top: 20px;">
            <p><i class="fab fa-whatsapp"></i> واتساب: 966533936881+</p>
            <p><i class="fas fa-envelope"></i> ايميل: awaad852@gmail.com</p>
        </div>
    </section>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2026 | أكاديمية المهارات الإدارية</p>
    </footer>

</body>
</html>
