<script>
  import Image from "../../components/image.svelte";

  const visualClass = 'petit-family-visual';

  const firstVisualName = 'petitfamily';
  const firstVisualAlt = 'Petit Family Logo';

  const secondVisualName = 'petitfamily2';
  const secondVisualAlt = 'Petit Family Branding';

</script>

<main>
  <div class="container">
    <div class="description">
      <h3>Petit Family</h3>
      <p>Corporate Design for Baby & Young Fashion.</p>
    </div>
    <div class="images">
      <Image className={visualClass} fileName={firstVisualName} alt={firstVisualAlt} />
      <Image className={visualClass} fileName={secondVisualName} alt={secondVisualAlt} />
    </div>
  </div>
</main>