<template>
  <NavBar />
  <router-view/>
  <FooterComp/>
</template>

<script>
import NavBar from "@/components/NavBar"
import FooterComp from "@/components/FooterComp.vue"
export default {
  components: { NavBar, FooterComp }
}
</script>

<style>

</style>
