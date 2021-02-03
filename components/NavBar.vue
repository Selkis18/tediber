<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light" id="navbar">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="~/assets/logo.png" alt="Logo Tediber">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            NOS PRODUITS
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a>
            </li>
          </ul>
          <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            LE CONCEPT
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a>
            </li>
          </ul>
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">AVIS</a>
        </li>
        <a class="navbar-brand" href="#">
          <img src="~/assets/logo2.png" alt="Logo Tediber" id="logo2">
        </a>
        <li class="nav-item">
          <a class="nav-link" href="#">PUB TV</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">MON COMPTE</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">MAG</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">CONTACTEZ-NOUS</a>
        </li>
        <a class="navbar-brand" href="#">
          <img src="~/assets/panier.png" alt="Logo Tediber">
        </a>
          </ul>
    </div>
  </div>
</nav>
</template>

<style>

#navbar{
  background: #ffffff !important;
  color: #212348;
}
#navbar ul li{
  padding: 19px 32px 19px 32px;
}
#navbar ul li a{
  color: #212348;
}
#logo2{
  padding: 0px 12px 0 12px;
}

</style>

