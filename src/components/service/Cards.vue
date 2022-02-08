<template>
  <!-- <section class="container mt-5">
        <div class="row">
            <div class="col">test1</div>
            <div class="col">test2</div>
            <div class="col">test3</div>
        </div>
     
    </section> -->
  <section class="container serv mt-5">
    <b-row>
      <b-col>
        <div class="card" style="width: 18rem">
          <img
            src="../../assets/imgs/idea.svg"
            class="card-img-top service-logo"
            alt="..."/>
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text mt-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
          </div>
        </div>
      </b-col>
      <b-col>
        <div class="card" style="width: 18rem">
          <img
            src="../../assets/imgs/work.svg"
            class="card-img-top service-logo"
            alt="..." />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text mt-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
          </div>
        </div>
      </b-col>
      <b-col>
        <div class="card" style="width: 18rem">
          <img
            src="../../assets/imgs/deliver.svg"
            class="card-img-top service-logo"
            alt="..."/>
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text mt-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
          </div>
        </div>
      </b-col>
    </b-row>
  </section>
</template>

<style>
.serv{
    margin: 0 auto !important;
}
 
.service-logo{
    height: 20vh;
    width: 5rem;
    margin: 0 auto;
}
</style>



<script>
export default {
  name: "Cards",
};
</script>