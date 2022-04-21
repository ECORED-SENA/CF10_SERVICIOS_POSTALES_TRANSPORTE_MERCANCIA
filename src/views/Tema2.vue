<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 2
      h1 Código de barras

    .row.justify-content-center.mb-5
      .col-lg-11
        .bloque-texto-g.clr--pink.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/t2_01.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            p.mb-0 Así como es importante la ubicación de los productos dentro del almacén bien sea por número de pasillo o por código de la estantería, los productos deben ser identificados a través de un código único por artículo para la buena organización de las existencias, por tanto, optimizar los recursos y agregar valor a las actividades que se desarrollan en el almacén. El proceso de codificación de mercancías consiste en identificar los productos en forma de código, el cual se asocia a una etiqueta adherida al producto, que permitirá acceder al producto electrónicamente, a través del sistema de información. En caso que el producto sea nuevo y no tenga código, se deberá asignar uno y registrar todas las especificaciones propias del producto.

    p.mb-5 Dicha codificación debe guardar relación con la aplicada para ubicaciones al interior de la empresa, logrando así trazabilidad de la información; la manera más razonable de cumplir con las entregas previstas es mantener un almacén organizado, por tanto, es necesario localizar el producto de forma sencilla, clara y rápida; para no cometer errores y enviar productos equivocados.  Dentro de los beneficios de la codificación tenemos: lograr automatizar los procesos, optimizar la cadena de suministro, lograr operatividad en tiempo real, rápida respuesta ante controles, histórico de movimientos, reducción de errores y costos.

    .titulo-sexto.color-acento-contenido
      h5 Figura 4.
      span SGA

    h3.text-center Sistema de Gestión de Almacenes (SGA)

    figure(data-aos="zoom-in").mb-4
      img(src="@/assets/curso/tema2/t2_02.png", alt="alt").m-auto

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-7
        p Para una eficiente operación y trazabilidad de las mercancías, los almacenes deben contar con un sistema de información denominado Sistema de Gestión del Almacén (SGA) con el objeto de controlar las referencias. Es así como la codificación de las mercancías es una labor de cuidado desde el momento que llega el producto hasta que sale del almacén, cada área puede participar en la asignación del código de acuerdo a los criterios que requieran controlar y hacer seguimiento. 
        p.mb-0 Nota. Tomado de UOC. 
      .col-lg-5
        figure(data-aos="fade-right")
          img(src="@/assets/curso/tema2/t2_03.png", alt="alt").img400.m-auto

    p Existen varias metodologías de codificación:

    .cajon.cjn--amarillo.p-4.mb-5
      ul
        li #[strong - Codificación libre:] no existe un parámetro específico, simplemente se asigna un código que no esté repetido o no se haya utilizado.
        li #[strong - Codificación libre al azar:] se asigna un código al azar, para aquellos productos nuevos.
        li #[strong - Codificación Inteligente:] se utilizan los códigos de familias y subfamilias, así: 
          br
          br
          | #[span.ms-3 Familias de productos principales: utilizan 2 dígitos numéricos.]
          br
          | #[span.ms-3 Subfamilia: subdivisión de la familia, utilizan 2 dígitos más.]
          br
          | #[span.ms-3 Referencia única: asignación de código específico para el producto de 3 dígitos en adelante.] 
      p.mb-2 Ejemplo: camisa adulto referencia 56789, de la colección 2020, subfamilia 34 (talla M).
      p.mb-0 Código: #[strong 203456789].

    h3.mb-5 Códigos y etiquetas

    .row.justify-content-center.mb-5
      .col-lg-11
        .row.justify-conten-center.align-items-center
          .col-auto
            figure(data-aos="fade-right")
              img(src="@/assets/curso/tema2/t2_04.svg", alt="alt").img270.m-auto
          .col
            p De acuerdo al ítem anterior, la codificación puede ser libre según la naturaleza de la organización; sin embargo, en Colombia a través del:

    .row.justify-content-center.mb-5
      .col-lg-10
        .bg_img_02
          .row.justify-content-end
            .col-lg-8
              .crd.crd--white
                h4 Decreto<br>2153/diciembre/2016
                p Se establece el Sistema armonizado de designación y codificación de mercancías, es una nomenclatura internacional de productos multipropósito desarrollado por la Organización Mundial de Aduanas (OMA).

    .row.align-items-center.mb-5
      .col-auto
        figure(data-aos="fade-right")
          img(src="@/assets/curso/tema2/t2_06.png", alt="alt").img150.m-auto
      .col
        p.mb-0 El cual contiene alrededor de 5.000 grupos de productos; cada uno identificado por un código de seis dígitos, apoyado por reglas bien definidas para lograr una clasificación uniforme.  A continuación, se relacionan los diferentes tipos de etiquetas:

    .titulo-sexto.color-acento-contenido
      h5 Tabla 7.
      span Tipos de etiquetas
   
    .tabla-a.mb-5
      table.customTable_01
        thead
          tr
            th(style="width:20%;").text-center TIPO DE ETIQUETA
            th.text-center DESCRIPCI&Oacute;N
            th.text-center IMAGEN
        tbody
          tr.cell--gray 
            td.text-center #[strong C&Oacute;DIGO DE BARRAS]
            td
              | Denominado sistema GS1 de identificaci&oacute;n y transmisi&oacute;n de datos mediante c&oacute;digo de barras.  Utilizado en m&aacute;s de 105 pa&iacute;ses.  Permite identificar todas las unidades de productos en la cadena log&iacute;stica.
              br
              | Se compone de dos partes: c&oacute;digo num&eacute;rico y el s&iacute;mbolo; las barras contienen informaci&oacute;n codificada.
            td.py-4 #[img(src="@/assets/curso/tema2/t2_08.svg" alt="" style="width:350px;").m-auto]           
          tr.cell--gray 
            td.text-center #[strong GTIN 13]
            td
              | C&oacute;digo indicado para identificar mercanc&iacute;a o productos que se dirigen al punto de venta. Est&aacute; conformado por:
              br
              br
              | Prefijo asignado al pa&iacute;s (Colombia-70)
              br
              | Prefijo de la empresa (5-8 d&iacute;gitos)
              br
              | C&oacute;digo del producto (por marcas)
              br
              | C&oacute;digo de control
            td.py-4 #[img(src="@/assets/curso/tema2/t2_09.svg" alt="" style="width:370px;").m-auto] 
          tr.cell--gray 
            td.text-center #[strong GTIN 14]
            td
              | Denominado tambi&eacute;n EAN14, por componerse de 14 d&iacute;gitos. <br><br>Utilizado para cada unidad del producto contenida en un grupo GTIN13, se elimina el c&oacute;digo de control y se asigna uno nuevo al inicio. Ver imagen
            td.py-4 #[img(src="@/assets/curso/tema2/t2_10.svg" alt="" style="width:430px;").m-auto] 
          tr.cell--gray 
            td.cell--yellow.text-center #[strong GS1-128]
            td
              | Sistema est&aacute;ndar internacional de identificaci&oacute;n de mercanc&iacute;as en entornos log&iacute;sticos.
              br
              br
              | Requisito: toda la informaci&oacute;n de la etiqueta debe ser legible.
              br
              br
              | Contenido: caracter&iacute;sticas del producto, c&oacute;digo agrupaci&oacute;n, cantidad, lote, fecha fabricaci&oacute;n, envasado, consumo, etc.
              br
              | Importante tener en cuenta que esta etiqueta deber&aacute; estar en el producto a lo largo de toda la cadena de suministro
            td.py-4 #[img(src="@/assets/curso/tema2/t2_11.png" alt="" style="width:170px;").m-auto] 
          tr.cell--gray 
            td.text-center #[strong C&Oacute;DIGO DATA MATRIX]
            td
              | Sistema de c&oacute;digo de barras bidimensionales (2D), que permite almacenar gran cantidad de informaci&oacute;n en una matriz de puntos.
              br
              br
              | Requiere un contacto visual entre el equipo lector y el c&oacute;digo.
            td.py-4 #[img(src="@/assets/curso/tema2/t2_12.svg" alt="" style="width:170px;").m-auto] 

    .row.justify-content-center
      .col-lg-10
        .cta--purple2
          .bubble--right          
          .row.align-items-center
            .col-auto.mb-4.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/t2_13.png", alt="alt").img350.m-auto
            .col-12.col-lg.px-5.pt-0.pt-lg-5.txt-mg--right
              p.mb-4 Para ampliar la información, lo invitamos a consultar #[strong “Gestión de operaciones de almacenaje”] haciendo clic en el enlace.

              a.boton.color-acento-contenido-botones.texto-blanco.float-end(href="https://elibro-net.bdigital.sena.edu.co/es/ereader/senavirtual/43773?page=66" target="_blank").mb-5.mb-lg-0
                span Ingresar
                i.fas.fa-link

    

</template>

<script>
export default {
  name: 'Tema2',
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
