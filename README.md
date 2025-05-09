# Bootstrap.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Layout</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">MySite</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasMenu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse d-none d-lg-flex" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Features</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Offcanvas Menu -->
<div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasMenu">
  <div class="offcanvas-header">
    <h5 class="offcanvas-title">Menu</h5>
    <button type="button" class="btn-close" data-bs-dismiss="offcanvas"></button>
  </div>
  <div class="offcanvas-body">
    <ul class="list-unstyled">
      <li><a href="#" class="text-decoration-none d-block mb-2">Home</a></li>
      <li><a href="#" class="text-decoration-none d-block mb-2">About</a></li>
      <li><a href="#" class="text-decoration-none d-block mb-2">Services</a></li>
    </ul>
  </div>
</div>

<!-- Hero Section -->
<section class="bg-primary text-white text-center p-5">
  <h1>Welcome to MySite</h1>
  <p class="lead">A simple, responsive layout with Bootstrap 5</p>
</section>

<!-- Card Grid -->
<div class="container my-5">
  <div class="row g-4">
    <div class="col-md-4">
      <div class="card">
        <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card One</h5>
          <p class="card-text">Some quick content about the first card.</p>
          <a href="#" class="btn btn-primary">Explore</a>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card Two</h5>
          <p class="card-text">Details and features of the second card.</p>
          <a href="#" class="btn btn-primary">Explore</a>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card Three</h5>
          <p class="card-text">Learn more with the third card info.</p>
          <a href="#" class="btn btn-primary">Explore</a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
  <p class="mb-0">© 2025 MySite. All rights reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
