<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="img/brand/logo2.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <img src="img/brand/red-panda.png">
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <router-link to="#RoadmapTitle" class="btn btn-link navbar-text-default">Roadmap</router-link>
                <router-link to="#FaqTitle" class="btn btn-link navbar-text-default">FAQ</router-link>
                <router-link to="#RarityTitle" class="btn btn-link navbar-text-default">Rarity</router-link>
                <router-link to="#TeamTitle" class="btn btn-link navbar-text-default">Team</router-link>
            </ul>

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item" style="text-align: center;">
                    <button type="button" class="btn btn-primary" style="background-color: white;
    color: #ee7c19;
    border-color: #ee7c19;"><i class="fa fa-paw"></i> Coinflip</button>

                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};

</script>
<style>

</style>
