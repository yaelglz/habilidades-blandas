<script setup>
import Inicio from './components/Inicio.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div>
    <header>
      <div class="banner-container">
        <img alt="banner" class="banner" src="./assets/s1.jpg" />
        <div class="texto-en-banner">
          <p>Habilidades Blandas</p>
        </div>
      </div>
    </header>
    <main>
      <!-- Contenido principal aquí -->
    </main>
    <div class="mensaje">
      <Inicio />
    </div>
    <Footer />
  </div>
</template>


