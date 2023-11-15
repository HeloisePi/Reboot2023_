<script>
    export let imgSrc;
    export let title;
    export let description;
</script>

<div class="contenaire">
    <img src="{imgSrc}" alt="{title}">
    <div class="titleDescription">
        <h4>{title}</h4>
        <p>{description}</p>
    </div>
</div>

<style>
    .contenaire{
        width: 250px;
        height: 500px;
        display: flex;
        flex-direction: column;
        border: 1px black;
        transition: 500ms;
    }
    .contenaire:hover{
        transform: scale(110%);
    }
    img{
        width: auto;
        height: auto;
    }

</style>