<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 	 Diseño de controles de seguridad
    .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img.w-45(
        :style="{'background-image': `url(${require('@/assets/template/tema-1-1.png')})`}"
      )
      .bloque-texto-g__texto.w-72.p-4
        p.mb-0 En este contexto de la ciberseguridad, se entiende por controles todas aquellas acciones, medidas o procesos que buscan asegurar el desarrollo normal del ciberespacio o del manejo de los equipos e información dentro de la organización. 
    .row.mt-5
      .col-12.col-lg-7.align-self-center.pr-4(data-aos="fade-right")
        .h2.color-primario El diseño de los controles ayuda a preparar las estrategias de ciberseguridad elaborando una hoja de ruta de acuerdo con normas y documentos requeridos ya establecidos.
      .col-4.col-lg-4.offset-4.offset-lg-0.px-0(data-aos="fade-left")
        figure.pl-5.py-3.borde-botones-left
          img(src="@/assets/template/tema-1-2.svg")
    .row.mt-5(data-aos="fade-right")
      .col-10.offset-1
        .h4 Otros aspectos importantes de los controles de seguridad son:
      .col-10.offset-1.mt-3.py-3.px-4.bg-aguamarina
        .row
          .col-3.px-5.align-self-center
            figure
              img(src="@/assets/template/tema-1-3.svg")
          .col-9.py-4.pr-4
            .h2 Madurez y capacidad de los sistemas
            p.mt-3 Ayudan a trazar las estrategias para descubrir un camino que permita a la organización alcanzar el estado de madurez y capacidad deseado en todo lo que tiene que ver con seguridad digital.
      .col-10.offset-1.mt-2.py-3.px-4.bg-rosa
        .row
          .col-3.px-5.align-self-center
            figure
              img(src="@/assets/template/tema-1-4.svg")
          .col-9.py-4.pr-4
            .h2 Responsabilidad del diseño de controles
            p.mt-3 En la organización, quien se encarga de diseñar dichos controles es la oficina de Tecnologías de la Información (TI) o, en su defecto, una persona experta en seguridad que haya sido contratada para tal fin.
      .col-10.offset-1.mt-2.py-3.px-4.bg-morado-claro
        .row
          .col-3.px-5.align-self-center
            figure
              img(src="@/assets/template/tema-1-5.svg")
          .col-9.py-4.pr-4
            .h2 Jefatura de sistemas
            p.mt-3 En la mayoría de los casos, cuando la organización cuenta con la posibilidad de tener personal propio para esos propósitos, quien establece el diseño de controles es quien hace las veces de jefe o jefa de sistemas.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    overFlag: '',
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
  methods: {
    chBg(id) {
      this.overFlag = id
    },
    chBgTransparent() {
      this.overFlag = ''
    },
  },
}
</script>

<style lang="sass" scoped></style>
