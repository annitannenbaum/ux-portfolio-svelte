<script></script>

<main>
  <div class="container">
    <div class="description">
      <h3>Autotrade Ahrensburg</h3>
      <p>Corporate Design for a car processing company.</p>
    </div>
    <div class="images">
      <img class="scribble" src="/assets/aa-scribble.png" alt="Autotrade Ahrensburg handdrawn design">
      <div class="business-cards">
        <img class="business-card top" src="/assets/aa-businesscard-front.png" alt="Autotrade Ahrensburg business card front">
        <img class="business-card bottom" src="/assets/aa-businesscard-back.png" alt="Autotrade Ahrensburg business card back">
      </div>
      <div class="logos">
        <img class="logo top" src="/assets/aa-logo-2.png" alt="Autotrade Ahrensburg logo alternative">
        <img class="logo" src="/assets/aa-logo.png" alt="Autotrade Ahrensburg logo">
      </div>
    </div>
  </div>
</main>

<style>
  .business-cards, .logos {
    display: flex;
    flex-direction: column;
    margin: 0 2rem;
  }

  .scribble {
    width: 30vw;
    margin: 0 2rem;
  }

  .business-card {
    height: 22vh;
  }

  .business-card.top {
    margin-bottom: 3.5rem;
  }

  .logo {
    width: 60%;
  }

  .logo.top {
    width: 60%;
    margin-bottom: 3.5rem;
  }

  @media screen and (max-width: 1024px) {

    .business-cards, .logos {
      justify-content: center;
      align-items: center;
    }

    .scribble, .business-card, .business-card.top {
      width: 90%;
      margin: 2rem 0;
    }
  }
</style>