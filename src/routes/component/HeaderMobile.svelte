<script>
import { onMount } from 'svelte';

onMount(() => {
  const headermobile = document.querySelector(".headermobile");
  const toggle = document.querySelector(".toggle");
  const slide = document.querySelector(".slide");
  const hamburger = document.querySelector(".hamburger");
  const cross = document.querySelector(".cross");

  const handleClick = (e) => {
    console.log('ga');

    if (e.target.classList.contains("toggle")) {
      slide.classList.toggle("close");
      toggle.classList.toggle("is-close");
      hamburger.classList.toggle("active");
      cross.classList.toggle("active");


    }

    if (e.target.classList.contains("close-menu")) {
      slide.classList.remove("close");
    }
  };

  headermobile.addEventListener("click", handleClick);

  return () => {
    // Cleanup event listener on component destruction
    headermobile.removeEventListener("click", handleClick);
  };
});
</script>

<header class="headermobile">
    <div class="headershow">
      <a href="../../"><img class="logo" src="favicon.svg" alt="logo" /></a>
      <div class="toggle"></div>
      <div class="menu">
        <img class="hamburger active" src="/images/logo/hamburger.svg" alt="hamburger menu" />
        <img class="cross" src="/images/logo/cross.svg" alt="cross menu" />
      </div>
      
    </div>
    <div class="slide close">
      <a class="close-menu" href="../saga"><p>XXXXXXX</p></a>
      <a class="close-menu" href="../creationSerge"><p>XXXXXXX</p></a>
      <a class="close-menu" href="../#about"><p>XXXXXXX</p></a>
      <a class="close-menu" href="../#contact"><p>XXXXXXX</p></a>
    </div>
</header>


<style>
  .headershow .active{
    display: block;
  }
  .hamburger{
    display: none;
  }
  .cross{
    display: none;
  }

   .menu{
    width: 3rem;
    height: 3rem;
    position: absolute;
    right: 1rem;

  }
  .menu img{
    width: 100%;
    height: 100%;
  }
  .headermobile {
    top: 0;
    left: 0;
    z-index: 3;
    position: fixed;

  }
    
    .headershow {
      height: 70px;
      width: 100vw;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: white;
      padding: 1rem;
      z-index: 4;
    }

      .toggle{
        width: 3rem;
        height: 3rem;
        z-index: 100;
      }
        

      .logo {
        width: 4rem;
        height: fit-content;
      }
    
    .close {
      transform: translateX(100%);
    }
  
    .slide {
      background-color: white;
      height: 100vh;
      width: 50vw;
      right: 0;
      position: absolute;
      padding: 5%;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    a{
      color: black;
    }
    
</style>
