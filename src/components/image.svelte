<script>

  export let fileName;
  export let alt;
  export let className;

</script>

<main>
  <picture>
    <source class={className} srcset="/assets/webp/{fileName}.webp" type="image/webp">
    <img class={className} src="/assets/png/{fileName}.png" alt={alt}>
  </picture>
</main>