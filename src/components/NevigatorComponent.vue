<template>
    <div>
        <div class="container nevigator-main">
            <div class="row justify-content-center" v-for="i in numberOfRows" :key="i">
                <div class="col col-class" v-for="j in numberOfCols" :key="j">
                    <div class="card" style="width: 18rem;">
                        <div class="card-body text-center">
                            <h5 class="card-title">Card title</h5>
                            <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                                the card's content.</p>
                            <a href="#" class="card-link">Card link</a>
                            <a href="#" class="card-link">Another link</a>
                        </div>
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
      numberOfRows: 2, // Change this number to control the number of divs
      numberOfCols:4
    };
  },
};
</script>

<style>
.nevigator-main {
    margin-top: 5%;
    background: #7D3434;
    height: 533px;

}
.col-class{
    margin-top: 69px;
    margin-bottom: 37px;
    margin-left: 15px;

}
</style>