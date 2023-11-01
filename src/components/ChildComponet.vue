<template>
    <div>
        <div class="container">

            <div class="row">
                <div class="col-12 col-md-4" v-for="item in items" :key="item.id">
                    <div class="dot"></div>
                </div>
            </div>
            <div class="row">
                <div class="col-12 col-md-4" v-for="item in items" :key="item.id">
                    <div class="dot"></div>
                </div>
            </div>
        </div>


    </div>
</template>

<script>
export default {
    data() {
        return {
            items: [
                { id: 1, name: '1', value: "myvalue" },
                { id: 2, name: '2', value: "myvalue" },
                { id: 3, name: '3', value: "myvalue" },


            ],
        };
    },

}
</script>

<style>
.dot {

    height: 150px;
    width: 150px;
    background-color: #bbb;
    border-radius: 50%;
    display: inline-block;




}

.dot h1 {
    font-size: 2.5rem;
    text-align: center;
    margin-top: 44px;
}</style>