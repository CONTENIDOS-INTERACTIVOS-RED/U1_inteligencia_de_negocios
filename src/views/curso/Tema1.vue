<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Concepto y evolución de la inteligencia de negocios '")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5.mx-0
      .col-12.col-xl-8.d-flex.align-items-center.bg-amarillo.p-4(data-aos="fade-right")
        p.mb-0(data-aos="fade-up") La inteligencia de negocios o Business Intelligence (BI) ha recorrido un largo camino desde sus inicios, cuando las empresas dependían de métodos manuales para el análisis de datos, hasta convertirse en una disciplina sofisticada que integra tecnologías avanzadas para la toma de decisiones estratégicas. Su evolución refleja cómo los avances tecnológicos han transformado la forma en que las organizaciones gestionan y aprovechan su información. A continuación, se detalla las principales etapas de desarrollo de la inteligencia de negocios, destacando los momentos clave y las herramientas que marcaron cada periodo.
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-left")
        img.h-100(src='@/assets/curso/unidad/img-3.png', alt='Texto que describa la imagen')
    
    .row.mb-5
      .col-10.mx-auto
        LineaTiempoD.fs-16px
          p(numero="1950" titulo="Antes de 1950").d-flex(data-aos="fade-up")
            img(src='@/assets/curso/unidad/img-4.png', alt='Texto que describa la imagen')
            span.px-4 Antes de la invención de la inteligencia de negocios moderna, las empresas dependían de informes financieros y análisis manuales de datos. El análisis se realizaba a través de métodos tradicionales, como la contabilidad financiera y la generación de informes escritos a mano. Este trabajo era llevado a cabo por contadores y analistas que utilizaban herramientas rudimentarias como papel y lápiz. El enfoque estaba en el análisis de datos históricos, sin predicciones ni análisis en tiempo real, limitándose a métricas financieras tradicionales como ventas, ingresos y costos.
          p(numero="1950" titulo="1950-1960").d-flex(data-aos="fade-up")
            img(src='@/assets/curso/unidad/img-5.png', alt='Texto que describa la imagen')
            span.px-4 Con la llegada de las primeras computadoras, las empresas comenzaron a automatizar ciertos procesos de análisis de datos. Se introdujeron los primeros sistemas de procesamiento de datos para gestionar grandes volúmenes de información financiera. Aunque las herramientas disponibles no eran sofisticadas ni permitían análisis complejos, marcaron el inicio de un cambio en la forma de abordar la gestión de datos. Durante este período, las bases de la inteligencia de negocios moderna comenzaron a establecerse.  
          p(numero="1960" titulo="1960-1970").d-flex(data-aos="fade-up")  
            img(src='@/assets/curso/unidad/img-6.png', alt='Texto que describa la imagen')
            span.px-4 En esta época surgieron avances importantes en la gestión de datos. Se introdujeron las primeras bases de datos, especialmente en sectores como el bancario, para almacenar grandes volúmenes de datos transaccionales. Además, el uso de mainframes permitió procesar datos de manera más rápida en comparación con los métodos tradicionales. A pesar de estos avances, la capacidad de análisis seguía siendo limitada, enfocada principalmente en la gestión de información básica.
          p(numero="1970" titulo="1970-1980 (DSS)").d-flex(data-aos="fade-up") 
            img(src='@/assets/curso/unidad/img-7.png', alt='Texto que describa la imagen')
            span.px-4 Se desarrollaron los Sistemas de Soporte a la Decisión (DSS, por sus siglas en inglés), que ofrecieron a las empresas herramientas computacionales para analizar datos y tomar decisiones informadas. Estos sistemas permitían simulaciones y escenarios hipotéticos. También surgió la primera generación de software analítico, como el Decision Support System de IBM, que facilitaba el análisis de datos en tiempo real, aunque con alcance limitado.
          p(numero="1980" titulo="1980-1990 (Business Intelligence)").d-flex(data-aos="fade-up")
            img(src='@/assets/curso/unidad/img-8.png', alt='Texto que describa la imagen')
            span.px-4 En 1989, el término Business Intelligence (BI) fue acuñado por Howard Dresner. Surgieron conceptos como el data warehousing, que consolidaba grandes volúmenes de datos de diversas fuentes en almacenes centralizados, y las herramientas de OLAP (Online Analytical Processing), que permitieron análisis rápidos y multidimensionales. Además, aparecieron las primeras plataformas de BI, como Cognos y MicroStrategy, que ofrecían capacidades avanzadas para informes y análisis.
          p(numero="1990" titulo="1990-2000").d-flex(data-aos="fade-up")
            img(src='@/assets/curso/unidad/img-9.png', alt='Texto que describa la imagen')
            span.px-4 El BI se consolidó como herramienta esencial en la toma de decisiones empresariales. Las empresas adoptaron plataformas corporativas que integraban análisis históricos, en tiempo real y predicciones de tendencias. La minería de datos (data mining) y el análisis predictivo emergieron como elementos clave para descubrir patrones ocultos y anticipar comportamientos futuros. Herramientas como BusinessObjects, SAP BW y Oracle BI ofrecieron soluciones de análisis avanzadas y accesibles.
          p(numero="2000" titulo="2000-2010 (Big Data y BI moderno)").d-flex(data-aos="fade-up") 
            img(src='@/assets/curso/unidad/img-10.png', alt='Texto que describa la imagen')
            span.px-4 La llegada del Big Data revolucionó la inteligencia de negocios, permitiendo procesar y analizar grandes volúmenes de datos provenientes de diversas fuentes, como redes sociales y dispositivos IoT, con tecnologías como Hadoop y Spark. La computación en la nube (cloud computing) facilitó el almacenamiento y procesamiento de datos sin necesidad de infraestructuras costosas. Además, herramientas de visualización como Tableau y Power BI hicieron más accesible el análisis en tiempo real para usuarios no técnicos.

    h2 Inteligencia Artificial, Machine Learning y la Inteligencia de Negocios del futuro (2010-Presente)
    p.mb-5 La evolución de la Inteligencia de Negocios (BI) en la última década ha estado profundamente influenciada por la integración de tecnologías avanzadas como la Inteligencia Artificial (IA) y el Machine Learning (ML). Este desarrollo ha transformado las capacidades de BI, llevándola más allá de los informes tradicionales hacia un enfoque más dinámico y automatizado para la toma de decisiones. Los avances más destacados de este periodo incluyen:

    .row.mb-4
      .col-4.d-none.d-xl-block(data-aos="fade-right")
        img(src='@/assets/curso/unidad/img-11.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8(data-aos="fade-left")
        lineaTiempoD.large
          p(numero="1" titulo="Integración con IA y ML")(data-aos="fade-up") Las plataformas de BI ahora incluyen capacidades de machine learning, permitiendo predicciones más precisas y recomendaciones automatizadas basadas en el análisis de patrones de datos.
          p(numero="2" titulo="Automatización de la toma de decisiones")(data-aos="fade-up") Herramientas avanzadas de BI están automatizando decisiones basadas en patrones aprendidos, mejorando la eficiencia empresarial y reduciendo el error humano en procesos críticos.
          p(numero="3" titulo="BI móvil")(data-aos="fade-up") La accesibilidad desde dispositivos móviles permite a los usuarios tomar decisiones en tiempo real y desde cualquier ubicación, favoreciendo la agilidad empresarial.
          p(numero="4" titulo="BI como servicio (BIaaS)")(data-aos="fade-up") Los modelos basados en la nube han democratizado el acceso a potentes herramientas de análisis, eliminando la necesidad de infraestructuras internas costosas y complejas.
          
    p.mb-5 La evolución de BI desde sistemas manuales hasta la integración con IA y Big Data ha revolucionado la gestión empresarial. Hoy en día, la inteligencia de negocios es un pilar fundamental para decisiones estratégicas, operativas y tácticas, y su desarrollo continuará impulsado por tecnologías emergentes.

    #t_1_1.titulo-segundo
      div.d-flex
        span.me-3 1.1  
        h2 Fundamentos de la Inteligencia de Negocios (IN)

    .row.mb-5
      .col-12.col-xl-7.col-xxl-8.d-flex.flex-column
        p.mb-5 La inteligencia de negocios (IN) es un proceso estratégico que combina tecnologías, herramientas y metodologías para transformar datos en información valiosa que facilite la toma de decisiones en las organizaciones. Este enfoque permite analizar datos históricos y actuales para identificar patrones, tendencias y oportunidades, impulsando decisiones informadas y estratégicas. Según Turban et al. (2011), "la inteligencia de negocios es una colección de aplicaciones, tecnologías y procesos que se utilizan para recolectar, almacenar, acceder y analizar datos para ayudar a los usuarios a tomar mejores decisiones empresariales".
        .d-flex.align-items-start.bg-rosa.p-4.mb-4(data-aos="fade-right")
          img.me-3(style="width: 90px" src='@/assets/curso/unidad/img-12.svg', alt='Texto que describa la imagen')
          .d-flex.flex-column
            p.pe-xl-3.mb-0 La IN está compuesta por diversos elementos clave, como almacenes de datos (data warehouses), sistemas OLAP, minería de datos y dashboards. Estas herramientas facilitan el análisis multidimensional, la identificación de tendencias y la visualización de información estratégica. Además, la IN incorpora indicadores clave de desempeño (KPI) para monitorear el progreso en tiempo real hacia los objetivos empresariales, permitiendo a las empresas reaccionar proactivamente a los cambios del mercado y ajustar sus estrategias en consecuencia.
      .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-13.png', alt='Texto que describa la imagen')  
    p.mb-5 En los últimos años, la IN ha evolucionado hacia el análisis en tiempo real e integra tecnologías como Big Data y análisis predictivo, lo que permite anticipar cambios y adoptar modelos de negocio ágiles. En este contexto, la IN se ha consolidado como un elemento estratégico esencial para mantener la competitividad y la innovación en el mercado global.

    #t_1_2.titulo-segundo
      div.d-flex
        span.me-3 1.2  
        h2 Ámbito de aplicación de la Inteligencia de Negocios

    p.mb-4 El ámbito de aplicación de la inteligencia de negocios es extenso y abarca diversos sectores, donde su capacidad para transformar datos en información estratégica resulta clave para optimizar procesos y mejorar la toma de decisiones.

    .row.mb-4.justify-content-center.card_hover
      .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3.mb-4.mb-xl-0
        .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-right")
          img.mx-auto.mb-4(src='@/assets/curso/unidad/img-14.svg', style="width: 80px")
          p.text-bold.mb-4.text-center Financiero
          p.px-1.text-small.mb-0.d-flex.text-center Gestión de riesgos, detección de fraudes, análisis de rentabilidad y tendencias del mercado. Ejemplo: Uso de análisis predictivo para ajustar estrategias de inversión y préstamos en tiempo real. 
      .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3.mb-4.mb-xl-0(data-aos="fade-up")
        .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100
          img.mx-auto.mb-4(src='@/assets/curso/unidad/img-15.svg', style="width: 80px")
          p.text-bold.mb-4.text-center Minorista
          p.px-1.text-small.mb-0.d-flex.text-center Comprensión del comportamiento del cliente, personalización de experiencias de compra, optimización de inventarios y análisis de tendencias de consumo. Ejemplo: Amazon utiliza IN para ofrecer recomendaciones personalizadas. 
      .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3(data-aos="fade-up")
        .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100
          img.mx-auto.mb-4(src='@/assets/curso/unidad/img-16.svg', style="width: 80px")
          p.text-bold.mb-4.text-center Salud
          p.px-1.text-small.mb-0.d-flex.text-center Gestión de datos de pacientes, optimización de recursos hospitalarios, mejora en diagnósticos y tratamientos personalizados. Ejemplo: Monitoreo de patrones de enfermedades y administración eficiente de camas y personal médico.
      .col-10.col-md-8.col-lg-6.col-xl-4.col-xxl-3(data-aos="fade-left")
        .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100
          img.mx-auto.mb-4(src='@/assets/curso/unidad/img-17.svg', style="width: 80px")
          p.text-bold.mb-4.text-center Manufactura
          p.px-1.text-small.mb-0.d-flex.text-center Optimización de cadenas de suministro, mantenimiento predictivo y mejora de procesos de producción. Ejemplo: Identificación de ineficiencias en líneas de producción para reducir costos y aumentar la calidad.

    p.mb-5 En conclusión, la inteligencia de negocios es una herramienta indispensable para empresas en todos los sectores, permitiendo una mejor comprensión de los datos y una toma de decisiones más informada. Con la constante evolución tecnológica, su relevancia seguirá aumentando, consolidándose como un pilar de la competitividad y la innovación empresarial.

    #t_1_3.titulo-segundo
      div.d-flex
        span.me-3 1.3  
        h2 Empresas desarrolladoras de inteligencia de negocios

    .row.mb-5
      .col-12.col-xl-7.col-xxl-8.d-flex.flex-column
        .d-flex.align-items-start.bg-amarillo.p-4.py-xl-5.h-100(data-aos="fade-right")
          img.me-3(style="width: 90px" src='@/assets/curso/unidad/img-18.svg', alt='Texto que describa la imagen')
          .d-flex.flex-column
            p.pe-xl-3.mb-0(data-aos="fade-up") Las empresas desarrolladoras de inteligencia de negocios (IN) desempeñan un papel crucial al ofrecer herramientas que transforman los datos en información estratégica. Estas compañías han desarrollado plataformas que permiten a las organizaciones integrar, analizar y visualizar datos para tomar decisiones informadas. A nivel global, gigantes como Microsoft, IBM, SAP y Oracle lideran este mercado, mientras que en Colombia empresas como BI Excellence e Hiperbótica destacan con soluciones adaptadas al contexto local. Estas compañías ofrecen herramientas con diversas funcionalidades y costos, lo que las hace accesibles tanto para grandes corporaciones como para pequeñas y medianas empresas (pymes).
      .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img.h-100(src='@/assets/curso/unidad/img-19.png', alt='Texto que describa la imagen')  

    .row.mb-4
      .col-4.d-none.d-xl-block(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-20.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8(data-aos="fade-left")
        lineaTiempoD.large
          p(numero="1" titulo="Integración con IA y ML") Ofrece Power BI, una herramienta que permite visualizar datos de forma interactiva e integrarse con otras aplicaciones como Excel y SharePoint. Su accesibilidad, que incluye una versión gratuita y planes premium, democratiza el acceso a la información dentro de las empresas, mejorando la colaboración y la toma de decisiones.
          p(numero="2" titulo="IBM") Desarrolla IBM Cognos, una plataforma de análisis avanzado y reportes personalizados. Destaca en áreas como el análisis predictivo, ayudando a empresas en sectores como banca y salud a anticipar cambios de mercado y gestionar riesgos. Sus costos están orientados a grandes empresas que buscan capacidades analíticas robustas. 
          p(numero="3" titulo="BI Excellence") Compañía colombiana enfocada en maximizar el valor de los datos mediante herramientas accesibles y servicios de consultoría. Su impacto es notable en sectores como comercio minorista y manufactura, ayudando a optimizar inventarios y reducir costos operativos con soluciones adaptadas al mercado local.
          p(numero="4" titulo="Hiperbótica") Empresa colombiana especializada en soluciones personalizadas de IN y Big Data  para pymes. Ofrece servicios escalables a precios competitivos, permitiendo a empresas más pequeñas acceder a herramientas avanzadas para optimizar operaciones e interpretar datos de clientes.
    .row.mb-4
      .d-flex.align-items-center(data-aos="fade-up")
        div.d-flex.align-items-center.bg-gris.px-3.py-4
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-21.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 En conclusión, tanto los líderes globales como las empresas locales ofrecen soluciones que permiten a las organizaciones de distintos tamaños mejorar su competitividad y adaptarse a un entorno cambiante. Aunque los costos varían, los beneficios en eficiencia operativa, reducción de costos y mejor toma de decisiones hacen que la inversión en IN sea una decisión estratégica cada vez más relevante.

    .bg-full-width.border-top-9-azul
      .px-4.px-md-5.pt-5.pb-0
        h2 Material complementario
        .row
          .col-12.col-md-6.col-lg-8
            p.d-flex.my-4
              img.me-3.mb-auto.mt-2(src='@/assets/componentes/youtube-icon.svg' :style="{'max-width':'16px'}")
              a.text-small.mt-1(target="_blank", href="https://www.youtube.com/watch?v=09Knu34bYdw") Universidad de Deusto / Deustuko Unibertsitatea. 2015 Conceptos básicos del Business Intelligence.
            p.d-flex.my-4
              img.me-3.mb-auto.mt-2(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a.text-small.mt-1(target="_blank", href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/114035 ") Curto Díaz, J. & Conesa Caralt, J. (Il.). (2015). ¿Cómo crear un data warehouse?: ( ed.). Editorial UOC.
          .col-12.col-md-6.col-lg-3
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='Texto que describa la imagen')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1
</style>
