<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white i
      h1 Introducción

    .row.justify-content-center.align-item-center.mb-5
      .col-lg-8
        p En los últimos tiempos se ha incrementado el comercio electrónico, por tanto, los pedidos a domicilio, lo que significa una reactivación de la economía de manera positiva, mientras que el sector logística podría verlo como una oportunidad para fortalecer y buscar soluciones óptimas para el transporte logístico en los centros de distribución, el cual debe ser más eficiente, porque de la programación adecuada de las rutas de reparto depende la optimización en los tiempos de entrega, reducción de los costos y satisfacción de los clientes.  

        p.mb-0 Para lograr un servicio eficiente en los tiempos de entrega, aumentar el número de encomiendas y reducir el consumo de combustible, se requiere establecer una planeación de rutas para entrega de mercancías en el menor tiempo posible y costos razonables; no sin antes realizar una correcta preparación iniciando con la identificación de los tipos de mercancías, organizarlas de acuerdo a sus características, ubicar en <i>pallets</i> para determinar el volumen final y seleccionar el tipo de transporte que realizará la última milla.

      .col-lg-4
        figure(data-aos="fade-left")
          img(src="@/assets/curso/intro.svg", alt="alt").img350.m-auto
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/6phzzMEfztk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
