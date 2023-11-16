<script>
    export let title;
    export let horaire;
    export let map;
    export let phone;
</script>


<div class="contenaire">
    <h3 class="bold">{title}</h3>
    <div>
        <img src="/images/logo/clock.svg" alt="horaires">
        <p>{horaire}</p>
    </div>
    <div>
        <img src="/images/logo/map.svg" alt="map">
        <p>{map}</p>
    </div>
    <div>
        <img src="/images/logo/phone.svg" alt="phone">
        <p>{phone}</p>
    </div>
</div>


<style>
    .contenaire{
        width: 560px;
        height: 400px;
        border-radius: 50px;
        background: white;
        box-shadow:  20px 20px 60px #bebebe,
             -20px -20px 60px #ffffff;
            display: flex;
            flex-direction: column;
            justify-content: start;
            align-items: start;
            gap: 2rem;
            padding: 5rem;
            padding-top: 2rem;
            padding-bottom: 2rem;
            margin-top: 5rem;
            margin-bottom: 5rem;
    }
    .contenaire div{
        display: flex;
        flex-direction: row;
        gap: 1rem;
        align-items: center;
    }
</style>