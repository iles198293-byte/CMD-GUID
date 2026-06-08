



<html lang="ar">
<head>
<meta charset="UTF-8">
<title>CMD Guide windows</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>CMD Guide for windows</h1>
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
<script>

function copyCode(button){

let code =
button.parentElement.querySelector("code").textContent;

navigator.clipboard.writeText(code)
.then(() => {

button.innerHTML = "✅ تم النسخ";

setTimeout(function(){
button.innerHTML = "نسخ";
},1500);

});

}

</script>
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



<script src="script.js"></script>


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

<html lang="ar">
<head>
<meta charset="UTF-8">
<title>CMD Guide windows</title>

<style>

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
}

.sidebar{
width:250px;
background:#111827;
padding:20px;
height:100vh;
}

.sidebar button{
width:100%;
padding:12px;
margin-bottom:10px;
border:none;
border-radius:10px;
background:#1e293b;
color:white;
cursor:pointer;
}

.content{
padding:20px;
}

.card{
background:#111827;
padding:20px;
border-radius:10px;
margin:10px;
}

</style>

</head>

<body>

<header class="topbar">
<h1>CMD Guide DZ</h1>
<input type="text" placeholder="ابحث عن أمر CMD">
</header>

<div style="display:flex;">

<div class="sidebar">
<h2>التصنيفات</h2>

<button>الشبكة</button>
<button>الملفات</button>
<button>النظام</button>

</div>

<div class="content">

<div class="card">
<h2>ipconfig</h2>
<p>عرض معلومات الشبكة</p>
</div>

<div class="card">
<h2>ping</h2>
<p>اختبار الاتصال</p>
</div>

</div>

</div>

</body>
</html>    

<html lang="ar">
<head>
<meta charset="UTF-8">
<title>CMD Guide DZ</title>

<style>
body{
margin:0;
font-family:Arial;
background:#0b1220;
color:white;
direction:rtl;
}

header{
background:#111827;
padding:20px;
text-align:center;
}

h1{
color:#38bdf8;
}

.search{
width:60%;
padding:12px;
border:none;
border-radius:10px;
background:#1e293b;
color:white;
}

.main{
display:flex;
}

.menu{
width:220px;
background:#111827;
padding:20px;
height:100vh;
}

.menu button{
width:100%;
padding:12px;
margin-top:10px;
border:none;
border-radius:10px;
background:#1e293b;
color:white;
cursor:pointer;
}

.cards{
display:flex;
gap:20px;
flex-wrap:wrap;
padding:20px;
}

.card{
background:#111827;
padding:20px;
width:220px;
border-radius:15px;
}

code{
display:block;
background:black;
padding:10px;
border-radius:10px;
margin-top:10px;
color:#00ff88;
}
</style>

</head>

<body>

<header>
<h1>CMD Guide DZ</h1>
<input class="search" type="text" placeholder="ابحث عن أمر CMD">
</header>

<div class="main">

<div class="menu">
<button>الشبكة</button>
<button>الملفات</button>
<button>النظام</button>
</div>

<div class="cards">

<div class="card">
<h2>ipconfig</h2>
<p>عرض الشبكة</p>
<code>ipconfig /all</code>
</div>

<div class="card">
<h2>ping</h2>
<p>اختبار الإنترنت</p>
<code>ping google.com</code>
</div>

</div>

</div>

</body>
</html>
<style>

body{
margin:0;
font-family:Arial;
background:#0b1220;
color:white;
direction:rtl;
overflow-x:hidden;
animation:fadeBody 1s ease;
}

@keyframes fadeBody{
from{
opacity:0;
}
to{
opacity:1;
}
}

header{
background:#111827;
padding:20px;
text-align:center;
animation:slideDown 1s ease;
}

@keyframes slideDown{
from{
transform:translateY(-50px);
opacity:0;
}
to{
transform:translateY(0);
opacity:1;
}
}

h1{
color:#38bdf8;
transition:0.3s;
}

h1:hover{
transform:scale(1.05);
}

.search{
width:60%;
padding:12px;
border:none;
border-radius:10px;
background:#1e293b;
color:white;
transition:0.3s;
}

.search:focus{
outline:none;
transform:scale(1.03);
box-shadow:0 0 15px #2563eb;
}

.main{
display:flex;
}

.menu{
width:220px;
background:#111827;
padding:20px;
height:100vh;
animation:slideLeft 1s ease;
}

@keyframes slideLeft{
from{
transform:translateX(100px);
opacity:0;
}
to{
transform:translateX(0);
opacity:1;
}
}

.menu button{
width:100%;
padding:12px;
margin-top:10px;
border:none;
border-radius:10px;
background:#1e293b;
color:white;
cursor:pointer;
transition:0.3s;
}

.menu button:hover{
background:#2563eb;
transform:scale(1.05);
box-shadow:0 0 15px #2563eb;
}

.cards{
display:flex;
gap:20px;
flex-wrap:wrap;
padding:20px;
}

.card{
background:#111827;
padding:20px;
width:220px;
border-radius:15px;
transition:0.4s;
animation:fadeUp 1s ease;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #2563eb;
}

@keyframes fadeUp{
from{
transform:translateY(40px);
opacity:0;
}
to{
transform:translateY(0);
opacity:1;
}
}

code{
display:block;
background:black;
padding:10px;
border-radius:10px;
margin-top:10px;
color:#00ff88;
}

</style>
<script>

let buttons = document.querySelectorAll(".btn");

buttons.forEach(button => {

button.addEventListener("click", function(){

let code = this.parentElement.querySelector("code").innerText;

navigator.clipboard.writeText(code);

this.innerText = "تم النسخ ✅";

setTimeout(() => {
this.innerText = "نسخ";
}, 1500);

});

});

</script>
<div class="card">
<h2>gpupdate</h2>
<p>تحديث إعدادات النظام</p>
<code>gpupdate /force</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>driverquery</h2>
<p>عرض تعريفات الجهاز</p>
<code>driverquery</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>getmac</h2>
<p>عرض عنوان MAC</p>
<code>getmac</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>nslookup</h2>
<p>فحص DNS</p>
<code>nslookup google.com</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>arp</h2>
<p>عرض جدول الشبكة</p>
<code>arp -a</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>route</h2>
<p>عرض مسارات الشبكة</p>
<code>route print</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>powercfg</h2>
<p>إعدادات الطاقة</p>
<code>powercfg /batteryreport</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>cipher</h2>
<p>تشفير الملفات</p>
<code>cipher</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>fc</h2>
<p>مقارنة ملفين</p>
<code>fc file1.txt file2.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>find</h2>
<p>البحث داخل ملف</p>
<code>find "hello" file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>findstr</h2>
<p>بحث متقدم داخل الملفات</p>
<code>findstr hello test.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>attrib</h2>
<p>إخفاء أو إظهار الملفات</p>
<code>attrib +h file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net user</h2>
<p>عرض المستخدمين</p>
<code>net user</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net localgroup</h2>
<p>عرض المجموعات</p>
<code>net localgroup</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>netsh</h2>
<p>إعدادات الشبكة</p>
<code>netsh wlan show profiles</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wmic</h2>
<p>معلومات الهاردوير</p>
<code>wmic cpu get name</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>cleanmgr</h2>
<p>تنظيف القرص</p>
<code>cleanmgr</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>control</h2>
<p>فتح لوحة التحكم</p>
<code>control</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>msconfig</h2>
<p>إعدادات الإقلاع</p>
<code>msconfig</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>regedit</h2>
<p>فتح Registry</p>
<code>regedit</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>services.msc</h2>
<p>الخدمات</p>
<code>services.msc</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>dxdiag</h2>
<p>معلومات DirectX</p>
<code>dxdiag</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>perfmon</h2>
<p>مراقبة الأداء</p>
<code>perfmon</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>osk</h2>
<p>لوحة مفاتيح الشاشة</p>
<code>osk</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>mrt</h2>
<p>أداة إزالة الفيروسات</p>
<code>mrt</code>
<button class="btn">نسخ</button>
</div>
<div class="card">
<h2>path</h2>
<p>عرض مسارات النظام</p>
<code>path</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>set</h2>
<p>عرض متغيرات النظام</p>
<code>set</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>time</h2>
<p>عرض أو تغيير الوقت</p>
<code>time</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>date</h2>
<p>عرض التاريخ</p>
<code>date</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>vol</h2>
<p>عرض اسم القرص</p>
<code>vol</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>label</h2>
<p>تغيير اسم القرص</p>
<code>label C:</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>tree</h2>
<p>عرض شجرة الملفات</p>
<code>tree</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>xcopy</h2>
<p>نسخ ملفات كثيرة</p>
<code>xcopy folder1 folder2 /E</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>robocopy</h2>
<p>نسخ احترافي للملفات</p>
<code>robocopy C:\A C:\B</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>clip</h2>
<p>نسخ النص للحافظة</p>
<code>dir | clip</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>compact</h2>
<p>ضغط الملفات</p>
<code>compact /c file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>expand</h2>
<p>فك الملفات المضغوطة</p>
<code>expand file.cab</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>replace</h2>
<p>استبدال ملفات</p>
<code>replace file.txt folder</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>sort</h2>
<p>ترتيب النصوص</p>
<code>sort file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>more</h2>
<p>عرض النص صفحة صفحة</p>
<code>more file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>subst</h2>
<p>إنشاء قرص وهمي</p>
<code>subst X: C:\Folder</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>takeown</h2>
<p>أخذ صلاحية ملف</p>
<code>takeown /f file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>cacls</h2>
<p>صلاحيات الملفات</p>
<code>cacls file.txt</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>icacls</h2>
<p>إدارة الصلاحيات</p>
<code>icacls folder</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>schtasks</h2>
<p>إدارة المهام المجدولة</p>
<code>schtasks</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>shutdown -l</h2>
<p>تسجيل الخروج</p>
<code>shutdown -l</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>shutdown -a</h2>
<p>إلغاء الإيقاف</p>
<code>shutdown -a</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>logoff</h2>
<p>تسجيل خروج</p>
<code>logoff</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>msg</h2>
<p>إرسال رسالة</p>
<code>msg * hello</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>openfiles</h2>
<p>عرض الملفات المفتوحة</p>
<code>openfiles</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>query user</h2>
<p>عرض المستخدمين</p>
<code>query user</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>quser</h2>
<p>معلومات المستخدم</p>
<code>quser</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>qwinsta</h2>
<p>جلسات النظام</p>
<code>qwinsta</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net view</h2>
<p>عرض أجهزة الشبكة</p>
<code>net view</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net share</h2>
<p>المجلدات المشتركة</p>
<code>net share</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net session</h2>
<p>الجلسات النشطة</p>
<code>net session</code>
<button class="btn">نسخ</button>
</div>
<div class="card">
<h2>netsh wlan show profiles</h2>
<p>عرض شبكات Wi-Fi المحفوظة</p>
<code>netsh wlan show profiles</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>netsh wlan show profile</h2>
<p>عرض كلمة مرور Wi-Fi محفوظة</p>
<code>netsh wlan show profile "WiFi" key=clear</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>ipconfig /flushdns</h2>
<p>مسح DNS Cache</p>
<code>ipconfig /flushdns</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>ipconfig /release</h2>
<p>تحرير IP</p>
<code>ipconfig /release</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>ipconfig /renew</h2>
<p>تجديد IP</p>
<code>ipconfig /renew</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net user administrator</h2>
<p>معلومات حساب المدير</p>
<code>net user administrator</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net accounts</h2>
<p>إعدادات الحسابات</p>
<code>net accounts</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net config workstation</h2>
<p>معلومات الجهاز</p>
<code>net config workstation</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wmic bios get serialnumber</h2>
<p>Serial Number للجهاز</p>
<code>wmic bios get serialnumber</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wmic diskdrive get model</h2>
<p>معلومات القرص</p>
<code>wmic diskdrive get model</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wmic cpu get name</h2>
<p>اسم المعالج</p>
<code>wmic cpu get name</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wmic memorychip</h2>
<p>معلومات الرام</p>
<code>wmic memorychip get capacity</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wmic os get caption</h2>
<p>نسخة Windows</p>
<code>wmic os get caption</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>gpresult /r</h2>
<p>سياسات الجهاز</p>
<code>gpresult /r</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>powercfg /energy</h2>
<p>فحص البطارية والطاقة</p>
<code>powercfg /energy</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>powercfg /batteryreport</h2>
<p>تقرير البطارية</p>
<code>powercfg /batteryreport</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>sc query</h2>
<p>عرض الخدمات</p>
<code>sc query</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>sc stop</h2>
<p>إيقاف خدمة</p>
<code>sc stop wuauserv</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>sc start</h2>
<p>تشغيل خدمة</p>
<code>sc start wuauserv</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>fsutil</h2>
<p>إدارة نظام الملفات</p>
<code>fsutil fsinfo drives</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>netstat -b</h2>
<p>البرامج المتصلة بالإنترنت</p>
<code>netstat -b</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>pathping</h2>
<p>تحليل الاتصال</p>
<code>pathping google.com</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>nbtstat</h2>
<p>معلومات NetBIOS</p>
<code>nbtstat -n</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>net file</h2>
<p>الملفات المفتوحة على الشبكة</p>
<code>net file</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>auditpol</h2>
<p>سياسات الأمان</p>
<code>auditpol /get /category:*</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>cipher /w</h2>
<p>حذف آمن للبيانات</p>
<code>cipher /w:C</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>wevtutil qe</h2>
<p>سجلات الأحداث</p>
<code>wevtutil qe System</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>logman</h2>
<p>إدارة Logs</p>
<code>logman query</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>tzutil /g</h2>
<p>المنطقة الزمنية</p>
<code>tzutil /g</code>
<button class="btn">نسخ</button>
</div>

<div class="card">
<h2>systemreset</h2>
<p>إعادة ضبط Windows</p>
<code>systemreset</code>
<button class="btn">نسخ</button>
</div>
<script>

document.querySelectorAll(".btn").forEach(button => {

button.onclick = function () {

let command =
this.parentElement.querySelector("code").innerText;

navigator.clipboard.writeText(command);

this.innerHTML = "✅ تم النسخ";

setTimeout(() => {
this.innerHTML = "نسخ";
}, 1500);

};

});

</script>
<button class="btn">نسخ</button>
<code>ipconfig /all</code>
<div class="card">
<h2>ipconfig</h2>
<p>عرض الشبكة</p>

<code>ipconfig /all</code>

<button class="btn">نسخ</button>
</div>
<script>

function copyCode(button){

let code =
button.parentElement.querySelector("code").textContent;

navigator.clipboard.writeText(code)
.then(() => {

button.innerHTML = "✅ تم النسخ";

setTimeout(function(){
button.innerHTML = "نسخ";
},1500);

});

}

</script>
<div class="card">

<h2>ipconfig</h2>
<p>عرض معلومات الشبكة</p>

<code>ipconfig /all</code>

<button onclick="copyCode(this)" class="btn">
نسخ
</button>

</div>
<div class="card">
<h2>ping</h2>
<code>ping google.com</code>
<button onclick="copyCode(this)" class="btn">
نسخ
</button>
</div>

<div class="card">
<h2>tasklist</h2>
<code>tasklist</code>
<button onclick="copyCode(this)" class="btn">
نسخ
</button>
</div>

<div class="card">
<h2>sfc</h2>
<code>sfc /scannow</code>
<button onclick="copyCode(this)" class="btn">
نسخ
</button>
</div>
<script>

// ================== COPY BUTTON ==================
function copyCode(btn){

let code = btn.parentElement.querySelector("code").innerText;

navigator.clipboard.writeText(code);

btn.innerHTML = "✅ تم النسخ";

setTimeout(() => {
btn.innerHTML = "نسخ";
}, 1500);

}


// ================== SEARCH ==================
let searchInput = document.querySelector(".search");

searchInput.addEventListener("input", function(){

let value = this.value.toLowerCase();

let cards = document.querySelectorAll(".card");

cards.forEach(card => {

let text = card.innerText.toLowerCase();

if(text.includes(value)){
card.style.display = "block";
}else{
card.style.display = "none";
}

});

});

</script>
<button class="btn" onclick="copyCode(this)">
نسخ
</button>
<input class="search" type="text" placeholder="ابحث عن أمر CMD">
<div class="card">

<h2>How to Open CMD</h2>

<img src="cmd-open.jpg"
style="width:100%; border-radius:10px;">

<p>
1. Press the <b>Windows</b> key.<br>
2. Type <b>cmd</b> in search.<br>
3. Press <b>Enter</b> or click
<b>Command Prompt</b>.
</p>

<code>cmd</code>

<button class="btn" onclick="copyCode(this)">
Copy
</button>

</div>
placeholder="Search CMD command..."
<button>🌐 Network</button>
<button>📁 Files</button>
<button>⚙️ System</button>
<button>💾 Disk</button>
<button>🔒 Security</button>
<div class="card">
<h2>ipconfig</h2>
<p>Show network information</p>
<code>ipconfig /all</code>
<button class="btn" onclick="copyCode(this)">
Copy
</button>
</div>

<div class="card">
<h2>ping</h2>
<p>Test internet connection</p>
<code>ping google.com</code>
<button class="btn" onclick="copyCode(this)">
Copy
</button>
</div>

<div class="card">
<h2>tasklist</h2>
<p>Show running programs</p>
<code>tasklist</code>
<button class="btn" onclick="copyCode(this)">
Copy
</button>
</div>

<div class="card">
<h2>sfc</h2>
<p>Repair system files</p>
<code>sfc /scannow</code>
<button class="btn" onclick="copyCode(this)">
Copy
</button>
</div>
<button class="btn" onclick="copyCode(this)">
نسخ
</button>
<div class="card">

<h2>ipconfig</h2>

<p>عرض معلومات الشبكة</p>

<code>ipconfig /all</code>

<button class="btn" onclick="copyCode(this)">
نسخ
</button>

</div>
<div class="card">

<h2>ipconfig</h2>

<p>Show network information</p>

<code>ipconfig /all</code>

<button class="btn" onclick="copyCode(this)">
Copy
</button>

</div>
<div class="card">
<script>

function searchCommand() {

let input =
document.querySelector(".search").value.toLowerCase();

let cards =
document.querySelectorAll(".card");

cards.forEach(function(card){

let title =
card.querySelector("h2").innerText.toLowerCase();

let description =
card.innerText.toLowerCase();

if(
title.includes(input) ||
description.includes(input)
){
card.style.display = "block";
}
else{
card.style.display = "none";
}

});

}

</script>
<input 
type="text" 
class="search"
placeholder="Search CMD command..."
onkeyup="searchCommand()">
<script>

function searchCommand() {

let input =
document.getElementById("search")
.value.toLowerCase();

let cards =
document.querySelectorAll(".card");

for(let i = 0; i < cards.length; i++){

let text =
cards[i].innerText.toLowerCase();

if(text.includes(input)){
cards[i].style.display = "";
}
else{
cards[i].style.display = "none";
}

}

}

</script>
<input
type="text"
id="search"
placeholder="Search CMD command..."
onkeyup="searchCommand()">
<div class="card">

<h2>ipconfig</h2>

<p class="english">
Show network information
</p>

<p class="translation">
عرض معلومات الشبكة
</p>

<code>ipconfig /all</code>

<button class="btn" onclick="copyCode(this)">
Copy
</button>

</div>
<style>

.card{
background:#111827;
padding:20px;
border-radius:15px;
width:260px;
text-align:center;
box-shadow:0 0 10px rgba(0,0,0,0.3);
}

.card h2{
color:#38bdf8;
margin-bottom:10px;
}

.english{
font-size:18px;
font-weight:bold;
color:white;
margin:5px 0;
}

.translation{
font-size:15px;
color:#bdbdbd;
margin-bottom:15px;
}

code{
display:block;
background:black;
padding:10px;
border-radius:10px;
color:#00ff88;
margin-bottom:10px;
}

.btn{
width:100%;
padding:10px;
border:none;
border-radius:10px;
cursor:pointer;
}

</style>
<style>

/* دخول الصفحة */
body{
animation: fadeIn 1.2s ease;
}

@keyframes fadeIn{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}

/* عنوان الموقع */
h1{
animation: glow 2s infinite alternate;
}

@keyframes glow{
from{
text-shadow:0 0 5px #38bdf8;
}
to{
text-shadow:0 0 25px #38bdf8;
}
}

/* البطاقات */
.card{
background:#111827;
padding:20px;
border-radius:20px;
transition:0.4s;
animation: slideUp 0.8s ease;
position:relative;
overflow:hidden;
}

/* حركة دخول الكروت */
@keyframes slideUp{
from{
opacity:0;
transform:translateY(60px);
}
to{
opacity:1;
transform:translateY(0);
}
}

/* Hover جميل */
.card:hover{
transform:
translateY(-10px)
scale(1.03);

box-shadow:
0 0 30px rgba(37,99,235,0.7);
}

/* خط أزرق متحرك */
.card::before{
content:"";
position:absolute;
top:0;
left:-100%;
width:100%;
height:4px;
background:linear-gradient(
90deg,
transparent,
#38bdf8,
transparent
);

transition:0.7s;
}

.card:hover::before{
left:100%;
}

/* الأزرار */
.btn{
background:#2563eb;
color:white;
border:none;
padding:12px;
width:100%;
border-radius:12px;
cursor:pointer;
font-size:16px;
transition:0.3s;
}

/* حركة الزر */
.btn:hover{
transform:scale(1.08);
box-shadow:0 0 20px #2563eb;
}

/* مربع البحث */
.search{
transition:0.3s;
}

.search:focus{
transform:scale(1.03);
box-shadow:0 0 20px #38bdf8;
outline:none;
}

/* صورة CMD */
img{
transition:0.4s;
border-radius:15px;
}

img:hover{
transform:scale(1.04);
box-shadow:0 0 20px #38bdf8;
}

</style>
<script>

// =====================
// COPY BUTTON
// =====================
function copyCode(btn){

let code =
btn.parentElement.querySelector("code").innerText;

navigator.clipboard.writeText(code)
.then(() => {

btn.innerHTML = "✅ Copied";

setTimeout(() => {
btn.innerHTML = "Copy";
},1500);

});

}


// =====================
// CATEGORY FILTER
// =====================
function showCategory(category){

let cards =
document.querySelectorAll(".card");

cards.forEach(card => {

if(category === "all"){
card.style.display = "block";
}
else if(card.dataset.category === category){
card.style.display = "block";
}
else{
card.style.display = "none";
}

});

}

</script>
<button onclick="showCategory('all')">
📂 All Commands
</button>
<button onclick="showCategory('network')">
🌐 Network
</button>

<button onclick="showCategory('files')">
📁 Files
</button>

<button onclick="showCategory('system')">
⚙️ System
</button>
<div class="card" data-category="network">

<h2>ipconfig</h2>

<p>Show network information</p>

<code>ipconfig /all</code>

<button class="btn"
onclick="copyCode(this)">
Copy
</button>

</div>
<div class="card" data-category="files">

<h2>dir</h2>

<p>Show files</p>

<code>dir</code>

<button class="btn"
onclick="copyCode(this)">
Copy
</button>

</div>
<div class="card" data-category="system">

<h2>tasklist</h2>

<p>Show running programs</p>

<code>tasklist</code>

<button class="btn"
onclick="copyCode(this)">
Copy
</button>

</div>
