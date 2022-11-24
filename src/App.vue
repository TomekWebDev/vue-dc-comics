<template>
  <!-- Mappa della struttura con tutti i componenti che diventano "tag" -->
  <div id="app">
    <HeaderComp />
    <JumbotronComp />
    <ContentComp />
    <MainNav />
    <FooterNav />
    <FooterSocial />
  </div>
</template>

<script>
// Importare tutti i componenti che sono direttamente figli dell'app VUE
// I componenti figli di altri componenti sono importati solo all'interno del loro componente padre

import HeaderComp from "./components/HeaderComp.vue";
import JumbotronComp from "./components/JumbotronComp.vue";
import ContentComp from "./components/ContentComp.vue";
import MainNav from "./components/MainNav.vue";
import FooterNav from "./components/FooterNav.vue";
import FooterSocial from "./components/FooterSocial.vue";

// Export di default dei components che sono stati importati

export default {
  name: "App",
  components: {
    HeaderComp,
    JumbotronComp,
    ContentComp,
    MainNav,
    FooterNav,
    FooterSocial,
  },
};
</script>

<style lang="scss">
// Style scss generale con la possibilità di selezionare i tag annidandoli nella sintassi (vedi primo esempio in HeaderComp a riga 42)

#app {
  width: 100vw;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
