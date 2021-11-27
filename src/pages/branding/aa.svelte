<script>
  import Image from "../../components/image.svelte";

  const scribble = 'aa-scribble';
  const scribbleAlt = 'Autotrade Ahrensburg handdrawn design';

  const bcTop = 'aa-businesscard-front';
  const bcTopAlt = 'Autotrade Ahrensburg business card front';

  const bcBottom = 'aa-businesscard-back';
  const bcBottomAlt = 'Autotrade Ahrensburg business card back';

  const logoTop = 'aa-logo-2';
  const logoTopAlt = 'Autotrade Ahrensburg logo alternative';

  const logo = 'aa-logo';
  const logoAlt = 'Autotrade Ahrensburg logo';

</script>

<main>
  <div class="container">
    <div class="description">
      <h3>Autotrade Ahrensburg</h3>
      <p>Corporate Design for a car processing company.</p>
    </div>
    <div class="images">
      <div class="scribble">
        <Image fileName={scribble} alt={scribbleAlt} />
      </div>
      <div class="business-cards">
        <div class="business-card top">
          <Image fileName={bcTop} alt={bcTopAlt}/>
        </div>
        <div class="business-card">
          <Image fileName={bcBottom} alt={bcBottomAlt}/>
        </div>
      </div>
      <div class="logos">
        <div class="logo">
          <Image fileName={logoTop} alt={logoTopAlt}/>
        </div>
        <div class="logo">
          <Image fileName={logo} alt={logoAlt}/>
        </div>
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
    width: 25vw;
  }

  .business-card.top {
    margin-bottom: 2rem;
  }

  .logo {
    width: 60%;
    margin-bottom: 3.5rem;
  }

  @media screen and (max-width: 1024px) {

    .business-cards, .logos {
      justify-content: center;
      align-items: center;
    }

    .scribble, .business-card {
      width: 90%;
      margin: 2rem 0;
    }

    .logo {
      margin: 0 auto;
    }
  }
</style>