<script >
    // import emailjs from '@emailjs/browser';
	// import { onMount } from 'svelte';
    // onMount(() => {
    //     let user_mail = document.querySelector('#user_mail');
    //     let form = document.querySelector('form')
    // });
    // function sendEmail(e) {
    //   emailjs.sendForm('heloise.pingitore@mmibordeaux.com', user_mail, e.target, 'publicKey')
    //     .then((result) => {
    //         console.log('SUCCESS!', result.text);
    //     }, (error) => {
    //         console.log('FAILED...', error.text);
    //     });
    // }
  
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
            <form>
                <label class="bold" for="">Votre Mail</label>
                <input type="text" id="user_mail">
                <label class="bold" for="">Message</label>
                <textarea class="message"/>
                <input type="submit" value="Envoyer">
            </form>
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
input{
    height: 3rem;
    border-radius: 4px;
    background-color: white;
    margin-bottom: 64px;
    width: 10rem;
}
p, label{
    margin-bottom: 32px;
}

.message{
    height: 10rem;
    width: 20rem;
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
    form{
        display: flex;
        flex-direction: column;
    }

    @media screen and (max-width: 740px) {
        .contenaire{
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        div, form{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
    }
    p, a, h5, h4, h3, label{
        color: white;
    }
    .black{
        color: black;
    }
</style>
