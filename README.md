<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>CMD Guide DZ</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>CMD Guide DZ</h1>
<p>تعلم كل أوامر Windows CMD بسهولة</p>

<input type="text" id="search" placeholder="ابحث عن أمر مثل ipconfig...">
</header>

<section class="container">

<div class="card">
<h2>ipconfig</h2>
<p>عرض إعدادات الشبكة</p>
<code>ipconfig /all</code>
</div>

<div class="card">
<h2>ping</h2>
<p>اختبار الاتصال بالإنترنت</p>
<code>ping google.com</code>
</div>

<div class="card">
<h2>cls</h2>
<p>مسح الشاشة</p>
<code>cls</code>
</div>

<div class="card">
<h2>dir</h2>
<p>عرض الملفات داخل المجلد</p>
<code>dir</code>
</div>

</section>

<script src="script.js"></script>
</body>
</html># CMD-GUID
<h2>🌐 أوامر الشبكة</h2>

<div class="card">
<h3>ipconfig</h3>
<p>عرض معلومات الشبكة</p>
<code>ipconfig /all</code>
</div>

<div class="card">
<h3>ping</h3>
<p>اختبار الاتصال بالإنترنت</p>
<code>ping google.com</code>
</div>

<div class="card">
<h3>tracert</h3>
<p>تتبع مسار الاتصال</p>
<code>tracert google.com</code>
</div>

<div class="card">
<h3>netstat</h3>
<p>عرض الاتصالات النشطة</p>
<code>netstat -an</code>
</div>

<!-- أوامر الملفات -->
<h2>📁 أوامر الملفات</h2>

<div class="card">
<h3>dir</h3>
<p>عرض الملفات</p>
<code>dir</code>
</div>

<div class="card">
<h3>cd</h3>
<p>الدخول لمجلد</p>
<code>cd Desktop</code>
</div>

<div class="card">
<h3>mkdir</h3>
<p>إنشاء مجلد</p>
<code>mkdir test</code>
</div>

<div class="card">
<h3>del</h3>
<p>حذف ملف</p>
<code>del file.txt</code>
</div>

<!-- أوامر النظام -->
<h2>⚙️ أوامر النظام</h2>

<div class="card">
<h3>cls</h3>
<p>مسح الشاشة</p>
<code>cls</code>
</div>

<div class="card">
<h3>shutdown</h3>
<p>إيقاف أو إعادة تشغيل الجهاز</p>
<code>shutdown /s /t 0</code>
</div>

<div class="card">
<h3>tasklist</h3>
<p>عرض البرامج المفتوحة</p>
<code>tasklist</code>
</div>

<div class="card">
<h3>taskkill</h3>
<p>إغلاق برنامج بالقوة</p>
<code>taskkill /im notepad.exe /f</code>
</div>

<!-- أوامر متقدمة -->
<h2>🔥 أوامر متقدمة</h2>

<div class="card">
<h3>sfc</h3>
<p>فحص وإصلاح النظام</p>
<code>sfc /scannow</code>
</div>

<div class="card">
<h3>chkdsk</h3>
<p>فحص القرص الصلب</p>
<code>chkdsk C:</code>
</div>

<div class="card">
<h3>systeminfo</h3>
<p>معلومات الجهاز</p>
<code>systeminfo</code>
</div>

<div class="card">
<h3>assoc</h3>
<p>عرض ربط الملفات</p>
<code>assoc</code>
</div>

</section>

<script src="script.js"></script>
</body>
</html>
<section class="container">

<h2>🌐 أوامر الشبكة (Network)</h2>

<div class="card"><h3>ipconfig</h3><p>عرض إعدادات الشبكة</p><code>ipconfig /all</code></div>
<div class="card"><h3>ping</h3><p>اختبار الاتصال</p><code>ping google.com</code></div>
<div class="card"><h3>tracert</h3><p>تتبع المسار</p><code>tracert google.com</code></div>
<div class="card"><h3>netstat</h3><p>الاتصالات النشطة</p><code>netstat -an</code></div>
<div class="card"><h3>nslookup</h3><p>بحث DNS</p><code>nslookup google.com</code></div>
<div class="card"><h3>arp</h3><p>عرض جدول الشبكة</p><code>arp -a</code></div>
<div class="card"><h3>route</h3><p>عرض مسارات الشبكة</p><code>route print</code></div>
<div class="card"><h3>hostname</h3><p>اسم الجهاز</p><code>hostname</code></div>

<h2>📁 أوامر الملفات</h2>

<div class="card"><h3>dir</h3><p>عرض الملفات</p><code>dir</code></div>
<div class="card"><h3>cd</h3><p>الدخول للمجلد</p><code>cd Desktop</code></div>
<div class="card"><h3>mkdir</h3><p>إنشاء مجلد</p><code>mkdir test</code></div>
<div class="card"><h3>rmdir</h3><p>حذف مجلد</p><code>rmdir test</code></div>
<div class="card"><h3>del</h3><p>حذف ملف</p><code>del file.txt</code></div>
<div class="card"><h3>copy</h3><p>نسخ ملفات</p><code>copy a.txt b.txt</code></div>
<div class="card"><h3>move</h3><p>نقل الملفات</p><code>move file.txt folder</code></div>
<div class="card"><h3>ren</h3><p>تغيير اسم ملف</p><code>ren file.txt new.txt</code></div>
<div class="card"><h3>type</h3><p>عرض محتوى ملف</p><code>type file.txt</code></div>

<h2>⚙️ أوامر النظام</h2>

<div class="card"><h3>cls</h3><p>مسح الشاشة</p><code>cls</code></div>
<div class="card"><h3>systeminfo</h3><p>معلومات النظام</p><code>systeminfo</code></div>
<div class="card"><h3>tasklist</h3><p>البرامج المفتوحة</p><code>tasklist</code></div>
<div class="card"><h3>taskkill</h3><p>إغلاق برنامج</p><code>taskkill /f /im chrome.exe</code></div>
<div class="card"><h3>shutdown</h3><p>إيقاف الجهاز</p><code>shutdown /s /t 0</code></div>
<div class="card"><h3>restart</h3><p>إعادة تشغيل</p><code>shutdown /r /t 0</code></div>
<div class="card"><h3>ver</h3><p>إصدار النظام</p><code>ver</code></div>
<div class="card"><h3>whoami</h3><p>اسم المستخدم</p><code>whoami</code></div>

<h2>🔧 أوامر النظام المتقدمة</h2>

<div class="card"><h3>sfc</h3><p>إصلاح النظام</p><code>sfc /scannow</code></div>
<div class="card"><h3>chkdsk</h3><p>فحص القرص</p><code>chkdsk C:</code></div>
<div class="card"><h3>diskpart</h3><p>إدارة الأقراص</p><code>diskpart</code></div>
<div class="card"><h3>format</h3><p>فرمتة قرص</p><code>format C:</code></div>
<div class="card"><h3>bootrec</h3><p>إصلاح الإقلاع</p><code>bootrec /fixmbr</code></div>
<div class="card"><h3>bcdedit</h3><p>إعدادات الإقلاع</p><code>bcdedit</code></div>
<div class="card"><h3>driverquery</h3><p>عرض التعريفات</p><code>driverquery</code></div>

<h2>📊 أوامر إضافية (Power CMD)</h2>

<div class="card"><h3>assoc</h3><p>ربط الملفات</p><code>assoc</code></div>
<div class="card"><h3>fc</h3><p>مقارنة ملفات</p><code>fc file1 file2</code></div>
<div class="card"><h3>find</h3><p>البحث داخل ملف</p><code>find "hello" file.txt</code></div>
<div class="card"><h3>echo</h3><p>طباعة نص</p><code>echo Hello</code></div>
<div class="card"><h3>set</h3><p>عرض المتغيرات</p><code>set</code></div>
<div class="card"><h3>pause</h3><p>إيقاف مؤقت</p><code>pause</code></div>

</section>
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CMD Guide DZ</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header class="topbar">
    <div class="logo">
        <h1>CMD Guide DZ</h1>
        <p>كل أوامر CMD في مكان واحد</p>
    </div>

    <input type="text" placeholder="ابحث عن أمر مثل ipconfig">
</header>

<div class="container">

<aside class="sidebar">
    <h2>التصنيفات</h2>

    <button>🌐 أوامر الشبكة</button>
    <button>📁 أوامر الملفات</button>
    <button>⚙️ أوامر النظام</button>
    <button>💾 إدارة الأقراص</button>
    <button>🔒 أوامر الحماية</button>
</aside>

<main class="content">

<h2>جميع أوامر CMD</h2>

<div class="cards">

<div class="card">
<h3>ipconfig</h3>
<p>عرض إعدادات الشبكة</p>
<code>ipconfig /all</code>
<button>نسخ</button>
</div>

<div class="card">
<h3>ping</h3>
<p>اختبار الاتصال بالإنترنت</p>
<code>ping google.com</code>
<button>نسخ</button>
</div>

<div class="card">
<h3>tracert</h3>
<p>تتبع الاتصال</p>
<code>tracert google.com</code>
<button>نسخ</button>
</div>

<div class="card">
<h3>dir</h3>
<p>عرض الملفات</p>
<code>dir</code>
<button>نسخ</button>
</div>

<div class="card">
<h3>tasklist</h3>
<p>عرض البرامج المفتوحة</p>
<code>tasklist</code>
<button>نسخ</button>
</div>

<div class="card">
<h3>sfc</h3>
<p>إصلاح ملفات النظام</p>
<code>sfc /scannow</code>
<button>نسخ</button>
</div>

</div>

</main>
</div>

</body>
</html>
body{
margin:0;
font-family:Arial;
background:#0b1220;
color:white;
direction:rtl;
}

.topbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px;
background:#111827;
border-bottom:1px solid #222;
}

.logo h1{
margin:0;
font-size:30px;
}

.logo p{
margin:5px 0;
color:#aaa;
}

.topbar input{
width:350px;
padding:12px;
border:none;
border-radius:10px;
background:#1f2937;
color:white;
}

.container{
display:flex;
}

.sidebar{
width:250px;
background:#111827;
height:100vh;
padding:20px;
}

.sidebar h2{
margin-bottom:20px;
}

.sidebar button{
width:100%;
padding:15px;
margin-bottom:10px;
border:none;
border-radius:10px;
background:#1e293b;
color:white;
cursor:pointer;
font-size:16px;
}

.sidebar button:hover{
background:#2563eb;
}

.content{
flex:1;
padding:25px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fill,minmax(250px,1fr));
gap:20px;
}

.card{
background:#111827;
padding:20px;
border-radius:15px;
box-shadow:0 0 10px rgba(0,0,0,0.4);
}

.card h3{
margin-top:0;
color:#38bdf8;
}

.card p{
color:#bbb;
}

code{
display:block;
background:black;
padding:10px;
border-radius:10px;
margin:10px 0;
color:#00ff88;
}

.card button{
width:100%;
padding:10px;
border:none;
border-radius:10px;
background:#2563eb;
color:white;
cursor:pointer;
font-size:16px;
}

.card button:hover{
background:#1d4ed8;
}
