<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-tasks" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5   

    .row.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0        
        figure
          img(src="@/assets/template/falso-verdadero.svg", alt="Texto que describa la imagen").img250.m-auto

      .col-12.col-md-8.col-lg-9
        .titulo-segundo.mb-3
          h2 Clasificar conceptos
        p.mb-4 Familiarizar al aprendiz con el vocabulario aplicable a Preparación de la carga para distribución de mercancías.
        .tarjeta.tarjeta--azul.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Arrastrar y soltar.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

</template>

<script>
export default {
  name: 'Actividad',
}
</script>

<style lang="sass"></style>
