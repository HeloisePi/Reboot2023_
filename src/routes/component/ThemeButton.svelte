<script>
    export let logo;
    export let src;
</script>


<a href="{src}" class="contenaire">
    <img src="{logo}" alt="">
    <p class="bold"><slot></slot></p>
</a>

<style>
    a{
        padding: 2rem;
        display: flex;
        flex-direction: column;
        width: 400px;
        height: 400px;
        border-radius: 38px;
        background: #ffffff;
        box-shadow:  13px 13px 26px #cccccc,
             -13px -13px 26px #ffffff;
        align-items: center;
        justify-content: center;
        gap: 1rem;
        transition: ease-in  500ms;
        cursor: pointer;

    }
    a:hover{
        border-radius: 38px;
        background: #ffffff;
        box-shadow: inset 13px 13px 26px #cccccc,
            inset -13px -13px 26px #ffffff;
    }
    p{
        max-width: 300px;
        text-align: center;
    }
    img{
        width: 170px;
    }
</style>