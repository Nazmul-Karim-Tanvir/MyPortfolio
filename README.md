# Web Development Career: Tips and Portfolio Project Demo

![Alt text](./Portfolio%20Website//Project/Images/portfolio.png)

## Introduction to Bootstrap

![Alt text](./Portfolio%20Website//Project/Images/bootsrap.jpg)

### Why Bootstrap?

Bootstrap is a widely-used front-end framework that makes web development faster and easier. Here are some reasons why Bootstrap is beneficial:

1. **Responsive Design**: Ensures your website looks great on all devices, from phones to desktops.
2. **Pre-designed Components**: Comes with pre-styled components like buttons, forms, navbars, and modals.
3. **Consistency**: Maintains a consistent design across all web pages.
4. **Cross-browser Compatibility**: Addresses many browser inconsistencies.
5. **Ease of Use**: Simple to learn and implement, ideal for beginners.

![Alt text](./Portfolio%20Website/Project/Images/Slide1.JPG)

### Integrating Bootstrap into an HTML File

To integrate Bootstrap into your HTML file, follow these steps:

1. **Add Bootstrap CSS**: Include the Bootstrap CSS file in the `<head>` section of your HTML.
2. **Add Bootstrap JS**: Include the Bootstrap JavaScript and its dependencies at the bottom of the `<body>`.

Here is an example HTML file with Bootstrap integrated:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Integration Example</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <h1 class="text-center">Hello, Bootstrap!</h1>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.min.js"></script>
</body>
</html>
```

# Portfolio Website Documentation

This documentation provides an overview of the HTML structure and components used in the portfolio website. By following this guide, you can customize the template to create your own portfolio.
Follow the customization parts.

## Table of Contents

1. [HTML Structure](#html-structure)
2. [Head Section](#head-section)
3. [Navbar](#navbar)
4. [Sections](#sections)
   * [Home](#home-section)
   * [About](#about-section)
   * [Services](#services-section)
   * [Projects](#projects-section)
   * [Skills](#skills-section)
   * [Contact](#contact-section)
5. [Footer](#footer)
6. [JavaScript](#javascript)
7. [CSS](#custom-css)

## 1 HTML Structure

The HTML document is structured as follows:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Head content -->
</head>

<body>
    <!-- Navbar -->
    <!-- Home section -->
    <!-- About section -->
    <!-- Services section -->
    <!-- Projects section -->
    <!-- Skills section -->
    <!-- Contact section -->
    <!-- Footer -->
    <!-- JavaScript -->
</body>

</html>

```

## 2 Head Section

The head section includes meta-information about the document, links to external stylesheets, and the title of the webpage.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nazmul Karim Tanvir - Portfolio</title>

    <!-- Bootstrap CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome CDN -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css">
</head>

```

#### Customization

Title: Change the `<title>` tag to reflect your name or portfolio title.

```html
<title>Your Name - Portfolio</title>

```

## 3 Navbar

A navbar allows users to navigate through different sections of your website. Here's how to create a simple responsive navbar:

```html
 <nav class="navbar navbar-expand-lg navbar-dark fixed-top shadow">
        <div class="container">
            <a class="navbar-brand" href="#home">Nazmul Karim Tanvir</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home"><i class="fas fa-home"></i> Home</a>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#about"><i class="fas fa-user"></i> About</a>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#services"> <i class="fas fa-laptop-code"></i>
                            Services</a>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#projects"><i class="fas fa-folder-open"></i>
                            Projects</a>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#skills"><i class="fas fa-code"></i> Skills</a>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#contact"><i class="fas fa-envelope"></i> Contact</a>
                    </li>
                </ul>
                <button id="theme-toggle" class="btn btn-outline-light ms-3" aria-label="Toggle theme">
                    <i id="theme-icon" class="fas fa-moon"></i>
                </button>
            </div>
        </div>
    </nav>
```

#### Customization

Brand Name: Change the `<a class="navbar-brand">` tag to your own name or brand.

```html
<a class="navbar-brand" href="#home">Your Name</a>
```

You can add or remove as many nav-links as you wish

```html
<li class="nav-item"><a class="nav-link" href="#home"><i class="fas fa-home"></i> Home</a></li>
```

* To add a new link like "Certifications" just remove "Home" also make #home to #certifications

## 4 Sections

### 4.1 Home

The home section welcomes visitors to your portfolio.

```html
<!-- Home Section -->
<header id="home" class="hero">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 text-center text-lg-start">
                    <h1>Welcome to My Portfolio</h1>
                    <p class="lead">A passionate Software Engineer with a focus on Full Stack Development and Mobile
                        Applications.</p>
                </div>
                <div class="col-lg-6 text-center text-lg-end">
                    <div class="img-container">
                        <img class="img-fluid rounded" src="./Images/tanvir.jpg" alt="Profile Picture">
                    </div>
                </div>
            </div>
        </div>
    </header>
```

#### Customization

* **Text** : Update the heading (`<h1>`) and paragraph (`<p>`) to introduce yourself.

```html
<h1>Welcome to My Portfolio</h1>
<p class="lead">A passionate [Your Profession] with a focus on [Your Specialization].</p>
```

* **Image** : Change the `src` attribute of the `<img>` tag to link to your profile picture.

```
<img class="img-fluid rounded" src="path/to/your-image.jpg" alt="Profile Picture">
```

### 4.2 About

The about section provides information about you, your background, and your interests.

```html
 <!-- About section -->
    <section id="about" class="py-5">
        <div class="container text-center">
            <div class="section-title">
                <h2>About Me</h2>
            </div>
            <div class="row info">
                <div class="col-lg-6">
                    <div>
                        <p class="lead">Hello! I'm Nazmul Karim Tanvir, a Software Engineer with experience in full
                            stack development
                            and mobile applications.I have a strong background in both frontend and backend technologies
                            and thrive in fast-paced, agile environments.</p>

                        <div class="mt-4">
                            <p><i class="fas fa-briefcase"></i> Support Associate at Shikho | Full Stack Web Developer
                                (MERN) | Android App Developer |
                                Fiver | Upwork</p>

                            <p><i class="fas fa-car"></i> Founder of Tanvir_Rent_A_Car, providing affordable rides to
                                300+ users within 6 months.
                                <strong>Tanvir_Rent_A_Car:</strong> <a href="https://www.facebook.com/TanviRentACar"
                                    target="_blank" rel="noopener">Visit</a><br>
                            </p>

                            <p><i class="fas fa-paint-brush " style="color: #05daff;"></i> Passionate about painting,
                                traveling, and blogging. NK VLOGS BD, a blogging channel with 800+ subscribers and
                                100,000+ views. <strong>NK VLOGS BD:</strong> <a
                                    href="https://www.youtube.com/channel/UCRvLlXr3hn8dpG7ZRXkE7Tw" target="_blank"
                                    rel="noopener">Visit</a></p>

                            </p>
                        </div>

                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="img-container1 text-center">
                        <img class="img-fluid" src="./Images/graduationimage.jpeg"
                            alt="15th convocation BRAC University">
                    </div>
                    <div class="mt-4 ">
                        <p><i class="fas fa-graduation-cap fa-2x"></i></p>
                        <h6>
                            <strong>BSC , MSC</strong> in
                            <strong>CSE</strong>
                            BRAC University
                        </h6>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>
```

#### Customization

* **Text** : Update the content in the `<p>` tags to describe yourself.

```html
<p class="lead">Hello! I'm [Your Name], a [Your Profession] with a passion for [Your Interests].</p>
```

* **Images** : Replace the images with your own by updating the `src` attributes.
* **Additional Information** : Add or remove content as needed to best represent your background and achievements.

### 4.3 Services

The projects section showcases your work and accomplishments.

```html
<!-- Services section -->
    <section id="services" class="py-5">
        <div class="container text-center">
            <div class="section-title">
                <h2>Services</h2>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <div class="info">
                        <i class="fas fa-laptop-code" style="color: #007bff; font-size: 3rem;"></i>
                        <h4>Web Development</h4>
                        <p>We provide modern web development solutions using the latest technologies to create
                            responsive and user-friendly websites.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
```

#### Customization

* **Service Items** : Add or remove `<div class="col-md-6">` blocks to list all the services you offer.

```html
<div class="col-lg-4 col-md-6">
    <div class="service-box">
        <i class="fas fa-laptop-code"></i>
        <h3>Web Development</h3>
        <p>Building responsive and modern websites.</p>
    </div>
</div>
```

* **Icons and Text** : Update the icons and text to match your services.

### 4.4 Projects

The skills section lists your professional skills and proficiencies.

```html
<!-- Projects section -->
<section id="projects" class="py-5">
        <div class="container text-center">
            <div class="section-title">
                <h2>Projects</h2>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <div class="info">
                        <div class="img-container1 text-center">
                            <img class="img-fluid" src="./Images/e1.png" alt="15th convocation BRAC University">
                        </div>
                        <div>
                            <h4>E-commerce Website</h4>
                            <p>Using modern technologies like ReactJS</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="info">
                        <div class="img-container1 text-center">
                            <img class="img-fluid" src="./Images/e2.png" alt="15th convocation BRAC University">
                        </div>
                        <div>
                            <h4>Resturent App</h4>
                            <p>Using modern technologies like React-Native</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
```

#### Customization

* **Projects** : Add or remove project blocks to showcase your work.
* **Images and Text** : Update the images and descriptions to reflect your projects.

```html
<div class="col-lg-4 col-md-6">
    <div class="project-box">
        <img class="img-fluid" src="path/to/project-image.jpg" alt="Project Image">
        <h3>Project Title</h3>
        <p>Short description of the project.</p>
    </div>
</div>
```

### 4.5 Skills

The skils section highlights your relevant skills.

```html
<!-- Skills section -->
    <section id="skills" class="py-5">
        <div class="container text-center">
            <div class="section-title">
                <h2>Skills</h2>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <div class="info">
                        <h4><i class="fas fa-code" style="color: #ff5733;"></i> Frontend Development</h4>
                        <p>HTML5, CSS, Bootstrap, JavaScript, React, Angular</p>
                    </div>
                </div>
  
            </div>
        </div>
    </section>
```

#### Customizations

* add or replace as many coloumn div you want in a row

```html
<div class="col-md-6">
                    <div class="info">
                        <h4><i class="fas fa-code" style="color: #ff5733;"></i> Frontend Development</h4>
                        <p>HTML5, CSS, Bootstrap, JavaScript, React, Angular</p>
                    </div>
                </div>
```

### 4.6 Contact

```html
<!-- Contact section -->
    <section id="contact" class="py-5">
        <div class="container">
            <div class="section-title text-center">
                <h2>Contact</h2>
            </div>
            <div class="contact-info">
                <div class="row">
                    <div class="col-md-4 info-item">
                        <div class="icon"><i class="fas fa-map-marker-alt"></i></div>
                        <p>Dhaka Bangladesh</p>
                    </div>
                    <div class="col-md-4 info-item">
                        <div class="icon"><i class="fas fa-envelope"></i></div>
                        <p>email@example.com</p>
                    </div>
                    <div class="col-md-4 info-item">
                        <div class="icon"><i class="fas fa-phone"></i></div>
                        <p>+88 01698237927</p>
                    </div>
                </div>
            </div>
            <form class="contact-form form-bg-editing rounded" action="mailto:nazmul.karim.tanvir@g.bracu.ac.bd"
                method="post" enctype="text/plain">

                <div class="form-group">
                    <label for="Country"><i>Country/Region:</i></label>
                    <input type="text" class="form-control" id="countryname" name="countryname"
                        placeholder="Enter your country/region" required>
                </div>

                <div class="form-group">
                    <label for="name"><i>Your name:</i></label>
                    <input type="text" class="form-control" id="name" name="name" placeholder="Enter your name"
                        required>
                </div>

                <div class="form-group">
                    <label for="text"><i>Message:</i></label>
                    <textarea class="form-control" id="text" name="text" rows="5" placeholder="Enter some text"
                        required></textarea>
                </div>

                <div class="form-group">
                    <label for="number">Contact Number: </label>
                    <input type="number" class="form-control" id="number" name="number"
                        placeholder="Enter your number (Optional)">
                </div>

                <button type="submit" class="btn btn-primary btn-sm mb-2">
                    Send
                </button>

            </form>
        </div>
    </section><!-- Contact section -->
    <section id="contact" class="py-5">
        <div class="container">
            <div class="section-title text-center">
                <h2>Contact</h2>
            </div>
            <div class="contact-info">
                <div class="row">
                    <div class="col-md-4 info-item">
                        <div class="icon"><i class="fas fa-map-marker-alt"></i></div>
                        <p>Dhaka Bangladesh</p>
                    </div>
                </div>
            </div>
            <form class="contact-form form-bg-editing rounded" action="mailto:nazmul.karim.tanvir@g.bracu.ac.bd"
                method="post" enctype="text/plain">

                <div class="form-group">
                    <label for="Country"><i>Country/Region:</i></label>
                    <input type="text" class="form-control" id="countryname" name="countryname"
                        placeholder="Enter your country/region" required>
                </div>

                <div class="form-group">
                    <label for="name"><i>Your name:</i></label>
                    <input type="text" class="form-control" id="name" name="name" placeholder="Enter your name"
                        required>
                </div>

                <div class="form-group">
                    <label for="text"><i>Message:</i></label>
                    <textarea class="form-control" id="text" name="text" rows="5" placeholder="Enter some text"
                        required></textarea>
                </div>

                <div class="form-group">
                    <label for="number">Contact Number: </label>
                    <input type="number" class="form-control" id="number" name="number"
                        placeholder="Enter your number (Optional)">
                </div>

                <button type="submit" class="btn btn-primary btn-sm mb-2">
                    Send
                </button>

            </form>
        </div>
    </section>
```

#### Customization

* **Form** : Update form fields and action URL.

```html
<form>
    <div class="form-group">
        <input type="text" class="form-control" placeholder="Your Name">
    </div>
    <div class="form-group">
        <input type="email" class="form-control" placeholder="Your Email">
    </div>
    <div class="form-group">
        <textarea class="form-control" rows="4" placeholder="Your Message"></textarea>
    </div>
    <button type="submit" class="btn btn-primary">Send Message</button>
</form>
```

## 5 Footer

The footer section provides additional information like contact details or social media links.

```html
<!-- Footer Section -->
<footer class="footer">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="social-icons">
                        <a href="https://github.com/Nazmul-Karim-Tanvir" target="_blank" rel="noopener"
                            aria-label="GitHub">
                            <i class="fab fa-github"></i>
                        </a>
                        <a href="https://www.linkedin.com/in/nazmul-karim-tanvir-795563159/" target="_blank"
                            rel="noopener" aria-label="LinkedIn">
                            <i class="fab fa-linkedin"></i>
                        </a>
                        <a href="https://www.youtube.com/channel/UCyGLwYaTWCR-l68h58yixEg" target="_blank"
                            rel="noopener" aria-label="YouTube">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                    <p class="mt-3">© 2024 Nazmul Karim Tanvir. All Rights Reserved.</p>
                </div>
            </div>
        </div>
    </footer>
```

#### Customization

* **Text** : Update the copyright information.

```html
<p>© 2024 Your Name. All Rights Reserved.</p>
```

* Social Links: Update links to your social media profiles.

```html
<a href="https://www.linkedin.com/in/yourprofile" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>
```

## 6 JavaScript

No need to modify it. This Javascript part contains all the functionality of theme change, navbar collapse and more.

```javascript
<!-- JS Code  -->
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const navbarToggler = document.querySelector('.navbar-toggler');
            const togglerIcon = navbarToggler.querySelector('.navbar-toggler-icon');
            const navLinks = document.querySelectorAll('.nav-link');
            const navbarCollapse = document.querySelector('.navbar-collapse');
            const themeToggle = document.getElementById('theme-toggle');
            const themeIcon = document.getElementById('theme-icon');

            // Toggle icon change on navbar toggler click
            navbarToggler.addEventListener('click', function () {
                if (navbarToggler.classList.contains('collapsed')) {
                    togglerIcon.classList.remove('fas', 'fa-times');
                    togglerIcon.classList.add('navbar-toggler-icon');
                } else {
                    togglerIcon.classList.remove('navbar-toggler-icon');
                    togglerIcon.classList.add('fas', 'fa-times');
                }
            });

            // Handle nav-link clicks
            navLinks.forEach(function (navLink) {
                navLink.addEventListener('click', function (event) {
                    // Prevent default link behavior
                    event.preventDefault();

                    // Remove 'active' class from all nav-links
                    navLinks.forEach(function (link) {
                        link.classList.remove('active');
                    });

                    // Add 'active' class to the clicked nav-link
                    navLink.classList.add('active');

                    // Close the collapsed navbar after click (for mobile view)
                    if (navbarCollapse.classList.contains('show')) {
                        navbarToggler.click();
                    }

                    // Scroll to the clicked section
                    const targetId = navLink.getAttribute('href');
                    const targetSection = document.querySelector(targetId);
                    if (targetSection) {
                        targetSection.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                });
            });

            // Theme toggle functionality
            themeToggle.addEventListener('click', function () {
                document.body.classList.toggle('dark-mode');

                // Change theme icon
                if (document.body.classList.contains('dark-mode')) {
                    themeIcon.classList.remove('fa-moon');
                    themeIcon.classList.add('fa-sun');
                } else {
                    themeIcon.classList.remove('fa-sun');
                    themeIcon.classList.add('fa-moon');
                }
            });
        });
    </script>
```

## 7 CSS

* no need to change anything if you follow this portfolio theme

```css
body {
    background-color: #F4F2EE;
    font-family: 'Arial', sans-serif;
    transition: background-color 0.3s, color 0.3s;
}

.contact-form {
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    color: #343a40;
    margin-top: 40px;
    padding: 20px;
    transition: background-color 0.3s;
}

.contact-form .form-control {
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin-bottom: 15px;
}

.contact-form button {
    background-color: #007bff;
    border: none;
    border-radius: 10px;
    color: white;
    cursor: pointer;
    padding: 12px 20px;
    transition: background-color 0.3s;
}

.contact-form button:hover {
    background-color: #0056b3;
}

.contact-info {
    margin: 40px 0;
    text-align: center;
}

.contact-info .icon {
    color: #007bff;
    font-size: 2rem;
    margin-bottom: 10px;
}

.contact-info .info-item {
    margin-bottom: 20px;
}

.container {
    margin: 0 auto;
    max-width: 1080px;
}

.footer {
    background-color: #007bff;
    border-top: 4px solid #ddd;
    color: white;
    padding: 20px 0;
    text-align: center;
}

.hero {
    background: linear-gradient(90deg, rgb(243, 85, 85) 0%, rgba(123, 158, 255, 1) 100%);
    color: white;
    padding: 100px 0;
    padding-top: 170px;
    text-align: center;
}

.img-container {
    border: 3px solid #007bff;
    border-radius: 50%;
    display: inline-block;
    height: 250px;
    margin: 0 auto;
    overflow: hidden;
    width: 250px;
}

.img-container img {
    border-radius: 50%;
    display: block;
    height: auto;
    width: 100%;
}

.img-container1 {
    border: 2px solid #0048ff;
    border-radius: 5%;
    display: inline-block;
    height: 320px;
    margin: 0 auto;
    overflow: hidden;
    width: 320px;
}

.info {
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    color: #343a40;
    margin-bottom: 20px;
    padding: 20px;
    transition: transform 0.3s;
}

.info:hover {
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    transform: translateY(-10px);
}

.nav-item {
    font-family: 'Roboto', sans-serif;
    margin: auto;
    padding: auto;
}

.navbar {
    background-color: #007bff;
}

.navbar-brand {
    color: #fff;
    font-family: 'Roboto', sans-serif;
    font-size: 24px;
    font-weight: bold;
}

.navbar-brand,
.nav-link {
    color: #fff;
}

.section-title {
    color: #007bff;
    font-family: 'Pacifico', cursive;
    margin: 40px 0;
    text-align: center;
}

.section-title h2 {
    border-bottom: 3px solid #007bff;
    display: inline-block;
    padding: 10px 20px;
}

.social-icons a {
    color: white;
    font-size: 1.5rem;
    margin: 0 10px;
    transition: color 0.3s;
}

.social-icons a:hover {
    color: #d3d3d3;
}



/* CSS for Dark Mode */
.dark-mode {
    background-color: #343a40;
    color: #e0e0e0;
}

.dark-mode .contact-form {
    background-color: #454545;
    color: #e0e0e0;
}

.dark-mode .contact-form button {
    background-color: royalblue;
}

.dark-mode .contact-form button:hover {
    background-color: green;
    color: whitesmoke;
}

.dark-mode .contact-info .icon {
    color: #5ee1f5;
}

.dark-mode .footer {
    background-color: #222;
    border-top: 4px solid #444;
}

.dark-mode .hero {
    background-color: #2234ae;
    background-image: linear-gradient(315deg, #2234ae 0%, #191714 74%);
}

.dark-mode .info {
    background-color: #5a5a5a;
    color: #e0e0e0;
}

.dark-mode .info:hover {
    background-color: #6d6d6d;
}

.dark-mode .navbar {
    background-color: #222;
}

.dark-mode .project-item {
    background-color: #3C3C3C;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
    color: #e0e0e0;
}

.dark-mode .project-item:hover {
    background-color: #5a5a5a;
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
}

.dark-mode .section-title h2 {
    border-color: rgb(72, 210, 72);
    color: #5ee1f5;
}

```
