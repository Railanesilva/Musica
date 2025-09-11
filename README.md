# Musica
Site simples sobre música

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mundo da Música</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css" rel="stylesheet">
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#inicio">🎵 Música</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#generos">Gêneros</a></li>
          <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li>
          <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- INÍCIO -->
  <header id="inicio" class="bg-dark text-white text-center p-5">
    <h1 class="display-4 fw-bold">Bem-vindo ao Mundo da Música</h1>
    <p class="lead">Explore ritmos, artistas e histórias que marcam gerações</p>
    <a href="#generos" class="btn btn-primary btn-lg">Começar</a>
  </header>

  <!-- GÊNEROS -->
  <section id="generos" class="container py-5">
    <h2 class="text-center mb-4">Principais Gêneros Musicais</h2>
    <div class="row text-center">
      <div class="col-md-4">
        <i class="bi bi-music-note-beamed display-4 text-primary"></i>
        <h4>Pop</h4>
        <p>Ritmos modernos que dominam as paradas de sucesso no mundo todo.</p>
      </div>
      <div class="col-md-4">
        <i class="bi bi-vinyl-fill display-4 text-danger"></i>
        <h4>Rock</h4>
        <p>Guitarras, bateria e muita atitude que marcaram gerações inteiras.</p>
      </div>
      <div class="col-md-4">
        <i class="bi bi-headphones display-4 text-success"></i>
        <h4>Hip-Hop</h4>
        <p>Batidas fortes, rimas marcantes e uma cultura que vai além da música.</p>
      </div>
    </div>
  </section>

  <!-- GALERIA -->
  <section id="galeria" class="bg-light py-5">
    <div class="container">
      <h2 class="text-center mb-4">Artistas em Destaque</h2>
      <div class="row g-4">
        <div class="col-md-3"><img src="https://picsum.photos/300/300?random=1" class="img-fluid rounded-4"></div>
        <div class="col-md-3"><img src="https://picsum.photos/300/300?random=2" class="img-fluid rounded-4"></div>
        <div class="col-md-3"><img src="https://picsum.photos/300/300?random=3" class="img-fluid rounded-4"></div>
        <div class="col-md-3"><img src="https://picsum.photos/300/300?random=4" class="img-fluid rounded-4"></div>
      </div>
    </div>
  </section>

  <!-- CONTATO -->
  <section id="contato" class="container py-5">
    <h2 class="text-center mb-4">Fale Conosco</h2>
    <form class="col-md-8 mx-auto">
      <div class="mb-3">
        <label for="nome" class="form-label">Railane</label>
        <input type="text" id="nome" class="form-control" placeholder="Railane">
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">railanesilvaa08@gmail.com</label>
        <input type="email" id="email" class="form-control" placeholder="Railanesilvaa08@gmail.com">
    
    
<section class="text-center py-4 bg-primary text-white">
  <h2>🎶 Explore o mundo da música!</h2>
  <p>Gêneros, artistas e diversão em um só site.</p>
</section>
