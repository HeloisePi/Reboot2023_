<script></script>

<div><slot></slot></div>

<style>
    div{
        border-radius: 50px;
        background: white;
        box-shadow:  20px 20px 60px #bebebe,
             -20px -20px 60px #ffffff;
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

    @media screen and (max-width: 400px) {
        div{
            box-shadow: none;
        }
    }
    @media screen and (max-width: 450px) {
        div{
        padding: 0rem;
    }
    }


</style>