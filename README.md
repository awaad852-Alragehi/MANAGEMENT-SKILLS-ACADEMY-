<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أكاديمية المهارات الإدارية 2026 | Management Skills Academy</title>
    
    <!-- مكتبات الأيقونات والخطوط 2026 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <link href="https://fonts.googleapis.com" rel="stylesheet">
    
    <style>
        :root {
            --primary: #1a2a6c;
            --secondary: #b21f1f;
            --accent: #fdbb2d;
            --white: #ffffff;
            --bg-light: #f4f7f6;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Almarai', sans-serif; background: var(--bg-light); color: #333; line-height: 1.8; }

        header {
            background: var(--primary); padding: 20px 5%;
            display: flex; justify-content: space-between; align-items: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3); position: sticky; top: 0; z-index: 1000;
        }
        .logo-container { display: flex; align-items: center; gap: 15px; color: var(--accent); text-decoration: none; }
        .logo-text h1 { font-size: 1.2rem; color: var(--white); }

        .hero {
            background: linear-gradient(rgba(26, 42, 108, 0.85), rgba(26, 42, 108, 0.85)), 
                        url('https://images.pexels.com');
            background-size: cover; background-position: center;
            color: white; padding: 80px 5%; text-align: center;
        }

        .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 30px; padding: 50px 5%; }
        .course-card { background: white; border-radius: 20px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.1); transition: 0.4s; border-bottom: 6px solid var(--accent); }
        .course-card:hover { transform: translateY(-10px); }

        /* حاوية الغلاف */
        .img-container { width: 100%; height: 250px; background: #000; overflow: hidden; position: relative; }
        .img-container img { width: 100%; height: 100%; object-fit: cover; transition: 0.5s; opacity: 0.9; }
        .course-card:hover .img-container img { transform: scale(1.1); opacity: 1; }

        .card-body { padding: 30px; text-align: right; }
        .card-body h3 { color: var(--primary); font-size: 1.4rem; margin-bottom: 15px; border-right: 4px solid var(--accent); padding-right: 10px; }
        
        .description-box { font-size: 0.9rem; color: #555; margin-bottom: 20px; }
        .lang-tag { display: inline-block; padding: 2px 8px; background: #eee; border-radius: 4px; font-size: 0.7rem; font-weight: bold; margin-bottom: 5px; }

        .price { font-size: 1.8rem; color: var(--secondary); font-weight: 800; margin: 15px 0; }

        .btn-booking {
            background: #25d366; color: white; padding: 15px; border-radius: 50px;
            text-decoration: none; display: block; text-align: center; font-weight: 800; transition: 0.3s;
        }
        .btn-booking:hover { background: #128c7e; box-shadow: 0 5px 15px rgba(37, 211, 102, 0.4); }

        footer { background: var(--primary); color: white; padding: 40px 5%; text-align: center; }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo-container">
            <i class="fas fa-graduation-cap fa-2x"></i>
            <div class="logo-text"><h1>أكاديمية المهارات الإدارية</h1></div>
        </a>
    </header>

    <section class="hero">
        <h1>إدارة وتسويق المستقبل 2026</h1>
        <p>برامج تخصصية للأطباء، الصيادلة، والمدراء الطموحين</p>
    </section>

    <section class="services">
        
        <!-- دورة التسويق الصيدلاني (الجديدة) -->
        <div class="course-card">
            <div class="img-container">
                <!-- غلاف يعبر عن الطب والتسويق -->
                <img src="https://images.pexels.com" alt="Pharmaceutical Marketing">
            </div>
            <div class="card-body">
                <h3>التسويق الصيدلاني | PHARMA MARKETING</h3>
                
                <div class="description-box">
                    <span class="lang-tag">عربي</span>
                    <p>احتراف استراتيجيات الترويج الدوائي، بناء العلاقات مع القطاعات الصحية، ودمج الذكاء الاصطناعي في تحليل بيانات المرضى والأطباء لرفع المبيعات الطبية بأسلوب أخلاقي.</p>
                </div>
                
                <div class="description-box">
                    <span class="lang-tag">ENGLISH</span>
                    <p style="direction: ltr; text-align: left;">Master pharmaceutical promotion strategies, healthcare relationship building, and AI integration for data-driven medical sales and ethical marketing outcomes.</p>
                </div>

                <div class="price">1500 ريال</div>
                <a href="https://wa.me" class="btn-booking">سجل الآن | Register Now</a>
            </div>
        </div>

        <!-- دورة PMP -->
        <div class="course-card">
            <div class="img-container">
               <iframe style="width: 100%; height: 100%;" src="https://www.youtube-nocookie.com" frameborder="0" allowfullscreen></iframe>
            </div>
            <div class="card-body">
                <h3>إدارة المشاريع الاحترافية (PMP)</h3>
                <div class="description-box">
                    <p>تأهيل كامل لاجتياز اختبار PMP الإصدار السابع. يشمل إدارة المشاريع الطبية والإنشائية والتقنية بفعالية.</p>
                </div>
                <div class="price">400 ريال</div>
                <a href="https://wa.me" class="btn-booking">سجل الآن | Register Now</a>
            </div>
        </div>

        <!-- دورة القيادة -->
        <div class="course-card">
            <div class="img-container">
                <img src="https://images.pexels.com" alt="Leadership">
            </div>
            <div class="card-body">
                <h3>القيادة الإبداعية والفعالة</h3>
                <div class="description-box">
                    <p>بناء المهارات القيادية، فن التفاوض، وإدارة فرق العمل عالية الأداء في البيئات الطبية والإدارية.</p>
                </div>
                <div class="price">950 ريال</div>
                <a href="https://wa.me" class="btn-booking">سجل الآن | Register Now</a>
            </div>
        </div>

    </section>

    <footer>
        <p>تواصل معنا: +966533936881</p>
        <p>جميع الحقوق محفوظة لأكاديمية المهارات الإدارية &copy; 2026</p>
    </footer>

</body>
</html>
