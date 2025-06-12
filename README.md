<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thato Jonathan Mokupo | Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Thato Jonathan Mokupo</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Hero Section -->
    <header id="home" class="hero-section d-flex align-items-center text-white bg-primary" style="min-height: 100vh;">
        <div class="container text-center">
            <h1 class="display-1 fw-bold mb-4">Thato Jonathan Mokupo</h1>
            <h2 class="display-5 mb-5">Back-end Developer & Database Administrator</h2>
            <a href="#contact" class="btn btn-light btn-lg me-3">Get In Touch</a>
            <a href="#projects" class="btn btn-outline-light btn-lg">View My Work</a>
        </div>
    </header>
    <!-- About Section -->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 mb-4">
                    <h2 class="section-title">About Me</h2>
                    <p class="lead">Hi! I'm Thato Jonathan Mokupo—Jonathan is fine. I'm an aspiring developer actively seeking opportunities in the IT field. I bring a wide range of technical proficiencies—please refer to my CV for the full story.</p>
                    <p>I specialize in backend development using OOP, and I also have frontend experience, 4IR and hardware knowledge, and a strong background in database administration. My experience includes roles as a simulation engineer and a Digital Transformation Officer.</p>
                    <p>Outside of work, I enjoy gaming, working on my car, exercising, learning about emerging technologies, and studying towards my BCom in Information Technology.</p>
                    <a href="https://drive.google.com/file/d/19cr-wsSoBv6VZNazGiou9epfUkwxfF9O/view?usp=drive_link" class="btn btn-primary mt-3" target="_blank">Download CV</a>
                </div>
                <div class="col-lg-6">
                    <img src="https://media.licdn.com/dms/image/v2/D5603AQEFDyh1pnXlZA/profile-displayphoto-shrink_200_200/B56ZYaBONsHQAY-/0/1744193252386?e=1752710400&v=beta&t=aJZZubyxSV21an35FV9KY3Zv15_H0xiWxn0hvG-VKx4" alt="Thato Jonathan Mokupo" class="img-fluid rounded shadow">
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section (NEW) -->
    <section id="contact" class="py-5 bg-dark text-white">
        <div class="container">
            <h2 class="section-title text-center mb-5">Get in Touch</h2>
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Your name">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Your email">
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" rows="5" placeholder="Your message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h3 class="h5">Thato Jonathan Mokupo</h3>
                    <p>Back-end Developer & Database Administrator</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <div class="social-links">
                        <a href="https://github.com/ThatoJonathanMokupo" class="text-white me-3"><i class="fab fa-github fa-lg"></i></a>
                        <!-- Add more social icons as needed -->
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

