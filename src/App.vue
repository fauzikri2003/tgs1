<template>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
  
    <header>
      <h1>Fauzikri Ghifari</h1>
      <h2>Teknik Informatika</h2>
      <h3>Portofolio</h3>
    </header>
  
    <nav>
      <a href="#about">Tentang</a>
      <a href="#hobby">Hobi</a>
      <a href="#contact">Kontak</a>
    </nav>
  
    <section id="about" class="about-me">
      <h2>Tentang Saya</h2>
      <p>Saya adalah seorang mahasiswa aktif di Universitas Islam Riau.</p>
      <div class="gallery">
        <img src="./assets/fauzikri.jpg" alt="Fauzikri">
      </div>
    </section>
  
    <section id="hobby" class="hobby">
      <h2>My Hobbies</h2>
      <ul>
        <li><a href="#">Bermain Game</a></li>
        <li><a href="#">Menggambar</a></li>
        <li><a href="#">Membaca Buku</a></li>
      </ul>
    </section>
  
    <section id="contact" class="contact">
      <h2>Kontak</h2>
      <p>Anda bisa menghubungi saya melalui email di <a href="mailto:fauzikri2003@gmail.com">fauzikri2003@gmail.com</a>.</p>
      <div class="social-icons">
        <a href="https://www.instagram.com/stmw_dragon_/?igsh=MTNobGp3eGN1OWd6dQ%3D%3D" target="_blank"><i class="fa-brands fa-instagram"></i></a>
      </div>
    </section>
  
    <section class="testimonials">
      <h2>Address</h2>
      <p>Tempat Tanggal Lahir</p>
      <p>Pekanbaru, 15-8-2003</p>
    </section>
  
    <footer>
      <p>Teknik Informatika 2024 | Fauzikri Ghifari</p>
    </footer>
  </template>
  
  <style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
  }
  
  nav {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px;
    margin: 5px;
  }
  
  section {
    padding: 20px;
  }
  
  .about-me,
  .hobby,
  .contact {
    text-align: center;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin-bottom: 20px;
  }
  
  .hobby ul {
    list-style-type: none;
  }
  
  .hobby li {
    margin-bottom: 10px;
  }
  
  .gallery {
    text-align: center;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .gallery img {
    width: 200px;
    margin: 10px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  .testimonials {
    font-style: italic;
    margin-bottom: 10px;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 74%;
  }
  
  .social-icons {
    margin-top: 10px;
  }
  
  .social-icons a {
    display: inline-block;
    width: 30px;
    height: 30px;
    background-color: #000;
    color: #fff;
    border-radius: 50%;
    line-height: 30px;
    text-align: center;
    margin: 0 5px;
    text-decoration: none;
  }
</style>
