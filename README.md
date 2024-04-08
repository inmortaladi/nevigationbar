<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Smooth Scroll Navigation</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth; /* Enable smooth scrolling */
  }
  nav {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
  }
  nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px;
  }
  section {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2em;
  }
  #home { background-color: #f0f0f0; }
  #about { background-color: #e6e6e6; }
  #contact { background-color: #dcdcdc; }
</style>
</head>
<body>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About Us</a>
  <a href="#contact">Contact Us</a>
</nav>

<section id="home">
  <h2>Home Section</h2>
  <!-- Your home content goes here -->
</section>

<section id="about">
  <h2>About Us Section</h2>
  <!-- Your about us content goes here -->
</section>

<section id="contact">
  <h2>Contact Us Section</h2>
  <!-- Your contact us content goes here -->
</section>

</body>
</html>
