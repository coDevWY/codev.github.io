<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Pages Navbar</title>
    <link rel="stylesheet" href="styles.css">
    <style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.navbar {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    transition: all 0.3s ease; /* Geçiş efekti ekleme */
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    margin: 0;
}

.nav-links {
    list-style-type: none;
    padding: 0;
    margin: 0; /* Ekstra boşlukları kaldırma */
}

.nav-links li {
    display: inline;
    margin-left: 20px;
}

.nav-links li a {
    text-decoration: none;
    color: #fff;
}

/* Navbar'ın üzerine gelindiğinde rengini değiştirme */
.navbar:hover {
    background-color: #555;
}

.content {
    padding: 50px;
}




    
  </style>
</head>
<body>

<nav class="navbar">
    <div class="container">
        <h1 class="logo">My Website</h1>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>
</nav>

<div class="content">
    <h2>Welcome to My Website</h2>
    <p>This is some content.</p>
</div>

</body>
</html>
