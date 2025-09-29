<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Kadir'i Rahmetle Anıyoruz</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f6f6f6;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #444;
      color: #fff;
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      margin-bottom: 10px;
      font-size: 28px;
    }

    header p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 16px;
      line-height: 1.6;
    }

    .gallery {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
      gap: 40px;
    }

    .photo-card {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
      max-width: 700px;
      width: 100%;
      overflow: hidden;
    }

    .photo-card img {
      width: 100%;
      height: auto;
      display: block;
    }

    .caption {
      padding: 15px 20px;
      font-size: 15px;
      line-height: 1.6;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 13px;
      color: #888;
    }

    footer .author {
      margin-top: 10px;
      font-style: italic;
      color: #aaa;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 24px;
      }

      header p {
        font-size: 14px;
      }

      .caption {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Yanındayım, Hep Yanında Olacağım</h1>
    <p>
      Hayat, zaman zaman bizi en sevdiklerimizden ayırarak derin izler bırakır. Böyle zamanlarda kelimeler yetersiz kalır, ama yanında olduğumu bilmeni istiyorum Aleyna. Kadir’in gidişi hepimizi derinden etkiledi, ama senin hissettiklerin, yaşadıkların elbette çok daha derin. O, sadece kuzenin değil; bir dostun, sırdaşın, çocukluğunun bir parçasıydı. <br><br>
      Üç ay geçti ama acı hâlâ taze. Bil ki bu süreçte elini hiç bırakmayacağım. Gözlerin dolduğunda yanında ben olacağım, sustuğunda sessizliğini dinleyeceğim. Bu küçük sayfa, onunla geçirdiğiniz o güzel anıları hatırlatmak ve onu rahmetle anmak için burada. Kadir’in ışığı sönmedi; sadece farklı bir yerde parlamaya devam ediyor.
    </p>
  </header>

  <section class="gallery">

    <!-- Fotoğraf 1 -->
    <div class="photo-card">
      <img src="fotto1.jpg" alt="Aleyna ve Kadir">
      <div class="caption">
        "Zaman dursa, sadece o ana dönsek... Gülüşleriniz hafızamızda kaldı, kalbimizde hep yaşayacak. Kadir, seninle geçirilen her an bir hazineymiş."
      </div>
    </div>

    <!-- Fotoğraf 2 -->
    <div class="photo-card">
      <img src="fotto2.jpg" alt="Aleyna, Kadir ve diğer kuzen">
      <div class="caption">
        "Bazen bir kare, binlerce anı saklar içinde. Bu fotoğraf, sevgiyle kurulmuş bir bağın sessiz tanığı. Kadir, sen bu ailenin hiç unutulmayacak parçasısın."
      </div>
    </div>

    <!-- Fotoğraf 3 -->
    <div class="photo-card">
      <img src="fotto3.jpg" alt="Bayram ya da özel bir gün">
      <div class="caption">
        "O gün yüzünüzdeki gülümsemeler ne güzeldi... Şimdi o gülüşlerin ardında bir özlem saklı. Ama bil ki seni hiç unutmadık Kadir, hatıran hep bizimle."
      </div>
    </div>

    <!-- Fotoğraf 4 (Mezar) -->
    <div class="photo-card">
      <img src="fotto4.jpg" alt="Kadir'in Mezarı">
      <div class="caption">
        "Toprağın altında değil, dualarımızdasın. Mekânın cennet olsun Kadir... Seni sevenler asla unutmuyor, her zaman rahmetle anıyor."
      </div>
    </div>

  </section>

  <footer>
    © 2025 | Kadir'in Hatırasına
    <div class="author">
      Hazırlayan: Yasin Şahin
    </div>
  </footer>

</body>
</html>
