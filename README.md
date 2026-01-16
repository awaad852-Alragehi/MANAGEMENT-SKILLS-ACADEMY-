<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Management Skills Academy | أكاديمية المهارات الإدارية</title>
    
    <!-- Fonts & Icons 2026 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <link href="https://fonts.googleapis.com" rel="stylesheet">
    
    <style>
        :root {
            --primary: #1a2a6c;
            --secondary: #b21f1f;
            --accent: #fdbb2d;
            --white: #ffffff;
            --text-dark: #2d3436;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Almarai', 'Poppins', sans-serif; background: #f4f7f6; color: var(--text-dark); line-height: 1.8; }

        header {
            background: var(--primary); padding: 20px 5%;
            display: flex; justify-content: space-between; align-items: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2); position: sticky; top: 0; z-index: 1000;
        }

        .logo-container { display: flex; align-items: center; gap: 15px; color: var(--accent); text-decoration: none; }
        .logo-icon { font-size: 2.5rem; }
        .logo-text h1 { font-size: 1.2rem; color: var(--white); line-height: 1.2; }
        .logo-text span { font-size: 0.8rem; color: var(--accent); display: block; }

        .hero {
            background: linear-gradient(rgba(26, 42, 108, 0.9), rgba(26, 42, 108, 0.9)), 
                        url('https://images.unsplash.com');
            background-size: cover; background-position: center;
            color: white; padding: 100px 5%; text-align: center;
        }

        .section-padding { padding: 80px 5%; }
        .about-box { background: white; border-radius: 20px; padding: 40px; box-shadow: 0 10px 30px rgba(0,0,0,0.05); margin-bottom: 50px; }
        .dual-lang { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; text-align: justify; }
        .lang-ar { direction: rtl; }
        .lang-en { direction: ltr; font-family: 'Poppins', sans-serif; border-left: 2px solid #eee; padding-left: 40px; }

        h2.section-title { text-align: center; margin-bottom: 40px; color: var(--primary); font-size: 2rem; position: relative; }
        h2.section-title::after { content: ''; width: 80px; height: 4px; background: var(--accent); position: absolute; bottom: -10px; left: 50%; transform: translateX(-50%); }

        .courses-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 30px; }
        .course-card { background: white; border-radius: 20px; overflow: hidden; box-shadow: 0 15px 35px rgba(0,0,0,0.1); border-top: 6px solid var(--accent); }
        
        .course-img { width: 100%; height: 230px; object-fit: cover; border-bottom: 1px solid #eee; }
        
        .video-wrapper { position: relative; padding-bottom: 56.25%; height: 0; background: #000; }
        .video-wrapper iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }

        .course-content { padding: 30px; }
        .price { font-size: 1.8rem; color: var(--secondary); font-weight: 800; margin: 20px 0; }
        
        .btn-wa {
            background: #25d366; color: white; padding: 15px; border-radius: 12px;
            text-decoration: none; display: block; text-align: center; font-weight: 700;
            transition: 0.3s; font-size: 1.1rem;
        }
        .btn-wa:hover { background: #128c7e; transform: scale(1.02); }

        .contact-footer { background: var(--primary); color: white; padding: 60px 5%; text-align: center; }
        
        @media (max-width: 768px) { .dual-lang { grid-template-columns: 1fr; } .lang-en { border-left: 0; border-top: 2px solid #eee; padding-left: 0; padding-top: 40px; } }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo-container">
            <i class="fas fa-graduation-cap logo-icon"></i>
            <div class="logo-text">
                <h1>أكاديمية المهارات الإدارية</h1>
                <span>MANAGEMENT SKILLS ACADEMY</span>
            </div>
        </a>
    </header>

    <section class="hero">
        <h1>Building Future Leaders 2026</h1>
        <h2>نصنع قادة المستقبل بمعايير عالمية</h2>
    </section>

    <section class="section-padding" id="about">
        <div class="about-box">
            <h2 class="section-title">من نحن | About Us</h2>
            <div class="dual-lang">
                <div class="lang-ar">
                    <h3>رؤيتنا الإستراتيجية</h3>
                    <p>تعد أكاديمية المهارات الإدارية صرحاً تدريبياً رائداً في الشرق الأوسط، تأسست لتقديم حلول تعليمية وتطويرية متكاملة. نحن متخصصون في تحويل المفاهيم الإدارية المعقدة إلى مهارات تطبيقية. نركز في عام 2026 على دمج الذكاء الاصطناعي في الإدارة، وتطوير القيادة الاستراتيجية، وإدارة المشاريع الضخمة وفقاً لرؤية المملكة 2030. نهدف إلى سد الفجوة بين المعرفة النظرية ومتطلبات سوق العمل العالمي من خلال مدربين معتمدين دولياً وبيئة تعليمية تفاعلية.</p>
                </div>
                <div class="lang-en">
                    <h3>Our Strategic Vision</h3>
                    <p>Management Skills Academy is a leading educational institution in the Middle East, established to provide integrated learning and development solutions. We specialize in transforming complex management concepts into practical skills. In 2026, we focus on integrating AI into management, strategic leadership development, and mega-project management aligned with Vision 2030. We aim to bridge the gap between theoretical knowledge and global market demands through internationally certified trainers.</p>
                </div>
            </div>
        </div>

        <h2 class="section-title">برامجنا التدريبية | Training Programs</h2>
        
        <div class="courses-grid">
            
            <!-- Course 1: PMP -->
            <div class="course-card">
                <div class="video-wrapper">
                    <iframe src="https://www.youtube.com" title="PMP" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="course-content">
                    <div class="dual-lang" style="grid-template-columns: 1fr; gap: 15px;">
                        <div class="lang-ar">
                            <h3>إدارة المشاريع الاحترافية (PMP)</h3>
                            <p>الدورة الأشهر عالمياً لاحتراف إدارة المشاريع وفق منهجية PMI الإصدار السابع. تشمل إدارة المخاطر، الجدولة الزمنية، والقيادة الرشيقة (Agile).</p>
                        </div>
                        <div class="lang-en" style="border:0; padding:0;">
                            <h3>Project Management Professional</h3>
                            <p>The world's most prestigious certification in project management according to PMI 7th edition. Covers risk management, scheduling, and Agile leadership.</p>
                        </div>
                    </div>
                    <div class="price">400 SAR</div>
                    <a href="https://wa.me" class="btn-wa"><i class="fab fa-whatsapp"></i> سجل الآن | Register Now</a>
                </div>
            </div>

            <!-- Course 2: Leadership -->
            <div class="course-card">
                <img src="https://images.unsplash.com" class="course-img" alt="Leadership">
                <div class="course-content">
                    <div class="dual-lang" style="grid-template-columns: 1fr; gap: 15px;">
                        <div class="lang-ar">
                            <h3>القيادة الإبداعية والفعالة</h3>
                            <p>تركز هذه الدورة على بناء مهارات القائد المؤثر، اتخاذ القرارات الاستراتيجية تحت الضغط، وبناء فرق العمل عالية الأداء في بيئة العمل الرقمية.</p>
                        </div>
                        <div class="lang-en" style="border:0; padding:0;">
                            <h3>Creative & Effective Leadership</h3>
                            <p>Focuses on building influential leader skills, strategic decision-making under pressure, and high-performance team building in digital environments.</p>
                        </div>
                    </div>
                    <div class="price">950 SAR</div>
                    <a href="https://wa.me" class="btn-wa"><i class="fab fa-whatsapp"></i> سجل الآن | Register Now</a>
                </div>
            </div>

            <!-- Course 3: Digital Transformation -->
            <div class="course-card">
                <img src="https://images.unsplash.com" class="course-img" alt="AI">
                <div class="course-content">
                    <div class="dual-lang" style="grid-template-columns: 1fr; gap: 15px;">
                        <div class="lang-ar">
                            <h3>التحول الرقمي والذكاء الاصطناعي</h3>
                            <p>تأهيل المدراء لقيادة التحول الرقمي في مؤسساتهم، واستخدام أدوات AI لرفع الإنتاجية وتحليل البيانات الضخمة لدعم القرار.</p>
                        </div>
                        <div class="lang-en" style="border:0; padding:0;">
                            <h3>Digital Transformation & AI</h3>
                            <p>Qualifying managers to lead digital transformation and use AI tools to increase productivity and analyze big data for decision support.</p>
                        </div>
                    </div>
                    <div class="price">1200 SAR</div>
                    <a href="https://wa.me" class="btn-wa"><i class="fab fa-whatsapp"></i> سجل الآن | Register Now</a>
                </div>
            </div>

        </div>
    </section>

    <footer class="contact-footer">
        <h2>تواصل معنا | Contact Us</h2>
        <div style="margin: 20px 0;">
            <p><i class="fab fa-whatsapp"></i> +966533936881</p>
            <p><i class="fas fa-envelope"></i> awaad852@gmail.com</p>
        </div>
        <p>&copy; 2026 Management Skills Academy. All rights reserved.</p>
    </footer>

</body>
</html>
