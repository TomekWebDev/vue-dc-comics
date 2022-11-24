<template>
  <div class="def">
    <nav>
      <div>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span><p>DIGITAL COMICS</p></span>
      </div>
      <div>
        <img src="../assets/img/buy-comics-merchandise.png" alt="" />
        <span><p>DC MERCHANDISE</p></span>
      </div>
      <div>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
        <span><p>SUBSCRIPTION</p></span>
      </div>
      <div>
        <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
        <span><p>COMIC SHOP LOCATOR</p></span>
      </div>
      <div>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
        <span><p>DC POWER VISA</p></span>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.def {
  background-color: blue;
}

nav {
  background-color: blue;
  display: flex;
  justify-content: space-around;
  width: 80%;
  margin: auto;
  padding: 3rem;

  div {
    display: flex;
    width: calc(100% / 5);

    align-items: center;

    img {
      width: 50px;
      height: 60px;
    }

    span {
      p {
        margin-left: 10px;
        font-size: 0.8rem;
      }
    }
  }
}

p {
  color: white;
}
</style>