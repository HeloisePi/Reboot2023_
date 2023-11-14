<footer>
    <div class="contenaire">

        <div class="">
            <h5>
                À propros
            </h5>
            <p>
                Qui sommes-nous
            </p>
            <p>
                Contacts
            </p>
        </div>
        <div class="">
            <h5>
                Mentions légales
            </h5>
            <p>
                Accessibilité
            </p>
            <p>
                Confidentialité
            </p>
            <p>
                Conditions
            </p>
        </div>
        <div class="">
            <h5>
                Feedback
            </h5>
            <form action="">
                <label for="">Prénom</label>
                <input type="text">
                <label for="">Message</label>
                <input type="text">
                <input type="submit">
            </form>
        </div>
        
    </div>
    <div class="end">
        <p>© Partenaires de crime - Tous droits réservés</p>
    </div>
</footer>
    
    <style>
        .contenaire{
            display: flex;
        justify-content: space-around;
        background-color: rgb(133, 133, 133);
        padding: 1rem;
    }

    .end{
        background-color: rgb(63, 63, 63);
        width: 100vw;
        padding: 1rem;
        text-align: center;
    }
    form{
        display: flex;
        flex-direction: column;
    }

    @media screen and (max-width: 500px) {
        .contenaire{
            flex-direction: column;
        }
    }
</style>
