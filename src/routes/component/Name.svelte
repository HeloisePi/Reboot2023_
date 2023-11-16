<script>
    export let name;
    export let adresse;
    export let mail;
</script>

<div class="">
<h4 class="bold">{name}</h4>
<p>{adresse}</p>
<p>{mail}</p>
</div>
<style>
    div{
        display: flex;
        flex-direction: column;
        gap: 0.4;
    }
</style>