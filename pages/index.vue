

<template>
  <div class="container">
    <div class="trait">
      <h1>SUIVI DE COMMANDE</h1>
    </div>
    <div class="text-center">
      <img src="~/assets/vagues.png" alt="Vaguelette jaune">
    </div>
    <div class="d-flex justify-content-center mt-5" id="commande">
      <div class="d-flex flex-column w-50 p-3" id="commande2">
        <div class="p-2 bd-highlight">
          <ul>N° de commande : 405560003</ul>
          <ul>Date de commande : 1 mai 2019</ul>
          <ul>Date d'expedition : 3 mai 2019</ul>
        </div>
    <hr>
        <!-- Bouton accordéon -->
      <div class="accordion accordion-flush pl-4" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              Suivi de commande
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              Informations sur les retours
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
          </div>
        </div>
      </div>
      <hr>
    </div>

    <!-- liste articles -->
  <div>

        <div>
          <p>ARTICLES (4)</p>
        </div>

    <div class="w-100 p-3 mb-3 rectangle">

        <!-- <div> -->
          <img src="~/assets/matelas.png" alt="Photo de l'incroyable matelas Tediber" class="photosPanier">
        <!-- </div> -->
        <div class="inline">
          <h4>L'INCROYABLE MATELAS TEDIBER</h4>
          <div class="inline prixTaille">
            <p>750 €<br>TAILLE : 160 x 200 cm<br>QTE : 1</p>
          </div>
        </div>
      </div>

      <div class="w-100 p-3 mb-3 rectangle">
        <!-- <div> -->
          <img src="~/assets/oreiller.png" alt="Photo de l'incroyable matelas Tediber" class="photosPanier">
        <!-- </div> -->
        <div class="inline">
          <h4>L'INCROYABLE OREILLER TEDIBER</h4>
          <div class="inline prixTaille">
            <p>85 €<br>TAILLE : 60 x 60 cm<br>QTE : 2</p>
          </div>
        </div>
      </div>

      <div class="w-100 p-3 mb-3 rectangle">
        <!-- <div> -->
          <img src="~/assets/couette.png" alt="Photo de l'incroyable matelas Tediber" class="photosPanier">
        <!-- </div> -->
        <div class="inline">
          <h4>L'INCROYABLE COUETTE TEDIBER</h4>
          <div class="inline prixTaille">
            <p>210 €<br>TAILLE : 240 x 220 cm<br>QTE : 1</p>
          </div>
        </div>
      </div>
    </div>
    </div>
  <!-- encart Carte bancaire -->
    <div class="trait trait2 mt-3">
      <h1>INFORMATIONS DE PAIEMENT</h1>
    </div>
    <div class="text-center">
      <img src="~/assets/vagues.png" alt="Vaguelette jaune">
    </div>
    <div class="rectangle2 mt-4 mb-4">
      <img src="~/assets/visa.png" alt="">
      <p class="inline">VISA</p>
    </div>

    <!-- encart total commande -->
    <div>
      <div class="trait mt-3">
      <h1>TOTAL COMMANDE</h1>
    </div>
    <div class="text-center">
      <img src="~/assets/vagues.png" alt="Vaguelette jaune">
    </div>
    <div class="text-center rectangle2 mt-4 mb-4">
      <pre class="font p-3">Sous-totale             1130<br>Livraison     GRATUITE<br>TOTAL :                 1130</pre>
    </div>

  <!-- encart besoin d'aide -->
    <div class="trait mt-3">
      <h1>BESOIN D'AIDE</h1>
    </div>
    <div class="text-center">
      <img src="~/assets/vagues.png" alt="Vaguelette jaune">
    </div>

          <!-- Bouton accordéon -->
      <hr class="hrAide">
      <div class="accordion accordion-flush pl-4" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              FOIRE AUX QUESTIONS TEDIBER
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              LA GARANTIE TEDIBER
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              REPRISE DE L'ANCIENNE LITERIE
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              COMMENT FAIRE UN RETOUR ?
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
          </div>
        </div>

      </div>
      <hr class="hrAide">
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
.font{
  font-family: Gill-Sans;
  color:#212348;
}
.trait {
  background-size: cover;
  width:100% !important;
  margin:0 auto;
}
h1 {
  text-align:center;
  overflow:hidden;
  font-size:26px !important;
}
h1:before, h1:after {
  content:'';
  width: 100%;
  border-bottom:#212348 solid;
  display:inline-block;
  vertical-align:middle;
}
h1:before {
  margin-left:-100%;
  margin-right:1em
}
h1:after {
  margin-right:-100%;
  margin-left:1em;
}
#flush-headingOne button{
  font-family: Gill-Sans;
  color:#212348;
}
.photosPanier{
  width: 19%;
  top: -47%;
  position: relative;
}
.inline{
  display: inline-block;
}
.rectangle{
  border: #F1F1F1 solid;
  box-shadow: 10px 5px 5px #F1F1F1;
  height: 140px;
}
hr{
  height: 1px !important;
  background:#212348 !important;
}
.rectangle2{
  border: #F1F1F1 solid;
  box-shadow: 10px 5px 5px #F1F1F1;
}
.hrAide{
  width: 98%;
  margin-left: 26px;
}
.trait{
  width: 312px;
}

@media screen and (max-width: 991px) {
  #commande{
    display: block !important;
  }
  #commande2{
    width: 100% !important;
    padding:0;
  }
  .photosPanier{
    width: 40%;
    top: -43%;
  }
  .inline{
    width: 58% !important;
  }
  .inline h4{
    font-size: 16px;
  }
  .inline p{
    font-size: 12px;
    width: 100% !important;
  }
  .prixTaille{
    width: 100% !important;
  }
  .trait2{
    width: 247px;
  }
  .trait h1{
    font-size: 21px !important;
  }
}
</style>

