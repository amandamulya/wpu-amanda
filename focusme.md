<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Focus Me</title>

    <!--Fonts-->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,400;0,700;1,700&display=swap"
      rel="stylesheet"
    />

    <!--Feather Icons-->
    <script src="https://unpkg.com/feather-icons"></script>

    <!--My Style-->
    <link rel="stylesheet" href="css/style.css" />
  </head>

  <body>
    <!--Navbar Start-->
    <nav class="navbar">
      <a href="#" class="navbar-logo">focus<span>me</span>.</a>

      <div class="navbar-nav">
        <a href="#">Home</a>
        <a href="#about">Tentang Kami</a>
        <a href="#pilihan">Pilihan</a>
        <a href="#products">Produk</a>
        <a href="#contact">Kontak</a>
      </div>

      <div class="navbar-extra">
        <a href="#" id="search-button"><i data-feather="search"></i></a>
        <a href="#" id="shopping-cart-button"
          ><i data-feather="shopping-cart"></i
        ></a>
        <a href="#" id="hamburger-menu"><i data-feather="menu"></i></a>
      </div>

      <!-- Search Form Start -->
      <div class="search-form">
        <input type="search" id="search-box" placeholder="search here..." />
        <label for="search-box"><i data-feather="search"></i></label>
      </div>
      <!-- Search Form End -->

      <!--Shopping Card Start-->
      <div class="shopping-cart">
        <div class="cart-item">
          <img src="img/products/product1.jpg" alt="Product 1" />
          <div class="item-detail">
            <h3>Product 1</h3>
            <div class="item-price">IDR 1.000.000</div>
          </div>
          <i data-feather="trash-2" class="remove-item"></i>
        </div>
        <div class="cart-item">
          <img src="img/products/product1.jpg" alt="Product 1" />
          <div class="item-detail">
            <h3>Product 1</h3>
            <div class="item-price">IDR 1.000.000</div>
          </div>
          <i data-feather="trash-2" class="remove-item"></i>
        </div>
        <div class="cart-item">
          <img src="img/products/product1.jpg" alt="Product 1" />
          <div class="item-detail">
            <h3>Product 1</h3>
            <div class="item-price">IDR 1.000.000</div>
          </div>
          <i data-feather="trash-2" class="remove-item"></i>
        </div>
      </div>
      <!--Shopping Card End-->
    </nav>
    <!--Navbar End-->

    <!--Hero Section Start-->
    <section class="hero" id="home">
      <main class="content">
        <h1>Abadikan Setiap Momen <span>Indahmu</span></h1>
        <p>Jadikan setiap momen berharga menjadi kenangan abadi bersama kami</p>
        <a href="#" class="cta">Pesan Sekarang</a>
      </main>
    </section>
    <!--Hero Section End-->

    <!--About Section-->
    <section id="about" class="about">
      <h2><span>Tentang</span> Kami</h2>

      <div class="row">
        <div class="about-img">
          <img src="img/tentang-kami.jpg" alt="Tentang Kami" />
        </div>
        <div class="content">
          <h3>Kenapa Memilih Jasa Kami ?</h3>
          <p>
            Kami merupakan pilihan tepat untuk jasa fotografer karena kami
            menawarkan hasil foto yang memuaskan dengan harga terjangkau
          </p>
          <p>
            Keunggulan kami terletak pada kombinasi kreativitas, keahlian
            teknis, dan harga yang terjangkau, memberikan hasil fotografi yang
            memukau dan puas
          </p>
        </div>
      </div>
    </section>

    <!--About Section-->

    <!--Menu Section Start-->
    <section id="pilihan" class="menu">
      <h2><span>Pilihan</span> Kami</h2>
      <p>
        Kami menawarkan pilihan paket yang fleksibel, mulai dari sesi foto
        individual, keluarga, hingga acara khusus, sesuai dengan kebutuhan dan
        anggaran Anda.
      </p>

      <div class="row">
        <div class="menu-card">
          <img src="img/pilihan/1a.jpg" alt="Wedding" class="menu-card-img" />
          <h3 class="menu-card-tittle">- Wedding -</h3>
          <p class="menu-card-price">IDR 1.000.000</p>
        </div>
        <div class="menu-card">
          <img
            src="img/pilihan/grad.jpg"
            alt="Graduatio"
            class="menu-card-img"
          />
          <h3 class="menu-card-tittle">- Graduation -</h3>
          <p class="menu-card-price">IDR 250.000</p>
        </div>
        <div class="menu-card">
          <img src="img/pilihan/nb.png" alt="Newborn" class="menu-card-img" />
          <h3 class="menu-card-tittle">- Newborn -</h3>
          <p class="menu-card-price">IDR 400.000</p>
        </div>
        <div class="menu-card">
          <img src="img/pilihan/prdc.jpg" alt="Product" class="menu-card-img" />
          <h3 class="menu-card-tittle">- Product -</h3>
          <p class="menu-card-price">IDR 25.000</p>
        </div>
        <div class="menu-card">
          <img
            src="img/pilihan/enga.jpg"
            alt="Engagement"
            class="menu-card-img"
          />
          <h3 class="menu-card-tittle">- Engagement -</h3>
          <p class="menu-card-price">IDR 350.000</p>
        </div>
        <div class="menu-card">
          <img src="img/pilihan/brt.jpg" alt="Birthday" class="menu-card-img" />
          <h3 class="menu-card-tittle">- Birthday -</h3>
          <p class="menu-card-price">IDR 150.000</p>
        </div>
      </div>
    </section>
    <!--Menu Section End-->
    <!--Product Section Start-->
    <section class="products" id="products">
      <h2><span>Paket Unggulan</span> Kami</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias sit sed
        facilis ipsum repellendus libero.
      </p>
      <div class="row">
        <div class="product-card">
          <div class="product-icons">
            <a href="#"><i data-feather="shopping-cart"></i></a>
            <a href="#" class="item-detail-button"
              ><i data-feather="eye"></i
            ></a>
          </div>
          <div class="product-image">
            <img src="img/products/product1.jpg" alt="Product 1" />
          </div>
          <div class="product-content">
            <h3>Wedding</h3>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 1.000.000 <span>IDR 1.500.000</span>
            </div>
          </div>
        </div>
        <div class="product-card">
          <div class="product-icons">
            <a href="#"><i data-feather="shopping-cart"></i></a>
            <a href="#" class="item-detail-button"
              ><i data-feather="eye"></i
            ></a>
          </div>
          <div class="product-image">
            <img src="img/products/product2.jpg" alt="Product 2" />
          </div>
          <div class="product-content">
            <h3>Graduation</h3>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 250.000 <span>IDR 300.000</span>
            </div>
          </div>
        </div>
        <div class="product-card">
          <div class="product-icons">
            <a href="#"><i data-feather="shopping-cart"></i></a>
            <a href="#" class="item-detail-button"
              ><i data-feather="eye"></i
            ></a>
          </div>
          <div class="product-image">
            <img src="img/products/product3.jpg" alt="Product 3" />
          </div>
          <div class="product-content">
            <h3>Newborn</h3>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 400.000 <span>IDR 450.000</span>
            </div>
          </div>
        </div>
        <div class="product-card">
          <div class="product-icons">
            <a href="#"><i data-feather="shopping-cart"></i></a>
            <a href="#" class="item-detail-button"
              ><i data-feather="eye"></i
            ></a>
          </div>
          <div class="product-image">
            <img src="img/products/product4.jpg" alt="Product 4" />
          </div>
          <div class="product-content">
            <h3>Product</h3>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">IDR 25.000 <span>IDR 30.000</span></div>
          </div>
        </div>
        <div class="product-card">
          <div class="product-icons">
            <a href="#"><i data-feather="shopping-cart"></i></a>
            <a href="#" class="item-detail-button"
              ><i data-feather="eye"></i
            ></a>
          </div>
          <div class="product-image">
            <img src="img/products/product5.jpg" alt="Product 5" />
          </div>
          <div class="product-content">
            <h3>Engagement</h3>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 350.000 <span>IDR 400.000</span>
            </div>
          </div>
        </div>
        <div class="product-card">
          <div class="product-icons">
            <a href="#"><i data-feather="shopping-cart"></i></a>
            <a href="#" class="item-detail-button"
              ><i data-feather="eye"></i
            ></a>
          </div>
          <div class="product-image">
            <img src="img/products/product6.jpg" alt="Product 6" />
          </div>
          <div class="product-content">
            <h3>Birthday</h3>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 150.000 <span>IDR 200.000</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--Product Section End -->

    <!--Contact Section Start-->
    <section id="contact" class="contact">
      <h2><span>Kontak</span> Kami</h2>
      <p>
        Jika anda berminat, anda dapat menghubungi kami dengan mengisi data
        dibawah ini:
      </p>
      <div class="row">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d31689.336857369755!2d109.11723959999999!3d-6.8705707!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6fb9dfbf3264c3%3A0x3027a76e352bbe0!2sTegal%2C%20Kota%20Tegal%2C%20Jawa%20Tengah!5e0!3m2!1sid!2sid!4v1684337230437!5m2!1sid!2sid"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          class="map"
        ></iframe>

        <form action="">
          <div class="input-group">
            <i data-feather="user"></i>
            <input type="text" placeholder="nama" />
          </div>
          <div class="input-group">
            <i data-feather="mail"></i>
            <input type="text" placeholder="email" />
          </div>
          <div class="input-group">
            <i data-feather="phone"></i>
            <input type="text" placeholder="no hp" />
          </div>
          <button type="submit" class="btn">kirim pesan</button>
        </form>
      </div>
    </section>
    <!--Contact Section End-->
    <!--Footer Start-->
    <footer>
      <div class="socials">
        <a href="#"><i data-feather="instagram"></i></a>
        <a href="#"><i data-feather="twitter"></i></a>
        <a href="#"><i data-feather="facebook"></i></a>
      </div>

      <div class="links">
        <a href="#home">Home</a>
        <a href="#about">Tentang Kami</a>
        <a href="#pilihan">Pilihan</a>
        <a href="#contact">Kontak</a>
      </div>

      <div class="credit">
        <p>Created by <a href="">focusme</a>. | &copy;2023.</p>
      </div>
    </footer>
    <!--Footer End-->
    <!--Modal Box Item Detail Start-->
    <div class="modal" id="item-detail-modal">
      <div class="modal-container">
        <a href="#" class="close-icon"><i data-feather="x"></i></a>
        <div class="modal-content">
          <img src="img/products/product1.jpg" alt="Product 1" />
          <div class="product-content">
            <h3>Paket 1</h3>
            <p>
              1 Paket include : Jasa photographer 1x24 jam, album foto isi 25
              lembar, soft file yang sudah diedit, free handbouquet.
            </p>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 1.000.000
              <span
                style="
                  text-decoration: line-through;
                  font-weight: lighter;
                  font-size: 1rem;
                "
                >IDR 1.500.000</span
              >
              <a href="#"
                ><i data-feather="shopping-cart"></i><span>add to cart</span></a
              >
            </div>
          </div>
        </div>
      </div>
      <!--<div class="modal-container">
        <a href="#" class="close-icon"><i data-feather="x"></i></a>
        <div class="modal-content">
          <img src="img/products/product2.jpg" alt="Product 2" />
          <div class="product-content">
            <h3>Paket 2</h3>
            <p>sdkhsdfhkufheekljwifulskd.</p>
            <div class="product-stars">
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
              <i data-feather="star" class="star-full"></i>
            </div>
            <div class="product-price">
              IDR 250.000
              <span
                style="
                  text-decoration: line-through;
                  font-weight: lighter;
                  font-size: 1rem;
                "
                >IDR 300.000</span
              >
              <a href="#"
                ><i data-feather="shopping-cart"></i><span>add to cart</span></a
              >
            </div>
          </div>
        </div>
      </div>-->
    </div>
    <!--Modal Box Item Detail end-->
    <!--Feather Icons-->
    <script>
      feather.replace();
    </script>
    <!--My Javascript-->
    <script src="js/script.js"></script>
  </body>
</html>
