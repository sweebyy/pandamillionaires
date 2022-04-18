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
     <strong>Panda Millionaires</strong> is NFT series composed of 777 hand-drawn combinations of red panda.<br>
     <strong>Panda Millionaires</strong> is the first NFT project on near which plans a jackpot players versus players<br>
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
If you hold at least one panda, you will benefit from the royalties that the project will generate. App, floor sweep, giveaway... Everything will be determined by the DAO in order to make the most of the holders.<br>
A project that uses 50% of the royalties to build and do what the community needs and wants can really become something big. That's what we're clearly aiming for.

            </p>
          </li>
          <li class="toFlip">
            <input type="checkbox" checked />
            <i class="arrow"></i>
            <h2><i class="fa fa-paw"></i>What is the mint price?</h2>
            <p>
              WL Mint : <strong>3 Near</strong><br>
              Public Mint : <strong>4</strong> Near
            </p>
          </li>
          <li class="toFlip">
            <input type="checkbox" checked />
            <i class="arrow"></i>
            <h2><i class="fa fa-paw"></i>When?</h2>
            <p>
 We plan to mint at the 30th April, thanks to Enleap's amazing Launchpad.<br>
 The Enleap team guarantees a smooth minting experience.
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
