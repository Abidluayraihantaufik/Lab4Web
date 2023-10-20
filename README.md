# Lab4Web
Pertanyaan dan Tugas
1. Tambahkan Layout untuk menu About
=> buat single layout yang berisi deskripsi, portfolio, dll.
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <header></header>
    <section class="about">
      <h2>Deskripsi Diri</h2>
      <p>
        Perkenalkan Nama saya Abid Luay Raihan Taufik, Saya lahir di Bekasi pada
        hari Selasa tanggal 30 Maret 2004. Saya anak ke-2 dari 3 bersaudara.
        Kini saya sedang berkuliah di salah satu Universitas di Cikarang, yaitu
        Universitas Pelita Bangsa.
      </p>
    </section>
    <section class="portfolio">
      <h2>Portofolio</h2>
      <ul>
        <li><a href="https://contohlinkportofolio1.com">Portofolio 1</a></li>
        <li><a href="https://contohlinkportofolio2.com">Portofolio 2</a></li>
        <!-- Tambahkan portofolio lainnya sesuai kebutuhan -->
      </ul>
    </section>
  </body>
</html>
```
![img](Gambar/Menu%20about.PNG)
3. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <header>
      <h1>Contact Us</h1>
    </header>
    <section class="contact-form">
      <form action="submit_form.php" method="post">
        <div class="form-group">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required />
        </div>
        <div class="form-group">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required />
        </div>
        <div class="form-group">
          <label for="message">Message:</label>
          <textarea id="message" name="message" rows="4" required></textarea>
        </div>
        <div class="form-group">
          <button type="submit">Submit</button>
        </div>
      </form>
    </section>
  </body>
</html>
```
![img]
