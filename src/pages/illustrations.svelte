<script>
  import Image from "../components/image.svelte";

  const left = 'juicewrldsmiley';
  const leftText = 'Man with dreadlocks and smileys for eyes';
  const right = 'juicewrldangel';
  const rightText = 'Man with dreadlocks and a halo';

  const className = 'illustration';
</script>

<main>
  <div class="left-corner-gradient"></div>
  <div class="background-layer"></div>
  <div class="right-corner-gradient"></div>

  <div class="illustrations-container">
      <Image className={className} fileName={left} alt={leftText} />
      <Image className={className} fileName={right} alt={rightText} />
  </div>
</main>

<style>
  .illustrations-container {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    padding: 5rem;
  }

  @media screen and (max-width: 1024px) {
    .illustrations-container {
      flex-direction: column;
    }
  }
</style>