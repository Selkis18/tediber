<template>
  <div>
    <NavBar />
    <nuxt/>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar'  // permet d'importer le fichier navbar de components
export default {
  components: { NavBar } // permet d'appeler le fichier NavBar dans le code html au dessus
}
</script>

<style>

</style>

