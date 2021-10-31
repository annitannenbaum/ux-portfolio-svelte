<script></script>

<main>
  <div class="container">
    <div class="description">
      <h3>Vermont7teen</h3>
      <p>Fashion Brand for Streetwear.</p>
    </div>
    <div class="images">
      <div class="logos">
        <img class="logo" src="/assets/vermont7teen-logo.png" alt="Vermont7teen logo">
        <div class="colors">
          <div class="color red"></div>
          <div class="color black"></div>
        </div>
        <img class="logo" src="/assets/vermont7teen-visual.png" alt="Vermont7teen visual">
      </div>
      <img class="hoodie" src="/assets/vermont7teen-front.png" alt="Vermont7teen hoodie front">
      <img class="hoodie" src="/assets/vermont7teen-back.png" alt="Vermont7teen hoodie back">
    </div>
  </div>
</main>

<style>

.logos {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 25vw;
}

.logo {
  width: 65%;
}

.hoodie {
  border-radius: 10px;
  box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
  -webkit-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
  -moz-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
  margin: 0 2rem;
  max-width: 25vw;
  max-height: 60vh;
  width: auto;
  height: auto;
}

.colors {
  display: flex;
  flex-direction: row;
  margin: 2rem 0;
}

.color {
  margin: .5rem;
  border-radius: 25px;
  box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  -webkit-box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  -moz-box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  width: 50px;
  height: 50px;
}

.red {
  background-color: #B10F46;
}

.black {
  background-color: #000000;
}

@media screen and (max-width: 1024px) {
  .logos {
    width: 80%;
  }

  .hoodie {
    max-width: 60vw;
    margin: 2rem 0;
  }
}

</style>