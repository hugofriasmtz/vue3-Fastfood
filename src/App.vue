
<template>
    <header>
        <div class="card text-center">
            <div class="card-header border-dark">
              <ul class="nav nav-pills card-header-pills">
                <li class="nav-item">
                  <a class="nav-link active" href="#">Menú</a>
                </li>
              </ul>
            </div>
            <div class="card-body">
                <h2 class="card-title">COMIDA RAPIDA</h2>

               
            </div>
        </div>
    </header>
    <div class="row row-cols-1 row-cols-md-3 g-4">
    
        <card url="https://cdn.noticiasdequeretaro.com.mx/wp-content/uploads/2022/01/27011056/20221251125115_1.jpg" title="Litter Cesar" name="Pizza Batman" description="pizza de pepperoni,con sabor a parmesano y mantequilla." price="$129 MXN"  /> 

        <card url="https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/styles/1200/public/media/image/2021/07/patatas-fritas-mcdonalds-2398633.jpg?itok=43Uuy6-m" title="Macdonald´s" name="Papas Fritas" description="Nuestras Papitas Mundialmente Famosas® de McDonald's ." price="$69.00 MXN." />

        <card url="https://i.pinimg.com/564x/69/4a/8f/694a8f0aceecce9bfcffb8d87b206620.jpg" title="Macdonald´s" name="Hamburguesa" description="Viene cubierta con pepinillos, crujiente lechuga, cebollas y queso americano" price="$200 MXN." />

        <card url="https://www.laespanolaaceites.com/wp-content/uploads/2019/05/espaguetis-a-la-bolonesa-1080x671.jpg" title="VIPS" name="Spaghetti" description=" Tiene forma de delgada cuerda larga" price="$70.00 MXN." />

        <card url="https://i.pinimg.com/564x/08/e3/b1/08e3b19ba6926de14f47b0fe1e126ca6.jpg" title="Carnitas Santa Elena" name="Empanadas" description="masa quebrada u hojaldre rellena con una preparación salada o dulce " price="$35 MXN." />

        <card url="https://i.pinimg.com/564x/a3/d9/34/a3d93497180e92e5ca7166141efdb493.jpg" title="Macdonald´s" name="Hot Dog" description="Panecillo largo lleno con una salchicha de Frankfurt" price="$55 MXN." />
    </div>
    <footer>
        <div class="card">
            <div class="card-header border-dark">
            </div>
            <div class="card-body">
            <h5 class="card-title">Gracias !</h5>
            <p class="card-text">Vuelve Pronto :)</p>
            </div>
        </div>
    </footer>
</template>



<script>
    import Card from "./components/Card.vue"
    export default {
      components: {
        Card,
      },
      
    };
</script>
       

