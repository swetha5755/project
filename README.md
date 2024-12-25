# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #4e452d;/* Replace with your image URL */
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
        .bg-primary {
            background-color: #b4a784 !important; /* Replace with your desired color */
        }
        .card {
            width: 18rem; /* Adjust the card size here */
            margin: auto; /* Center the card within its column */
        }
        .card img {
            height: 200px; /* Adjust the image height to match your design needs */
            object-fit: cover;
        }
		.text-white {
            color: #ffffff !important; /* White text for better readability */
        }
        .text-dark {
            color: #c40707 !important; /* Dark text for contrast */
        }
		.btn-primary {
            background-color: #c29b5d !important; /* Custom color for the email button */
            border-color: #c29b5d !important; /* Match border color with background */
        }
		p {
    color: #01030c !important; /* White text color for the paragraphs */
		}
	    h2 {
    color: #c29b5d !important; /* Custom gold color for the headings */
         }
    </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="#">FEIN</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="bg-primary text-white text-center py-5">
    <div class="container">
        <h1>Welcome to Fein Store</h1>
        <p class="lead">Discover a curated collection of premium clothing that combines comfort, quality, and timeless designs. Whether you're dressing for everyday chic or a special occasion, Fein offers apparel that complements your personality and elevates your wardrobe. Step into style, step into Fein!"</p>
        <a href="#gallery" class="btn btn-light btn-lg">Explore Gallery</a>
    </div>
</section>

<!-- About Section -->
<section id="about" class="py-5">
    <div class="container text-center">
        <h2>About Us</h2>
        <p class="lead">Fein is where style meets individuality. We offer a curated collection of high-quality, stylish, and comfortable clothing for every occasion. Our mission is to inspire confidence and celebrate your unique fashion journey.</p>
    </div>
</section>

<!-- Gallery Section -->
<section id="gallery" class="py-5 bg-light">
    <div class="container">
        <h2 class="text-center">Gallery</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="https://i.pinimg.com/736x/7b/48/bb/7b48bb0da76bdc783107695865bbcc7b.jpg" class="card-img-top" alt="Work 1">
                    <div class="card-body">
                        <h5 class="card-title">Clothing</h5>
                        <p class="card-text">Discover a wide range of stylish and comfortable clothing for every occasion.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://i.pinimg.com/236x/ca/f3/00/caf300d2b1bd0f6cf07b409afbc7c8f3.jpg" class="card-img-top" alt="Work 2">
                    <div class="card-body">
                        <h5 class="card-title">Footwear</h5>
                        <p class="card-text">Step into style with our collection of trendy and durable footwear.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://i.pinimg.com/736x/e0/28/28/e0282823921f2cac7b35e2d8f8f176d1.jpg" class="card-img-top" alt="Work 3">
                    <div class="card-body">
                        <h5 class="card-title">Accessories</h5>
                        <p class="card-text">Complete your look with our elegant and functional accessories.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5">
    <div class="container text-center">
        <h2>Contact Us</h2>
        <p class="lead">Have questions or want to get in touch? Contact us!</p>
        <a href="mailto:info@dribbbleclone.com" class="btn btn-primary">Email Us</a>
    </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
    <div class="container">
        <p>&copy; 2024 Dribbble Clone.Swetha S</p>
    </div>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-24 221400](https://github.com/user-attachments/assets/0a8e3a24-6c7c-4143-a270-ce2d788fa9d7)
![Screenshot 2024-12-24 221439](https://github.com/user-attachments/assets/3c8c3540-159a-4433-9f13-818e8f49942d)
# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
