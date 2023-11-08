<template>
  <div class="container">
    <div class="intro">
      <h1 class="burbuja">{{ mensaje }}</h1>
      <p>
        Las habilidades blandas (o soft skills) son rasgos de carácter y
        competencias interpersonales que caracterizan la forma de interactuar y
        relacionarse de una persona con otra.
      </p>
    </div>
    <img src="../assets/SoftS.png" class="tops" />
  </div>
  <div class="vid-sec">
    <div class="video">
      <iframe width="100%" height="500" src="https://www.youtube.com/embed/yLUP01mHQc8?si=Yy6DMFOefrtBhNNP"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen></iframe>
    </div>
    <div class="npc">
      <img src="../assets/NPC1.png" alt="" width="350" />
    </div>
  </div>
  <div class="container-vid">
    <div class="video-container">
      <video controls style="width: 70%; height: auto;">
        <source src="../../src/assets/Video1.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="divider">
      <img src="../assets/Tips.png" alt="" style="width: 500px; height: auto; margin: 0 auto; display: block;">
    </div>
    <div class="video-container">
      <video controls style="width: 70%; height: auto;">
        <source src="../../src/assets/Video2.mp4" type="video/mp4" />
      </video>
    </div>
  </div>
  <div>
    <image-slider></image-slider>
  </div>
</template>



<script setup>
// import ImageSlider from './ImageSlider.vue'; // Ajusta la ruta según tu estructura de archivos
import { ref } from "vue";
const videoS = ref("../assets/Video1.mp4");
const mensaje = "¿Qué son las habilidades blandas?";
</script>
