<template>
    <div class="timeline">
        <div class="timeline-line"></div>
        <div v-for="(event, index) in timelineData" :key="index" class="event" :style="{ left: eventStyles[index].left }">
            <div class="event-info" @click.stop="toggleEventDetails(index)">
                <p class="year">{{ event.year }}</p>
                <p class="description">{{ event.description }}</p>
            </div>
            <div v-if="selectedEvent === index" class="event-details">
                <span class="close-button" @click.stop="closeEventDetails">×</span>
                <p class="year">{{ event.year }}</p>
                <p class="description">{{ event.fullDescription }}</p>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            timelineData: [
                {
                    year: 'FASE 1',
                    description: 'Diseño del Acuerdo de Coaching',
                    fullDescription: 'La primera fase en el coaching es crucial, ya que sienta las bases para el éxito de todo el proceso. Esta etapa se centra en la selección del coach adecuado y la construcción de una relación de confianza.'
                },
                {
                    year: 'FASE 2',
                    description: 'Evaluación y Diagnóstico',
                    fullDescription: 'La segunda fase del proceso de coaching se enfoca en evaluar y diagnosticar las áreas de mejora y oportunidades de crecimiento del coachee. Establece objetivos claros y específicos que guiarán el proceso.'
                },
                {
                    year: 'FASE 3',
                    description: 'Establecimiento de Objetivos y Plan de Acción',
                    fullDescription: 'Una vez evaluadas las necesidades y objetivos del coachee, se procede a la tercera fase del proceso de coaching, que consiste en establecer objetivos claros y diseñar un plan de acción para alcanzarlos. Esta etapa es crucial para garantizar el enfoque y la dirección adecuada en el proceso.'
                },
                {
                    year: 'FASE 4',
                    description: 'Desarrollo de Habilidades y Competencias',
                    fullDescription: 'En la cuarta fase del proceso de coaching, se aborda el desarrollo de habilidades y competencias del coachee, utilizando diversas técnicas de coaching para impulsar el crecimiento personal y profesional. Además, se monitorea el progreso y se realizan ajustes en función de los resultados obtenidos.'
                },
                {
                    year: 'FASE 5',
                    description: 'Seguimiento y Evaluación del Progreso',
                    fullDescription: 'Es fundamental medir los resultados y ajustar el plan de acción según sea necesario para garantizar el éxito en el desarrollo personal y profesional del coachee.'
                },
                {
                    year: 'FASE 6',
                    description: 'Finalización y Cierre del Proceso de Coaching',
                    fullDescription: 'Consiste en la finalización y cierre del proceso, donde se realiza una evaluación final y reflexión sobre los logros obtenidos y se planifica el mantenimiento y seguimiento a largo plazo para asegurar la continuidad del desarrollo y crecimiento del coachee.'
                }
            ],
            selectedEvent: null
        };
    },
    computed: {
        eventStyles() {
            return this.timelineData.map((event, index) => ({
                left: `${(index + 1) * 15}%`
            }));
        }
    },
    methods: {
        toggleEventDetails(index) {
            this.selectedEvent = this.selectedEvent === index ? null : index;
        },
        closeEventDetails() {
            this.selectedEvent = null;
        }
    }
};
</script>
  
<style scoped>
.event:hover .event-details,
.event .event-info:hover+.event-details {
    left: 0;
    /* Cambia el valor a 0 cuando se hace clic o se pasa el ratón sobre la tarjeta de información */
}

.timeline {
    position: relative;
    width: 100%;
    margin: 100px auto;
}

.timeline-line {
    position: absolute;
    top: 50%;
    left: 0;
    width: 100%;
    height: 4px;
    background-color: #ffffff;
    transform: translateY(-50%);
}

.event {
    position: absolute;
    width: 20px;
    height: 20px;
    background-color: #ffffff;
    border-radius: 50%;
    cursor: pointer;
    /* Ajusta estos valores según sea necesario */
    top: 50%;
    /* Puedes ajustar la posición vertical */
    left: 50%;
    /* Puedes ajustar la posición horizontal */
    transform: translate(-50%, -50%);
    /* Centra el elemento correctamente */
}


.event-info {
    position: absolute;
    top: -80px;
    left: 50%;
    /* Ajusta la posición horizontal para centrar la tarjeta sobre el evento */
    transform: translateX(-50%);
    /* Centra la tarjeta correctamente */
    background-color: #ffffff;
    padding: 10px;
    border: 1px solid #000;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    opacity: 0;
    transition: opacity 0.3s;
    cursor: pointer;
    width: 200px;
    z-index: 1;
    /* Asegura que la tarjeta esté por encima del círculo */
}

.event:hover .event-info {
    opacity: 1;
}

.event-details {
    position: absolute;
    top: -120px;
    left: -200%;
    /* Ajusta este valor según tus necesidades iniciales */
    background-color: #ffffff;
    padding: 20px;
    border: 1px solid #f2be7e;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: left;
    opacity: 1;
    transition: left 0.3s, width 0.3s;
    /* Mantén la transición de la posición izquierda y agrega la transición del ancho */
    width: 350px;
    /* Ajusta el ancho según tu preferencia */
    z-index: 1;
    /* Asegura que la tarjeta esté por encima del círculo */
}

.event:hover .event-details {
    left: -120%;
}

.year {
    font-weight: bold;
}

.description {
    color: #555;
    font-style: italic;
}

.close-button {
    cursor: pointer;
    font-size: 30px;
    position: absolute;
    top: 10px;
    right: 10px;
}</style>