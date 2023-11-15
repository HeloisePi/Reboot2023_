<script>
 export let src;
 export let imgSrc;
</script>

<a href="{src}"><p><slot></slot></p></a>
{#if imgSrc}
    <img src="{imgSrc}" alt="bonton">
{/if}
<style>

</style>