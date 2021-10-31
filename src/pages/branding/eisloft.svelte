<script></script>

<main>
  <div class="container">
    <div class="description">
      <h3>Eisloft</h3>
      <p>Corporate Design for an ice cream shop.</p>
    </div>
    <div class="images">
      <img class="front-view" src="/assets/eisloft-mockup.png" alt="Eisloft shop front view">

      <div class="colors-illustrations">
        <img src="/assets/eisloft-logo.svg" alt="Eisloft logo">
        <div class="color-palette">
          <div class="color light-grey"></div>
          <div class="color dark-grey"></div>
          <div class="color light-beige"></div>
          <div class="color beige"></div>
          <div class="color sand"></div>
          <div class="color mauve"></div>
          <div class="color brown"></div>
          <div class="color red-brown"></div>
          <div class="color terracotta"></div>
        </div>
        <div class="illustrations">
          <img src="/assets/eisloft-icecream-illustration.svg" alt="Eisloft icecream illustration">
          <img src="/assets/eisloft-filter-illustration.svg" alt="Eisloft coffee filter illustration">
        </div>
      </div>

    </div>
  </div>
</main>

<style>

.front-view {
  max-width: 70%;
  width: auto;
  max-height: 60vh;
  height: auto;
  border-radius: 10px;
  margin: 0 2rem;
  box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
  -webkit-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
  -moz-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
}

.colors-illustrations {
  width: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.illustrations {
  margin: 2rem 0;
}

.illustrations img {
  margin: 2rem 0;
  width: 25%;
}

.color-palette {
  display: flex;
  flex-direction: row;
}
.color {
  width: 50px;
  height: 50px;
  margin: .5rem;
  border-radius: 5px;
  box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  -webkit-box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  -moz-box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
}

.light-grey {
  background-color: #F7F2F0;
}

.dark-grey {
  background-color: #808080;
}

.light-beige {
  background-color: #F2E3D3;
}

.beige {
  background-color: #EFCDAC;
}

.sand {
  background-color: #D9BA9E;
}

.mauve {
  background-color: #CDAA99;
}

.brown {
  background-color: #A17969;
}

.red-brown {
  background-color: #9C5C40;
}

.terracotta {
  background-color: #BD7254;
}

@media screen and (max-width: 1024px) {
  .colors-illustrations {
    width: 80%;
    align-items: center;
    margin: 2rem 0;
  }
}

</style>