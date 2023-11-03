<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Controles: características
    p.mt-5(data-aos="fade-right") La estrategia de ciberseguridad y seguridad de la información de una organización ha de encaminarse y enfocarse en lograr la construcción de un ciberespacio seguro y resistente, que se alcanza, entre otras maneras, trazando las estrategias de acuerdo con los controles requeridos y, como se ha dicho ya, elaborando una hoja de ruta para mejorar el nivel de la ciberseguridad. 
    .h4.mt-5(data-aos="fade-right") En ese sentido, los controles de seguridad pueden caracterizarse con tres atributos constitutivos, que se presentan a continuación: 
    .row.mt-5
      .col-10.offset-1(data-aos="fade-left")
        SlyderA.slyder-bg-img.text-white.rounded-20
          .row
            .col-4.align-self-center
              figure
                img(src="@/assets/template/tema-3-2.svg").w-31.margin-0-auto
            .col-6.mb-5
              .h4.mt-5 Prevenir errores
              p.mt-5 El carácter preventivo de los controles otorga al plan de seguridad un enfoque que favorece la intervención de los riesgos, antes de que estos se materialicen o, como es de esperarse, previniendo que estos sucedan con el mismo rigor y afectación que si no se previeran.

          div.row
            .col-4.align-self-center
              figure
                img(src="@/assets/template/tema-3-3.svg").w-31.margin-0-auto
            .col-6.mb-5
              .h4.mt-5 Detectar errores
              p.mt-5 Detectar los errores es, básicamente, lograr ampliar el espectro de seguridad de los sistemas de información y, por tanto, generar con más acierto, en tiempo y forma, los mecanismos de intervención y atención a la materialización de los riesgos y/o errores detectados.
          div.row
            .col-4.align-self-center
              figure
                img(src="@/assets/template/tema-3-4.svg").w-31.margin-0-auto
            .col-6.mb-5
              .h4.mt-5 Corregir errores
              p.mt-5 La corrección de errores se presume como una acción necesaria cuando la prevención y la detección no han sido suficientes o no se han aplicado con el cuidado justo y pertinente. La corrección de los errores, siempre ofrecerá la posibilidad de generar mecanismos o acciones de prevención para nuevos riesgos o errores potenciales.  
    



    
          



</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
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
<style lang="sass">
@media(max-width: 700px)
  .slyder-a__btn--sigt, .slyder-a__btn--atrs
    top: 25% !important
</style>
