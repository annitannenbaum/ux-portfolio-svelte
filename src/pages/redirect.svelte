<script>
  import { onMount } from 'svelte';
  import { navigate } from 'svelte-routing';

  export let to;

  onMount(() => {
    console.log('blubb')
    navigate(to);
  });
</script>
<main></main>