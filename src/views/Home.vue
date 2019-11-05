<template>
  <v-container fluid fill-height class="home" style="max-height:100vh;">
    <v-layout justify-center align-center column pa-5>
      <div id="app" class="home">
        <center>
          <v-img
            class="white--text align-end"
            height="50%"
            width="50%"
            src="@/assets/images/tooth.png"
          ></v-img>
        </center>
        <p>
          <center>
            <h1>
              <b>ToothBook</b>
            </h1>
          </center>
        </p>
      </div>
    </v-layout>
  </v-container>
</template>

<script>
//import axios from "axios";

export default {
  name: "Home",
  components: {}
};
</script>

<style scoped>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

.btn:hover {
  background: #666;
}
.home {
  background-image: url("../assets/images/dental.jpg");
  background-size: cover;
  width: 100%;
  height: 100%;
}
</style>
