<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>E-Commerce Website</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <style>
        html {
            scroll-behavior: smooth;
        }
        
        body {
            background-color: #d9f3ff;
        }
        
        .card img {
            height: 250px;
            object-fit: cover;
        }
        
        section {
            padding-top: 70px;
            padding-bottom: 70px;
        }
        
        .hero {
            height: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header class="bg-dark text-light p-3 d-flex justify-content-between align-items-center px-5 sticky-top">

        <h2>Site Name</h2>

        <ul class="nav">
            <li><a class="nav-link text-light" href="#shop">Shop</a></li>
            <li><a class="nav-link text-light" href="#service">Service</a></li>
            <li><a class="nav-link text-light" href="#about">About</a></li>
            <li><a class="nav-link text-light" href="#contact">Contact</a>
            </li>
        </ul>

        <div>
            <i class="fa-solid fa-user me-3"></i>
            <i class="fa-solid fa-cart-shopping"></i>
        </div>

    </header>

    <!-- HERO SECTION -->
    <section class="hero bg-primary text-warning text-center">
        <h1 class="display-3 fw-bold">My Website</h1>
        <p class="fs-4">Welcome to our online store</p>
        <button class="btn btn-warning text-dark">
            Shop Now
        </button>
    </section>

    <!-- Shop SECTION -->
    <section id="shop" class="bg-dark text-light text-center">

        <div class="container">

            <h1 class="mb-4">SHOP</h1>

            <div class="row g-4">

                <!-- PRODUCT 1 -->
                <div class="col-lg-3 col-md-6">

                    <div class="card text-center shadow">

                        <div class="card-header">
                            <h4>Product Name</h4>
                        </div>

                        <div class="card-body">

                            <img class="w-100" src="photo_2026-04-29_19-00-30.jpg" alt="Product Image">

                            <h3 class="text-danger mt-3">
                                $780 <s class="text-secondary">$980</s>
                            </h3>

                            <p>
                                Description of the product goes here.
                            </p>

                        </div>

                        <div class="card-footer">
                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                        </div>

                    </div>

                </div>

                <!-- PRODUCT 2 -->
                <div class="col-lg-3 col-md-6">

                    <div class="card text-center shadow">

                        <div class="card-header">
                            <h4>Product Name</h4>
                        </div>

                        <div class="card-body">

                            <img class="w-100" src="photo_2026-04-29_19-00-46.jpg" alt="Product Image">

                            <h3 class="text-danger mt-3">
                                $780 <s class="text-secondary">$980</s>
                            </h3>

                            <p>Description of the product goes here.
                            </p>

                        </div>

                        <div class="card-footer">
                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                        </div>

                    </div>

                </div>

                <!-- PRODUCT 3 -->
                <div class="col-lg-3 col-md-6">

                    <div class="card text-center shadow">

                        <div class="card-header">
                            <h4>Product Name</h4>
                        </div>

                        <div class="card-body">

                            <img class="w-100" src="photo_2026-04-29_19-00-51.jpg" alt="Product Image">

                            <h3 class="text-danger mt-3">
                                $780 <s class="text-secondary">$980</s>
                            </h3>

                            <p>
                                Description of the product goes here.
                            </p>

                        </div>

                        <div class="card-footer">
                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                        </div>

                    </div>

                </div>

                <!-- PRODUCT 4 -->
                <div class="col-lg-3 col-md-6">

                    <div class="card text-center shadow">

                        <div class="card-header">
                            <h4>Product Name</h4>
                        </div>

                        <div class="card-body">

                            <img class="w-100" src="photo_2026-04-29_19-00-55.jpg" alt="Product Image">

                            <h3 class="text-danger mt-3">
                                $780 <s class="text-secondary">$980</s>
                            </h3>

                            <p>
                                Description of the product goes here.
                            </p>

                        </div>

                        <div class="card-footer">
                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                        </div>

                    </div>

                </div>

            </div>

            <!-- About SECTION -->
            <section id="about" class="bg-dark text-light text-center">

                <div class="container">

                    <h1 class="mb-4">ABOUT</h1>

                    <div class="row g-4">

                        <!-- PRODUCT 1 -->
                        <div class="col-lg-3 col-md-6">

                            <div class="card text-center shadow">

                                <div class="card-header">
                                    <h4>Product Name</h4>
                                </div>

                                <div class="card-body">

                                    <img class="w-100" src="photo_2026-04-29_19-00-30.jpg" alt="Product Image">

                                    <h3 class="text-danger mt-3">
                                        $780 <s class="text-secondary">$980</s>
                                    </h3>

                                    <p>
                                        Description of the product goes here.
                                    </p>

                                </div>

                                <div class="card-footer">
                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                </div>

                            </div>

                        </div>

                        <!-- PRODUCT 2 -->
                        <div class="col-lg-3 col-md-6">

                            <div class="card text-center shadow">

                                <div class="card-header">
                                    <h4>Product Name</h4>
                                </div>

                                <div class="card-body">

                                    <img class="w-100" src="photo_2026-04-29_19-00-46.jpg" alt="Product Image">

                                    <h3 class="text-danger mt-3">
                                        $780 <s class="text-secondary">$980</s>
                                    </h3>

                                    <p>Description of the product goes here.
                                    </p>

                                </div>

                                <div class="card-footer">
                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                </div>

                            </div>

                        </div>

                        <!-- PRODUCT 3 -->
                        <div class="col-lg-3 col-md-6">

                            <div class="card text-center shadow">

                                <div class="card-header">
                                    <h4>Product Name</h4>
                                </div>

                                <div class="card-body">

                                    <img class="w-100" src="photo_2026-04-29_19-00-51.jpg" alt="Product Image">

                                    <h3 class="text-danger mt-3">
                                        $780 <s class="text-secondary">$980</s>
                                    </h3>

                                    <p>
                                        Description of the product goes here.
                                    </p>

                                </div>

                                <div class="card-footer">
                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                </div>

                            </div>

                        </div>

                        <!-- PRODUCT 4 -->
                        <div class="col-lg-3 col-md-6">

                            <div class="card text-center shadow">

                                <div class="card-header">
                                    <h4>Product Name</h4>
                                </div>

                                <div class="card-body">

                                    <img class="w-100" src="photo_2026-04-29_19-00-55.jpg" alt="Product Image">

                                    <h3 class="text-danger mt-3">
                                        $780 <s class="text-secondary">$980</s>
                                    </h3>

                                    <p>
                                        Description of the product goes here.
                                    </p>

                                </div>

                                <div class="card-footer">
                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                </div>

                            </div>

                        </div>

                    </div>
                    <!-- SERVICE SECTION -->
                    <section id="service" class="bg-dark text-light text-center">

                        <div class="container">

                            <h1 class="mb-4"> SERVICES</h1>

                            <div class="row g-4">

                                <!-- PRODUCT 1 -->
                                <div class="col-lg-3 col-md-6">

                                    <div class="card text-center shadow">

                                        <div class="card-header">
                                            <h4>Product Name</h4>
                                        </div>

                                        <div class="card-body">

                                            <img class="w-100" src="photo_2026-04-29_19-00-30.jpg" alt="Product Image">

                                            <h3 class="text-danger mt-3">
                                                $780 <s class="text-secondary">$980</s>
                                            </h3>

                                            <p>
                                                Description of the product goes here.
                                            </p>

                                        </div>

                                        <div class="card-footer">
                                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                                        </div>

                                    </div>

                                </div>

                                <!-- PRODUCT 2 -->
                                <div class="col-lg-3 col-md-6">

                                    <div class="card text-center shadow">

                                        <div class="card-header">
                                            <h4>Product Name</h4>
                                        </div>

                                        <div class="card-body">

                                            <img class="w-100" src="photo_2026-04-29_19-00-46.jpg" alt="Product Image">

                                            <h3 class="text-danger mt-3">
                                                $780 <s class="text-secondary">$980</s>
                                            </h3>

                                            <p>Description of the product goes here.
                                            </p>

                                        </div>

                                        <div class="card-footer">
                                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                                        </div>

                                    </div>

                                </div>

                                <!-- PRODUCT 3 -->
                                <div class="col-lg-3 col-md-6">

                                    <div class="card text-center shadow">

                                        <div class="card-header">
                                            <h4>Product Name</h4>
                                        </div>

                                        <div class="card-body">

                                            <img class="w-100" src="photo_2026-04-29_19-00-51.jpg" alt="Product Image">

                                            <h3 class="text-danger mt-3">
                                                $780 <s class="text-secondary">$980</s>
                                            </h3>

                                            <p>
                                                Description of the product goes here.
                                            </p>

                                        </div>

                                        <div class="card-footer">
                                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                                        </div>

                                    </div>

                                </div>

                                <!-- PRODUCT 4 -->
                                <div class="col-lg-3 col-md-6">

                                    <div class="card text-center shadow">

                                        <div class="card-header">
                                            <h4>Product Name</h4>
                                        </div>

                                        <div class="card-body">

                                            <img class="w-100" src="photo_2026-04-29_19-00-55.jpg" alt="Product Image">

                                            <h3 class="text-danger mt-3">
                                                $780 <s class="text-secondary">$980</s>
                                            </h3>

                                            <p>
                                                Description of the product goes here.
                                            </p>

                                        </div>

                                        <div class="card-footer">
                                            <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                            <button class="btn btn-danger">
                            Buy Now
                        </button>
                                        </div>

                                    </div>

                                </div>

                            </div>

                            <!-- CONTACT SECTION -->
                            <section id="contact" class="bg-dark text-light text-center">

                                <div class="container">

                                    <h1 class="mb-4">CONTACT</h1>

                                    <div class="row g-4">

                                        <!-- PRODUCT 1 -->
                                        <div class="col-lg-3 col-md-6">

                                            <div class="card text-center shadow">

                                                <div class="card-header">
                                                    <h4>Product Name</h4>
                                                </div>

                                                <div class="card-body">

                                                    <img class="w-100" src="photo_2026-04-29_19-00-30.jpg" alt="Product Image">

                                                    <h3 class="text-danger mt-3">
                                                        $780 <s class="text-secondary">$980</s>
                                                    </h3>

                                                    <p>
                                                        Description of the product goes here.
                                                    </p>

                                                </div>

                                                <div class="card-footer">
                                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                                </div>

                                            </div>

                                        </div>

                                        <!-- PRODUCT 2 -->
                                        <div class="col-lg-3 col-md-6">

                                            <div class="card text-center shadow">

                                                <div class="card-header">
                                                    <h4>Product Name</h4>
                                                </div>

                                                <div class="card-body">

                                                    <img class="w-100" src="photo_2026-04-29_19-00-46.jpg" alt="Product Image">

                                                    <h3 class="text-danger mt-3">
                                                        $780 <s class="text-secondary">$980</s>
                                                    </h3>

                                                    <p>Description of the product goes here.
                                                    </p>

                                                </div>

                                                <div class="card-footer">
                                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                                </div>

                                            </div>

                                        </div>

                                        <!-- PRODUCT 3 -->
                                        <div class="col-lg-3 col-md-6">

                                            <div class="card text-center shadow">

                                                <div class="card-header">
                                                    <h4>Product Name</h4>
                                                </div>

                                                <div class="card-body">

                                                    <img class="w-100" src="photo_2026-04-29_19-00-51.jpg" alt="Product Image">

                                                    <h3 class="text-danger mt-3">
                                                        $780 <s class="text-secondary">$980</s>
                                                    </h3>

                                                    <p>
                                                        Description of the product goes here.
                                                    </p>

                                                </div>

                                                <div class="card-footer">
                                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                                </div>

                                            </div>

                                        </div>

                                        <!-- PRODUCT 4 -->
                                        <div class="col-lg-3 col-md-6">

                                            <div class="card text-center shadow">

                                                <div class="card-header">
                                                    <h4>Product Name</h4>
                                                </div>

                                                <div class="card-body">

                                                    <img class="w-100" src="photo_2026-04-29_19-00-55.jpg" alt="Product Image">

                                                    <h3 class="text-danger mt-3">
                                                        $780 <s class="text-secondary">$980</s>
                                                    </h3>

                                                    <p>
                                                        Description of the product goes here.
                                                    </p>

                                                </div>

                                                <div class="card-footer">
                                                    <button class="btn btn-primary">
                            Add to Cart
                        </button>

                                                    <button class="btn btn-danger">
                            Buy Now
                        </button>
                                                </div>

                                            </div>

                                        </div>

                                    </div>
                                </div>

                                </footer>

</body>

</html>
