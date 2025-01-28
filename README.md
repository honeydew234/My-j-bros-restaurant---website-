<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Bella Cucina | Authentic Italian Restaurant</title>
    <!-- Bootstrap CSS for responsiveness -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
        .hero-section {
            background: url('https://example.com/restaurant-hero-image.jpg') no-repeat center center/cover;
            height: 80vh;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .navbar {
            background: rgba(0, 0, 0, 0.8);
        }
        .menu-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .footer {
            background: #333;
            color: white;
            padding: 2rem 0;
        }
        .btn-primary {
            background: #c39d63;
            border: none;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top">
        <div class="container">
            <a class="navbar-brand text-white" href="#">La Bella Cucina</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#menu">Menu</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section">
        <div class="container">
            <h1>Welcome to La Bella Cucina</h1>
            <p class="lead">Authentic Italian Flavors Since 1995</p>
            <a href="#menu" class="btn btn-primary btn-lg">Explore Our Menu</a>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Our Menu</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card menu-card">
                        <img src="https://example.com/pasta.jpg" alt="Pasta">
                        <div class="card-body">
                            <h5>Homemade Pasta</h5>
                            <p>Fresh pasta with truffle sauce. $18</p>
                        </div>
                    </div>
                </div>
                <!-- Add more menu items here -->
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Our Story</h2>
            <p>Founded in 1995, we bring the taste of Italy to your table...</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Visit Us</h2>
            <div class="row">
                <div class="col-md-6">
                    <h4>Address</h4>
                    <p>123 Main Street, New York, NY</p>
                    <h4>Hours</h4>
                    <p>Mon-Sun: 11 AM - 10 PM</p>
                </div>
                <div class="col-md-6">
                    <form>
                        <input type="text" class="form-control mb-3" placeholder="Name">
                        <input type="email" class="form-control mb-3" placeholder="Email">
                        <textarea class="form-control mb-3" placeholder="Message"></textarea>
                        <button class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container text-center">
            <p>Follow us on <a href="#" class="text-white">Instagram</a> and <a href="#" class="text-white">Facebook</a></p>
            <p>&copy; 2023 La Bella Cucina</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
