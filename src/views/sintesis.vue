<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      p.mb-5 La presente síntesis organiza los elementos clave que estructuran las ventas en el formato comercial, cada sección aborda aspectos relevantes como la promoción, el portafolio de productos, y la omnicanalidad, proporcionando un marco integral para entender las estrategias comerciales y las herramientas que potencian la interacción con los consumidores en distintos escenarios. 
  
      .row.justify-content-center
        .col-lg-12.mb-5
          figure
            img(src="@/assets/curso/temas/sintesis.png", alt="La imagen representa un esquema jerárquico dividido en tres bloques principales: publicidad en el punto de venta, productos y servicios, y comunicación comercial. Cada bloque incluye elementos fundamentales, como las características y eventos en el punto de venta, las estrategias comerciales y demostraciones para productos, y los niveles y medios utilizados en la comunicación. Este diseño ofrece una organización clara y precisa de los conceptos esenciales en la gestión comercial.")
        .col-auto
          a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              p Anexo. Síntesis
  
  </template>

<script>
export default {
  name: 'Sintesis',
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
