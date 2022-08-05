<template>

  <div>

    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/imagen/universidad.jpg" class="d-block w-50" alt="universidad">
    </div>
    <div class="carousel-item">
      <img src="/imagen/campus.jpg" class="d-block w-50" alt="campus">
    </div>
    <div class="carousel-item">
      <img src="/imagen/estudiantes.jpg" class="d-block w-50" alt="estudiantes">
    </div>
  </div>
    </div>
<div class="py-5 container">
  <div class="row">
    <div class="col md 12 text-center">
      <h1 class="main-heading">Lecciones Aprendida</h1>
      <div class="underline">
        <p>
          Como sabemos nuxt.js no es nada mas que un framework que está basado en Vue.js y escrito en JavaScript.
          es muy conveniente y facil de usar nuxt en mi opinion porque ahorra mucho el tiempo, esta tiene una variedad de funciones 
          lo que hace que la aplicacion o la pagina web sea facil en desarollar.
        </p>
        <p>
          Despues de utilizar nuxt creo que es una de la herramientas muy desarollada para cualquier necesidad.
          se puede utilizar para cualquier tipo de paginas ya sea una pagina de landing page
          o sitios personales hasta sitioweb complejas o de comercial tambien. 
        </p>
        <p>
          Al desarollar con nuxt aprendi primero como instalar, crear y compilar el proyecto; luego logre integrar extenciones como Bootstrap
          , utilizando los layouts como barra de navegacion, footer en los componentes globales que esta disponible en la pagina web de nuxt logre llevar la pagina a mi gusto,
          ,luego tambien cree las paginas del menu y hice la vinculacion utilizando nuxtlink, logre agregar las imagenes desarollar carousel 
          y por ultimo logre configurar los meta tags como el titulo, meta descriptions y keyword en global y local. 
        </p>

      </div>

    </div>
  </div>
</div>

</div>


  
</template>

<script>
export default {
  name: 'IndexPage',
  head() {
      return {
        title: 'Pagina de Inicio',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Diseño de la pagina web con Nuxtjs - Pagina de Inicio '
          },
          {
            hid: 'Keywords',
            name: 'Keywords',
            content: 'Vue, Nuxt, javascript = Pagina de Inicio'
          }
        ]
      }
    }
}
</script>
