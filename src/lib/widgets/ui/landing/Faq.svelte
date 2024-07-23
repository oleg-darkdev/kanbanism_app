<script>
  import { FaqCard } from '$lib/entities'
  import { faqData } from '$lib/shared'
</script>

<section class='mb-20'>
    {#each faqData as faq}
        <FaqCard {faq} />
    {/each}
</section>


<style>

</style>
