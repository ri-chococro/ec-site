<template>
  <footer>
    <div class="container">
      <img src="img/header_logo.png" />
      <p>アロハな気分をあなたにお届け！</p>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class Footer extends Vue {}
</script>

<style scoped>
footer img {
  width: 200px;
}

footer p {
  color: #b3aeb5;
  font-size: 15px;
}

footer {
  padding-top: 5px;
  padding-bottom: 5px;
}
</style>
