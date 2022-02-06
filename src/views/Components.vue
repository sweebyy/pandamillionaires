<template>
    <div>
        <hero></hero>
        <basic-elements></basic-elements>
    </div>
</template>
<script>
import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";

export default {
  name: "components",
  components: {
    Hero,
    BasicElements
  }
};
</script>
