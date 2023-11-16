<script >
  </script>

<footer>
    <div class="contenaire">

        <div class="">
            <h5>
                À propros
            </h5>
            <p>
                Qui sommes-nous
            </p>
        </div>
        <div class="">
            <h5>Plan du site</h5>
            <p>
                Se divertir
            </p>
            <p>
                Se vêtir
            </p>
            <p>
                Se nourrir
            </p>
            <p>
                Divers
            </p>
        </div>
        <div class="">
            <h5>
                Feedback
            </h5>
            <p class="pFeedback">Envoyez un mail à cette adresse mail, pour nous recommender des tips.</p>
        </div>

        
        
    </div>
    <div class="end">
        <p class="black">© Frynge - Tous droits réservés - Mentions Légales</p>
    </div>
</footer>
    
    <style>
h5{
    margin-bottom: 64px;
    margin-top: 64px;
}

p{
    margin-bottom: 32px;
}


        
        .contenaire{
            display: flex;
        justify-content: space-around;
        background-color: #303030;
        padding: 1rem;
    }

    .end{
        width: 100vw;
        padding: 1rem;
        text-align: center;
    }


    @media screen and (max-width: 740px) {
        .contenaire{
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        div{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
    }
    p, h5{
        color: white;
    }
    .black{
        color: black;
    }

    .pFeedback{
        max-width: 350px;
    }
</style>
