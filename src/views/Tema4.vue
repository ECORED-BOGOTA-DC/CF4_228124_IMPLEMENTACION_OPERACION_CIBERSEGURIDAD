<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Recomendaciones importantes sobre controles
    p.mt-5(data-aos="fade-right") Después de identificar el “estado actual” y el “estado deseado” del proceso de seguridad digital, se requiere analizar la brecha actual entre los dos estados, determinando la brecha por cerrar con la implementación de la estrategia.
    .h4.mt-5(data-aos="fade-right") Así, se requiere la ejecución de acciones complementarias que optimizarán los controles generados, como las que se sugieren en el siguiente listado: 
    .cajon.color-acento-botones.p-4.mt-5.bg-gris(style="background-color:#FCF5FF;")(data-aos="fade-left")
      ul.lista-ul.mt-3.ml-5
        li.d-flex
          i.fas.fa-check.texto-acento-botones.mr-3
          |  Disponer de planes de trabajo y proyectos para cerrar la brecha y así poder llegar al estado deseado.
        li.d-flex
          i.fas.fa-check.texto-acento-botones.mr-3
          |  Acoger estándares de seguridad digital que soporten la política.
        li.d-flex
          i.fas.fa-check.texto-acento-botones.mr-3
          |  Apoyar las acciones de la organización en las orientaciones de las normas técnicas existentes. 
        li.d-flex
          i.fas.fa-check.texto-acento-botones.mr-3
          |  Para este punto concreto, por ejemplo, se sugiere utilizar la ISO/IEC 27002:2013.
        li.d-flex
          i.fas.fa-check.texto-acento-botones.mr-3
          |  Realizar un programa constante de sensibilización y capacitación en seguridad digital que posibilite implementar y adoptar, por todos los miembros de la organización, una estrategia eficaz.

</template>

<script>
export default {
  name: 'Tema4',
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
