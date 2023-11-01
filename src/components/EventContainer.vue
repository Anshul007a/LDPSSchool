<template>
    <div class="container-fluid Event-main">
        <h1 class="text-center">

            Upcoming Events
            <hr>
        </h1>
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-4" v-for="i in numberOfCols" :key="i">
                    <div class="card card-sm">
                        <div class="card-body text-center">
                            <h5 class="card-title">Small Card</h5>
                            <p class="card-text">This is a small card.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <h1 class="text-center">

            Achivements
            <hr>
        </h1>
        <div class="container">
    <div class="row justify-content-center">
        <div class="col-md-4" v-for="i in numberOfCols" :key="i">
            <div class="card card-sm">
                <img src="../assets/jhoola.jpg" class="card-img-top" alt="Image Alt Text">
            </div>
        </div>
    </div>
</div>


    </div>
</template>

<script>
export default {
    data() {
        return {
            numberOfCols: 3, // Change this number to control the number of divs

        };
    },

}
</script>

<style>
.Event-main {
    background: linear-gradient(180deg, rgba(125, 52, 52, 0.00) 0%, #7D3434 63.72%);
    width: 1438px;
    height: 1438px;
    flex-shrink: 0;
}
</style>