<DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>القوانين والشروط | شات الاقصى</title>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2563eb;
            --primary-dark: #1e40af;
            --secondary: #f97316;
            --success: #10b981;
            --text: #1f2937;
            --text-light: #6b7280;
            --border: #e5e7eb;
            --shadow: rgba(37, 99, 235, 0.1);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Tajawal', sans-serif;
            background: #f8fafc;
            color: var(--text);
            line-height: 1.6;
            user-select: none;
            -webkit-user-select: none;
        }

        .container { max-width: 1000px; margin: 0 auto; padding: 20px; }

        /* Hero Section */
        .hero-section {
            background: linear-gradient(135deg, var(--primary-dark) 0%, #1e3a8a 100%);
            color: white;
            padding: 60px 20px;
            border-radius: 30px;
            text-align: center;
            margin-bottom: 40px;
        }

        .card {
            background: white;
            border-radius: 24px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 10px 15px -3px var(--shadow);
            border: 1px solid var(--border);
        }

        .section-title {
            font-size: 1.8em;
            margin-bottom: 25px;
            padding-right: 15px;
            border-right: 5px solid var(--primary);
        }

        /* Accordion Style */
        .accordion-item {
            margin-bottom: 15px;
            border: 1px solid var(--border);
            border-radius: 12px;
            overflow: hidden;
        }

        .accordion-header {
            background: #f1f5f9;
            padding: 18px 25px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 700;
            transition: 0.3s;
        }

        .accordion-header:hover { background: #e2e8f0; }

        .accordion-content {
            display: none;
            padding: 25px;
            background: white;
            border-top: 1px solid var(--border);
        }

        .accordion-content ul {
            list-style: none;
            padding-right: 10px;
        }

        .accordion-content ul li {
            position: relative;
            padding-right: 25px;
            margin-bottom: 12px;
        }

        .accordion-content ul li::before {
            content: "•";
            color: var(--primary);
            font-weight: bold;
            position: absolute;
            right: 0;
            font-size: 1.2em;
        }

        /* Info & Warning Boxes */
        .warning-box { 
            background: #fff7ed; 
            border-right: 5px solid var(--secondary); 
            padding: 25px; 
            border-radius: 15px; 
            margin: 30px 0; 
        }

        .info-box { 
            background: #f0f9ff; 
            border-right: 5px solid var(--primary); 
            padding: 25px; 
            border-radius: 15px; 
        }

        h3 { margin-bottom: 10px; color: var(--primary-dark); }

        @media (max-width: 768px) {
            .hero-section { padding: 40px 15px; }
            .section-title { font-size: 1.5em; }
        }
    </style>
</head>
<body oncontextmenu="return false;">

<div class="container">
    <div class="hero-section">
        <h1>📜 القوانين والشروط</h1>
        <p>الالتزام بالقوانين يضمن تجربة أفضل للجميع - شكراً لتعاونك</p>
    </div>

    <div class="card">
        <h2 class="section-title">⚖️ القوانين العامة</h2>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>🔒 قوانين التسجيل والحسابات</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <ul>
                    <li>يُمنع التسجيل بأسماء مخالفة أو مسيئة للآداب العامة</li>
                    <li>العمر المسموح للدخول هو 18 سنة فأكثر</li>
                    <li>يُمنع استخدام الصور الإباحية أو غير اللائقة</li>
                    <li>يُسمح بعضوية واحدة فقط لكل مستخدم</li>
                    <li>عند اكتشاف تعدد العضويات سيتم حذف جميع الحسابات</li>
                    <li>تكرار المخالفات يؤدي إلى حظر دائم من الموقع</li>
                </ul>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>🤝 قوانين السلوك والتعامل</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <ul>
                    <li>يُمنع افتعال المشاكل أو المشاحنات مع الآخرين داخل الشات</li>
                    <li>يُمنع الدعوة أو العزيمة لأي موقع آخر أو الترويج لأي شات خارجي</li>
                    <li>يُمنع التعامل مع الشكاوى أو فتح نقاشات خلافية داخل الشات، ويُكتفى بإبلاغ الإدارة فقط</li>
                    <li>يُمنع استخدام الألفاظ المسيئة أو المخلة بالأدب بأي شكل من الأشكال</li>
                    <li>يجب الالتزام بالأدب والاحترام في الحديث مع الجميع دون استثناء</li>
                    <li>يُمنع استخدام خاصية التنبيه لإزعاج الآخرين أو استفزازهم</li>
                    <li>يُنصح باستخدام خاصية "التجاهل" لتفادي الإزعاج والمضايقات</li>
                    <li>يُرجى احترام خصوصية الآخرين وعدم التطفل على محادثاتهم الخاصة أو نقلها</li>
                </ul>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>🚷 المواضيع الممنوعة</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <ul>
                    <li>يُمنع التطرق إلى المواضيع الطائفية أو المذهبية</li>
                    <li>يُمنع نشر مواضيع سياسية أو دينية متطرفة</li>
                    <li>يُمنع تبادل المعلومات الشخصية أو الروابط الخارجية</li>
                    <li>يُمنع المحتوى الإباحي أو المخالف للشريعة</li>
                    <li>يُمنع الترويج لأي خدمات أو منتجات أخرى</li>
                    <li>يُمنع نشر الإشاعات أو الأخبار الكاذبة</li>
                </ul>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>🛡️ استخدام الصلاحيات</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <ul>
                    <li>يُمنع التلاعب بالصلاحيات أو استخدامها بشكل شخصي</li>
                    <li>صلاحية الطرد مسموحة فقط داخل الغرف الشخصية</li>
                    <li>يُمنع طلب البند أو الحظر عن أي شخص بناءً على معرفة سابقة</li>
                    <li>فصل سوبر عند كونك أدمن والاكتفاء بتقديم شكوى للإدارة</li>
                    <li>يُمنع كشف النك أو الأسماء لشخص آخر، حتى لو كان سوبر أو تعرفه مسبقاً</li>
                    <li>نظام اللايكات: 1500 لايك فقط لكل عضو جديد - يُمنع التلاعب</li>
                </ul>

                <div style="background: #f8fafc; padding: 25px; border-radius: 12px; margin-top: 25px; border: 2px solid var(--border);">
                    <h4 style="color: var(--primary-dark); margin-bottom: 15px; font-size: 1.15em;">📋 قوانين الحظر / الباند:</h4>
                    <p style="line-height: 1.9; margin-bottom: 15px;">يُمنع استخدام خاصية الباند / الحظر على الآخرين دون مبرر، ويُسمح بالحظر فقط عند ثبوت ارتكاب إحدى المخالفات التالية:</p>
                    <ul style="list-style: disc; padding-right: 20px; padding-left: 20px;">
                        <li style="padding: 8px 0;">الدعوة لموقع دردشة آخر "العزيمة"</li>
                        <li style="padding: 8px 0;">القذف أو السب أو الشتم الموجّه للآخرين</li>
                        <li style="padding: 8px 0;">نشر الصور الإباحية أو استخدام صور غير لائقة</li>
                        <li style="padding: 8px 0;">ابتزاز الزوار أو تهديدهم بالصور أو المحادثات</li>
                        <li style="padding: 8px 0;">نشر النفاق أو النميمة بين الزوار بقصد الإضرار</li>
                        <li style="padding: 8px 0;">سبّ الدين أو الذات الإلهية</li>
                        <li style="padding: 8px 0;">التحدث عن السياسة أو تخوين الحكومات العربية</li>
                        <li style="padding: 8px 0;">الدعاء على الحكام العرب</li>
                        <li style="padding: 8px 0;">التشدد أو التطرف الديني أو نشر مواد إرهابية</li>
                        <li style="padding: 8px 0;">النصب أو الاحتيال المالي أو التقني</li>
                    </ul>
                    <p style="margin-top: 15px; padding-top: 15px; border-top: 2px solid var(--border); font-weight: 600; color: var(--primary);">✓ ويجب تقديم دليل يثبت وقوع المخالفة المذكورة أعلاه عبر:</p>
                    <ul style="list-style: circle; padding-right: 20px; margin-top: 10px;">
                        <li>تصوير شاشة (سكرين شوت) للمخالفة</li>
                        <li>إحضار مقطع صوتي إذا كانت الحادثة داخل المايك</li>
                        <li>إحضار شهود من زوار الشات الموثوقين</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="warning-box">
            <h3>⚠️ تنبيه مهم جداً</h3>
            <p>أي مخالفة لهذه القوانين سيُطبق عليها <strong>نظام الإدارة بشكل فوري</strong>. قد تتضمن العقوبات: <strong>تحذير، إيقاف مؤقت، أو حظر دائم</strong> حسب جسامة المخالفة. نحن نلتزم بتطبيق القوانين بعدالة وشفافية للحفاظ على بيئة آمنة ومحترمة للجميع.</p>
        </div>

        <div class="info-box">
            <h3>📞 الإبلاغ عن المخالفات</h3>
            <p>يُرجى التواصل مع الإدارة عبر القنوات الرسمية في صفحة "اتصل بنا" فقط. <strong>لا تقم بمشاركة أي معلومات شخصية مع أي شخص يدعي أنه من الإدارة</strong> خارج القنوات الرسمية. سلامتك وأمانك أولويتنا.</p>
        </div>
    </div>
</div>

<script>
    function toggleAccordion(header) {
        const content = header.nextElementSibling;
        const icon = header.querySelector('.icon');
        
        if (content.style.display === "block") {
            content.style.display = "none";
            icon.textContent = "▼";
        } else {
            content.style.display = "block";
            icon.textContent = "▲";
        }
    }

    // حماية F12 وتعطيل الاختصارات
    document.onkeydown = function(e) {
        if(e.keyCode == 123) return false; 
        if(e.ctrlKey && e.shiftKey && e.keyCode == 'I'.charCodeAt(0)) return false;
        if(e.ctrlKey && e.keyCode == 'U'.charCodeAt(0)) return false;
    };
</script>

</body>
</html>
