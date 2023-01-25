<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  
    <section class="inicio">
      <section id="hero">
        <div class="hero_content">
          <h1 class="hero_content--title">Tienda isa</h1>
          <p class="hero_content--para">Dile adiós al “no tengo que ponerme", con nuestro extenso catálago tu
            armario no podrá estar más lleno</p>
          <a href="#">Catálogo</a>
        </div>
      </section>
      <section id="eslogan">
        <h1>Elige tu ropa, vive tu estilo</h1>
      </section>
      <section id="carrusel">
        <h1 class="carrusel-title">Artículos destacados</h1>
        <div class="container">
          <input type="radio" name="slider" id="item-1">
          <input type="radio" name="slider" id="item-2">
          <input type="radio" name="slider" id="item-3">
          <input type="radio" name="slider" id="item-4" checked>
          <input type="radio" name="slider" id="item-5">
          <div class="cards">
            <label class="card" for="item-1" id="it-1">
              <img src="../assets/imgs/ropa1.png" alt="prenda de ropa">
            </label>
            <label class="card" for="item-2" id="it-2">
              <img src="../assets/imgs/ropa2.png" alt="prenda de ropa">
            </label>
            <label class="card" for="item-3" id="it-3">
              <img src="../assets/imgs/ropa3.png" alt="prenda de ropa">
            </label>
            <label class="card" for="item-4" id="it-4">
              <img src="../assets/imgs/ropa4.png" alt="prenda de ropa">
            </label>
            <label class="card" for="item-5" id="it-5">
              <img src="../assets/imgs/ropa5.png" alt="prenda de ropa">
            </label>
          </div>
        </div>
      </section>
      <section id="siguenos">
        <h1>Síguenos</h1>
        <div class="content">
          <div class="../assets/imgs-siguenos">
            <img alt="Tienda de ropa" src="../assets/imgs/chica1.jpg">
            <img alt="Tienda de ropa" src="../assets/imgs/chica2.jpg">
            <img alt="Tienda de ropa" src="../assets/imgs/chico1.jpg">
          </div>
          <div class="informacion">
            <p>En tienda Isa trabajamos duro para satisfacer al cliente, síguenos en nuestras redes sociales
              para
              mantenerte al día de las ofertas y novedades</p>
            <div class="redes-sociales">
              <i class="fa-brands fa-youtube"></i>
              <i class="fa-brands fa-instagram"></i>
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-facebook"></i>
            </div>
          </div>
        </div>
      </section>
      <section id="recibe-ofertas">
        <h1>Recibe ofertas</h1>
        <form>
          <input type="email" id="correo" placeholder="Correo electrónico">
          <input type="submit" value="Subscribirme" id="subscribe">
        </form>
      </section>
    </section>
  
</template>
