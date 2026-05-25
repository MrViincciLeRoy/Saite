# Saite Project
## Overview
The Saite project is a web application that features a carousel and a navigation menu.
## Key Features
- Carousel with multiple slides
- Navigation menu with links to Home, Media, and About pages
- Social media links
## Tech Stack
- HTML
- CSS (with Bootstrap and Boxicons)
- JavaScript (with Bootstrap)
## Installation
To install the project, clone the repository and open the index.html file in a web browser.
## Usage
To use the project, simply open the index.html file in a web browser and navigate through the carousel and menu links.
## Environment Variables
No environment variables are required for this project.
## Code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Assests/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="Assests/boxicons/css/boxicons.min.css">
    <style>
        .bd-placeholder-img {
          font-size: 1.125rem;
          text-anchor: middle;
          -webkit-user-select: none;
          -moz-user-select: none;
          user-select: none;
        }

        @media (min-width: 768px) {
          .bd-placeholder-img-lg {
            font-size: 3.5rem;
          }
        }
      </style>


      <!-- Custom styles for this template -->
      <link href="Assests/css/carousel.css" rel="stylesheet">
    </head>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
          <div class="container-fluid">
            <a class="navbar-brand" href="#">Saite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarCollapse">
              <ul class="navbar-nav me-auto mb-2 mb-md-0">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#media">Media</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link " href="#about" tabindex="-1" aria-disabled="true">About</a>
                </li>
              </ul>
              <div>
                <div class="social-links text-center text-md-right pt-3 pt-md-0 px-4">

                    <a href="https://www.facebook.com/goitsemang.saite" class="facebook"><i class="h4 bx bxl-facebook"></i></a>

                  </div>
              </div>
            </div>
          </div>
        </nav>
      </header>

      <main>

        <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">

          </div>
        </div>

      </main>
    </body>
</html>
```