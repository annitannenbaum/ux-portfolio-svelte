<script>
  import Image from "../../components/image.svelte";

  const scribble = 'aa-scribble';
  const scribbleAlt = 'Autotrade Ahrensburg handdrawn design';

  const bcTop = 'aa-businesscard-front';
  const bcTopClass= 'business-card top';
  const bcTopAlt = 'Autotrade Ahrensburg business card front';

  const bcBottom = 'aa-businesscard-back';
  const bcBottomClass = 'business-card';
  const bcBottomAlt = 'Autotrade Ahrensburg business card back';

  const logoTop = 'aa-logo-2';
  const logoClass = 'logo';
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
        <Image className={scribble} fileName={scribble} alt={scribbleAlt} />
      <div class="business-cards">
          <Image className={bcTopClass} fileName={bcTop} alt={bcTopAlt}/>
          <Image className={bcBottomClass} fileName={bcBottom} alt={bcBottomAlt}/>
      </div>
      <div class="logos">
          <Image className={logoClass} fileName={logoTop} alt={logoTopAlt}/>
          <Image className={logoClass} fileName={logo} alt={logoAlt}/>
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

  @media screen and (max-width: 1024px) {

    .business-cards, .logos {
      justify-content: center;
      align-items: center;
    }
  }
</style>