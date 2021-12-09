<script>
  import Image from "../../components/image.svelte";

  const logoClass = 'logo-v17';
  const logoName = 'vermont7teen-logo';
  const logoAlt = 'Vermont7teen logo';

  const visualName = 'vermont7teen-visual';
  const visualAlt = 'Vermont7teen visual';

  const hoodieClass = 'hoodie';
  const hoodieFrontName = 'vermont7teen-front';
  const hoodieFrontAlt = 'Vermont7teen hoodie front';
  
  const hoodieBackName = 'vermont7teen-back';
  const hoodieBackAlt = 'Vermont7teen hoodie back';

</script>

<main>
  <div class="container">
    <div class="description">
      <h3>Vermont7teen</h3>
      <p>Fashion Brand for Streetwear.</p>
    </div>
    <div class="images">
      <div class="logos">
        <Image className={logoClass} fileName={logoName} alt={logoAlt} />
        <div class="colors">
          <div class="color red"></div>
          <div class="color black"></div>
        </div>
        <Image className={logoClass} fileName={visualName} alt={visualAlt} />
      </div>
      <Image className={hoodieClass} fileName={hoodieFrontName} alt={hoodieFrontAlt} />
      <Image className={hoodieClass} fileName={hoodieBackName} alt={hoodieBackAlt} />
    </div>
  </div>
</main>

<style>

.logos {
  display: flex;
  flex-direction: column;
  width: 20vw;
  margin-left: 2rem;
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
}

</style>