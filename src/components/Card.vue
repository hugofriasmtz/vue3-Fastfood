<template>
   <div class="col">
        <div class="card text-center" style="width: 18rem;">
            <img :src="url" class="card-img-top" :alt="title">
            <div class="card-body">
                <h5 class="text-center"> {{ title }} </h5>
                <p class="text-center"> {{ name }}.</p>
                <p class="text-center"> {{ description }} </p>
                <p class="text-center"> {{ price }} </p>
            </div>
        </div>
   </div>
   
    

    <!-- <div class="card" style="width: 18rem;">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        </div>
      </div> -->


</template>   



<script>

    export default {
        props: {
            url: {
                String,
            },
            title: {
                String,
            },
            name: {
                String,
            },
            description: {
                String,
            },
            price: {
                String,
            },
        },


    };
</script>
