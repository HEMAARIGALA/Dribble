# Project Responsive Web Design using Bootstrap
## Date:31/12/24

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom styles */
    .hero {
      background: #f7f7f7;
      padding: 100px 0;
      text-align: center;
    }
    .feature-shot {
      background: #fff;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-bottom: 30px;
    }
    .feature-shot img {
      width: 100%;
      height: auto;
    }
    .feature-shot .title {
      padding: 15px;
      font-size: 1.2rem;
      font-weight: 500;
      color: #333;
    }
    .feature-shot .author {
      padding: 0 15px 15px;
      font-size: 0.9rem;
      color: #888;
    }
    .footer {
      background: #f1f1f1;
      padding: 50px 0;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Explore</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Hire</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Sign Up</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Log In</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <h1 class="display-4">What are you working on?</h1>
    <p class="lead">Dribble is show and tell for designers</p>
    <a href="#" class="btn btn-primary btn-lg">Explore Now</a>
  </div>

  <!-- Featured Shots Section (6 columns) -->
  <div class="container py-5">
    <h2 class="text-center mb-4">Featured Shots</h2>
    <div class="row g-4">
      <div class="col-lg-2 col-md-3 col-sm-6">
        <div class="feature-shot">
          <img src="image.jpg1.jpeg" alt="Featured Shot 1">
          <div class="title">jewellery shop</div>
          <div class="author">by teena</div>
        </div>
      </div>
      <div class="col-lg-2 col-md-3 col-sm-6">
        <div class="feature-shot">
          <img src="image.jpg 2.jpeg" alt="Featured Shot 2">
          <div class="title">fruit shop</div>
          <div class="author">by prabha</div>
        </div>
      </div>
      <div class="col-lg-2 col-md-3 col-sm-6">
        <div class="feature-shot">
          <img src="image.jpg 3.jpeg" alt="Featured Shot 3">
          <div class="title">sweet shop</div>
          <div class="author">by johnson</div>
        </div>
      </div>
      <div class="col-lg-2 col-md-3 col-sm-6">
        <div class="feature-shot">
          <img src="image.jpg 4.jpeg" alt="Featured Shot 4">
          <div class="title">bakkery shop</div>
          <div class="author">by Alice Lee</div>
        </div>
      </div>
      <div class="col-lg-2 col-md-3 col-sm-6">
        <div class="feature-shot">
          <img src="image.jpg 5.jpeg" alt="Featured Shot 5">
          <div class="title">chocolate shop</div>
          <div class="author">by Charlie White</div>
        </div>
      </div>
      <div class="col-lg-2 col-md-3 col-sm-6">
        <div class="feature-shot">
          <img src="image.jpg 6.jpeg" alt="Featured Shot 6">
          <div class="title">toys shop</div>
          <div class="author">by Emma Green</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <p>&copy; 2024 Dribbble Clone. All rights reserved.</p>
  </div>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot (95).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
