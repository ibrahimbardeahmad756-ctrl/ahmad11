<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AHSUDALIS - Recycling Company Lagos</title>
    
    <!-- Bootstrap 5.3 CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    
    <style>
        :root {
            --primary-green: #2e7d32;
            --light-green: #4caf50;
            --bg-light: #e8f5e9;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .navbar {
            background-color: var(--primary-green) !important;
        }
        .navbar-brand img {
            height: 40px;
            margin-right: 10px;
        }
        .navbar-brand, .nav-link {
            color: white !important;
            font-weight: 600;
        }
        .nav-link:hover {
            color: #e0f2e9 !important;
        }
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&q=80') center/cover no-repeat;
            color: white;
            min-height: 70vh;
            display: flex;
            align-items: center;
            text-align: center;
            padding: 120px 20px;
        }
        .btn-primary-custom {
            background-color: var(--light-green);
            border-color: var(--light-green);
        }
        .btn-primary-custom:hover {
            background-color: #388e3c;
            border-color: #388e3c;
        }
        .section-title {
            color: var(--primary-green);
            font-weight: bold;
            margin-bottom: 2.5rem;
        }
        .card-img-top {
            height: 180px;
            object-fit: cover;
            border-top-left-radius: 0.375rem;
            border-top-right-radius: 0.375rem;
        }
        footer {
            background-color: var(--primary-green);
            color: white;
        }
        .form-success { color: var(--light-green); font-weight: bold; }
        .form-error { color: #dc3545; font-weight: bold; }
    </style>
</head>
<body>

    <!-- Navbar with Logo Image -->
    <nav class="navbar navbar-expand-lg fixed-top">
        <div class="container">
            <a class="navbar-brand d-flex align-items-center" href="#">
                <img src="https://img.freepik.com/free-photo/recycling-symbol-made-green-leaves_23-2152005815.jpg?semt=ais_hybrid&w=200" alt="AHSUDALIS Recycle Logo">
                AHSUDALIS Recycling
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1 class="display-3 fw-bold mb-4">AHSUDALIS Recycling</h1>
            <p class="lead mb-4">Sustainable waste management and recycling solutions in Lagos, Nigeria</p>
            <p class="mb-5">Turning waste into valuable resources – for a cleaner, greener tomorrow.</p>
            <a href="#contact" class="btn btn-primary-custom btn-lg px-5 py-3">Get a Quote Today</a>
        </div>
    </section>

    <!-- About Section with Image -->
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="section-title text-center">About Us</h2>
            <div class="row align-items-center">
                <div class="col-lg-6 mb-4 mb-lg-0">
                    <img src="https://plasticodyssey.org/wp-content/uploads/2024/07/visite-unilag-nigeria.jpg" class="img-fluid rounded shadow" alt="Workers sorting plastic bottles in Nigerian recycling facility">
                </div>
                <div class="col-lg-6">
                    <p class="lead">
                        AHSUDALIS Investment Nigeria Limited is a Lagos-based recycling company dedicated to environmental sustainability. 
                        We collect, sort, process, and recycle various materials including plastics, metals, paper, and e-waste.
                    </p>
                    <p>
                        Our mission is to reduce landfill waste, conserve natural resources, and create economic value through responsible recycling practices across Nigeria.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section with Images -->
    <section id="services" class="py-5" style="background-color: var(--bg-light);">
        <div class="container">
            <h2 class="section-title text-center">Our Services</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm border-0">
                        <img src="https://assets.bwbx.io/images/users/iqjWHBFdfxIU/i56_YJNPFeec/v2/-1x-1.webp" class="card-img-top" alt="Workers sorting plastic bottles in recycling">
                        <div class="card-body text-center">
                            <h3 class="card-title">Plastic Recycling</h3>
                            <p class="card-text">Collection, sorting, and processing of all types of plastic waste for reuse and manufacturing.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm border-0">
                        <img src="https://cdscrapmetal.com/wp-content/uploads/2024/08/mixed-scrap_1920-1200x630.jpg" class="card-img-top" alt="Pile of mixed metal scrap for recycling">
                        <div class="card-body text-center">
                            <h3 class="card-title">Metal Scrap</h3>
                            <p class="card-text">Buying and recycling ferrous and non-ferrous metals from households, industries, and construction sites.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm border-0">
                        <img src="https://wecyclers.com/_nuxt/img/recyclable_pickup.6e24624.jpg" class="card-img-top" alt="Recycling collection truck in Lagos">
                        <div class="card-body text-center">
                            <h3 class="card-title">Waste Collection</h3>
                            <p class="card-text">Reliable door-to-door pickup services for homes, offices, schools, and businesses.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm border-0">
                        <img src="https://cdn-ambpj.nitrocdn.com/jmDGlugVQTcwvvITmiNQuzuKVJBXzrwu/assets/images/optimized/rev-a610be2/sensoneo.com/wp-content/uploads/2023/03/11-1024x576.jpg" class="card-img-top" alt="Pile of electronic waste circuit boards">
                        <div class="card-body text-center">
                            <h3 class="card-title">E-Waste Management</h3>
                            <p class="card-text">Safe, certified collection and recycling of electronics to prevent environmental harm.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section with Form -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="section-title text-center">Contact Us</h2>
            <div class="row justify-content-center">
                <div class="col-lg-8 col-xl-6">

                    <!-- Contact Info -->
                    <div class="text-center mb-5">
                        <p class="fs-5">
                            <strong>Phone:</strong> +234-XXX-XXXXXXX<br>
                            <strong>Email:</strong> info@ahsudalis.com<br>
                            <strong>Address:</strong> Lagos, Nigeria (Add your full address here)
                        </p>
                        <p class="lead">Fill out the form below for pickup requests, quotes, or any inquiries!</p>
                    </div>

                    <!-- Contact Form (remember to replace endpoint) -->
                    <form action="https://formspree.io/f/YOUR_FORM_ID_HERE" method="POST" class="needs-validation" novalidate>
                        <input type="text" name="_gotcha" style="display:none" />

                        <div class="mb-3">
                            <label for="name" class="form-label">Full Name</label>
                            <input type="text" class="form-control" id="name" name="name" placeholder="Your name" required>
                            <div class="invalid-feedback">Please enter your name.</div>
                        </div>

                        <div class="mb-3">
                            <label for="email" class="form-label">Email address</label>
                            <input type="email" class="form-control" id="email" name="email" placeholder="name@example.com" required>
                            <div class="invalid-feedback">Please provide a valid email.</div>
                        </div>

                        <div class="mb-3">
                            <label for="subject" class="form-label">Subject</label>
                            <input type="text" class="form-control" id="subject" name="subject" placeholder="e.g. Quote for Plastic Recycling" required>
                            <div class="invalid-feedback">Please enter a subject.</div>
                        </div>

                        <div class="mb-4">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" name="message" rows="5" placeholder="Tell us about your needs..." required></textarea>
                            <div class="invalid-feedback">Please write your message.</div>
                        </div>

                        <div class="d-grid">
                            <button type="submit" class="btn btn-primary-custom btn-lg">Send Message</button>
                        </div>
                    </form>

                    <script>
                        (function () {
                            'use strict';
                            const form = document.querySelector('form.needs-validation');
                            form.addEventListener('submit', function (event) {
                                if (!form.checkValidity()) {
                                    event.preventDefault();
                                    event.stopPropagation();
                                }
                                form.classList.add('was-validated');
                            }, false);
                        })();
                    </script>

                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-4 text-center">
        <div class="container">
            <p class="mb-0">&copy; 2026 AHSUDALIS Recycling Company. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
