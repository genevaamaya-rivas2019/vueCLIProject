<template>
  <v-card class="mx-auto" max-width="400">
    <v-row>
      <v-col>
        <img :src="image" />
      </v-col>
      <!-- <v-col>{{name}}</v-col> -->
    </v-row>
    <v-card-title>{{name}}</v-card-title>
    <v-card-text class="text--primary">
      <div>{{position}}</div>
    </v-card-text>
  </v-card>
</template>
<script>
export default {
  props: {
    name: String,
    image: String,
    position: String
  }
};
</script>
<style scoped>
img {
  width: 100%;
  height: auto;
}
</style>
