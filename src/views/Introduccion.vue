<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.mt-5
      .col-12.col-lg-5(data-aos="fade-right")
        p En la actualidad, la ciberseguridad y la seguridad de la información han adquirido gran importancia en las organizaciones, lo que conlleva que se desarrollen documentos y directrices que orienten el uso adecuado de tecnologías, favoreciendo así la relativa integridad tanto de la información como de las acciones y desarrollos que tiene lugar en el ciberespacio. 
        p.mt-3 Teniendo en cuenta la importancia de la ciberseguridad en el desarrollo de las actividades de las personas en general, y con mayor razón de las organizaciones, se ha buscado mantener la seguridad de la misma, mediante la traza de estrategias de ciberseguridad y en concordancia con los controles requeridos.
        p.mt-3.cuadro-morado.pb-5 La elaboración de hojas de ruta de las estrategias y documentación de las mismas, es un aspecto característico y necesario, ya que esto contribuye, en buena medida, a la integridad y disponibilidad de la información ante descuidos de los usuarios, ante ataques informáticos e, incluso, frente a desastres de orden natural.
      .col-4.col-lg-6.offset-3.offset-lg-1(data-aos="fade-left")
        figure
          img(src="@/assets/template/tema-0-1.png", alt="")

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
