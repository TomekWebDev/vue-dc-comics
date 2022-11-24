<template>
  <div>
    <nav>
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="" />
      </div>
      <div class="headerNavbar">
        <div><a href="#">CHARACTERS</a></div>
        <div><a href="#">COMICS</a></div>
        <div><a href="#">MOVIES</a></div>
        <div><a href="#">TV</a></div>
        <div><a href="#">GAMES</a></div>
        <div><a href="#">COLLECTIBLES</a></div>
        <div><a href="#">VIDEOS</a></div>
        <div><a href="#">FANS</a></div>
        <div><a href="#">NEWS</a></div>
        <div><a href="#">SHOP</a></div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 80%;
  margin: auto;
}
.headerNavbar {
  display: flex;

  div {
    margin: 0 10px;
    height: 100px;
    display: flex;
    align-items: center;
  }
}

a {
  text-decoration: none;
  color: black;
}

.logo {
  padding: 1rem;
}
</style>