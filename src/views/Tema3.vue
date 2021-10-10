<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Comportamientos en línea
    .row.mb-5.align-items-center
      .col-lg-5(data-aos="fade-right"): img(src='@/assets/curso/62.svg')
      .col-lg-7(data-aos="fade-left")
        p Cuando se realiza acceso frecuente a plataformas y herramientas tecnológicas, incluyendo las redes sociales, hay que cumplir con una serie de recomendaciones en cuanto al comportamiento que debe realizarse igual en la interacción directa que en la online.
          br
          br
          |Particularmente se debe poner especial atención a lo que se escribe o publica, y se conoce con el nombre de netiqueta. Este concepto surge de la palabra francesa etiquette (buenas maneras) y la inglesa net (red), para determinar las normas de comportamiento que debían cumplir los usuarios al hacer uso de herramientas como foros, redes sociales, chats y correos electrónicos, entre otros.
    #t_3_1.titulo-segundo(data-aos='fade-right')
      h2 3.1 Normas de comportamiento
    p.mb-5 A continuación, se mencionan de manera general, las normas que se deben cumplir al hacer uso de aplicaciones o plataformas tecnológicas, de su buena aplicación depende el mantenimiento estable de la identidad digital:
    .contendor-listado.p-5
      .row.mb-5.justify-content-center
        .col-lg-11
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__1.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center(@mouseover="mostrarIndicador = false")
                .img-hover
                  img(src='@/assets/curso/64.svg')
                .indicador--hover(v-if="mostrarIndicador")
                p.mb-0.h2 01
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 Hacerse entender: 
                p escribir de manera clara y entendible lo que se desea opinar, evitar utilizar abreviaturas, palabras propias o inventadas o en otros idiomas; tener siempre presente la ortografía al momento de querer compartir su publicación.
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__2.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 02
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__3.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 03
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__4.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 04
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__5.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 05
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__6.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 06
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__7.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 07
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__8.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 08
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__9.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 09
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
          .row.mb-2.g-0
            .col-md-2.col-4
              .numero.morado__10.text-center.text-white.p-4.h-100.d-flex.align-items-center.justify-content-center
                .img-hover
                  img(src='@/assets/curso/64.svg')
                p.mb-0.h2 10
            .col-md-10.col-8
              .contenido.p-5.h-100
                h4 
                p 
    

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
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

<style lang="sass" scoped>
.contendor-listado
  background-image: url('../assets/curso/63.svg')
  background-repeat: no-repeat
  background-position: top
  background-size: cover
  .numero
    position: relative
    font-size: 60px
    font-weight: bold
    overflow: hidden
    &:hover
      .img-hover
        bottom: 0
    .img-hover
      position: absolute
      bottom: -100%
      left: 0
      width: 100%
      transition: all .5s ease-in-out
.contenido
  background-color: #F3F9FF
  &:hover
    .img-hover
      bottom: 0
</style>
