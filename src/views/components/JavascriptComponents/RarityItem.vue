<template>
  <div class="rarityItem-wrapper col-md-3 justify-content-center">
    <div class="property-card">
      <div class="property-image" :style="src"></div>
      <div class="property-description">
        <h6 class="rarityItemName"> {{itemName}}</h6>
        <h6 class="rarityItemPercentage">Rarity: {{rarityPercentage}}%</h6>
      </div>
    </div>
  </div>
</template>
 
<script>
export default {
  props: ["itemName", "rarityPercentage", "src"],
};
</script>
<style>
.rarityItem-wrapper{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 16px 24px;
}

.property-card {

  height: 18em;
  width: 14em;
  min-width: 14em;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  position: relative;
  -webkit-transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  -o-transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  border-radius: 16px;
  -webkit-box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
/* ^-- The margin bottom is necessary for the drop shadow otherwise it gets clipped in certain cases. */

/* Top Half of card, image. */

.property-image {
  height: 14em;
  width: 14em;
  padding: 1em 2em;
  position: Absolute;
  top: 0px;
  -webkit-transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  -o-transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  background-size: cover;
  background-repeat: no-repeat;
}

.property-card:hover{
    transform: scale(1.1);
}

/* Bottom Card Section */

.property-description {
  background-color: #fafafc;
  height: 4.5em;
  width: 14em;
  position: absolute;
  bottom: 0em;
  -webkit-transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  -o-transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  transition: all 0.4s cubic-bezier(0.645, 0.045, 0.355, 1);
  padding: 0.5em 1em;
  text-align: center;
}

.property-description h4 {
  padding: 6px;
  background: antiquewhite;
  border-radius: 5px;
}

.rarityItemName{
    font-weight: bold;

    padding-bottom: 6px;
    border-bottom: 1px solid rgba(17, 16, 16, 0.253);
}

</style>
