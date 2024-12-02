<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر إلكتروني</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>متجري الإلكتروني</h1>
            <nav>
                <ul>
                    <li><a href="#home">الرئيسية</a></li>
                    <li><a href="#products">المنتجات</a></li>
                    <li><a href="#contact">اتصل بنا</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home">
            <div class="hero">
                <h2>أهلاً بك في متجرنا!</h2>
                <p>اكتشف منتجاتنا المميزة بأسعار رائعة.</p>
                <a href="#products" class="btn">تسوق الآن</a>
            </div>
        </section>

        <section id="products">
            <h2>منتجاتنا</h2>
            <div class="product-list">
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="منتج 1">
                    <h3>منتج 1</h3>
                    <p>وصف قصير عن المنتج.</p>
                    <button>إضافة إلى السلة</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="منتج 2">
                    <h3>منتج 2</h3>
                    <p>وصف قصير عن المنتج.</p>
                    <button>إضافة إلى السلة</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="منتج 3">
                    <h3>منتج 3</h3>
                    <p>وصف قصير عن المنتج.</p>
                    <button>إضافة إلى السلة</button>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>اتصل بنا</h2>
            <form>
                <label for="name">الاسم:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">البريد الإلكتروني:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">الرسالة:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">إرسال</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 متجري الإلكتروني. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
