<script>
    export let srcImg;
    export let title;
    export let src;
</script>


<a class="contenaire" href="{src}">
    <img class="illustration" src="{srcImg}" alt="suggestion">
    <div class="titleDescription">
        <h3 class="bold">{title}</h3>
        <p><slot></slot></p>
    </div>
    <img class="arrow" src="/images/logo/arrow.svg" alt="en savoir plus">
</a>

<style>
    .contenaire{
        width: 100%;
        display: flex;
        justify-content: space-between;
        gap: 1rem;
        align-items: center;
        border-radius: 15px;
        background: #ffffff;
        transition: 500ms;
        box-shadow:  13px 13px 26px #cccccc,
             -13px -13px 26px #ffffff;
             overflow: hidden;
        max-height: 200px;
        cursor: pointer;
    }
    .contenaire:hover{
        transform: scale(105%);
    }
    .titleDescription{
        padding-top: 1rem;
        padding-bottom: 1rem;
    }
    .arrow{
        padding-right: 1rem;
    }
    .illustration{
        width: 290px;
        
    }
    p{
        min-width: 250px;
    }
    @media screen and (max-width: 950px) {
        .contenaire{
            flex-direction: column;
            width: fit-content;
            height: fit-content;
            min-width: none;
            max-width: none;
            min-height: none;
            max-height: none;
        }
        p, h3{        
            width: 200px;
        }
        .arrow{
            padding-bottom: 1rem;
        }
    }
</style>