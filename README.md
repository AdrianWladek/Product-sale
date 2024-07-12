# Product-sale
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="CSS/styles.css">
  <link rel="stylesheet" href="CSS/responsive.css">
  
  <title>Frontend Mentor | Product preview card component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>
<body>
  <main class="main__container">

    <div class="main__product">

      <img src="images/image-product-mobile.jpg" class="product__img" alt="Presentacion de producto">
      <img src="images/image-product-desktop.jpg" class="product__img-2" alt="Presentacion de producto">

      <section class="section__product">

        <h1 class="product__title product--text">PERFUME</h1>

        <h2 class="product__subtitle product--text">Gabrielle Essence Eau De Parfum</h2>
  
        <p class="product__paragraph product--text">A floral, solar and voluptuous interpretation composed by Olivier Polge, 
          Perfumer-Creator for the House of CHANEL.
        </p>
  
        <div class="product__prizes">

          <p class="product__prize">$149.99</p>
          <p class="product__prize--original"><del>$169.99</del></p>

        </div>

        <a href="#" class="cta__button">
          <img src="images/icon-cart.svg" alt="">
          Add to Cart
        </a>

      </section>
     
    </div> 
    
  </main>
  
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Adrian Madero Arreola</a>.
  </div>
  
</body>
</html>
