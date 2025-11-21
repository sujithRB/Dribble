# Project Responsive Web Design using Bootstrap
## Date:16-11-25

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

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Healthy Recipe Hub</title>
  <!-- Bootstrap CSS CDN -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-success bg-success text-white border-bottom shadow-sm">
    <a class="navbar-brand font-weight-bold text-white" href="#">Healthy Recipe Hub</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active"><a class="nav-link text-white" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link text-white" href="#">Recipes</a></li>
        <li class="nav-item"><a class="nav-link text-white" href="#">Tips</a></li>
        <li class="nav-item"><a class="nav-link text-white" href="#">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="jumbotron jumbotron-fluid bg-light text-center">
    <div class="container py-5">
      <h1 class="display-4 font-weight-bold text-success">Eat Healthy, Live Happy!</h1>
      <p class="lead">Discover easy, tasty recipes and wellness tips for a healthier lifestyle.</p>
      <a href="#" class="btn btn-success btn-lg">Browse Recipes</a>
    </div>
  </div>

  <!-- Recipes Showcase Section -->
  <div class="container py-4">
    <h2 class="mb-4 text-center text-success">Today's Featured Recipes</h2>
    <div class="row">
      <!-- Card 1 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100 shadow-sm">
          <img src="ima1.jpg" class="card-img-top" alt="Recipe 1">
          <div class="card-body">
            <h5 class="card-title text-success">Quinoa Salad Bowl</h5>
            <p class="card-text">A protein-packed bowl with veggies, feta, and lemon dressing.</p>
            <a href="#" class="btn btn-outline-success">See Recipe</a>
          </div>
        </div>
      </div>
      <!-- Card 2 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100 shadow-sm">
          <img src="ima2.jpg" class="card-img-top" alt="Recipe 2">
          <div class="card-body">
            <h5 class="card-title text-success">Avocado Toast Deluxe</h5>
            <p class="card-text">Whole-grain bread topped with smashed avocado and seeds.</p>
            <a href="#" class="btn btn-outline-success">See Recipe</a>
          </div>
        </div>
      </div>
      <!-- Card 3 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100 shadow-sm">
          <img src="ima3.jpg" class="card-img-top" alt="Recipe 3">
          <div class="card-body">
            <h5 class="card-title text-success">Berry Smoothie</h5>
            <p class="card-text">A refreshing blend of berries, banana, and almond milk.</p>
            <a href="#" class="btn btn-outline-success">See Recipe</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Tips Section -->
  <div class="container py-4">
    <h2 class="mb-4 text-success text-center">Healthy Living Tips</h2>
    <div class="row">
      <div class="col-md-6">
        <ul class="list-group list-group-flush">
          <li class="list-group-item">Eat colorful vegetables daily.</li>
          <li class="list-group-item">Stay hydrated—drink water often.</li>
          <li class="list-group-item">Get moving: 30 minutes exercise per day.</li>
          <li class="list-group-item">Choose whole grains over refined products.</li>
        </ul>
      </div>
      <div class="col-md-6">
        <ul class="list-group list-group-flush">
          <li class="list-group-item">Limit added sugar and salt.</li>
          <li class="list-group-item">Snack on nuts and fruit, not junk food.</li>
          <li class="list-group-item">Cook at home for better control.</li>
          <li class="list-group-item">Enjoy meals with loved ones.</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Contact Section -->
  <div class="container py-4">
    <h2 class="text-center mb-4 text-success">Contact Us</h2>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <form>
          <div class="form-group">
            <input type="text" class="form-control" placeholder="Your Name">
          </div>
          <div class="form-group">
            <input type="email" class="form-control" placeholder="Your Email">
          </div>
          <div class="form-group">
            <textarea class="form-control" rows="3" placeholder="Message"></textarea>
          </div>
          <button type="submit" class="btn btn-success btn-block">Send</button>
        </form>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-success text-white text-center py-3 mt-4">
    Created by &lt;DEVAHSRI S&gt;
  </footer>

  <!-- Bootstrap JS CDN -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2025-11-16 165513.png>)

![alt text](<Screenshot 2025-11-16 165531.png>)

![alt text](<Screenshot 2025-11-16 165541.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
