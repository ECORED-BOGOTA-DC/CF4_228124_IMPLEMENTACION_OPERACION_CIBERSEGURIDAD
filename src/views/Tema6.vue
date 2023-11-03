<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 Generalidades de los activos de información
    p.mt-5(data-aos="fade-right") Los activos de información relacionados con la seguridad de la información hacen referencia a cualquier información o dispositivo que tenga que ver con el tratamiento de esta y que sea de valor para la organización.
    .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5.mt-5(data-aos="fade-left")
      .bloque-texto-g__img.w-45(
        :style="{'background-image': `url(${require('@/assets/template/tema-6-1.png')})`}"
      )
      .bloque-texto-g__texto.w-72.p-4
        p.mb-0 Los activos de información cuentan con un sistema de clasificación, el cual se enfoca en las propiedades de confidencialidad, integridad y disponibilidad como elementos para el tratamiento de los datos. Además, evalúa el impacto que se tendría en caso de no cumplir con alguno de estos fundamentos. 
    .row.mt-5.bg-gris.bg-imagen-rosada(data-aos="fade-right")
      .col-11.offset-1.position-relative.z-index-2
        .h4.texto-acento-botones.mt-5 Algunos tipos de activos
        ul.lista-ul.mt-4
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p Las distintas políticas establecidas.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p El conjunto de estándares.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p Cada uno de los procedimientos.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p Todo el compendio de directrices.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p La o las arquitecturas.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p El conjunto de inspecciones o controles, tanto físicos como tecnológicos y de procedimientos.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p Tecnologías.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p Los roles y las distintas responsabilidades.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p Los proveedores de los servicios desde el exterior de la organización.
          li.d-flex
            i.fas.fa-check.texto-acento-botones.mr-3
            p El conjunto de instalaciones.
    .row.mt-3.bg-aguamarina.bg-imagen-aguamarina(data-aos="fade-left")
      .col-11.offset-1.position-relative.z-index-2
        .h4.texto-acento-aguamarina.mt-5 Ámbitos o elementos afectados por los activos y que hacen parte del proceso de la seguridad digital
        ul.lista-ul.mt-4
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Seguridad en el entorno.
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Contramedidas
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Seguridad del personal
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Conciencia y formación.
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Auditorías
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Cumplimiento
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Evaluación de amenazas
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Análisis de vulnerabilidades
          li.d-flex
            i.fas.fa-check.texto-acento-aguamarina.mr-3
            p Evaluación de riesgos 

</template>

<script>
export default {
  name: 'Tema6',
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

<style lang="sass" scoped></style>
