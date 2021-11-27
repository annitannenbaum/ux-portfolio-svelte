<script>
import { compute_rest_props } from "svelte/internal";

  export let fileName;
  export let alt;
</script>

<main>
  <picture>
    <source style="width: 100%" srcset="/assets/webp/{fileName}.webp" type="image/webp">
    <img style="width: 100%" src="/assets/png/{fileName}.png" alt={alt}>
  </picture>
</main>