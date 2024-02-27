<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fery - Fun Website</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <!-- Custom CSS -->
  <style>
    body {
      background-color: #f7f7f7;
    }
    .navbar {
      background-color: #FF69B4; /* Hot Pink */
    }
    .jumbotron {
      background-color: #FFD700; /* Gold */
      color: #000000; /* Black */
    }
    .card {
      background-color: #87CEEB; /* Sky Blue */
    }
    footer {
      background-color: #FF6347; /* Tomato */
      color: #ffffff; /* White */
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Fery</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="jumbotron text-center">
    <h1>Selamat Datang!</h1>
    <p>A fun and colorful website</p>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Card 1</h5>
            <p class="card-text">This is a fun card with some content.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Card 2</h5>
            <p class="card-text">Another fun card to enjoy!</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Card 3</h5>
            <p class="card-text">Last but not least, a fun card here.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <footer>
    <div class="container">
      <p>&copy; 2024 Fery - All Rights Reserved</p>
    </div>
  </footer>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
