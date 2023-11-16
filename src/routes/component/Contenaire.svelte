<script></script>

<div><slot></slot></div>

<style>
    div{
        background: white;
        border-radius: 10px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 5rem;
            padding-top: 2rem;
            padding-bottom: 2rem;
            margin-top: 5rem;
            margin-bottom: 5rem;
            max-width: 100%;
            height: fit-content;

    }

    @media screen and (max-width: 450px) {
        div{
        padding: 0rem;
    }
    div{
            box-shadow: none;
        }
    }


</style>