<template>
    <div class="col">
        <div class="card">
            <img :src="url" class="card-img-top" :alt="title">
            <div class="card-body">
                <h5 class="text-center"> {{ title }} </h5>
                <p class="text-center"> {{ name }}.</p>
                <p class="text-center"> {{ description }} </p>
                <p class="text-center"> {{ price }} </p>
            </div>
        </div>
    </div>


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
