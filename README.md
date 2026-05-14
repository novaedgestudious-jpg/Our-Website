# Our-Website
Our Website 
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nova Edge Studio</title>

<style>
:root {
    --main-color: #6C5CE7; /* غيّر اللون هنا حسب هوية الشركة */
    --bg: #0f0f1a;
    --text: #ffffff;
    --card: #1a1a2e;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: var(--bg);
    color: var(--text);
    direction: rtl;
}

/* الهيدر */
header {
    padding: 20px;
    background: var(--card);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    color: var(--main-color);
    margin: 0;
}

/* القسم الرئيسي */
.hero {
    text-align: center;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 40px;
    color: var(--main-color);
}

.hero p {
    max-width: 600px;
    margin: auto;
    opacity: 0.8;
}

/* زر */
.btn {
    margin-top: 20px;
    padding: 12px 25px;
    border: none;
    background: var(--main-color);
    color: white;
    cursor: pointer;
    border-radius: 8px;
}

/* الأقسام */
section {
    padding: 60px 20px;
}

.card-container {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background: var(--card);
    padding: 20px;
    border-radius: 12px;
    width: 250px;
    text-align: center;
    border: 1px solid rgba(255,255,255,0.1);
}

.card h3 {
    color: var(--main-color);
}

/* الفوتر */
footer {
    text-align: center;
    padding: 20px;
    background: var(--card);
    margin-top: 40px;
}
</style>
</head>

<body>

<header>
    <h1>Nova Edge Studio</h1>
    <nav>Home | Services | Team | Contact</nav>
</header>

<div class="hero">
    <h2>نصنع المستقبل الرقمي</h2>
    <p>
        نحن فريق تطوير متخصص في بناء مواقع الويب، التطبيقات، وتجارب رقمية حديثة تجمع بين الإبداع والتقنية.
    </p>
    <button class="btn">ابدأ مشروعك</button>
</div>

<section>
    <h2 style="text-align:center;">خدماتنا</h2>
    <div class="card-container">
        <div class="card">
            <h3>تطوير مواقع</h3>
            <p>مواقع احترافية سريعة ومتجاوبة.</p>
        </div>

        <div class="card">
            <h3>تطبيقات أندرويد</h3>
            <p>تطبيقات قوية تعمل بدون مشاكل.</p>
        </div>

        <div class="card">
            <h3>تصميم UI/UX</h3>
            <p>تصميمات حديثة وجذابة للمستخدم.</p>
        </div>
    </div>
</section>

<section>
    <h2 style="text-align:center;">فريق العمل</h2>
    <div class="card-container">
        <div class="card">
            <h3>Developer Team</h3>
            <p>تطوير وبناء الأنظمة والتطبيقات</p>
        </div>

        <div class="card">
            <h3>Design Team</h3>
            <p>تصميم الهوية البصرية وتجربة المستخدم</p>
        </div>

        <div class="card">
            <h3>Support Team</h3>
            <p>دعم ومتابعة المشاريع باستمرار</p>
        </div>
    </div>
</section>

<footer>
    © 2026 All Rights Reserved - Nova Edge Studio
</footer>

<script>
document.querySelector(".btn").addEventListener("click", function() {
    alert("جاهزين نبدأ مشروعك 🚀");
});
</script>

</body>
</html>
