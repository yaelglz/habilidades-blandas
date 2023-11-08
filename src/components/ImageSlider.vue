<!-- <template>
    <div class="image-slider">
        <button @click="prevImage">Anterior</button>
        <div class="image-container">
            <img :src="currentImage" :alt="currentImageAlt" />
        </div>
        <button @click="nextImage">Siguiente</button>
    </div>
</template>
  
<script setup>
import { ref } from "vue";
const images = [
    { src: "../assets/Info1.jpeg", alt: "Imagen 1" },
    { src: "../assets/Info2.jpeg", alt: "Imagen 2" },
    { src: "../assets/Info3.jpeg", alt: "Imagen 3" },
    { src: "../assets/Info4.jpeg", alt: "Imagen 4" },
    // Agrega más imágenes aquí
];

let currentIndex = 0;

const currentImage = ref(images[currentIndex].src);
const currentImageAlt = ref(images[currentIndex].alt);

const prevImage = () => {
    if (currentIndex > 0) {
        currentIndex--;
        currentImage.value = images[currentIndex].src;
        currentImageAlt.value = images[currentIndex].alt;
    }
};

const nextImage = () => {
    if (currentIndex < images.length - 1) {
        currentIndex++;
        currentImage.value = images[currentIndex].src;
        currentImageAlt.value = images[currentIndex].alt;
    }
};
</script> -->
  
