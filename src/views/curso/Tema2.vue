<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Herramientas y plataformas de inteligencia de negocios (BI)'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.mb-5.mx-0
      .col-12.col-xl-8.d-flex.align-items-center.bg-amarillo.p-4(data-aos="fade-right")
        p.mb-0(data-aos="fade-up") El éxito de la inteligencia de negocios (BI) depende de una arquitectura bien estructurada y de la integración de diversos componentes que transforman datos en información estratégica. Estos sistemas están diseñados para manejar grandes volúmenes de datos, analizar patrones y generar visualizaciones que apoyen la toma de decisiones. Los componentes principales incluyen bases de datos, almacenes de datos, procesos ETL y herramientas de análisis y visualización.
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-left")
        img.h-100(src='@/assets/curso/unidad/img-22.png', alt='Texto que describa la imagen')
    
    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        lineaTiempoD.large
          p(numero="1" titulo="Bases de datos")(data-aos="fade-up") Son sistemas de almacenamiento donde se guardan datos transaccionales generados diariamente. Estas bases de datos pueden ser relacionales (MySQL, PostgreSQL) o no relacionales (MongoDB), proporcionando flexibilidad para almacenar y recuperar datos según las necesidades del negocio.
          p(numero="2" titulo="Almacenes de datos (Data Warehouses)")(data-aos="fade-up") Sistemas especializados para integrar datos de múltiples fuentes y centralizarlos para análisis. Están optimizados para consultas y análisis históricos, permitiendo la identificación de tendencias. Ejemplos: Amazon Redshift, Google BigQuery, Microsoft Azure SQL Data Warehouse.
          p(numero="3" titulo="Procesos ETL (Extracción, Transformación y Carga)")(data-aos="fade-up") Proceso que extrae datos de diversas fuentes, los transforma para garantizar consistencia y exactitud, y los carga en el almacén de datos. Ejemplos de herramientas: Apache Nifi, Talend, Microsoft SQL Server Integration Services (SSIS).
          p(numero="4" titulo="Herramientas de análisis y visualización")(data-aos="fade-up") Permiten la interpretación de datos a través de gráficos, dashboards y reportes interactivos. Estas herramientas, como Power BI, Tableau y Qlik Sense , también integran análisis predictivo y minería de datos para realizar proyecciones y anticipar cambios.
      .col-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-23.png', alt='Texto que describa la imagen')

    .row.mb-4
      .d-flex.align-items-center(data-aos="fade-up")
        .d-flex.align-items-center.bg-gris.px-3.py-4
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-24.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 La integración de estos componentes dentro de la arquitectura de BI permite a las organizaciones gestionar y analizar grandes volúmenes de datos de manera eficiente, mejorando la toma de decisiones estratégicas en todos los niveles operativos.

    .bg-fondo-1.bg-full-width.mb-4
      div.px-5.pb-md-3.py-4

        h2 Arquitectura de la inteligencia de negocios
        p.mb-5 La arquitectura de un sistema de inteligencia de negocios (IN) sigue un flujo definido que conecta la recopilación de datos, su procesamiento y su presentación al usuario final. Este sistema se organiza en tres capas principales que trabajan en conjunto para transformar datos en información estratégica.

        .row.mb-0
          .col-10.col-md-6.col-xl-4.mb-4.mx-auto(data-aos="fade-right")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-25.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Capa de datos 
                p.text-small.px-4.text-center.pb-2 Es el nivel donde se almacenan los datos de origen provenientes de bases de datos operacionales y se integran en el almacén de datos (data warehouse). Este nivel centraliza y organiza los datos históricos y actuales para su posterior análisis.
          .col-10.col-md-6.col-xl-4.mb-4.mx-auto(data-aos="fade-up")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-26.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Capa de procesos
                p.text-small.px-4.text-center.pb-2 Aquí ocurre el proceso de Extracción, Transformación y Carga (ETL). Esta capa asegura que los datos sean consistentes, homogéneos y relevantes para el análisis. También limpia y estructura los datos para facilitar su comprensión y uso.
          .col-10.col-md-6.col-xl-4.mb-4.mx-auto(data-aos="fade-left")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-27.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Capa de presentación
                p.text-small.px-4.text-center.pb-2 En esta etapa, los datos procesados se visualizan y analizan mediante herramientas de dashboards, reportes interactivos y gráficos. Estas visualizaciones permiten a los usuarios interpretar fácilmente la información y tomar decisiones informadas.

    p.mb-4 La arquitectura de IN es esencial para maximizar el valor de los datos dentro de una organización. Centraliza, organiza y presenta la información de manera estratégica, facilitando decisiones informadas que impulsen el desempeño organizacional en entornos dinámicos y competitivos.

    .row.bg-amarillo.bg-full-width.py-4.mb-5
      div.px-5.pb-md-3.py-4.d-flex
        .col-12.col-xl-7.col-xxl-8.d-flex.pe-4.pe-xl-5.align-items-center.flex-column(data-aos="fade-right")
          h2.mb-4.pb-2.me-auto Análisis de datos en inteligencia de negocios (IN): principales herramientas y beneficios
          p.mb-5 En el documento <strong>Análisis de Datos en IN y Principales Herramientas</strong>, se exploran conceptos fundamentales, metodologías clave y herramientas destacadas como Power BI, Tableau y Qlik Sense, esenciales para transformar datos en decisiones estratégicas. Descubra cómo el análisis descriptivo, predictivo y prescriptivo, aplicado en casos como los de Walmart y Amazon, potencia la eficiencia operativa y la planificación estratégica. Se invita a leer el documento para conocer cómo estas herramientas pueden brindar ventajas competitivas en el entorno empresarial actual.
          a.d-flex.me-auto.bg-white.box-shadow.cursor-pointer(data-aos="zoom-in" :href="obtenerLink('/downloads/Anexo_Análisis de datos en IN y principales herramientas.pdf')" target="_blank")
            img.h-100(style="width: 48px" src='@/assets/componentes/pdf-icon-square.svg', alt='Texto que describa la imagen')
            p.text-small.fs-14px.my-auto.px-2 <strong>Anexo.</strong> Análisis de Datos en IN y Principales Herramientas
             
        .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
          img.h-100(src='@/assets/curso/unidad/img-28.png', alt='Texto que describa la imagen')

    #t_2_1.titulo-segundo
      div.d-flex
        span.me-3 2.1  
        h2 Función de la bodega de datos y el web scraping en inteligencia de negocios
    p.mb-5 En el ámbito de la inteligencia de negocios (IN), la bodega de datos (data warehouse) y el web scraping son herramientas complementarias que permiten la recopilación, centralización, y análisis de datos provenientes de fuentes internas y externas. Estas herramientas potencian la capacidad de las organizaciones para transformar datos dispersos en información estructurada y accionable, favoreciendo una toma de decisiones estratégica e informada.

    TabsC.mb-4
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Bodega de datos", :iconUrl="require('@/assets/curso/unidad/img-29.svg')")
        .row
          .d-none.d-lg-block.col-md-12.col-lg-5.col-xl-4(data-aos="fade-right")
            figure
              img(src='@/assets/curso/unidad/img-31.png', alt='Texto que describa la imagen')
          .col-md-12.col-lg-7.col-xl-8.mb-4.mb-md-0(data-aos="fade-left")
            h4 Bodega de datos
            p(data-aos="fade-up") Sistema centralizado diseñado para almacenar datos históricos y actuales provenientes de múltiples sistemas organizacionales. Centraliza los datos mediante procesos de ETL (Extracción, Transformación y Carga), garantizando su limpieza, transformación y estandarización. 
            span <strong>Beneficios</strong> Sirve como única fuente de verdad, mejora la precisión en informes y proyecciones, optimiza la eficiencia y reduce el tiempo necesario para obtener insights. Ejemplo: análisis de tendencias de ventas a largo plazo.
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Web scraping", :iconUrl="require('@/assets/curso/unidad/img-30.svg')")
        .row
          .d-none.d-lg-block.col-md-12.col-lg-5.col-xl-4(data-aos="fade-right")
            figure
              img(src='@/assets/curso/unidad/img-32.png', alt='Texto que describa la imagen')
          .col-md-12.col-lg-7.col-xl-8.mb-4.mb-md-0(data-aos="fade-left")
            h4 Web scraping
            p(data-aos="fade-up") Técnica para extraer datos de fuentes externas como sitios web mediante programas automatizados. Facilita el acceso a información en tiempo real y de difícil obtención, como precios de competidores, tendencias en redes sociales o análisis de reseñas de productos. 
            span <strong>Herramientas comunes:</strong> BeautifulSoup, Scrapy (Python). 
            span <strong>Consideraciones:</strong> Debe respetar políticas de privacidad y términos de uso para evitar problemas legales. 

    .bg-fondo-1.bg-full-width.mb-4
      div.px-5.pb-md-3.py-4
        h2 Integración entre la bodega de datos y el web scraping
        p.mb-4 La combinación de datos internos organizados en la bodega de datos con información externa obtenida a través del web scraping amplía el alcance del análisis en IN. Esta integración permite:
        .row.mb-5.justify-content-center 
          .col-10.col-md-8.col-lg-6.col-xl-4.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-right")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-33.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Enriquecer los datos internos
              p.px-1.text-small.mb-0.d-flex.text-center Incorporar información externa para complementar los datos históricos.
          .col-10.col-md-8.col-lg-6.col-xl-4.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-up")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-34.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Optimizar estrategias
              p.px-1.text-small.mb-0.d-flex.text-center Ajustar precios en tiempo real al combinar ventas internas con datos de precios de competidores.
          .col-10.col-md-8.col-lg-6.col-xl-4
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-left")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-35.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Obtener una visión integral
              p.px-1.text-small.mb-0.d-flex.text-center Analizar datos internos y externos en un único repositorio confiable.

    .row.mb-5
      .col-12.col-xl-7.col-xxl-8.d-flex.flex-column
        p.mb-4 Por ejemplo, una empresa minorista puede usar web scraping para recopilar precios de competidores y combinarlos con datos internos de ventas almacenados en su bodega de datos, ajustando sus estrategias de precios de manera inmediata y basada en datos actualizados.
        .d-flex.align-items-start.bg-azul.p-4.mb-0(data-aos="fade-right")
          img.me-3(style="width: 90px" src='@/assets/curso/unidad/img-36.svg', alt='Texto que describa la imagen')
          .d-flex.flex-column
            p.pe-xl-3.mb-0(data-aos="fade-up") En conclusión, la bodega de datos y el web scraping son componentes esenciales en la arquitectura de IN. Mientras la bodega organiza y centraliza los datos históricos internos, el web scraping aporta información externa en tiempo real, permitiendo una visión holística del mercado y una ventaja competitiva para las organizaciones.
      .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-37.png', alt='Texto que describa la imagen')

    .bg-full-width.border-top-9-azul
      .px-4.px-md-5.pt-5
        h2 Material complementario
        .row
          .col-12.col-md-6.col-lg-8
            p.d-flex.my-4
              img.me-3.mb-auto.mt-2(src='@/assets/componentes/youtube-icon.svg' :style="{'max-width':'16px'}")
              a.text-small(target="_blank", href="https://www.youtube.com/watch?v=ElgUy_7eYLQ") Universidad de Deusto / Deustuko Unibertsitatea. 2015 Introducción al Business Intelligence. (video) Youtube:
            p.d-flex.my-4
              img.me-3.mb-auto.mt-2(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a.text-small(target="_blank", href="https://www.ibm.com/co-es/it-infrastructure. https://www.ibm.com/mx-es/topics/business-intelligence") Productos de IBM, Infraestructura de TI, Libere y aproveche el poder de su infraestructura de TI
          .col-12.col-md-6.col-lg-3
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='Texto que describa la imagen')

</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema2',
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

<style lang="sass"></style>
