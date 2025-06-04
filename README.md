<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>loscorrales</title>
</head>
<body>
     <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Los Corrales - Productos Frescos y de Calidad</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* Estilos personalizados para Los Corrales */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa; /* Fondo gris claro */
            color: #333;
        }
        .navbar {
            box-shadow: 0 2px 4px rgba(0,0,0,.1);
        }
        .hero-section {
            background: linear-gradient(135deg, #28a745 0%, #1e7e34 100%); /* Gradiente verde */
            color: white;
            padding: 100px 0;
            text-align: center;
            border-bottom: 5px solid #1e7e34;
        }
        .hero-section h1 {
            font-size: 3.5rem;
            font-weight: bold;
        }
        .hero-section p {
            font-size: 1.5rem;
            max-width: 700px;
            margin: 0 auto 2rem;
            opacity: 0.9;
        }
        .section-title {
            font-size: 2.5rem;
            font-weight: bold;
            color: #343a40;
            margin-bottom: 2rem;
            position: relative;
            padding-bottom: 10px;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 70px;
            height: 4px;
            background-color: #28a745;
            border-radius: 2px;
        }
        .card {
            border: none;
            border-radius: 1rem;
            box-shadow: 0 0.5rem 1rem rgba(0,0,0,.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            height: 100%;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0.8rem 1.5rem rgba(0,0,0,.12);
        }
        .card-title {
            color: #28a745;
            font-size: 1.5rem;
            font-weight: bold;
        }
        .btn-custom-primary {
            background-color: #28a745;
            border-color: #28a745;
            color: white;
            padding: 0.7rem 2rem;
            font-size: 1.05rem;
            border-radius: 50px;
            transition: background-color 0.3s ease, border-color 0.3s ease;
        }
        .btn-custom-primary:hover {
            background-color: #218838;
            border-color: #1e7e34;
        }
        .bg-dark-light {
            background-color: #f0f0f0; /* Un gris muy claro */
        }
        .form-control:focus {
            border-color: #28a745;
            box-shadow: 0 0 0 0.25rem rgba(40, 167, 69, 0.25);
        }
        footer {
            background-color: #343a40;
            color: white;
            padding: 30px 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container">
            <a class="navbar-brand fs-4 fw-bold" href="#">Los Corrales</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#inicio">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#productos">Productos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#nosotros">Nosotros</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contacto">Contacto</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header id="inicio" class="hero-section d-flex align-items-center">
        <div class="container">
            <h1>¡Bienvenido a Los Corrales!</h1>
            <p class="lead">
                Tu destino en Montecristi para **productos frescos y de la mejor calidad**, directamente del campo a tu mesa.
            </p>
            <a href="#productos" class="btn btn-light btn-lg rounded-pill px-4 mt-3">Explorar Productos</a>
        </div>
    </header>

    <section id="productos" class="container my-5 py-4">
        <h2 class="text-center section-title mb-4">Nuestra Selección</h2>
        <p class="text-center lead mb-5">
            Descubre la excelencia en carnes, aves, lácteos y embutidos.
        </p>

        <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
            <div class="col">
                <div class="card h-100 shadow-sm">
                    <div class="card-body text-center">
                        <i class="bi bi-cow display-4 text-success mb-3"></i> <h5 class="card-title">Cortes de Carne Premium</h5>
                        <p class="card-text">
                            Selección de los mejores cortes de res, cerdo y cordero. Frescura y sabor garantizados.
                        </p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100 shadow-sm">
                    <div class="card-body text-center">
                        <i class="bi bi-egg-fried display-4 text-success mb-3"></i> <h5 class="card-title">Aves de Campo y Huevos</h5>
                        <p class="card-text">
                            Pollo y gallina criados naturalmente, además de huevos de granja.
                        </p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100 shadow-sm">
                    <div class="card-body text-center">
                        <i class="bi bi-journal-check display-4 text-success mb-3"></i> <h5 class="card-title">Embutidos y Lácteos </h5>
                        <p class="card-text">
                            Chorizos, jamones y quesos elaborados con recetas tradicionales y mucho amor.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    ---

    <section id="nosotros" class="container-fluid bg-dark-light py-5">
        <div class="container">
            <h2 class="text-center section-title mb-4">Conoce Los Corrales</h2>
            <div class="row justify-content-center">
                <div class="col-lg-8 text-center">
                    <p class="lead mb-4">
                        Con **más de 30 años de experiencia** en Montecristi, Los Corrales es sinónimo de **confianza y tradición**.
                        Nos dedicamos a seleccionar y ofrecer productos de la más alta calidad, apoyando a nuestros productores locales.
                    </p>
                    <p class="text-muted">
                        Nuestro compromiso es con la frescura, el sabor auténtico y la satisfacción total de nuestros clientes.
                        Ven y experimenta la diferencia.
                    </p>
                    <a href="#contacto" class="btn btn-outline-dark btn-lg rounded-pill mt-3">Pregúntanos</a>
                </div>
            </div>
        </div>
    </section>

    ---

    <section id="contacto" class="container my-5 py-4">
        <h2 class="text-center section-title mb-4">Contáctanos</h2>
        <div class="row justify-content-center">
            <div class="col-lg-7">
                <form class="p-4 bg-white rounded shadow-lg">
                    <div class="mb-3">
                        <label for="nombre" class="form-label fw-bold">Nombre</label>
                        <input type="text" class="form-control" id="nombre" required>
                    </div>
                    <div class="mb-3">
                        <label for="email" class="form-label fw-bold">Correo Electrónico</label>
                        <input type="email" class="form-control" id="email" required>
                    </div>
                    <div class="mb-4">
                        <label for="mensaje" class="form-label fw-bold">Mensaje</label>
                        <textarea class="form-control" id="mensaje" rows="5" required></textarea>
                    </div>
                    <div class="d-grid">
                        <button type="submit" class="btn btn-custom-primary btn-lg">Enviar Mensaje</button>
                    </div>
                </form>
            </div>
            <div class="col-lg-5 mt-4 mt-lg-0 text-center text-lg-start">
                <h4 class="text-success mb-3">Visítanos o Llámanos:</h4>
                <p class="fs-5 mb-2"><i class="bi bi-geo-alt-fill me-2"></i> Calle Principal S/N, Sector Los Bajos, Montecristi.</p>
                <p class="fs-5 mb-2"><i class="bi bi-telephone-fill me-2"></i>0968745698</p>
                <p class="fs-5 mb-2"><i class="bi bi-clock-fill me-2"></i> L-V: 6 AM - 8 PM | S: 8 AM - 6 PM</p>
                <p class="fs-5"><i class="bi bi-envelope-fill me-2"></i>loscorrales@gamil.com</p>
            </div>
        </div>
    </section>

    <footer class="text-center">
        <div class="container">
            <p class="mb-0">&copy; 2025 Los Corrales. Todos los derechos reservados.</p>
            <p class="mb-0 small text-muted">Diseñado con Bootstrap en Montecristi, Manabí, Ecuador.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</body>
</html>
