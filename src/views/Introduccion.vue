<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        .bg-amarillo.p-4.mb-4
          span En esta unidad se analizarán las habilidades gerenciales esenciales para un directivo de empresas tecnológicas, enfocándose en el liderazgo adaptativo y en cómo afrontar los cambios rápidos que trae la transformación digital en el mundo de los negocios. Analizarán variables como datos, mercado y clientes para apoyar una toma de decisiones en tiempo real que impulse la rentabilidad del negocio. Además, al comprender el Management Digital, identificarás distintas tecnologías de la información clave para las actividades empresariales, incluyendo software de gestión, análisis de datos, computación en la nube y el Internet de las Cosas (IoT). Esto te permitirá evaluar los alcances y la preparación de un proyecto de Inteligencia de Negocios (BI). 
        span Este desarrollo temático, le permitirá al estudiante acercarse a la comprensión de los conceptos y principios de la inteligencia de negocios y explicar su relevancia en el contexto empresarial actual.
      .col-xl-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-1.png', alt='Texto que describa la imagen')
    .row.mb-4
      .d-flex.align-items-center
        div.d-flex.align-items-center.bg-azul.px-3.py-4
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-2.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 Esta es una gran oportunidad formativa que le permitirá desarrollar habilidades académicas y de aplicación tanto en ámbito tecnológico como en el mundo de los negocios. <strong>Bienvenidos.</strong>
</template>

<script>
import BannerInterno from '../components/plantilla/BannerInterno'
import Muestras from '../components/muestras/Muestras.vue'

export default {
  name: 'Introduccion',
  components: {
    BannerInterno,
    Muestras,
  },
  data: () => ({
    globalData: global,
  }),
}
</script>

<style lang="sass"></style>
