<template>
  <section class="section section-components pb-0" id="section-components">

    <h1 class="display-2 text-center">Roadmap</h1>
      <!-- Timeline -->

  <div class="row justify-content-center">
      <div class="col-lg-5">
        <Roadmap />
      </div>
      <div class="col-lg-5" id="roadmap-images">

          <img class="toReveal" id="first-image" src="img/brand/roadmap-1.png" />
          <img class="toReveal" id="second-image" src="img/brand/roadmap-2.png"/>

      </div>
  </div>


      <!-- ################# -->


    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-12">

          <br>

          <h1 class="display-2 text-center">F.A.Q.</h1>
          <Faq/>

          <br>
          <!-- Button colors -->
          <div class="mb-3 mt-5">
            <small class="text-uppercase font-weight-bold"
              >Pick your color</small
            >
          </div>
          <base-button class="btn-1" type="primary">Primary</base-button>
          <base-button class="btn-1" type="info">Info</base-button>
          <base-button class="btn-1" type="success">Success</base-button>
          <base-button class="btn-1" type="warning">Warning</base-button>
          <base-button class="btn-1" type="danger">Danger</base-button>
          <base-button class="btn-1" type="neutral">Neutral</base-button>

          <div class="mb-3 mt-5">
            <small class="text-uppercase font-weight-bold">Outline</small>
          </div>

          <base-button class="btn-1" outline type="primary"
            >Outline Primary</base-button
          >
          <base-button class="btn-1" outline type="info"
            >Outline Info</base-button
          >
          <base-button class="btn-1" outline type="success"
            >Outline Success</base-button
          >
          <base-button class="btn-1" outline type="warning"
            >Outline Warning</base-button
          >
          <base-button class="btn-1" outline type="danger"
            >Outline Danger</base-button
          >
          <base-button class="btn-1" outline type="neutral"
            >Outline Neutral</base-button
          >
          <!-- Button links -->
          <div class="mb-3 mt-5">
            <small class="text-uppercase font-weight-bold">Links</small>
          </div>
          <a href="#" class="btn btn-link text-default">Default</a>
          <a href="#" class="btn btn-link text-primary">Primary</a>
          <a href="#" class="btn btn-link text-info">Info</a>
          <a href="#" class="btn btn-link text-success">Success</a>
          <a href="#" class="btn btn-link text-warning">Warning</a>
          <a href="#" class="btn btn-link text-danger">Danger</a>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
  import Roadmap from './Roadmap.vue';
  import Faq from './Faq.vue'

  export default {
      components: {
          'Roadmap': Roadmap,
          'Faq': Faq
      }
  };
</script>
<style>
</style>
