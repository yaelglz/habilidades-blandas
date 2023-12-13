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
  <div> <!--Infografias-->
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
        <dt class="rojo">
          <h3>ATENCIÓN</h3>
        </dt>
        <dd>Capacidad para mantener un estado de alerta suficiente para concentrarse en diversas situaciones.</dd>
        <ul>
          <li>Sea en una tarea en particular.</li>
          <li>Sea en dos tareas diferentes.</li>
          <li>Durante un período prolongado de tiempo.</li>
        </ul>

        <dt class="amarillo">
          <h3>LENGUAJE ORAL</h3>
        </dt>

        <dt class="verde">
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

        <dt class="morado">
          <h3>MOTRICIDAD</h3>
        </dt>
        <dd>Control del movimiento del cuerpo.</dd>

        <dt class="azul">
          <h3>PERCEPCIÓN</h3>
        </dt>
        <dd>De la forma, del color, de la distancia de los objetos.</dd>

        <dt class="azul">
          <h3>ORIENTACIÓN</h3>
        </dt>
        <dd>Percepción de las relaciones entre los objetos en el espacio.</dd>

        <dt class="amarillo">
          <h3>LENGUAJE ESCRITO</h3>
        </dt>

        <dt class="naranja">
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
  <br>
  <h1 style="font-size: 3em;">DIFERENCIA ENTRE LIDERAZGO Y COACHING</h1>
  <h1>LIDERAZGO</h1>
  <div class="container-liderazgo">
    <div class="info-liderazgo">
      <div class="container-caracte">
        <h2>Definición</h2>
        <p> Conjunto de habilidades directivas que tiene un individuo para influir en otros, cuando esta persona establece
          sus principios éticos, toma las decisiones correctas y actúa con bien, podemos decir que da ejemplo a otros
          sobre
          etica y sirve de inspiración.</p>
        <h2>Importancia</h2>
        <p>Los lideres tienen responsabilidades éticas porque poseen una posición especial en la que existe una mayor
          oportunidad de influir en los demás y en los resultados. </p>
      </div>
      <div class="container-caracte">
        <img src="../assets/liderazgo.png">
        <h3>Características</h3>
        <ul>
          <li>El líder tiene estándares éticos más elevados.</li>
          <li>Sus conductas moldean el comportamiento de los demás.</li>
          <li>Los valores del líder influyen en la cultura de la organización.</li>
          <li>Marcan la pauta, desarrollan la visión y los valores de los otros.</li>
        </ul>
      </div>
    </div>
    <div class="info-liderazgo">
      <div class="container-caracte">
        <img src="../assets/jefevslider.jpg" class="imagen-destacada">
      </div>
      <div class="container-caracte">
        <h2>Buen Líder</h2>
        <p>Persona que conduce hacia resultados éticos y no alguien que simplemente es bueno para liderar.</p>
        <ul>
          <li>Transformador</li>
          <li>Actitud de Servicio</li>
          <li>Autentico</li>
          <li>Con Valores</li>
          <li>Honesto</li>
          <li>Preocupado por la comunidad</li>
        </ul>
        <h2>Principios del liderazgo</h2>
        <ul>
          <li>Orientación humana</li>
          <li>Orientación hacia la responsabilidad y la sostenibilidad</li>
          <li>Orientación a la justicia</li>
          <li>Orientación de la moderación entre las distintas partes interesadas</li>
        </ul>
      </div>
    </div>
  </div>
  <h1>COACHING</h1>
  <div class="container-coaching">
    <div class="container-caracte">
      <h1>Coaching es:</h1>
      <ul>
        <li>Acompañar, guiar y facilitar.</li>
        <li>Un proceso para aprender y desarrollarse.</li>
        <li>Interacción para lograr compromisos mutuos.</li>
        <li>Proceso orientado a la acción y focalizado en la meta.</li>
      </ul>
    </div>
    <div>
      <img src="../assets/coaching.png" alt="">
    </div>
    <div class="container-caracte">
      <h1>Coaching no es:</h1>
      <ul>
        <li>Terapia</li>
        <li>Consultoria</li>
        <li>Supervisión</li>
        <li>Mentoring</li>
      </ul>
    </div>
  </div>
  <Timeline />
</template>



<script setup>
import Timeline from './Timeline.vue'
// import ImageSlider from './ImageSlider.vue'; // Ajusta la ruta según tu estructura de archivos
const mensaje = "¿Qué son las habilidades blandas?";
</script>
