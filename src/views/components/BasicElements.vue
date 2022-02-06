<template>
  <section class="section section-components pb-0" id="section-components">
    <div class="section-title">
      <h1 class="display-2 text-center">Roadmap</h1>
    </div>
    <!-- Timeline -->

    <div class="row justify-content-center">
      <div class="col-lg-5">
        <Roadmap />
      </div>
      <div class="col-lg-5" id="roadmap-images">
        <img class="toReveal" id="first-image" src="img/brand/roadmap-1.png" />
        <img class="toReveal" id="second-image" src="img/brand/roadmap-2.png" />
      </div>
    </div>

    <!-- ################# -->

    <div class="section-title">
      <h1 class="display-2 text-center">F.A.Q.</h1>
    </div>

    <div class="row justify-content-center" id="faqRow">
      <div class="col-lg-5 faqDiv">
        <img class="slide-right-effect" src="img/brand/red-panda-vector.png" />
      </div>
      <div class="col-lg-5 faqDiv">
        <Faq />
      </div>
    </div>

    <div class="section-title">
      <h1 class="display-2 text-center">Rarity</h1>
    </div>

    <div class="row justify-content-center" id="rarityRow">
      <div class="col-lg-12">
        <Rarity />
      </div>
    </div>

    <div class="section-title">
      <h1 class="display-2 text-center">Team</h1>
    </div>

    <div class="row justify-content-center" id="rarityRow">
      <div class="col-lg-12">
        <Team />
      </div>
    </div>

  </section>
</template>
<script>
import Roadmap from "./Roadmap.vue";
import Faq from "./Faq.vue";
import Rarity from "./Rarity.vue";
import Team from "./Team.vue";

export default {
  components: {
    Roadmap: Roadmap,
    Faq: Faq,
    Rarity: Rarity,
    Team: Team,
  },
};

function BasicElementsReveal() {
  var reveals = document.querySelectorAll(".slide-right-effect");

  for (var i = 0; i < reveals.length; i++) {
    var windowHeight = window.innerHeight;
    var elementTop = reveals[i].getBoundingClientRect().top;
    var elementVisible = 50;

    if (elementTop < windowHeight - elementVisible) {
      reveals[i].classList.add("active");
    }
  }
}

window.addEventListener("scroll", BasicElementsReveal);
</script>
<style>

.section-title{
  margin-top: 96px;
  margin-bottom: 24px;
}

.section-title .text-center{
  color: #ee7c19 !important;
}
</style>
