<template>
<div class="container">
  <div id="trait">
    <h2>SUIVI DE COMMANDE</h2>
  </div>
  <div class="text-center">
    <img src="~/assets/vagues.png" alt="Vaguelette jaune">
  </div>
  <div class="d-flex justify-content-center">
    <div>
        <ul>N° de commande : 405560003</ul>
        <ul>Date de commande : 1 mai 2019</ul>
        <ul>Date d'expedition : 3 mai 2019</ul>
      </div>
      <div>
        <p>test</p>
      </div>
  </div>









</div>




</template>

<script>


export default {

}
</script>

<style>

@font-face {
  font-family: 'Gill Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url('~assets/fonts/Gill_Sans_Std_Light.woff2') format('truetype');
}

@font-face {
  font-family: 'Gill Sans';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url('~assets/fonts/Gill_Sans_Std_Regular.woff2') format('truetype');
}
.container{
  font-family: Gill-Sans;
  color:#212348;
}

#trait {
  background-size: cover;
  width:800px;
  margin:0 auto;
}
h2 {
  text-align:center;
  overflow:hidden;
  font-size:26px;
}
h2:before, h2:after {
  content:'';
  width: 9em;
  border-bottom:#212348 solid;
  display:inline-block;
  vertical-align:middle;
}
h2:before {
  margin-left:-100%;
  margin-right:1em
}
h2:after {
  margin-right:-100%;
  margin-left:1em;
}



</style>

