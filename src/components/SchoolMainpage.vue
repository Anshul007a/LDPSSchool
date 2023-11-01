<template>
    <div>
        <div class="container-fluid main-container">
            <div class="row">
                <div class="col-3">
                    <img class="imgclass" src="../assets/Badge-Logo.png" alt="img not found">
                </div>
                <div class="col-6 ">
                    <h1 class="main-heading">Little Drop public school Hatta</h1>
                    <div class="sub-heading">
                        <h5>Amanganj Road-470775</h5>
                        <h6>Affilefied to CBSC</h6>

                    </div>

                </div>
                <div class="col-3">

                </div>
            </div>


        </div>

        <nav class="navbar navbar-expand-lg navbar-light bg-light custom-nav">
            <div class="container">
                <a class="navbar-brand" href="#">LDPS</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#"><i class="fas fa-home cutom-icon"></i>Home</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link" href="#"><i class="fa-regular fa-address-card cutom-icon"></i>About</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link" href="#"><i class="fa-solid fa-user cutom-icon"></i>Admission</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link" href="#"><i class="fa-solid fa-address-book cutom-icon"></i>Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner test-class">
    <div class="carousel-item active">
      <img src="../assets/jhoola.jpg" class="d-block crouser-img" alt="...">
    </div>
    <div class="carousel-item">
      <img src="../assets/jhoola.jpg" class="d-block crouser-img" alt="...">
    </div>
    <div class="carousel-item">
      <img src="../assets/jhoola.jpg" class="d-block crouser-img" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="container-fluid marquee">
    <marquee class="marque-data">This text will scroll from right to left</marquee>    
</div>












    </div>
</template>

<script>
export default {
    data() {
        return {
            message: "Welcome to my Vue 3 project!",
        };
    },

}

</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Irish+Grover&display=swap');
.main-container{
    background: #7D3434;

}
.marque-data{
    margin-top: 12px;
    color: white;


}
.marquee{
    height: 50px;
    background: linear-gradient(180deg, #7D3434 0%, rgba(125, 52, 52, 0.00) 100%);


}
.container-fluid {
    /* background: linear-gradient(180deg, #7D3434 0%, rgba(125, 52, 52, 0.00) 100%); */
    /* background: #7D3434; */

}
.carousel-inner {
    display: flex;
    align-items: center;
    justify-content: center;
   
}
.carousel-item {
    text-align: center;
}

.carousel-item img {
    max-width: 100%;
    max-height: 100%;
}
.main-heading {
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    font-family: 'Irish Grover', sans-serif;
    font-size: 45px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    color: #FFF6EE;
    margin-top: 15px;
    text-align: center;



}


.sub-heading {
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    font-size: 45px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    color: #FFF6EE;
    margin-top: 15px;
    text-align: center;

}



.imgclass {
    width: 71px;
    height: 85px;
    flex-shrink: 0;
    display: inline;
    margin-top: 15px;
    margin-left: 50px;
}

.cutom-icon {
    margin: 5px;
}

.custom-nav {
    background: linear-gradient(180deg, #7D3434 0%, rgba(125, 52, 52, 0.00) 100%);
    color: #FFF6EE;
}

.navbar-nav .nav-link {
    color: #712023;
    /* Your custom color */
}</style>

