<script>
    export let logo;
    export let src;
</script>

<a href="{src}">
    {#if logo}
    <img src="{logo}" alt="logo">
    {/if}
    <h3><slot/></h3>
    
</a>

<style>
    a{
        display: flex;
        width: 280px;
        height: 180px;
        border-radius: 38px;
        background: #ffffff;
        box-shadow:  13px 13px 26px #cccccc,
             -13px -13px 26px #ffffff;
        align-items: center;
        justify-content: center;
        gap: 0.5rem;
        transition: ease-in  500ms;
        cursor: pointer;
    }
    a:hover{
        border-radius: 38px;
        background: #ffffff;
        box-shadow: inset 13px 13px 26px #cccccc,
            inset -13px -13px 26px #ffffff;
    }
</style>