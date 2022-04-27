<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 3
      h1 Condiciones de seguridad de las mercancías

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.mb-4.mb-lg-0
        .float--container         
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/tema3/t3_01.png", alt="alt").img400.m-auto
          figure
            img(src="@/assets/curso/Float_01.png", alt="alt").float_03.img100
      .col-lg-6
        p Debido a todas las operaciones logísticas que se desarrollan al interior del almacén existe una probabilidad grande que ocurran accidentes tanto a los operadores como la mercancía; partiendo del hecho que deben manipular cargas paletizadas de varias toneladas de peso, circulan vehículos pesados con cargas, existen mercancías apiladas a elevadas alturas; razones más que suficientes para estar expuestos a riesgos constantes, los cuales conducen algún tipo de consecuencia.  

    .row.justify-content-center.mb-5
      .col-lg-10
        .cta--yellow
          .bubble--right
          .row.align-items-center
            .col-auto.mb-4.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/t3_02.png", alt="alt").img350.m-auto
            .col-12.col-lg.px-5.pt-0.pt-lg-5.txt-mg--right
              p.mb-4 Para ampliar la información, lo invitamos a leer la #[strong “Norma Técnica Colombiana NTC5689 Estanterías.”] 

              a.boton.color-acento-contenido-botones.texto-blanco.float-end(:href="obtenerLink('/downloads/Norma-tecnica-colombiana-NTC5689.pdf')" target="_blank").mb-5.mb-lg-0
                span Descargar
                i.fas.fa-link              
               

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p Las instalaciones del almacén deben ser adecuadas al entorno laboral, con el objetivo de disminuir los riesgos derivados de las operaciones, actos ocasionados por los trabajadores y/o condiciones que se deriven del estado en el que se encuentre tanto la estructura, las herramientas y equipos. 

        p La continua interacción entre los trabajadores y los equipos de movimentacion o manipulación, requiere la atención en aspectos relevantes como: capacitación continua, prevención, responsabilidad, mantenimiento e inspección técnica con el objetivo de ofrecer condiciones más seguras en el almacén para operarios y mercancías, que logren reducir la probabilidad del riesgo.

        p A continuación, se presentan los siguientes aspectos a implementar:

      .col-lg-4
        figure(data-aos="fade-right")
          img(src="@/assets/curso/tema3/t3_03.png", alt="alt").img400.m-auto

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--rosa")
      .row(titulo="Capacitación continua").justify-content-center
        .col-lg.ms-5
          p Más que capacitar, hace referencia a motivar a los trabajadores para que realicen sus actividades encaminadas a proteger su seguridad y salud en los puestos de trabajo; y adelantar procesos de formación.      
        .col-auto
          figure
            img(src='@/assets/curso/tema3/t3_04.png').img400.m-auto

      .row(titulo="Prevención").justify-content-center
        .col-lg.ms-5
          p Hace referencia a todas aquellas actividades encaminadas a la identificación, evaluación y control de los riesgos existentes, para prevenir la ocurrencia de daños.       
        .col-auto
          figure
            img(src='@/assets/curso/tema3/t3_05.png').img400.m-auto

      .row(titulo="Responsabilidad").justify-content-center
        .col-lg.ms-5
          p Identificación de responsabilidades específicas dentro del almacén, como proveedores de equipos y herramientas como sistema de almacenamiento.    
        .col-auto
          figure
            img(src='@/assets/curso/tema3/t3_06.png').img400.m-auto
      
      .row(titulo="Mantenimiento").justify-content-center
        .col-lg.ms-5
          p Se realiza a través del control y vigilancia permanente de aquellos factores que puedan influir en las condiciones óptimas de la operación logística.    
        .col-auto
          figure
            img(src='@/assets/curso/tema3/t3_07.png').img400.m-auto

      .row(titulo="Inspección").justify-content-center
        .col-lg.ms-5
          p Establecer a través del programa de inspecciones los criterios y frecuencia de todas aquellas condiciones que debe cumplir el almacén para identificar a tiempo y prevenir condiciones de riesgo; como: estanterías, orden y aseo, manipulación de cargas, condiciones de las mercancías, entre los principales.  
        .col-auto
          figure
            img(src='@/assets/curso/tema3/t3_08.png').img400.m-auto

    separador

    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Características de la mercancía 

    .row.justify-content-center.align-items-center.mb-5
      .col-auto.mb-4.mb-lg-0
        .float--container                    
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/tema3/t3_09.png", alt="alt").img430.m-auto
          figure.topIndex
            img(src="@/assets/curso/Float_01.png", alt="alt").float_03.img100
      .col-lg
        p.mb-0 Las mercancías en el almacén se deben ubicar de una forma lógica y atendiendo las normas de seguridad, establecidas por el sector logístico para la manipulación de las mismas durante la ubicación.  Se debe prestar especial atención a diferentes criterios tanto de espacio como ubicación para el tipo de mercancía; para aquellas organizaciones que cuenten con un Sistema de Gestión de Almacén (SGA) es más fácil la tarea, ya que él mismo indica la ubicación precisa en donde se encuentra el producto en tiempo real.  Dentro de las normas de seguridad que se deben atender tenemos:

    .row.justify-content-center.mb-4
      .col-lg-6.mb-4(data-aos="zoom-in")
        .crd_hover_txt
          .crd_hover_txt--img.mb-0         
            img(src="@/assets/curso/tema3/t3_10.jpg")
          .crd_hover_txt--font
            h4 Compatibilidad
            p.mb-0 De acuerdo a la matriz de compatibilidad para sustancias químicas (la desarrolla el departamento de Seguridad y Salud en el Trabajo) indica qué productos pueden estar almacenados juntos o distantes. Por ejemplo, no se pueden almacenar productos tóxicos con alimentos o fármacos.
      .col-lg-6.mb-4(data-aos="zoom-in")
        .crd_hover_txt
          .crd_hover_txt--img.mb-0         
            img(src="@/assets/curso/tema3/t3_11.jpg")
          .crd_hover_txt--font
            h4 Complementariedad
            p.mb-0 Se podrán colocar cercanas las mercancías que por lo regular deben ir en el mismo pedido.
      .col-lg-6.mb-4(data-aos="zoom-in")
        .crd_hover_txt
          .crd_hover_txt--img.mb-0         
            img(src="@/assets/curso/tema3/t3_12.jpg")
          .crd_hover_txt--font
            h4 Tamaño y peso
            p.mb-0 En lo posible aquellas mercancías de gran tamaño y volumen realizarán los menores desplazamientos.
      .col-lg-6.mb-4(data-aos="zoom-in")
        .crd_hover_txt
          .crd_hover_txt--img.mb-0         
            img(src="@/assets/curso/tema3/t3_13.jpg")
          .crd_hover_txt--font
            h4 Rotación
            p.mb-0 Cerca de la zona de expedición se ubicarán los productos de mayor rotación o actividad en el almacén.

    p.mb-5 Los centros de despacho deben asegurar una correcta manipulación y ubicación de la mercancía, para lo cual se requiere conocer características como: dimensiones, forma, volumen, peso, ubicación, fragilidad, propiedades, estado físico y nivel de rotación.  Estas características permiten clasificarlas e identificar los equipos necesarios para las actividades de recepción, manipulación, ubicación y almacenamiento, las cuales se describen a continuación:

    .titulo-sexto.color-acento-contenido
      h5 Tabla 8.
      span Clasificación de las mercancías, según características

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN VOLUMEN O DIMENSIONES
      table
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Muy voluminosa
            td.ps-5 Unidades muy grandes o agrupación de varias mercancías. <br>Requieren contenedor.
          tr
            td.ps-5 Volumen excepcional
            td.ps-5 Medidas excesivamente grandes, que requieren de algún medio especial de transporte, permisos y señalización.
          tr
            td.ps-5 Voluminosas
            td.ps-5 Muy parecido a paletizadas, sin embargo, las dimensiones forman parte del producto y no se pueden apilar.
          tr
            td.ps-5 Dimensiones especiales
            td.ps-5 Requieren puente grúa para la manipulación.
          tr
            td.ps-5 Pequeñas
            td.ps-5 Fácilmente manipular con las manos (máximo 10 Kg).
          tr
            td.ps-5 Paletizadas
            td.ps-5 Mercancía sobre paletas, con peso recomendado máximo 1.000 Kg.

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN EL PESO
      table
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica 
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Ligera
            td.ps-5 Mercancía hasta 5 Kg.
          tr
            td.ps-5 Media
            td.ps-5 Productos o mercancía entre 5 y 25 Kg.
          tr
            td.ps-5 Pesada
            td.ps-5 Mercancía entre 25 Kg y 1 Tonelada.
          tr
            td.ps-5 Muy pesada
            td.ps-5 Mercancía que supere 1 Tonelada.

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN UBICACIÓN
      table
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica 
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Sencillas
            td.ps-5 Con dimensiones dentro del rango (normales) se pueden ubicar fácilmente en los estantes del almacén. No pueden apilarse.
          tr
            td.ps-5 Apilables
            td.ps-5 Se pueden apilar, con algunas limitaciones.

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN FRAGILIDAD
      table
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica 
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Ligeras
            td.ps-5 Pueden soportar peso encima con limitaciones. Por ejemplo, cajas de yogurt.
          tr
            td.ps-5 Resistentes
            td.ps-5 Soportan mucho peso, por ejemplo, cajas de cerámicas para pisos.
          tr
            td.ps-5 Frágiles
            td.ps-5 No pueden soportar peso encima, se deben organizar individualmente.

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN PROPIEDADES
      table
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica 
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Duradero
            td.ps-5 No es prioritario organizar por orden de salida; el tiempo de almacenamiento es indiferente.
          tr
            td.ps-5 Perecedero
            td.ps-5 Por lo regular llevan una fecha de vencimiento; al momento de despachar las mercancías deben salir primero las más antiguas. Ocurre en el caso de alimentos y medicinas.

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN ESTADO FÍSICO
      table
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica 
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Líquido
            td.ps-5 Es necesario identificar la composición y reacción química con otros productos, podría cambiar su estado físico y generar algún tipo de riesgo.
          tr
            td.ps-5 Sólido
            td.ps-5 Aquellos productos compactos o individuales; como los utilizados en el sector agrícola.
          tr
            td.ps-5 Gaseoso
            td.ps-5 Al igual que el estado líquido se requiere identificar la composición química y reacción con otros productos

    .customTable_02.mb-4
      .cell_title
        h5.text-center SEGÚN ROTACIÓN
      table
        caption Nota. https://elibro-net.bdigital.sena.edu.co/es/ereader/senavirtual/50249
        thead          
          tr
            th(style="width:20%; font-size:1em;").ps-5 Característica 
            th(style="width:80%; font-size:1em;").ps-5 Descripción
        tbody          
          tr
            td.ps-5 Baja
            td.ps-5 Registran movimientos mínimos en el almacén.
          tr
            td.ps-5 Media
            td.ps-5 De mediana rotación.
          tr
            td.ps-5 Alta
            td.ps-5 Flujo bastante alto de movimiento tanto de entradas como salidas del almacén.

    separador

    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Criterios de verificación de la mercancía
    
    .row.mb-4
      .col-lg-7.mb-4.mb-lg-0
        p Los pequeños errores pueden generar sobrecostos o retrasos en las operaciones; por tanto, es importante realizar la verificación de la mercancía que ingresa y sale del almacén. En muchas empresas se tienen establecidos o estandarizados los procesos y procedimientos que desarrolla cada una de las áreas, lo cual facilita y aporta información de referencia en cada etapa del proceso; en este caso basados en las condiciones y características que deben cumplir los productos postales.

        .cajon.cjn--rojo.p-4
          p.mb-0 El éxito de las organizaciones se enmarca en el grado de satisfacción del cliente, por tanto, lo que se pretende es reducir al máximo reprocesos y pérdida de tiempo, traducido en otras palabras mayores costos; de aquí la necesidad de referenciar aquellas variables o criterios cualitativos (las puedo observar) como la calidad y el estado de la mercancía y cuantitativos (requieren un conteo, como peso, volumen, gramaje, etc.) en la verificación de mercancías y así aportar en la toma de decisiones de la organización.  

      .col-lg-5
        figure(data-aos="fade-left")
          img(src="@/assets/curso/tema3/t3_14.png", alt="alt").img400.m-auto

    p.mb-5 Lograr la identificación única por artículo o producto, facilita el control de los inventarios, tipo de servicio, verificación del <i>stock</i>, verificación y trazabilidad de la mercancía, operatividad en tiempo real, y reducción de costos; lo que requiere la aplicación de mecanismos de identificación (para el producto) como:

    .row.justify-content-center.mb-5
      .col-10.col-lg-4.mb-4.mb-lg-0
        .crd.crd--02.br--rad.p-5
          figure.mb-3
            img(src="@/assets/curso/tema3/t3_32.png", alt="alt").img100
          h3.mb-4 Código de barras
          h5 Sistema Internacional GS1
          p Codificación de unidades envasadas.
          p.mb-0 Representación de caracteres numéricos o alfabéticos en forma de código.

      .col-10.col-lg-4.mb-4.mb-lg-0
        .crd.crd--02.br--rad.p-5
          figure.mb-3
            img(src="@/assets/curso/tema3/t3_33.png", alt="alt").img100
          h3.mb-4 Código Datamatrix
          h5 Código de barras bidimensionales o código de respuesta rápida.
          p Permiten almacenar información en una matriz de puntos.
          p.mb-0 Reduce los errores en la lectura.

      .col-10.col-lg-4.mb-4.mb-lg-0
        .crd.crd--02.br--rad.p-5
          figure.mb-3
            img(src="@/assets/curso/tema3/t3_34.png", alt="alt").img100
          h3.mb-4 Etiquetas electrónicas
          h5 Etiqueta RFID
          p Permite identificación automática usando ondas de radiofrecuencia. 
          p.mb-0 Recurso más sofisticado, basado en circuitos y microprocesadores.

    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.cjn--gris.p-4(data-aos="zoom-in")
          p.mb-0 A través de la realización del inventario se podrá realizar un recuento exacto de las mercancías, con el objeto de #[strong controlar y verificar] las condiciones tanto físicas y de valor; por norma se debe realizar mínimo una vez al año; este ejercicio permitirá establecer el estado general de las mercancías. 

    p.mb-5 Existen principalmente dos tipos de inventarios: los periódicos y los permanentes, y uno en común que es el inventario físico:

    .row.justify-content-center.mb-4
      .col-auto.mb-4
        .crd.crd--01(data-aos="zoom-in")
          .row.justify-content-center
            .col-auto.mb-4
              .crd_circle
                .crd_circle--img         
                  img(src="@/assets/curso/tema3/t3_15.png", alt="alt")
            h5.text-center Inventario periódico
            p.text-center Se realiza al finalizar el periodo, el cual realiza el cómputo de toda la mercancía existente en el momento de aplicarlo.

      .col-auto.mb-4
        .crd.crd--01(data-aos="zoom-in")
          .row.justify-content-center
            .col-auto.mb-4
              .crd_circle
                .crd_circle--img         
                  img(src="@/assets/curso/tema3/t3_16.png", alt="alt")
            h5.text-center Inventario permanente
            p.text-center Es aquel conteo que se realiza de manera continua tanto de entradas como salidas; es desarrollado con aplicaciones informáticas (<i>software</i>), lo cual permite establecer diferencias por deterioros, daños, inconsistencias o pérdidas.
    
      .col-auto.mb-4
        .crd.crd--01(data-aos="zoom-in")
          .row.justify-content-center
            .col-auto.mb-4
              .crd_circle
                .crd_circle--img         
                  img(src="@/assets/curso/tema3/t3_17.png", alt="alt")
            h5.text-center Inventario físico
            p.text-center Es realizado en el almacén para determinar las existencias físicas de las mercancías por medio de inspección ocular e ir anotando las unidades, lotes y/o referencias.

    separador

    #t_3_3.titulo-segundo.color-acento-contenido
      h2 3.3 Técnicas de inspección de mercancías      

    .bloque-texto-a.img-01.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p.mb-0 Para lograr realizar una adecuada inspección de las mercancías, se debe reconocer antes la inspección técnica aplicable a los almacenes, pues dentro de ellos están ubicadas las mercancías.  Dentro de la inspección del almacén se evalúa el estado de las mercancías desde la recepción hasta el momento del despacho; verificando que se cumpla con la normatividad en operación y seguridad tanto de las mercancías como de los trabajadores.  La inspección del almacén debe realizarse de forma continua y puede ser de acuerdo con el tipo de mercancía almacenada, distribución del almacén, tipos de riesgo, por parte de entes de control, con frecuencias de tiempo diario, por turnos, semanales, mensual, trimestral o de acuerdo a las necesidades y requisitos.
        .col-lg-4.mb-4.mb-lg-0.d-none.d-flex-lg

    p.mb-5 Cada almacén tiene características y necesidades diferentes, que pueden influir en el programa de inspecciones, sin embargo, los objetivos siempre serán los mismos:

    .row.justify-content-center.mb-4
      .col-lg-4.mb-4
        .crd.card--yellowHover(data-aos="zoom-in") 
          .clr-border                  
            p.mb-0 Inventario del estado general de las mercancías
      .col-lg-4.mb-4
        .crd.card--yellowHover(data-aos="zoom-in")
          .clr-border             
            p.mb-0 Describir las características del estado y condiciones de las instalaciones
      .col-lg-4.mb-4
        .crd.card--yellowHover(data-aos="zoom-in")   
          .clr-border          
            p.mb-0 Mantenimiento y operatividad de los equipos
      .col-lg-4.mb-4
        .crd.card--yellowHover(data-aos="zoom-in")    
          .clr-border        
            p.mb-0 Identificar, evaluar y categorizar los peligros y riesgos
      .col-lg-4.mb-4
        .crd.card--yellowHover(data-aos="zoom-in") 
          .clr-border           
            p.mb-0 Sugerir posibles controles

    p.mb-5 El desarrollo de las inspecciones debe realizarse por fases, teniendo en cuenta sus características propias; así:

    ImagenInfograficaB.color-primario.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema3/t3_19.svg', alt='')          

      div(x="23.5%" y="25.5%" tooltip="Planeación de la inspección" numero="+")
        .crd.crd--modal
          .row.justify-content-center.align-items-center
            .col-lg-7
              h3.mb-4.txt-system.mb-2 Planeación de la inspección
              p.mb-0 Se debe tener en cuenta quiénes la realizan, tiempo (lugar, fecha y hora), plano de las instalaciones e instrumentos necesarios para el desarrollo (listas de verificación).
            .col-lg-5
              img(src="@/assets/curso/tema3/t3_20.png", alt="alt").img350.m-auto
              
      div(x="78%" y="47%" tooltip="Desarrollo de la inspección" numero="+")
        .crd.crd--modal
          .row.justify-content-center.align-items-center
            .col-lg-7
              h3.mb-4.txt-system.mb-2 Desarrollo de la inspección
              p.mb-0 Es utilizado al aplicar las listas de verificación sobre aspectos clave como: almacenamiento de sustancias peligrosas, almacenamiento de mercancías perecederas, manipulación de cargas, orden y limpieza, manejo y transporte de mercancías y elementos de protección personal.
            .col-lg-5
              img(src="@/assets/curso/tema3/t3_20.png", alt="alt").img350.m-auto     

      div(x="45%" y="70%" tooltip="Informe" numero="+")
        .crd.crd--modal
          .row.justify-content-center.align-items-center
            .col-lg-7
              h3.mb-4.txt-system.mb-2 Informe
              p.mb-0 Es un documento a través del cual se presentan los resultados de la actividad y se proponen las recomendaciones pertinentes y fundamentadas en los hallazgos. 
            .col-lg-5
              img(src="@/assets/curso/tema3/t3_22.png", alt="alt").img350.m-auto

    .row.justify-content-center
      .col-lg-10
        .cta--yellow
          .bubble--left
          .dots--left
          .row.align-items-center            
            .col-12.col-lg.px-5.pt-0.pt-lg-5.order-2.order-lg-1.txt-mg--left
              p.mb-4 Para ampliar información sobre desarrollo de inspecciones, lo invitamos a descargar el PDF con  la Norma Técnica NTC 4114 Realización de Inspecciones Planeadas.

              a.boton.color-acento-contenido-botones.texto-blanco(:href="obtenerLink('/downloads/6_NTC_4114_Realizacion_de_Inspecciones_Planeadas_ICONTEC.pdf')" target="_blank" type="application/pdf").mb-5.mb-lg-0
                span Descargar
                i.fas.fa-file-download

            .col-auto.order-1.order-lg-2.mb-4.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/t3_23.png", alt="alt").img385.m-auto

    separador

    #t_3_4.titulo-segundo.color-acento-contenido
      h2 3.4 Registro de novedades   

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        .float--container
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/tema3/t3_24.png", alt="alt").img385.m-auto
          figure
            img(src="@/assets/curso/Float_01.png", alt="alt").float_03.img100
      .col-lg-7
        p.mb-0 Partiendo de una de las frases célebres del filósofo Peter Drucker, quien afirmaba que “lo que no se mide no se controla, y si se controla es porque es importante”; existe una variedad de información en logística que permite medir y controlar la gestión.  Sin embargo, se debe tener en cuenta qué se quiere medir, para lograr identificar los datos necesarios en el registro y análisis de la información; para lo cual es importante tener presente los siguientes conceptos:

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--rosa")
      .row(titulo="Novedad").justify-content-center
        .col-lg-8.ms-3          
          p Condición especial de la mercancía identificada en el envío.      
        .col-lg-3
          figure(data-aos="fade-left")
            img(src='@/assets/curso/tema3/t3_25.png').img200.m-auto

      .row(titulo="Inconsistencia").justify-content-center
        .col-lg-8.ms-3          
          p Aquellos defectos de la mercancía encontrados al momento de realizar la verificación.      
        .col-lg-3
          figure(data-aos="fade-left")
            img(src='@/assets/curso/tema3/t3_26.png').img200.m-auto

      .row(titulo="Indicador de desempeño").justify-content-center
        .col-lg-8.ms-3          
          p Aquellos indicadores que se enfocan a cuantificar el desempeño de la gestión logística y cadena de abastecimiento.     
        .col-lg-3
          figure(data-aos="fade-left")
            img(src='@/assets/curso/tema3/t3_27.png').img200.m-auto

      .row(titulo="Logística").justify-content-center
        .col-lg-8.ms-3          
          p Conjunto de actividades necesarias para prestar un servicio, desde la compra, empaquetado, transporte, envío y entrega de un producto al cliente final.       
        .col-lg-3
          figure(data-aos="fade-left")
            img(src='@/assets/curso/tema3/t3_28.png').img200.m-auto

      .row(titulo="Abastecimiento").justify-content-center
        .col-lg-8.ms-3          
          p Traer todo aquello que se requiere para desarrollar una actividad específica.      
        .col-lg-3
          figure(data-aos="fade-left")
            img(src='@/assets/curso/tema3/t3_29.png').img200.m-auto

    .row.justify-content-center
      .col-auto
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema3/t3_30.png').img100.m-auto
      .col
        p Dentro del proceso logístico existe un documento denominado nota de entrega (Albarán), el objetivo es servir como respaldo que acredite la entrega de la mercancía al cliente en las condiciones inicialmente pactadas y así generar la información para elaborar la factura.  En caso que la mercancía recibida no cumpla con lo solicitado o registrado en el pedido, podrá devolverse al sitio de despacho y dejar por escrito la salvedad de la devolución firmando y describiendo en el albarán.  La información que debe contener es:

    .row.justify-content-center
      .col-lg-8
        ImagenInfografica.color-primario(data-aos="zoom-in")
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema3/t3_31.svg', alt='')          

          .crd.crd--purple(x="75%" y="7.5%" numero="+")            
            p.mb-0 Documento que justifica recepción de mercancía.
          .crd.crd--purple(x="88%" y="15.8%" numero="+")            
            p.mb-0 Número de orden
          .crd.crd--purple(x="20%" y="15.8%" numero="+")            
            p.mb-0 Datos del vendedor
          .crd.crd--purple(x="25%" y="32.5%" numero="+")            
            p.mb-0 Datos del cliente
          .crd.crd--purple(x="25%" y="36.8%" numero="+")            
            p.mb-0 Lugar de entrega de las mercancías
          .crd.crd--purple(x="16%" y="45.5%" numero="+")            
            p.mb-0 Cantidad en unidades
          .crd.crd--purple(x="33%" y="45.5%" numero="+")            
            p.mb-0 Descripción de la mercancía
          .crd.crd--purple(x="33%" y="82%" numero="+")            
            p.mb-0 Forma de envío
          .crd.crd--purple(x="73%" y="85%" numero="+")            
            p.mb-0 Conformidad mediante firma del cliente de que el envío es correcto.








  
        
          
        
           

          
        

      



      
          
          

     


    
   

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
