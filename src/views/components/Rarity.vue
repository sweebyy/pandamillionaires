<template>
  <div id="rarity" class="row justify-content-center">
    <div class="col-lg-8">
      <tabs fill class="flex-column flex-md-row">
        <card slot-scope="{ activeTabIndex }" style="border: none">
          <tab-pane key="tab1" style="display:flex; align-items:center">
            <template slot="title">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-person"
                viewBox="0 0 16 16"
              >
                <path
                  d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10z"
                /></svg
              >&nbsp;&nbsp;Body
            </template>

            <div class="row justify-content-center">

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />
            </div>

            
          </tab-pane>

          <tab-pane key="tab2">
            <template slot="title">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-paint-bucket"
                viewBox="0 0 16 16"
              >
                <path
                  d="M6.192 2.78c-.458-.677-.927-1.248-1.35-1.643a2.972 2.972 0 0 0-.71-.515c-.217-.104-.56-.205-.882-.02-.367.213-.427.63-.43.896-.003.304.064.664.173 1.044.196.687.556 1.528 1.035 2.402L.752 8.22c-.277.277-.269.656-.218.918.055.283.187.593.36.903.348.627.92 1.361 1.626 2.068.707.707 1.441 1.278 2.068 1.626.31.173.62.305.903.36.262.05.64.059.918-.218l5.615-5.615c.118.257.092.512.05.939-.03.292-.068.665-.073 1.176v.123h.003a1 1 0 0 0 1.993 0H14v-.057a1.01 1.01 0 0 0-.004-.117c-.055-1.25-.7-2.738-1.86-3.494a4.322 4.322 0 0 0-.211-.434c-.349-.626-.92-1.36-1.627-2.067-.707-.707-1.441-1.279-2.068-1.627-.31-.172-.62-.304-.903-.36-.262-.05-.64-.058-.918.219l-.217.216zM4.16 1.867c.381.356.844.922 1.311 1.632l-.704.705c-.382-.727-.66-1.402-.813-1.938a3.283 3.283 0 0 1-.131-.673c.091.061.204.15.337.274zm.394 3.965c.54.852 1.107 1.567 1.607 2.033a.5.5 0 1 0 .682-.732c-.453-.422-1.017-1.136-1.564-2.027l1.088-1.088c.054.12.115.243.183.365.349.627.92 1.361 1.627 2.068.706.707 1.44 1.278 2.068 1.626.122.068.244.13.365.183l-4.861 4.862a.571.571 0 0 1-.068-.01c-.137-.027-.342-.104-.608-.252-.524-.292-1.186-.8-1.846-1.46-.66-.66-1.168-1.32-1.46-1.846-.147-.265-.225-.47-.251-.607a.573.573 0 0 1-.01-.068l3.048-3.047zm2.87-1.935a2.44 2.44 0 0 1-.241-.561c.135.033.324.11.562.241.524.292 1.186.8 1.846 1.46.45.45.83.901 1.118 1.31a3.497 3.497 0 0 0-1.066.091 11.27 11.27 0 0 1-.76-.694c-.66-.66-1.167-1.322-1.458-1.847z"
                /></svg
              >&nbsp;Background
            </template>

            <div class="row justify-content-center">
                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />
            </div>
          </tab-pane>

          <tab-pane key="tab4">
            <template slot="title">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-mortarboard"
                viewBox="0 0 16 16"
              >
                <path
                  d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917l-7.5-3.5ZM8 8.46 1.758 5.965 8 3.052l6.242 2.913L8 8.46Z"
                />
                <path
                  d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466 4.176 9.032Zm-.068 1.873.22-.748 3.496 1.311a.5.5 0 0 0 .352 0l3.496-1.311.22.748L8 12.46l-3.892-1.556Z"
                /></svg
              >&nbsp;&nbsp;Hat
            </template>

            <div class="row justify-content-center">

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />
            </div>
          </tab-pane>

          <tab-pane key="tab5">
            <template slot="title">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-emoji-smile"
                viewBox="0 0 16 16"
              >
                <path
                  d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
                />
                <path
                  d="M4.285 9.567a.5.5 0 0 1 .683.183A3.498 3.498 0 0 0 8 11.5a3.498 3.498 0 0 0 3.032-1.75.5.5 0 1 1 .866.5A4.498 4.498 0 0 1 8 12.5a4.498 4.498 0 0 1-3.898-2.25.5.5 0 0 1 .183-.683zM7 6.5C7 7.328 6.552 8 6 8s-1-.672-1-1.5S5.448 5 6 5s1 .672 1 1.5zm4 0c0 .828-.448 1.5-1 1.5s-1-.672-1-1.5S9.448 5 10 5s1 .672 1 1.5z"
                /></svg
              >&nbsp;&nbsp;Face
            </template>

            <div class="row justify-content-center">
                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />
            </div>
          </tab-pane>

          <tab-pane key="tab6">
            <template slot="title">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-eye"
                viewBox="0 0 16 16"
              >
                <path
                  d="M16 8s-3-5.5-8-5.5S0 8 0 8s3 5.5 8 5.5S16 8 16 8zM1.173 8a13.133 13.133 0 0 1 1.66-2.043C4.12 4.668 5.88 3.5 8 3.5c2.12 0 3.879 1.168 5.168 2.457A13.133 13.133 0 0 1 14.828 8c-.058.087-.122.183-.195.288-.335.48-.83 1.12-1.465 1.755C11.879 11.332 10.119 12.5 8 12.5c-2.12 0-3.879-1.168-5.168-2.457A13.134 13.134 0 0 1 1.172 8z"
                />
                <path
                  d="M8 5.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5zM4.5 8a3.5 3.5 0 1 1 7 0 3.5 3.5 0 0 1-7 0z"
                /></svg
              >&nbsp;&nbsp;Eye
            </template>

            <div class="row justify-content-center">

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />
            </div>
          </tab-pane>

          <tab-pane key="tab7">
            <template slot="title">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-ear"
                viewBox="0 0 16 16"
              >
                <path
                  d="M8.5 1A4.5 4.5 0 0 0 4 5.5v7.047a2.453 2.453 0 0 0 4.75.861l.512-1.363a5.553 5.553 0 0 1 .816-1.46l2.008-2.581A4.34 4.34 0 0 0 8.66 1H8.5ZM3 5.5A5.5 5.5 0 0 1 8.5 0h.16a5.34 5.34 0 0 1 4.215 8.618l-2.008 2.581a4.555 4.555 0 0 0-.67 1.197l-.51 1.363A3.453 3.453 0 0 1 3 12.547V5.5ZM8.5 4A1.5 1.5 0 0 0 7 5.5v2.695c.112-.06.223-.123.332-.192.327-.208.577-.44.72-.727a.5.5 0 1 1 .895.448c-.256.513-.673.865-1.079 1.123A8.538 8.538 0 0 1 7 9.313V11.5a.5.5 0 0 1-1 0v-6a2.5 2.5 0 0 1 5 0V6a.5.5 0 0 1-1 0v-.5A1.5 1.5 0 0 0 8.5 4Z"
                /></svg
              >&nbsp;&nbsp;Ear
            </template>

            <div class="row justify-content-center">
                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-2.png');"
                />

                <RarityItem
                itemName="Robe Type 3"
                rarityPercentage="5"
                src="background-image:url('./img/brand/roadmap-1.png');"
                />
            </div>
          </tab-pane>
        </card>
      </tabs>
    </div>
  </div>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
import RarityItem from "./JavascriptComponents/RarityItem.vue";
export default {
  components: {
    Tabs,
    TabPane,
    RarityItem,
  },
};

function rarityReveal() {
    
    var reveals = document.querySelectorAll("#rarity");

    for (var i = 0; i < reveals.length; i++) {
        var windowHeight = window.innerHeight;
        var elementTop = reveals[i].getBoundingClientRect().top;
        var elementVisible = 50;

        if (elementTop < windowHeight - elementVisible) {
        reveals[i].classList.add("active");
        }
    }
}
  
window.addEventListener("scroll", rarityReveal);

</script>
<style>

#rarity.active {
	-webkit-animation: slide-in-bck-center 1.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
	        animation: slide-in-bck-center 1.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
}

@-webkit-keyframes slide-in-bck-center {
  0% {
    -webkit-transform: translateZ(600px);
            transform: translateZ(600px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateZ(0);
            transform: translateZ(0);
    opacity: 1;
  }
}
@keyframes slide-in-bck-center {
  0% {
    -webkit-transform: translateZ(600px);
            transform: translateZ(600px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateZ(0);
            transform: translateZ(0);
    opacity: 1;
  }
}

</style>
