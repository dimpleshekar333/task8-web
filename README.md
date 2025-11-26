# Simple Blog Project -- Bootstrap 5

This project is a **responsive blog webpage** built using **HTML5** and
**Bootstrap 5 CDN**.\
It includes a navigation bar, hero section, blog cards, and a footer
with social icons.

------------------------------------------------------------------------

## 📌 Features

### ✔️ **Responsive Navbar**

-   Uses Bootstrap's `navbar` component\
-   Contains links for Home, Posts, About, and Contact\
-   Collapsible menu on mobile

### ✔️ **Hero Section**

-   Clean and simple welcome banner\
-   Title + subtitle for better presentation

### ✔️ **Blog Cards Section**

-   Three blog cards created using Bootstrap grid\
-   Each card includes:
    -   Image (random placeholder from Picsum)
    -   Title
    -   Description
    -   Read More button

### ✔️ **Footer**

-   Dark footer section\
-   Copyright text\
-   Social media icons (Font Awesome)

------------------------------------------------------------------------

## 🛠️ Technologies Used

  Technology              Purpose
  ----------------------- -------------------------------------
  **HTML5**               Structure of the page
  **Bootstrap 5**         CSS framework for responsive design
  **Font Awesome 6**      Social media icons
  **Picsum Photos API**   Sample blog images

------------------------------------------------------------------------

## 📂 File Included

    index.html

------------------------------------------------------------------------

## ▶️ How to Run the Project

1.  Download the `index.html` file\
2.  Open it using any web browser (Chrome, Edge, Firefox, etc.)\
3.  No backend or server required

------------------------------------------------------------------------

## 📸 Screenshot (Structure Overview)

The page contains: - Navbar\
- Hero section\
- Blog cards\
- Footer with icons

You may take a screenshot by pressing:\
- **Windows:** Win + Shift + S\
- **Mac:** Cmd + Shift + 4

------------------------------------------------------------------------

## 📄 HTML Code (For Reference)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Simple Blog - Bootstrap 5</title>

        <!-- Bootstrap 5 CSS CDN -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

        <!-- Icons CDN -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    </head>
    <body>

        <!-- NAVBAR -->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <a class="navbar-brand fw-bold" href="#">MyBlog</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navBar">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navBar">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Posts</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>

        <!-- HERO SECTION -->
        <header class="bg-light py-5 text-center">
            <h1 class="fw-bold">Welcome to My Blog</h1>
            <p class="text-muted">Read the latest articles, guides, and tutorials.</p>
        </header>

        <!-- BLOG POSTS -->
        <div class="container my-5">
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card shadow-sm">
                        <img src="https://picsum.photos/600/300" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Blog Title One</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="card shadow-sm">
                        <img src="https://picsum.photos/601/300" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Blog Title Two</h5>
                            <p class="card-text">Donec aliquet est vel laoreet.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="card shadow-sm">
                        <img src="https://picsum.photos/602/300" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Blog Title Three</h5>
                            <p class="card-text">Pellentesque iaculis velit.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <!-- FOOTER -->
        <footer class="bg-dark text-white text-center py-3">
            <p class="mb-1">© 2025 MyBlog — All Rights Reserved</p>
            <div>
                <a href="#" class="text-white me-3"><i class="fab fa-facebook"></i></a>
                <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
                <a href="#" class="text-white me-3"><i class="fab fa-instagram"></i></a>
                <a href="#" class="text-white"><i class="fab fa-github"></i></a>
            </div>
        </footer>

        <!-- JS CDN -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </body>
    </html>

------------------------------------------------------------------------

## 📌 Author

Created for HTML/CSS + Bootstrap Lab Assignment

------------------------------------------------------------------------
