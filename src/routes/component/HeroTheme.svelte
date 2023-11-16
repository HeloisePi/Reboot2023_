<script>
    export let srcImg;
    export let title
</script>


<section>
    <img src="{srcImg}" alt="{title}">
    <h1>{title}</h1>
</section>

<style>
    section{
        display: flex;
        width: 80vw;
        margin: 0 auto;
        height: 70vh;
        align-items: center;
        justify-content: center;
        gap: 2rem;
        border-bottom: 1px solid black;

    }
    img{
        width: 10rem;
    }
    h2{
        letter-spacing: 2px;
    }
</style>