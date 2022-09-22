
<template>
  
  <nav class="navbar navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand">
        <img src="https://1000marcas.net/wp-content/uploads/2019/11/McDonalds-logo-768x432.png" height="50" alt="Logo" loading="lazy"/>
      </a>
    </div>
  </nav>

  <br>


  <div class="row row-cols-1 row-cols-md-3 g-4">
    
    <card name="Pizza Batman" description="pizza de pepperoni,con sabor a parmesano y mantequilla." price="$129 MXN"  > <img src="https://cdn.noticiasdequeretaro.com.mx/wp-content/uploads/2022/01/27011056/20221251125115_1.jpg" alt=""></card>
    <card name="Papas Fritas" description="Nuestras Papitas Mundialmente Famosas® de McDonald's ." price="$69.00 MXN." > <img src="https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/styles/1200/public/media/image/2021/07/patatas-fritas-mcdonalds-2398633.jpg?itok=43Uuy6-m" alt=""> </card>
    <card name="Hamburguesa" description="Viene cubierta con pepinillos, crujiente lechuga, cebollas y queso americano" price="$200 MXN." > <img src="https://cdn.foodandwineespanol.com/2021/11/mcdonalds-mccrispy-1536x864.jpg" alt=""> </card>
    <card name="Spaghetti" description=" Tiene forma de delgada cuerda larga" price="$70.00 MXN." > <img src="https://www.laespanolaaceites.com/wp-content/uploads/2019/05/espaguetis-a-la-bolonesa-1080x671.jpg" alt=""> </card>
    <card name="Empanadas" description="masa quebrada u hojaldre rellena con una preparación salada o dulce " price="$35 MXN." > <img src="https://cdn7.kiwilimon.com/recetaimagen/69/640x426/11549.jpg.webp" alt=""> </card>
    <card name="Hot Dog" description="Panecillo largo lleno con una salchicha de Frankfurt" price="$55 MXN."> <img src="https://chefeel.com/chefgeneralfiles/2021/11/barbecue-grilled-hot-dogs-with-yellow-american-mustard-on-dark-wooden-background-880x541.jpg" alt=""></card>
  </div>
  <br>
  
  <section class="">
    <footer class="text-center text-white" style="background-color: #0a4275;"> 
      <div class="container p-4 pb-0">
        <section class="">
          <p class="d-flex justify-content-center align-items-center">
            <span class="me-3">Gracias</span>
          </p>
        </section>
      </div>
      <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);"> Hugo Frias Martinez</div>
    </footer>
  </section>

</template>



<script>
    import Card from "./components/Card.vue"
    export default {
      components: {
        Card,
      },
      
    };
</script>
       

