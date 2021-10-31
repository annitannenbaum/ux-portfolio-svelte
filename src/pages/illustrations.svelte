<script></script>

<main>
  <div class="left-corner-gradient"></div>
  <div class="background-layer"></div>
  <div class="right-corner-gradient"></div>

  <div class="illustrations-container">
    <img class="illustration" src="/assets/juicewrldsmiley.png" alt="Man with dreadlocks and smileys for eyes">
    <img class="illustration" src="/assets/juicewrldangel.png" alt="Man with dreadlocks and a halo">
  </div>
</main>

<style>
  .illustrations-container {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    padding: 5rem;
  }

  .illustration {
    height: 60vh;
    margin: 1rem;
    box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  }

  @media screen and (max-width: 1024px) {
    .illustrations-container {
      flex-direction: column;
    }

    .illustration {
      width: 100%;
    }
  }
</style>