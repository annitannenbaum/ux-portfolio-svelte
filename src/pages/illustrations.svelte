<script>
  import Image from "../components/image.svelte";

  const left = 'juicewrldsmiley';
  const leftText = 'Man with dreadlocks and smileys for eyes';
  const right = 'juicewrldangel';
  const rightText = 'Man with dreadlocks and a halo';

  const style = 'height: 60vh; margin: 1rem; box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1); @media screen and (max-width: 1024px) { width: 100%; }';
</script>

<main>
  <div class="left-corner-gradient"></div>
  <div class="background-layer"></div>
  <div class="right-corner-gradient"></div>

  <div class="illustrations-container">
    <Image style={style} fileName={left} alt={leftText} />
    <Image style={style} fileName={right} alt={rightText} />
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