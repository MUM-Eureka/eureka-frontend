<template>
  <div
    class="flex flex-col justify-center items-center gap-10 w-screen h-screen bg-gradient-to-br from-violetblue via-lightblue to-turquoise"
  >
    <img
      class="sm:w-1/2 md:w-1/3 lg:w-1/4 xl:w-1/5 2xl:w-1/6 w-1/2 h-auto"
      alt="Eureka logo"
      src="../assets/logo.png"
    />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloEureka from "../components/HelloEureka.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloEureka,
  },
})
export default class Home extends Vue {}
</script>
