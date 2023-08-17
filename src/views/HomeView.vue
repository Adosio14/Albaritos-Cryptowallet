<template>
  <div class="container-fluid home">
    
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  components: {
  },
})
export default class HomeView extends Vue {}
</script>
<style scoped>
.home{
  height: 100vh;
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' version='1.1' xmlns:xlink='http://www.w3.org/1999/xlink' xmlns:svgjs='http://svgjs.dev/svgjs' width='2560' height='1440' preserveAspectRatio='none' viewBox='0 0 2560 1440'%3e%3cg mask='url(%26quot%3b%23SvgjsMask1078%26quot%3b)' fill='none'%3e%3crect width='2560' height='1440' x='0' y='0' fill='rgba(112%2c 238%2c 156%2c 1)'%3e%3c/rect%3e%3cpath d='M 0%2c304 C 170.8%2c342.4 512.4%2c517.8 854%2c496 C 1195.6%2c474.2 1366.8%2c219.4 1708%2c195 C 2049.2%2c170.6 2389.6%2c338.2 2560%2c374L2560 1440L0 1440z' fill='rgba(121%2c 174%2c 163%2c 1)'%3e%3c/path%3e%3cpath d='M 0%2c1041 C 170.8%2c1069 512.4%2c1174.4 854%2c1181 C 1195.6%2c1187.6 1366.8%2c1058.6 1708%2c1074 C 2049.2%2c1089.4 2389.6%2c1221.2 2560%2c1258L2560 1440L0 1440z' fill='rgba(67%2c 67%2c 113%2c 1)'%3e%3c/path%3e%3c/g%3e%3cdefs%3e%3cmask id='SvgjsMask1078'%3e%3crect width='2560' height='1440' fill='white'%3e%3c/rect%3e%3c/mask%3e%3c/defs%3e%3c/svg%3e");
  background-size: cover;
}
</style>
