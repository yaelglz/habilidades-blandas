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
      <video controls>
        <source src="../../src/assets/Video1.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="divider">
      <img src="../assets/Tips.png" alt="">
    </div>
    <div class="video-container">
      <video controls>
        <source src="../../src/assets/Video2.mp4" type="video/mp4" />
      </video>
    </div>
  </div>
  <div>
    <div class="info1">
      <img src="../assets/Info1.jpeg" width="900" />
    </div>
    <div class="info2">
      <img src="../assets/Info2.jpeg" />
    </div>
  </div>
  <div class="container-persuasion">
    <h1>Persuasión (¿Como conquistar consumidores?)</h1>
    <h2>Estos seis principios van a influir de forma fundamental para la aceptación de una solicitud, y obtendremos
      grandes
      beneficios si se añade alguno de estos a nuestra estrategia de marketing.</h2>
    <div class="info-puntos">
      <div>
        <h3>01.- RECIPROCIDAD </h3>
        <p>Si una solicitud viene precedida de un regalo inesperado tiene mayor potencial de convencer a los potenciales
          clientes. El regalo les hará sentir la importancia de devolver el favor, o ser recíproco.</p>
        <img src="../assets/reciprocidad.png" alt="">
      </div>
      <div>
        <h3>02.- COMPROMISO Y COHERENCIA </h3>
        <p>Si consigues que tus clientes se comprometan a algo y por lo general sin costo, como por ejemplo descargar un
          reporte, estaras aumentando la posibilidad de que se conviertan en tus clientes.</p>
        <img src="../assets/compromiso.png" alt="">
      </div>
    </div>
    <div class="info-puntos">
      <div>
        <h3>03.- PRUEBA SOCIAL </h3>
        <p>Cuendo estamos inseguros en la toma de una decisión, observamos qué hacen los demás para buscar "pruebas" o
          "evidencia" social de que algo funciona.</p>
        <img src="../assets/prueba.png" alt="">
      </div>
      <div>
        <h3>04.- SIMPATÍA / GUSTABILIDAD </h3>
        <p>La gente prefiere decir que si a los que les caen bien. Habla el mismo lenguaje que tu cliente, así, ellos se
          sentirán representados por ti. Tambien influye vestirse de manera alineada con ellos.</p>
        <img src="../assets/simpatia.png" alt="">
      </div>
    </div>
    <div class="info-puntos">
      <div>
        <h3>05.- AUTORIDAD </h3>
        <p>La gente seguirá a los expertos por su credibilidad. Busca que un individuo u organización respetada en tu
          nicho avale tu producto, servicio o empresa.</p>
        <img src="../assets/credibilidad.png" alt="">
      </div>
      <div>
        <h3>06.- ESCASEZ </h3>
        <p>Cuento menos disponible esté algo, más lo queremos. No es suficiente sólo decirle a la gente los beneficios
          que obtendrán, también necesitas resaltar lo que es único y lo que pueden perder.</p>
        <img src="../assets/escasez.png" alt="">
      </div>
    </div>
  </div>
  <div class="container-cerebro">
    <div class="info-cerebro">
      <h1>FUNCIONES DEL CEREBRO </h1>
      <dl>
        <dt>
          <h3>ATENCIÓN</h3>
        </dt>
        <dd>Capacidad para mantener un estado de alerta suficiente para concentrarse en diversas situaciones.</dd>
        <ul>
          <li>Sea en una tarea en particular.</li>
          <li>Sea en dos tareas diferentes.</li>
          <li>Durante un período prolongado de tiempo.</li>
        </ul>

        <dt>
          <h3>LENGUAJE ORAL</h3>
        </dt>

        <dt>
          <h3>FUNCIONES EJECUTIVAS</h3>
        </dt>
        <dd>Capacidad para adaptarse a nuevas o complejas situaciones.</dd>
        <ul>
          <li>Organización y planificación.</li>
          <li>Abstracción: Comprender la naturaleza y las relaciones entre las cosas y las ideas.</li>
          <li>Juicio: Evaluar los hechos y responder en consecuencia con empatía y sentido común.</li>
          <li>Autocontrol: Control de las emociones y acciones según las situaciones.</li>
          <li>Flexibilidad: Capacidad de pasar fácilmente de una idea a otra.</li>
        </ul>

        <dt>
          <h3>MOTRICIDAD</h3>
        </dt>
        <dd>Control del movimiento del cuerpo.</dd>

        <dt>
          <h3>PERCEPCIÓN</h3>
        </dt>
        <dd>De la forma, del color, de la distancia de los objetos.</dd>

        <dt>
          <h3>ORIENTACIÓN</h3>
        </dt>
        <dd>Percepción de las relaciones entre los objetos en el espacio.</dd>

        <dt>
          <h3>LENGUAJE ESCRITO</h3>
        </dt>

        <dt>
          <h3>MEMORIA</h3>
        </dt>
        <ul>
          <li>Memoria a corto plazo: Permite retener una cantidad de información limitada durante un breve período
            (algunos
            segundos).</li>
          <li>Memoria a largo plazo: Memoria de hechos, conocimientos y habilidades acumulados durante años, incluidas
            experiencias personales, conocimientos generales asociados al lenguaje y conceptos.</li>
        </ul>
      </dl>

    </div>
    <div class="imagen-cerebro">
      <!-- Imagen Cerebro-->
      <img src="../assets/funcioncerebral.png">
    </div>
  </div>
</template>



<script setup>
// import ImageSlider from './ImageSlider.vue'; // Ajusta la ruta según tu estructura de archivos
import { ref } from "vue";
const mensaje = "¿Qué son las habilidades blandas?";
</script>
