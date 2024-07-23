<script>
  import { BeneficialCard } from '$lib/entities'
  import { beneficialData } from '$lib/shared'
</script>

<section>
  {#each beneficialData as benefits}
      <BeneficialCard {benefits} />
  {/each}
</section>

<style>

</style>
