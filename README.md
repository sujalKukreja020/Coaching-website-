# Coaching-website-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Coaching Center</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
<nav>
    <div class="logo"><h2>Coaching Center</h2></div>
    <div class="links">
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="fees.html">Fees</a>
        <a href="students.html">Students</a>
        <a href="youtube.html">YouTube</a>
        <a href="contact.html">Contact</a>
    </div>
</nav>

<div class="container">
    <h1>Welcome to Our Coaching Center</h1>
    <p>We provide the best guidance for students to achieve their dreams.</p>
    <a href="contact.html" class="btn">Enroll Now</a>
</div>

<footer>
    <p>&copy; 2026 Coaching Center. All rights reserved.</p>
</footer>
</body>
</html>
body {
    background-color: #121212;
    color: #f1f1f1;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 15px 30px;
    background-color: #1f1f1f;
}

nav a {
    color: #f1f1f1;
    text-decoration: none;
    margin-left: 15px;
}

nav a:hover {
    color: #ff6f61;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 40px 20px;
}

.btn {
    padding: 10px 20px;
    background-color: #ff6f61;
    color: #fff;
    text-decoration: none;
}

.btn:hover {
    background-color: #ff3b2f;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #1f1f1f;
    margin-top: 50px;
}