# Web development career discussions and making a demo portfolio project



## Introduction to Bootstrap

![Alt text](./Project/Images/bootsrap.jpg)

### Why Bootstrap?

Bootstrap is a widely-used front-end framework that makes web development faster and easier. Here are some reasons why Bootstrap is beneficial:

1. **Responsive Design**: Ensures your website looks great on all devices, from phones to desktops.
2. **Pre-designed Components**: Comes with pre-styled components like buttons, forms, navbars, and modals.
3. **Consistency**: Maintains a consistent design across all web pages.
4. **Cross-browser Compatibility**: Addresses many browser inconsistencies.
5. **Ease of Use**: Simple to learn and implement, ideal for beginners.

![Alt text](./Project/Images/Slide1.JPG)

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

# Creating a Portfolio Website Using Bootstrap

Let's create a portfolio website step by step using Bootstrap.

## Creating the Navbar

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

## Creating the Home Section

The home section is the first thing visitors see. It usually contains a welcoming message or an introduction.

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

## Creating the About Section

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

## Creating the Services Section

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

## Creating the Projects Section

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

## Creating the Skilss Section

The certifications section highlights your relevant certifications.

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
## Creating the Contact Section
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

## Creating the Footer Section

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
                    <p class="mt-3">&copy; 2024 Nazmul Karim Tanvir. All Rights Reserved.</p>
                </div>
            </div>
        </div>
    </footer>
```


# Conclusion

With this step-by-step guide, customize each section further to reflect your unique style and professional achievements. Bootstrap's extensive documentation and community support will be valuable resources as they continue to develop their web design skills.
