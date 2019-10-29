<template>
  <div class="about">
   <b> DEVELOPERS</b><br>
    <jessa/><br>
    <ivy/><br>
    <gen/>
  </div>
</template>

<script>
import jessa from "../components/Jessa";
import ivy from "../components/Ivy";
import gen from "../components/Gen";


export default {
  name: "About",
  components: {
    jessa,
    ivy,
    gen
  }
};
</script>
<style scoped>
  .about{}
</style>