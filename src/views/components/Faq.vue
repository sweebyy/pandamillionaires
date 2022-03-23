<template>
  <div id="faq" class="row justify-content-center">
    <div class="col-lg-12">
      <div class="accordion-menu">
        <ul>
          <li class="toFlip">
            <input type="checkbox" checked />
            <i class="arrow"></i>
            <h2><i class="fa fa-paw"></i>What is Panda Millionaires?</h2>
            <p>
     <strong>Panda Millionaires</strong> is NFT series composed of 2222 hand-drawn combinations of red panda.<br>
     <strong>Panda Millionaires</strong> is the first NFT project on near to ever give back 100% of the rewards generated from secondary market sales to the holders.<br>
     <strong>Panda Millionaires</strong> is not only about NFT but mostly a DAO planning to build big things on Near. 
            </p>
          </li>
          <li class="toFlip">
            <input type="checkbox" checked />
            <i class="arrow"></i>
            <h2>
              <i class="fa fa-paw"></i>What is the benefit for you? 
            </h2>
            <p>
If you hold at least one panda, you will benefit from the royalties that the project will generate. Stacking, floor sweep, giveaway... Everything will be determined by the DAO in order to make the most of the holders.<br>
A project that uses 100% of the royalties to build and do what the community needs and wants can really become something big. That's what we're clearly aiming for.

            </p>
          </li>
          <li class="toFlip">
            <input type="checkbox" checked />
            <i class="arrow"></i>
            <h2><i class="fa fa-paw"></i>What is the benefit for you?</h2>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
              reprehenderit in voluptate velit esse cillum dolore eu fugiat
              nulla pariatur.
              faq
            </p>
          </li>
          <li class="toFlip">
            <input type="checkbox" checked />
            <i class="arrow"></i>
            <h2><i class="fa fa-paw"></i>Wen?</h2>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
              reprehenderit in voluptate velit esse cillum dolore eu fugiat
              nulla pariatur.
            </p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>

function faqReveal() {
    
    var reveals = document.querySelectorAll(".toFlip");

    for (var i = 0; i < reveals.length; i++) {
        var windowHeight = window.innerHeight;
        var elementTop = reveals[i].getBoundingClientRect().top;
        var elementVisible = 50;

        if (elementTop < windowHeight - elementVisible) {
        reveals[i].classList.add("active");
        }
    }
}
  
window.addEventListener("scroll", faqReveal);


</script>
<style>
</style>
