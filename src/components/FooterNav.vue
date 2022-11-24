<template>
  <div class="def">
    <div class="flex">
      <div>
        <h3>DC COMICS</h3>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>

        <h3>SHOP</h3>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <div>
        <h3>DC</h3>
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy Policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <div>
        <h3>SITES</h3>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>

      <div class="dcBg"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.def {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}

h3 {
  color: white;
}

li {
  list-style: none;
  color: gray;
}

ul {
  padding-inline-start: 0px;
}

.flex {
  display: flex;
  width: 90%;
  margin: auto;

  div {
    padding: 1rem;
  }
}

.dcBg {
  width: 400px;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-size: cover;
  margin-left: 300px;
}
</style>