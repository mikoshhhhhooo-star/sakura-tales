<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sakura Tales | حكايات ساكورا</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    font-family:Arial,Tahoma,sans-serif;
    background:#fff8fc;
    color:#4d3542;
}

/* الشريط العلوي */
header{
    background:white;
    border-bottom:1px solid #f3d5e2;
    padding:16px 6%;
    display:flex;
    align-items:center;
    justify-content:space-between;
    position:sticky;
    top:0;
    z-index:10;
}

.logo{
    text-decoration:none;
    color:#d45d91;
    font-size:24px;
    font-weight:bold;
}

nav{
    display:flex;
    gap:20px;
}

nav a{
    text-decoration:none;
    color:#624655;
    font-weight:bold;
}

nav a:hover{
    color:#d45d91;
}

/* الترحيب */
.hero{
    text-align:center;
    padding:80px 20px;
    background:linear-gradient(135deg,#ffe4ef,#fff8fc);
}

.sakura{
    font-size:60px;
}

.hero h1{
    color:#c84f82;
    font-size:45px;
    margin:15px 0;
}

.hero p{
    color:#765765;
    font-size:18px;
    margin-bottom:25px;
}

.button{
    display:inline-block;
    background:#d45d91;
    color:white;
    text-decoration:none;
    padding:13px 25px;
    border-radius:25px;
    font-weight:bold;
}

/* الأقسام */
.section{
    padding:60px 7%;
}

.section-title{
    text-align:center;
    color:#c84f82;
    font-size:30px;
    margin-bottom:35px;
}

/* بطاقة المانهوا */
.manga-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
    gap:25px;
    max-width:1000px;
    margin:auto;
}

.manga{
    background:white;
    border:1px solid #f1d7e3;
    border-radius:20px;
    overflow:hidden;
    box-shadow:0 8px 25px rgba(160,70,110,.08);
}

.cover{
    height:300px;
    background:linear-gradient(135deg,#ffd3e4,#fff0f6);
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    font-size:70px;
}

.info{
    padding:20px;
}

.info h3{
    color:#593b4a;
    font-size:22px;
    margin-bottom:8px;
}

.info p{
    color:#806674;
    line-height:1.7;
    margin-bottom:15px;
}

.tag{
    display:inline-block;
    background:#ffe3ee;
    color:#b94e7c;
    padding:4px 10px;
    border-radius:20px;
    font-size:13px;
    font-weight:bold;
    margin-bottom:10px;
}

.read{
    display:inline-block;
    color:#d45d91;
    text-decoration:none;
    font-weight:bold;
}

/* آخر الفصول */
.latest{
    background:#fff0f6;
}

.chapter{
    background:white;
    border:1px solid #f1d7e3;
    border-radius:15px;
    padding:18px;
    margin:12px auto;
    max-width:800px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.chapter a{
    color:#d45d91;
    text-decoration:none;
    font-weight:bold;
}

/* عن الموقع */
.about{
    text-align:center;
    padding:70px 20px;
}

.about p{
    max-width:650px;
    margin:auto;
    color:#765765;
    line-height:2;
}

/* الفوتر */
footer{
    background:#d45d91;
    color:white;
    text-align:center;
    padding:25px;
}

/* الهاتف */
@media(max-width:650px){

    header{
        flex-direction:column;
        gap:12px;
    }

    nav{
        gap:12px;
        font-size:14px;
    }

    .hero h1{
        font-size:34px;
    }

    .chapter{
        margin:12px 5%;
    }
}
</style>
</head>

<body>

<header>

<a href="#" class="logo">
🌸 Sakura Tales
</a>

<nav>
<a href="#home">الرئيسية</a>
<a href="#manga">المانهوا</a>
<a href="#chapters">الفصول</a>
<a href="#about">عن الموقع</a>
</nav>

</header>


<!-- الصفحة الرئيسية -->

<section class="hero" id="home">

<div class="sakura">🌸</div>

<h1>حكايات ساكورا</h1>

<p>
مرحبًا بكِ في عالمي الصغير للمانهوا والقصص 💗
</p>

<a href="#manga" class="button">
اكتشفي المانهوا ✨
</a>

</section>


<!-- المانهوا -->

<section class="section" id="manga">

<h2 class="section-title">
📚 المانهوا
</h2>

<div class="manga-grid">


<!-- مانهوا كيغ -->

<div class="manga">

<div class="cover"><img src="اسم-صورة-الغلاف.jpg" alt="غلاف مانهوا كيغ"></div>

<div class="info">

<span class="tag">
رومانسية
</span>

<h3>
كيغ
</h3>

<p>
هنا سنضع وصف مانهوا كيغ عندما تعطيني الوصف الذي تريدينه.
</p>

<a href="#chapters" class="read">
قراءة المانهوا ←
</a>

</div>

</div>


<!-- مانهوا ثانية -->

<div class="manga">

<div class="cover">
✨🌙
</div>

<div class="info">

<span class="tag">
قريبًا
</span>

<h3>
مانهوا جديدة
</h3>

<p>
مكان مخصص لإضافة مانهوا أخرى في المستقبل.
</p>

<a href="#manga" class="read">
قريبًا ✨
</a>

</div>

</div>

</div>

</section>


<!-- الفصول -->

<section class="section latest" id="chapters">

<h2 class="section-title">
✨ فصول كيغ
</h2>


<div class="chapter">

<div>
<strong>كيغ — الفصل 01</strong>
<br>
<span>الفصل الأول</span>
</div>

<a href="#">
قراءة الفصل ←
</a>

</div>


<div class="chapter">

<div>
<strong>كيغ — الفصل 02</strong>
<br>
<span>قريبًا</span>
</div>

<a href="#">
قريبًا
</a>

</div>


</section>


<!-- عن الموقع -->

<section class="about" id="about">

<h2 class="section-title">
💗 عن Sakura Tales
</h2>

<p>
Sakura Tales هو موقع عربي مخصص لنشر وقراءة المانهوا.
هنا أشارك قصصي وفصول المانهوا الخاصة بي مع القراء
في مكان بسيط وناعم مستوحى من أزهار الساكورا 🌸
</p>

</section>


<footer>

🌸 Sakura Tales — حكايات ساكورا

<br><br>

© 2026 جميع الحقوق محفوظة

</footer>

</body>
</html>
