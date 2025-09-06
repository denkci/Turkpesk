<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turkpesk - Sivil Elektronik Kitler</title>
    <style>
        body { font-family: Arial, sans-serif; margin:0; padding:0; }
        header { background-color: #004080; color: white; padding: 15px 20px; display: flex; justify-content: space-between; align-items: center; }
        nav a { color: white; margin: 0 10px; text-decoration: none; }
        nav a:hover { text-decoration: underline; }
        .banner { background-color: #e6f0ff; padding: 50px; text-align: center; font-size: 24px; }
        .categories { display: flex; justify-content: space-around; flex-wrap: wrap; padding: 20px; }
        .category { background-color: #f0f8ff; margin: 10px; padding: 20px; width: 250px; text-align: center; border-radius: 10px; box-shadow: 0 0 5px rgba(0,0,0,0.1); }
        footer { background-color: #004080; color: white; text-align: center; padding: 20px; margin-top: 20px; }
    </style>
</head>
<body>
    <header>
        <div class="logo">Turkpesk</div>
        <nav>
            <a href="#">Ana Sayfa</a>
            <a href="#">Ürünler</a>
            <a href="#">Eğitim & Destek</a>
            <a href="#">Toplu Satış</a>
            <a href="#">Hakkımızda</a>
            <a href="#">İletişim</a>
            <a href="#">Sepet/Hesabım</a>
        </nav>
    </header>

    <div class="banner">
        Turkpesk Eğitim Serisi – Elektronik ve Robotik Kitler
    </div>

    <section class="categories">
        <div class="category">Temel Elektronik Kartlar</div>
        <div class="category">Sensör ve Modül Setleri</div>
        <div class="category">Robotik Başlangıç Kitleri</div>
        <div class="category">Elektronik Eğitim Setleri</div>
        <div class="category">Aksesuar ve Destek Ürünleri</div>
    </section>

    <footer>
        © 2025 Turkpesk. Tüm hakları saklıdır.
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turkpesk - Sivil Elektronik Kitler</title>
    <style>
        body { font-family: Arial, sans-serif; margin:0; padding:0; }
        header { background-color: #004080; color: white; padding: 15px 20px; display: flex; justify-content: space-between; align-items: center; }
        nav { position: relative; }
        nav ul { list-style: none; margin:0; padding:0; display: flex; }
        nav ul li { position: relative; }
        nav ul li a { color: white; padding: 10px 15px; text-decoration: none; display: block; }
        nav ul li a:hover { background-color: #003060; }
        nav ul li ul { display: none; position: absolute; top: 100%; left: 0; background-color: #004080; min-width: 200px; flex-direction: column; }
        nav ul li:hover ul { display: flex; flex-direction: column; }
        nav ul li ul li a { padding: 10px; }
        .banner { background-color: #e6f0ff; padding: 50px; text-align: center; font-size: 24px; }
        .categories, .products { display: flex; justify-content: space-around; flex-wrap: wrap; padding: 20px; }
        .category, .product { background-color: #f0f8ff; margin: 10px; padding: 20px; width: 250px; text-align: center; border-radius: 10px; box-shadow: 0 0 5px rgba(0,0,0,0.1); }
        .product h3 { margin: 10px 0; }
        .product p { margin: 5px 0; }
        footer { background-color: #004080; color: white; text-align: center; padding: 20px; margin-top: 20px; }
        button { background-color: #004080; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer; }
        button:hover { background-color: #003060; }
    </style>
</head>
<body>
    <header>
        <div class="logo">Turkpesk</div>
        <nav>
            <ul>
                <li><a href="#">Ana Sayfa</a></li>
                <li>
                    <a href="#">Ürünler</a>
                    <ul>
                        <li><a href="#temel-kartlar">Temel Elektronik Kartlar</a></li>
                        <li><a href="#sensor-setleri">Sensör ve Modül Setleri</a></li>
                        <li><a href="#robot-kit">Robotik Başlangıç Kitleri</a></li>
                        <li><a href="#egitim-seti">Elektronik Eğitim Setleri</a></li>
                        <li><a href="#aksesuar">Aksesuar ve Destek Ürünleri</a></li>
                    </ul>
                </li>
                <li><a href="#">Eğitim & Destek</a></li>
                <li><a href="#">Toplu Satış</a></li>
                <li><a href="#">Hakkımızda</a></li>
                <li><a href="#">İletişim</a></li>
                <li><a href="#">Sepet/Hesabım</a></li>
            </ul>
        </nav>
    </header>

    <div class="banner">
        Turkpesk Eğitim Serisi – Elektronik ve Robotik Kitler
    </div>

    <!-- Kategoriler -->
    <section class="categories">
        <div class="category"><a href="#temel-kartlar">Temel Elektronik Kartlar</a></div>
        <div class="category"><a href="#sensor-setleri">Sensör ve Modül Setleri</a></div>
        <div class="category"><a href="#robot-kit">Robotik Başlangıç Kitleri</a></div>
        <div class="category"><a href="#egitim-seti">Elektronik Eğitim Setleri</a></div>
        <div class="category"><a href="#aksesuar">Aksesuar ve Destek Ürünleri</a></div>
    </section>

    <!-- Ürünler -->
    <section class="products" id="temel-kartlar">
        <div class="product">
            <h3>Arduino Başlangıç Seti</h3>
            <p>Arduino UNO, breadboard, jumper kablolar, LED ve direnç seti</p>
            <p>Fiyat: 500 TL</p>
            <button>Sepete Ekle</button>
        </div>
        <div class="product">
            <h3>ESP32 IoT Seti</h3>
            <p>ESP32 modül, 3 sensör, breadboard, jumper kablolar</p>
            <p>Fiyat: 600 TL</p>
            <button>Sepete Ekle</button>
        </div>
    </section>

    <section class="products" id="sensor-setleri">
        <div class="product">
            <h3>Sensör Modül Seti</h3>
            <p>10 farklı sensör (IR, ultrasonic, gaz, sıcaklık, nem vs.)</p>
            <p>Fiyat: 300 TL</p>
            <button>Sepete Ekle</button>
        </div>
    </section>

    <section class="products" id="robot-kit">
        <div class="product">
            <h3>Mini Robot Kit</h3>
            <p>Arduino Nano, motorlar, motor sürücü, mini şasi, breadboard</p>
            <p>Fiyat: 800 TL</p>
            <button>Sepete Ekle</button>
        </div>
    </section>

    <section class="products" id="egitim-seti">
        <div class="product">
            <h3>Elektronik Eğitim Seti</h3>
            <p>Arduino UNO, sensörler, motorlar, robot şasi, breadboard</p>
            <p>Fiyat: 1000 TL</p>
            <button>Sepete Ekle</button>
        </div>
    </section>

    <section class="products" id="aksesuar">
        <div class="product">
            <h3>Aksesuar Paketi</h3>
            <p>Breadboard, jumper kablolar, direnç/kapasitör setleri, USB güç kaynağı</p>
            <p>Fiyat: 150 TL</p>
            <button>Sepete Ekle</button>
        </div>
    </section>

    <footer>
        © 2025 Turkpesk. Tüm hakları saklıdır.
    </footer>
</body>
</html>
