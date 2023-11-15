<script>
	import Footer from "./component/Footer.svelte";
	import Header from "./component/Header.svelte";
	import HeaderMobile from "./component/HeaderMobile.svelte";

</script>

<div class="headerdesktop">
	<Header />
</div>
<div class="headerMobile">
	<HeaderMobile />
</div>

<div class="app">
	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	.headerMobile{
			display: none;
		}

  @media screen and (max-width: 500px) {
        footer p {
            font-size: 14px;
        }
    }
	@media screen and (max-width: 870px) {
		.headerMobile{
			display: block;
		}
		.headerdesktop{
			display: none;
		}
        
    }



	/*   Variable.css */
@font-face {
    font-family: 'HelveticaNeueInterface';
    src: url(/src/lib/assets/HelveticaNeueInterface.ttf);
}
@font-face {
    font-family: 'HelveticaNeueInterface_thin';
    src: url(/src/lib/assets/HelveticaNeueInterface_thin.ttf);
}

h1{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New'; 
    font-size: 4rem;
}

@media screen and (max-width: 750px) {
    h1{
        font-family: 'HelveticaNeueInterface_thin', 'Courier New';     
        font-size: 100px;
    }
}
@media screen and (max-width: 400px) {
    h1{     
        font-size: 2rem;
    }
}

h2{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 36px;
}

h3{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 1.25rem;
}

h4{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 1.25rem;
}

h5{
    font-family: 'HelveticaNeueInterface', 'Courier New';    
    font-size: 24px;
}

p{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 1.25rem;
}
label{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New'; 
}

a{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
   color: black; 
}

.bold{
    font-family: 'HelveticaNeueInterface' ;
}

/*    reset.css */

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
	background-color: red;
}

/* HTML5 display-role reset for older browsers */

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}


ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}




table {
    border-collapse: collapse;
    border-spacing: 0;
}
a{
    text-decoration: none;
}
* {
    box-sizing: border-box;
}

html, body{
    width: 100vw;
    overflow-x: hidden;
    scroll-behavior: smooth;
}

/* width */
::-webkit-scrollbar {
    width: 5px;
    height: 5px;
  }
  
  /* Track */
  ::-webkit-scrollbar-track {
    background: #f1f1f1; 
  }
   
  /* Handle */
  ::-webkit-scrollbar-thumb {
    background: #888; 
  }
  
  /* Handle on hover */
  ::-webkit-scrollbar-thumb:hover {
    background: #555; 
  }

img{
    width: fit-content;
    height: fit-content;
}
	</style>