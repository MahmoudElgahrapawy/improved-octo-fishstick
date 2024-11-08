تمام، إليك الكود الأساسي لصفحتك الشخصية على الويب:

HTML و CSS للصفحة:

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الصفحة الشخصية Elgahrapawy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eaf1f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background: url('https://example.com/cardiac-background.jpg') no-repeat center center/cover;
            height: 300px;
            text-align: center;
            color: white;
            padding-top: 50px;
        }

        header h1 {
            font-size: 36px;
            font-weight: bold;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .profile-section {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
        }

        .profile-section img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 30px;
        }

        .profile-section h2 {
            font-size: 28px;
            color: #2c3e50;
        }

        .bio {
            font-size: 18px;
            line-height: 1.6;
            color: #34495e;
            margin-bottom: 30px;
        }

        .social-links a {
            margin: 0 10px;
            font-size: 18px;
            text-decoration: none;
            color: #2980b9;
        }

        .video-section {
            margin-top: 50px;
        }

        .video-section h3 {
            font-size: 24px;
            margin-bottom: 15px;
        }

        iframe {
            width: 100%;
            height: 400px;
        }

    </style>
</head>
<body>

<header>
    <h1>مرحبًا بك في صفحة شوشو الغرباوي</h1>
</header>

<div class="container">
    <div class="profile-section">
        <!-- ضع رابط الصورة الشخصية هنا -->
        <img src="https://example.com/profile-picture.jpg" alt="شوشو الغرباوي">
        <div>
            <h2>شوشو الغرباوي</h2>
            <p class="bio">أستاذ أحياء، متحمس لنقل المعرفة العلمية للطلاب بطريقة ممتعة وسهلة. أعمل على تقديم محتوى تعليمي في الكيمياء والفيزياء بالإضافة إلى الأحياء. هدفي هو مساعدة الطلاب في اكتساب المهارات العلمية المطلوبة في المستقبل.</p>
            <div class="social-links">
                <a href="https://www.facebook.com/profile.php?id=100052917521481&mibextid=ZbWKwL" target="_blank">صفحة فيسبوك</a>
            </div>
        </div>
    </div>

    <div class="video-section">
        <h3>فيديوهات تعليمية</h3>
        <!-- ضع رابط فيديو يوتيوب هنا -->
        <iframe src="https://www.youtube.com/embed/YourVideoID" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>

</body>
</html>

ملاحظات:

1. خلفية الصفحة: يمكنك تحميل صورة لقلب الإنسان على الإنترنت (أو استخدام صورة خاصة بك) ووضع رابط الصورة في مكان 'https://example.com/cardiac-background.jpg'.


2. الصورة الشخصية: استبدل الرابط في الوسم <img src="https://example.com/profile-picture.jpg"> بالصورة الشخصية التي تريدها.


3. الفيديوهات التعليمية: يمكنك إضافة رابط فيديوهاتك على يوتيوب في الوسم <iframe>، استبدل YourVideoID برابط الفيديو المطلوب.


4. الفيسبوك: رابط صفحة فيسبوك موجود، ولا يحتاج لتغيير إذا كان هو الرابط الصحيح.



قم بتعديل الروابط حسب احتياجاتك، ويمكنك حفظ الملف بتنسيق .html وفتحه في أي متصفح لعرض الصفحة.

هل تحتاج إلى إضافة شيء آخر أو تعديل على التصميم؟

تمام، إليك الكود الأساسي لصفحتك الشخصية على الويب:

HTML و CSS للصفحة:

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الصفحة الشخصية - شوشو الغرباوي</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eaf1f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background: url('https://example.com/cardiac-background.jpg') no-repeat center center/cover;
            height: 300px;
            text-align: center;
            color: white;
            padding-top: 50px;
        }

        header h1 {
            font-size: 36px;
            font-weight: bold;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .profile-section {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
        }

        .profile-section img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 30px;
        }

        .profile-section h2 {
            font-size: 28px;
            color: #2c3e50;
        }

        .bio {
            font-size: 18px;
            line-height: 1.6;
            color: #34495e;
            margin-bottom: 30px;
        }

        .social-links a {
            margin: 0 10px;
            font-size: 18px;
            text-decoration: none;
            color: #2980b9;
        }

        .video-section {
            margin-top: 50px;
        }

        .video-section h3 {
            font-size: 24px;
            margin-bottom: 15px;
        }

        iframe {
            width: 100%;
            height: 400px;
        }

    </style>
</head>
<body>

<header>
    <h1>مرحبًا بك في صفحة شوشو الغرباوي</h1>
</header>

<div class="container">
    <div class="profile-section">
        <!-- ضع رابط الصورة الشخصية هنا -->
        <img src="https://example.com/profile-picture.jpg" alt="شوشو الغرباوي">
        <div>
            <h2>شوشو الغرباوي</h2>
            <p class="bio">أستاذ أحياء، متحمس لنقل المعرفة العلمية للطلاب بطريقة ممتعة وسهلة. أعمل على تقديم محتوى تعليمي في الكيمياء والفيزياء بالإضافة إلى الأحياء. هدفي هو مساعدة الطلاب في اكتساب المهارات العلمية المطلوبة في المستقبل.</p>
            <div class="social-links">
                <a href="https://www.facebook.com/profile.php?id=100052917521481&mibextid=ZbWKwL" target="_blank">صفحة فيسبوك</a>
            </div>
        </div>
    </div>

    <div class="video-section">
        <h3>فيديوهات تعليمية</h3>
        <!-- ضع رابط فيديو يوتيوب هنا -->
        <iframe src="https://www.youtube.com/embed/YourVideoID" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>

</body>
</html>

ملاحظات:

1. خلفية الصفحة: يمكنك تحميل صورة لقلب الإنسان على الإنترنت (أو استخدام صورة خاصة بك) ووضع رابط الصورة في مكان 'https://example.com/cardiac-background.jpg'.


2. الصورة الشخصية: استبدل الرابط في الوسم <img src="https://example.com/profile-picture.jpg"> بالصورة الشخصية التي تريدها.


3. الفيديوهات التعليمية: يمكنك إضافة رابط فيديوهاتك على يوتيوب في الوسم <iframe>، استبدل YourVideoID برابط الفيديو المطلوب.


4. الفيسبوك: رابط صفحة فيسبوك موجود، ولا يحتاج لتغيير إذا كان هو الرابط الصحيح.



قم بتعديل الروابط حسب احتياجاتك، ويمكنك حفظ الملف بتنسيق .html وفتحه في أي متصفح لعرض الصفحة.

هل تحتاج إلى إضافة شيء آخر أو تعديل على التصميم؟

تمام، إليك الكود الأساسي لصفحتك الشخصية على الويب:

HTML و CSS للصفحة:

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الصفحة الشخصية - شوشو الغرباوي</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eaf1f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background: url('https://example.com/cardiac-background.jpg') no-repeat center center/cover;
            height: 300px;
            text-align: center;
            color: white;
            padding-top: 50px;
        }

        header h1 {
            font-size: 36px;
            font-weight: bold;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .profile-section {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
        }

        .profile-section img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 30px;
        }

        .profile-section h2 {
            font-size: 28px;
            color: #2c3e50;
        }

        .bio {
            font-size: 18px;
            line-height: 1.6;
            color: #34495e;
            margin-bottom: 30px;
        }

        .social-links a {
            margin: 0 10px;
            font-size: 18px;
            text-decoration: none;
            color: #2980b9;
        }

        .video-section {
            margin-top: 50px;
        }

        .video-section h3 {
            font-size: 24px;
            margin-bottom: 15px;
        }

        iframe {
            width: 100%;
            height: 400px;
        }

    </style>
</head>
<body>

<header>
    <h1>مرحبًا بك في صفحة شوشو الغرباوي</h1>
</header>

<div class="container">
    <div class="profile-section">
        <!-- ضع رابط الصورة الشخصية هنا -->
        <img src="https://example.com/profile-picture.jpg" alt="شوشو الغرباوي">
        <div>
            <h2>شوشو الغرباوي</h2>
            <p class="bio">أستاذ أحياء، متحمس لنقل المعرفة العلمية للطلاب بطريقة ممتعة وسهلة. أعمل على تقديم محتوى تعليمي في الكيمياء والفيزياء بالإضافة إلى الأحياء. هدفي هو مساعدة الطلاب في اكتساب المهارات العلمية المطلوبة في المستقبل.</p>
            <div class="social-links">
                <a href="https://www.facebook.com/profile.php?id=100052917521481&mibextid=ZbWKwL" target="_blank">صفحة فيسبوك</a>
            </div>
        </div>
    </div>

    <div class="video-section">
        <h3>فيديوهات تعليمية</h3>
        <!-- ضع رابط فيديو يوتيوب هنا -->
        <iframe src="https://www.youtube.com/embed/YourVideoID" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>

</body>
</html>

ملاحظات:

1. خلفية الصفحة: يمكنك تحميل صورة لقلب الإنسان على الإنترنت (أو استخدام صورة خاصة بك) ووضع رابط الصورة في مكان 'https://example.com/cardiac-background.jpg'.


2. الصورة الشخصية: استبدل الرابط في الوسم <img src="https://example.com/profile-picture.jpg"> بالصورة الشخصية التي تريدها.


3. الفيديوهات التعليمية: يمكنك إضافة رابط فيديوهاتك على يوتيوب في الوسم <iframe>، استبدل YourVideoID برابط الفيديو المطلوب.


4. الفيسبوك: رابط صفحة فيسبوك موجود، ولا يحتاج لتغيير إذا كان هو الرابط الصحيح.



قم بتعديل الروابط حسب احتياجاتك، ويمكنك حفظ الملف بتنسيق .html وفتحه في أي متصفح لعرض الصفحة.

هل تحتاج إلى إضافة شيء آخر أو تعديل على التصميم؟

