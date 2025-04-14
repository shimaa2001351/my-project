<!DOCTYPE html>s
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>السيرة الذاتية - شيماء</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --text-color: #333;
            --light-bg: #f8f9fa;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.8;
            margin: 0;
            padding: 0;
            color: var(--text-color);
            background-color: #f5f7fa;
        }
        .container {
            max-width: 850px;
            margin: 40px auto;
            padding: 40px;
            background: white;
            box-shadow: 0 5px 25px rgba(0,0,0,0.08);
            border-radius: 12px;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 3px solid var(--secondary-color);
            position: relative;
        }
        header::after {
            content: "";
            position: absolute;
            bottom: -3px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 3px;
            background: var(--accent-color);
        }
        h1 {
            color: var(--primary-color);
            margin-bottom: 10px;
            font-size: 2.2rem;
        }
        .job-title {
            color: #555;
            font-size: 1.2rem;
            margin-top: 0;
            font-weight: 500;
        }
        h2 {
            color: var(--secondary-color);
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 8px;
            margin-top: 30px;
            font-size: 1.5rem;
            position: relative;
        }
        h2::after {
            content: "";
            position: absolute;
            bottom: -2px;
            right: 0;
            width: 50px;
            height: 2px;
            background: var(--accent-color);
        }
        .contact-info {
            margin: 20px 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        .contact-info p {
            margin: 0;
            display: flex;
            align-items: center;
        }
        .contact-info i {
            margin-left: 8px;
            color: var(--secondary-color);
        }
        .section {
            margin-bottom: 30px;
        }
        ul {
            padding-right: 20px;
        }
        li {
            margin-bottom: 10px;
            position: relative;
            padding-right: 15px;
        }
        li::before {
            content: "•";
            color: var(--secondary-color);
            font-weight: bold;
            position: absolute;
            right: 0;
        }
        .date {
            color: #777;
            font-style: italic;
            font-size: 0.9rem;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }
        .skill {
            background: #e3f2fd;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
            color: #1565c0;
        }
        .courses {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 12px;
        }
        .course {
            background: var(--light-bg);
            padding: 12px;
            border-radius: 8px;
            border-left: 3px solid var(--secondary-color);
            transition: transform 0.3s;
        }
        .course:hover {
            transform: translateY(-3px);
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        .progress-container {
            width: 100%;
            background-color: #e0e0e0;
            border-radius: 5px;
            margin-top: 15px;
        }
        .progress-bar {
            height: 8px;
            border-radius: 5px;
            background-color: var(--secondary-color);
            width: 75%; //
        }
        @media print {
            body {
                background: none;
            }
            .container {
                box-shadow: none;
                padding: 20px;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>شيماء الدعمة</h1>
            <p class="job-title">طالبة بكالوريوس نظم معلومات</p>
            <div class="contact-info">
                <p><i class="fas fa-envelope"></i> aldamaashimaa@gmail.com</p>
                <p><i class="fas fa-phone"></i> 0599693566</p>
                <p><i class="fas fa-map-marker-alt"></i> فلسطين</p>
                <p><i class="fas fa-university"></i> جامعة الأقصى</p>
            </div>
        </header>

        <div class="section">
            <h2>الملف الشخصي</h2>
            <p>طالبة متحمسة في السنة الثالثة من تخصص نظم المعلومات بجامعة الأقصى، أمتلك أساسيات قوية في تحليل النظم وإدارة قواعد البيانات. أسعى لاكتساب خبرة عملية في مجال تكنولوجيا المعلومات من خلال التدريب العملي وتطوير مشاريع شخصية. أتميز بقدرة على التعلم السريع والعمل ضمن فريق.</p>
        </div>

        <div class="section">
            <h2>التعليم</h2>
            <ul>
                <li>
                    <strong>بكالوريوس نظم معلومات</strong> - جامعة الأقصى<br>
                                            <div class="progress-bar" style="width: 65%;"></div>
                    </div>
                    <small>إتمام 65% من الخطة الدراسية</small>
                </li>
            </ul>
        </div>

        <div class="section">
            <h2>المقررات المتميزة</h2>
            <div class="courses">
                <div class="course">
                    <strong>تحليل وتصميم النظم</strong>
                    <p>أسس تحليل متطلبات النظام وتصميم الحلول التقنية</p>
                </div>
                <div class="course">
                    <strong>قواعد البيانات</strong>
                    <p>تصميم وتنفيذ قواعد البيانات العلائقية باستخدام SQL</p>
                </div>
                <div class="course">
                    <strong>هندسة البرمجيات</strong>
                    <p>منهجيات تطوير الأنظمة ودورة حياة البرمجيات</p>
                </div>
                <div class="course">
                    <strong>برمجة الويب</strong>
                    <p>أساسيات تطوير تطبيقات الويب باستخدام HTML, CSS, JavaScript</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>المهارات التقنية</h2>
            <div class="skills">
                <span class="skill">تحليل النظم</span>
                <span class="skill">SQL</span>
                <span class="skill">Microsoft Office</span>
                <span class="skill">HTML/CSS</span>
                <span class="skill">إدارة المشاريع</span>
                <span class="skill">UML</span>
                <span class="skill">تطبيقات Google Workspace</span>
                <span class="skill">إدارة قواعد البيانات</span>
            </div>
        </div>

        <div class="section">
            <h2>المشاريع الأكاديمية</h2>
            <ul>
                <li>
                    <strong>نظام إدارة مكتبة</strong><br>
                    نموذج أولي لنظام إدارة مكتبة باستخدام مفاهيم تحليل النظم وقواعد البيانات
                </li>
                <li>
                    <strong>تصميم موقع ويب</strong><br>
                    تطبيق عملي لمبادئ برمجة الويب الأساسية
                </li>
            </ul>
        </div>

        <div class="section">
            <h2>اللغات</h2>
            <ul>
                <li>
                    <strong>العربية</strong> - اللغة الأم
                    <div class="progress-container">
                        <div class="progress-bar" style="width: 100%;"></div>
                    </div>
                </li>
                <li>
                    <strong>الإنجليزية</strong> - جيد (قراءة، كتابة، محادثة)
                    <div class="progress-container">
                        <div class="progress-bar" style="width: 70%;"></div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</body>
</html>