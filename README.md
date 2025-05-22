# Project Responsive Web Design using Bootstrap
## Date:17/05/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```html
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Products - Sports Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Sports Shop</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="products.html">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="deals.html">Deals</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <header class="bg-primary text-white text-center py-4">
    <h1>Welcome to ONE | ALL SPORTS</h1>
    <p>Your one-stop shop for all sports gear!</p>
  </header>

  <!-- Product Preview -->
  <div class="container my-4">
    <h2 class="mb-4 text-center">Featured Products</h2>
    <div class="row g-4">
      <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://images.unsplash.com/photo-1486286701208-1d58e9338013?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Phone 1" />
          <div class="card-body">
            <h5 class="card-title">Football</h5>
            <p class="card-text">$499</p>
            <a href="#" class="btn btn-primary w-100">Buy Now</a>
          </div>
        </div>
      </div>

      <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://img.freepik.com/premium-photo/tennis-racket-with-tennis-ball-lying-top-it-ready-game-detailed-closeup-tennis-racquet-neon-yellow-ball-ai-generated_538213-41165.jpg?w=360" class="card-img-top" alt="Phone 2" />
          <div class="card-body">
            <h5 class="card-title">Tennis Racket</h5>
            <p class="card-text">$599</p>
            <a href="#" class="btn btn-primary w-100">Buy Now</a>
          </div>
        </div>
      </div>

     <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://plus.unsplash.com/premium_photo-1674128995385-dc35fa3ff392?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Phone 2" />
          <div class="card-body">
            <h5 class="card-title">Basketball</h5>
            <p class="card-text">$599</p>
            <a href="#" class="btn btn-primary w-100">Buy Now</a>
          </div>
        </div>
      </div>

     <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://images.unsplash.com/photo-1530028828-25e8270793c5?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Phone 2" />
          <div class="card-body">
            <h5 class="card-title">Golf Club</h5>
            <p class="card-text">$599</p>
            <a href="#" class="btn btn-primary w-100">Buy Now</a>
          </div>
        </div>
      </div>
      <!-- Add more featured products as needed -->
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Developed by Deepak S</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


products.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Products - Sports Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Sports Shop</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link active" href="products.html">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="deals.html">Deals</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <header class="bg-info text-white text-center py-4">
    <h1>Welcome to ONE | ALL SPORTS</h1>
    <p>Your one-stop shop for all sports gear!</p>
  </header>

  <!-- Product Content -->
  <div class="container my-4">
    <div class="row g-4">
      <!-- Repeat product cards as needed -->
      <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Nike shoe</h5>
            <p class="card-text">$5800INR</p>
            <a href="#" class="btn btn-success w-100">Buy Now</a>
          </div>
        </div>
      </div>

      <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://plus.unsplash.com/premium_photo-1712761997872-2963252bc19d?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Fitness Tracker</h5>
            <p class="card-text">$4990INR</p>
            <a href="#" class="btn btn-success w-100">Buy Now</a>
          </div>
        </div>
      </div>

      <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://images.unsplash.com/photo-1637666532931-b835a227b955?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Sports Dress</h5>
            <p class="card-text">$699INR</p>
            <a href="#" class="btn btn-success w-100">Buy Now</a>
          </div>
        </div>
      </div>

      <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card h-100">
          <img src="https://images.unsplash.com/photo-1605050824853-7fb0755face3?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Sports Glasses/Helmet</h5>
            <p class="card-text">$999INR</p>
            <a href="#" class="btn btn-success w-100">Buy Now</a>
          </div>
        </div>
      </div>


    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Developed by Deepak S</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


deals.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Deals - Sports Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Sports Shop</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="products.html">Products</a></li>
          <li class="nav-item"><a class="nav-link active" href="deals.html">Deals</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <header class="bg-success text-white text-center py-4">
    <h1>Hot Deals & Offers</h1>
    <p>Grab the best discounts before they’re gone!</p>
  </header>

  <!-- Deals Section -->
  <div class="container my-4">
    <div class="alert alert-warning text-center">
      🔥 Flat 20% Off on iPhone 14 - Limited Time Offer!
    </div>
    <div class="alert alert-info text-center">
      🎁 Buy 1 Get 1 Free on Select Accessories!
    </div>
    <!-- Add more deals here -->
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Developed by Deepak S</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact - Sports Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Sports Shop</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="products.html">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="deals.html">Deals</a></li>
          <li class="nav-item"><a class="nav-link active" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <header class="bg-secondary text-white text-center py-4">
    <h1>Contact Us</h1>
    <p>We’re here to help. Reach out anytime.</p>
  </header>

  <!-- Contact Form -->
  <div class="container my-4">
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Your Name</label>
        <input type="text" class="form-control" id="name" required />
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email address</label>
        <input type="email" class="form-control" id="email" required />
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Your Message</label>
        <textarea class="form-control" id="message" rows="4" required></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Send</button>
    </form>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Developed by Jeevika R</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/28e14649-2b44-463e-8dc9-0f20d28541c9)

![image](https://github.com/user-attachments/assets/ffd88be0-226a-4fc8-9708-1c9266a507bf)

![image](https://github.com/user-attachments/assets/7f597837-4f24-4007-a00a-a342084af4c5)

![image](https://github.com/user-attachments/assets/c1ecb062-2f43-4b69-be1d-cf412d8b87af)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
