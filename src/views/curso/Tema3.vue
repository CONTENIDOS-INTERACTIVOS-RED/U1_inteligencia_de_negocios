<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Ciclo de vida de un sistema de inteligencia de negocios'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.mb-5.mx-0
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-38.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8.d-flex.align-items-center.bg-rosa.p-4(data-aos="fade-left")
        p.mb-0(data-aos="fade-up") El ciclo de vida de un sistema de inteligencia de negocios incluye la identificación de necesidades, el diseño de la arquitectura, la integración de datos, la implementación de herramientas y la mejora continua. Estas etapas aseguran que el sistema responda a las necesidades actuales del negocio y evolucione para cumplir con futuras demandas.

    #t_3_1.titulo-segundo
      div.d-flex
        span.me-3 3.1  
        h2 Fase de planificación y definición de requisitos en un sistema de IN

    p.mb-4 La fase de planificación y definición de requisitos es el primer y uno de los pasos más críticos en el ciclo de vida de un sistema de inteligencia de negocios (IN). Esta etapa establece el propósito, alcance y objetivos del sistema, asegurando que esté alineado con las metas estratégicas y operativas de la organización. Una planificación adecuada en esta fase maximiza el valor de los datos, optimiza los procesos de toma de decisiones y reduce los riesgos asociados al desarrollo e implementación del sistema.

    .row.bg-amarillo.bg-full-width.py-4.mb-5
      div.px-5.pb-md-3.py-4.d-flex
        .col-12.col-xl-7.col-xxl-8.d-flex.pe-4.pe-xl-5.align-items-center.flex-column(data-aos="fade-right")
          h2.mb-4.pb-2.me-auto Análisis de datos en inteligencia de negocios (IN): principales herramientas y beneficiosFase de planificación y definición de requisitos en un sistema de inteligencia de negocios (IN)
          p.mb-5 En el documento Fase de planificación y definición de requisitos en un sistema de inteligencia de negocios (IN)  se describe el primer y más crítico paso en el ciclo de vida de estos sistemas. Se detalla cómo esta etapa establece el propósito, alcance y objetivos del sistema, garantizando su alineación con las metas estratégicas de la organización. Lo invitamos a consultar el documento para ampliar esta información y conocer cómo una planificación adecuada optimiza la toma de decisiones y minimiza riesgos.
          a.d-flex.me-auto.bg-white.box-shadow.cursor-pointer(data-aos="zoom-in" :href="obtenerLink('/downloads/Anexo_Fase de planificación y definición de requisitos en un sistema de inteligencia de negocios (IN) .pdf')" target="_blank")
            img.h-100(style="width: 48px" src='@/assets/componentes/pdf-icon-square.svg', alt='Texto que describa la imagen')
            p.text-small.fs-14px.my-auto.px-2 <strong>Anexo.</strong> Fase de planificación y definición de requisitos en un sistema de inteligencia de negocios (IN)  
             
        .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
          img.h-100(src='@/assets/curso/unidad/img-39.png', alt='Texto que describa la imagen')

    #t_3_2.titulo-segundo
      div.d-flex
        span.me-3 3.2  
        h2 Desarrollo e implementación del sistema de inteligencia de negocios (IN) 

    p.mb-4 La fase de desarrollo e implementación de un sistema de inteligencia de negocios (IN) es crucial para garantizar que las organizaciones puedan procesar, analizar y visualizar datos de manera efectiva. En esta etapa se construyen los componentes necesarios, se integran los datos provenientes de diversas fuentes y se configuran las herramientas de análisis y visualización que permitirán la toma de decisiones estratégicas.

    .row.position-relative.mb-4.py-4.bg-azul-1.bg-full-width
      div.px-4.px-md-5.py-md-3
        SlyderA(tipo="b").bg-white
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0(data-aos="zoom-in-right")
              p.text-bold Infraestructura de datos
              p Se construyen y organizan componentes como bodegas de datos (data warehouses), bases de datos y almacenes de datos para centralizar la información proveniente de sistemas transaccionales, archivos y aplicaciones externas. Esto asegura un almacenamiento eficiente y estructurado.
            .d-none.d-lg-block.col-md-6.col-lg-4(data-aos="zoom-in-left")
              figure
                img(src='@/assets/curso/unidad/img-40.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold ETL (Extracción, Transformación y Carga)
              p Proceso fundamental para la recolección de datos de diversas fuentes, su limpieza y transformación en un formato adecuado, y su posterior carga en la infraestructura central. Herramientas como Talend y Apache Nifi son ampliamente utilizadas.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-41.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold ETL (Extracción, Transformación y Carga)
              p Proceso fundamental para la recolección de datos de diversas fuentes, su limpieza y transformación en un formato adecuado, y su posterior carga en la infraestructura central. Herramientas como Talend y Apache Nifi son ampliamente utilizadas.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-42.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Plataformas de análisis y visualización
              p Herramientas como Power BI, Tableau y Qlik se configuran para crear dashboards interactivos, gráficos y reportes comprensibles para los usuarios finales, facilitando la interpretación de los datos.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-43.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Integración con sistemas existentes
              p El sistema de IN se conecta con sistemas previos como CRM, ERP y bases de datos operativas, creando un flujo continuo de datos que permite análisis en tiempo real y consistencia en la información utilizada.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-44.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Calidad de los datos 
              p Se asegura que los datos cargados en el sistema sean correctos, completos, consistentes y oportunos. Esto incluye procesos de limpieza, validación y monitoreo para garantizar la confiabilidad de los insights generados.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-44.png', alt='Texto que describa la imagen')

    .row.position-relative.mb-0.py-4.bg-fondo-1.bg-full-width
      div.px-4.px-md-5.py-md-3

        h2 Ejemplos de aplicación
        p.mb-0 A continuación, se presentan casos destacados donde los sistemas de inteligencia de negocios han sido implementados con éxito en diferentes sectores:
    
        .row.mb-0
          .col-10.col-md-6.col-lg-4.mb-4.mx-auto(data-aos="fade-right")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-45.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Sector financiero
                p.text-small.px-4.text-center.pb-2 Bancos como JP Morgan utilizan sistemas de inteligencia de negocios para analizar transacciones, predecir comportamientos de clientes y detectar patrones de fraude.
          .col-10.col-md-6.col-lg-4.mb-4.mx-auto(data-aos="fade-up")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-46.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Retail
                p.text-small.px-4.text-center.pb-2 Walmart integra datos de ventas, inventarios y proveedores para optimizar su cadena de suministro y predecir demandas de productos.
          .col-10.col-md-6.col-lg-4.mb-4.mx-auto(data-aos="fade-left")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-47.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Salud
                p.text-small.px-4.text-center.pb-2 Clínicas y hospitales analizan datos médicos para gestionar recursos, detectar enfermedades en etapas tempranas y mejorar la atención al paciente.

    h2 Beneficios
    p.mb-4 Estos son los principales beneficios que las organizaciones pueden obtener al implementar sistemas de inteligencia de negocios:
    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        lineaTiempoD.large
          p(numero="1" titulo="Mejora en la toma de decisiones") Proporciona acceso a datos procesados y analizados para tomar decisiones informadas basadas en hechos.
          p(numero="2" titulo="Optimización de recursos") Identifica áreas ineficientes, mejora la productividad y reduce costos operativos mediante análisis de datos históricos.
          p(numero="3" titulo="Competitividad") Facilita la adaptación rápida a cambios del mercado y otorga una ventaja competitiva.
          p(numero="4" titulo="Visibilidad en tiempo real") Ofrece a los directivos una visión clara del rendimiento operativo a través de dashboards y reportes interactivos.
      .col-4.d-none.d-xl-block(data-aos="fade-left")
        img.h-100(src='@/assets/curso/unidad/img-48.png', alt='Texto que describa la imagen')

    .row.position-relative.mb-5.py-4.bg-fondo-1.bg-full-width
      div.px-4.px-md-5.py-md-3

        h2 
        p.mb-5
        .row.mb-5.justify-content-center 
          .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-right")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-49.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Infraestructura tecnológica
              p.px-1.text-small.mb-0.d-flex.text-center Adquisición o alquiler de hardware y software necesarios para alojar y procesar datos.
          .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-up")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-50.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Licencias de software
              p.px-1.text-small.mb-0.d-flex.text-center Herramientas como Power BI o Tableau tienen costos anuales basados en el tamaño de la empresa y el número de usuarios.
          .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-up")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-51.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Consultoría y desarrollo
              p.px-1.text-small.mb-0.d-flex.text-center Contratar expertos para personalizar e implementar el sistema puede generar costos adicionales.
          .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-left")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-52.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Mantenimiento <br> y actualizaciones
              p.px-1.text-small.mb-0.d-flex.text-center Costos recurrentes para mantener el sistema actualizado y eficiente.

    h2 Capacitación del personal
    p.mb-4 La formación de los equipos involucrados es crucial para garantizar el uso adecuado del sistema y maximizar sus beneficios:

    ImagenInfografica.color-secundario.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/unidad/img-53.png', alt='Texto que describa la imagen')

      .tarjeta.bg-white.p-4(x="40.4%" y="51%" numero="+")
        .h5.mb-2 Seguridad
        p Capacitación en la protección de datos sensibles y en garantizar la integridad de la información.
      .tarjeta.bg-white.p-4(x="48.3%" y="35%" numero="+")
        .h5.mb-2 Capacitación técnica
        p Administradores y desarrolladores aprenden a manejar infraestructura, herramientas ETL y bases de datos.
      .tarjeta.bg-white.p-4(x="56.2%" y="51%" numero="+")
        .h5.mb-2 Herramientas de análisis
        p Analistas de negocio son formados en el uso de plataformas como Power BI o Tableau para crear reportes y dashboards.
      .tarjeta.bg-white.p-4(x="48.3%" y="64.4%" numero="+")
        .h5.mb-2 Calidad de los datos
        p Los equipos reciben formación para asegurar la precisión y confiabilidad de los datos procesados.

    .row.mb-5.mx-0
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-54.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8.d-flex.align-items-center.bg-rosa.p-4(data-aos="fade-left")
        p.mb-0(data-aos="fade-up") El desarrollo e implementación de un sistema de inteligencia de negocios implica construir una infraestructura sólida, integrar datos de múltiples fuentes y configurar herramientas que permitan la visualización y análisis de datos. Aunque existen costos asociados, los beneficios en términos de productividad, competitividad y toma de decisiones informadas son indispensables para mantener una posición destacada en el mercado. La capacitación del personal es clave para maximizar el uso del sistema y garantizar su éxito a largo plazo.
    
    #t_3_3.titulo-segundo
      div.d-flex
        span.me-3 3.3  
        h2 Mantenimiento y evolución del sistema de inteligencia de negocios (IN)

    p.mb-4 El mantenimiento y evolución de un sistema de inteligencia de negocios (IN) es una fase crítica para asegurar su funcionalidad continua y su alineación con las necesidades organizacionales. Dado que los entornos empresariales, los datos y las tecnologías cambian constantemente, es imprescindible que el sistema de IN se adapte y evolucione para seguir siendo útil y relevante. Esta etapa incluye actividades de monitoreo, actualizaciones, ajustes de algoritmos y mejoras en la seguridad de los datos, así como capacitación para el personal involucrado. 

    .row.position-relative.mb-0.py-4.bg-azul-1.bg-full-width
      div.px-4.px-md-5.py-md-3
        SlyderA(tipo="b").bg-white
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0(data-aos="zoom-in-right")
              p.text-bold Monitoreo continuo
              p Consiste en el seguimiento constante del rendimiento del sistema, verificando la correcta operación de las fuentes de datos, los procesos ETL y las herramientas de análisis. Permite identificar problemas y solucionarlos de manera oportuna.
            .d-none.d-lg-block.col-md-6.col-lg-4(data-aos="zoom-in-left")
              figure
                img(src='@/assets/curso/unidad/img-55.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0(data-aos="zoom-in-right")
              p.text-bold Actualización de herramientas
              p Las herramientas de análisis y visualización (Power BI, Tableau, Qlik, etc.) deben ser actualizadas regularmente para incorporar mejoras de rendimiento, nuevas funcionalidades y actualizaciones de seguridad.
            .d-none.d-lg-block.col-md-6.col-lg-4(data-aos="zoom-in-left")
              figure
                img(src='@/assets/curso/unidad/img-56.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0(data-aos="zoom-in-right")
              p.text-bold Ajuste de algoritmos
              p Los algoritmos de análisis y predicción se ajustan a medida que cambian los datos y los patrones de negocio, garantizando la precisión y relevancia de los insights.
            .d-none.d-lg-block.col-md-6.col-lg-4(data-aos="zoom-in-left")
              figure
                img(src='@/assets/curso/unidad/img-57.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0(data-aos="zoom-in-right")
              p.text-bold Mejora de la seguridad
              p La seguridad de los datos es prioritaria. Las actualizaciones incluyen la implementación de mejores prácticas de cifrado, protección contra amenazas cibernéticas y cumplimiento con normativas legales.
            .d-none.d-lg-block.col-md-6.col-lg-4(data-aos="zoom-in-left")
              figure
                img(src='@/assets/curso/unidad/img-58.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0(data-aos="zoom-in-right")
              p.text-bold Adaptación a cambios organizacionales
              p Si la estructura del negocio evoluciona (nuevos procesos, fusiones, expansiones), el sistema de IN debe ajustarse para reflejar y soportar estos cambios, integrando nuevas fuentes de datos y ajustando los procesos existentes.
            .d-none.d-lg-block.col-md-6.col-lg-4(data-aos="zoom-in-left")
              figure
                img(src='@/assets/curso/unidad/img-59.png', alt='Texto que describa la imagen')

    .row.bg-amarillo.bg-full-width.py-4.mb-5.border-top-naranja-11px
      div.px-5.pb-md-3.py-4.d-flex
        .col-12.col-xl-7.col-xxl-8.d-flex.pe-4.pe-xl-5.align-items-center.flex-column(data-aos="fade-right")
          h2.mb-4.pb-2.me-auto Ejemplos, beneficios, costos y capacitación del sistema de inteligencia de negocios (IN)
          p.mb-5 En el documento Ejemplos, beneficios, costos y capacitación del sistema de inteligencia de negocios (IN)  se abordan aspectos esenciales que permiten comprender y aprovechar al máximo estas herramientas tecnológicas. Se destacan casos prácticos de aplicación, los beneficios que aportan a las organizaciones, los costos asociados a su implementación y la importancia de la capacitación para garantizar su efectividad. Lo invitamos a consultar el documento para ampliar esta información y descubrir cómo la Inteligencia de Negocios puede transformar la gestión empresarial.
          a.d-flex.me-auto.bg-white.box-shadow.cursor-pointer(data-aos="zoom-in" :href="obtenerLink('/downloads/Anexo_Ejemplos, beneficios, costos y capacitación del sistema de inteligencia de negocios (IN).pdf')" target="_blank")
            img.h-100(style="width: 48px" src='@/assets/componentes/pdf-icon-square.svg', alt='Texto que describa la imagen')
            p.text-small.fs-14px.my-auto.px-2 <strong>Anexo.</strong> Ejemplos, beneficios, costos y capacitación del sistema de inteligencia de negocios (IN)  
             
        .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
          img.h-100(src='@/assets/curso/unidad/img-60.png', alt='Texto que describa la imagen')


</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema3',
  components: {
    BannerInterno,
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.material-complementario
  padding-top: 3rem
  border-top: 9px solid $color-sistema-e
</style>
