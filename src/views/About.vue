<template>
  <div class="about">
    <br />
    <center>
      <h1>
        <b>DEVELOPERS</b>
      </h1>
    </center>
    <br />
    <devprofile
      v-bind:image="require('@/assets/images/grace.jpg')"
      v-bind:name="'Mary Grace Tiburillo'"
      v-bind:position="'Software Developer and Project Manager'"
    ></devprofile>
    <devprofile
      v-bind:image="require('@/assets/images/gen.jpg')"
      v-bind:name="'Geneva Rivas'"
      v-bind:position="'Back-End Developer'"
    ></devprofile>
    <devprofile
      v-bind:image="require('@/assets/images/jessa.jpg')"
      v-bind:name="'Jessa Jalandoni'"
      v-bind:position="'Front-End Developer'"
    ></devprofile>
    <devprofile
      v-bind:image="require('@/assets/images/ivy.jpg')"
      v-bind:name="'Ivy Joy Devilleres'"
      v-bind:position="'Back-End Developer'"
    ></devprofile>
  </div>
</template>

<script>
import devprofile from "../components/DevelopersProfile";

export default {
  components: {
    devprofile
  }
};
</script>
<style scoped>
.about {
  /* background-color: pink; */
  background-image: url("../assets/images/dental.jpg");
  background-size: cover;
  width: 100%;
  height: 100%;
}
</style>