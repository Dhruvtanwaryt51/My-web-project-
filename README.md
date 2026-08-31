# My-web-project-
My web project about frontend development 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Web Project</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
          rel="stylesheet">
</head>

<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">

    <div class="container">

        <a class="navbar-brand" href="#">My Website</a>

        <button class="navbar-toggler"
                data-bs-toggle="collapse"
                data-bs-target="#navbar">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbar">

            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#home">Home</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>

        </div>
    </div>
</nav>

<section id="home" class="text-center p-5 bg-light">

    <h1>Welcome to My Website</h1>

    <p>This is my responsive web development project.</p>

    <button class="btn btn-primary" onclick="showMessage()">
        Click Me
    </button>

</section>

<section id="about" class="container py-5 text-center">

    <h2>About</h2>

    <p>
        This website is developed using HTML5, CSS3, JavaScript
        and Bootstrap.
    </p>

</section>

<section id="contact" class="container py-5">

    <h2>Contact</h2>

    <form>

        <input class="form-control mb-3"
               type="text"
               placeholder="Enter your name">

        <input class="form-control mb-3"
               type="email"
               placeholder="Enter your email">

        <textarea class="form-control mb-3"
                  placeholder="Enter your message"></textarea>

        <button class="btn btn-success">
            Submit
        </button>

    </form>

</section>

<footer class="bg-dark text-white text-center p-3">
    © 2026 My Website
</footer>

<script>

function showMessage() {
    alert("Welcome to my website!");
}

</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
