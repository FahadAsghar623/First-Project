# First Project
Website project

# First Project
Website project

<!DOCTYPE html>
<html>
<head>
    <title>My first website as Dveloper.</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        /* Navigation table style */
        table.nav {
            border: 1px solid rgb(168, 25, 25);
            width: 100%;
            border-collapse: collapse;
        }
        table.nav td {
            border: 1px solid black;
            text-align: center;
            padding: 8px;
            background-color: #ccc;
        }
        table.nav td a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        table.nav td a:hover {
            color: white;
        }

        /* Sections are hidden by default */
        section {
            display: none;
            padding: 20px;
            margin-top: 10px;
            border: 1px solid #000;
        }

        /* Show the section when targeted */
        section:target {
            display: block;
        }

        /* Show home by default */
        #home {
            display: block;
        }

        /* Logo */
        #logo {
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
    </style>
</head>
<body>

<!-- Logo -->
<img src="ChatGPT Image May 17, 2025, 12_17_53 PM.jpg" alt="Logo" id="logo" width="70">

<!-- Navigation table -->
<table class="nav">
    <tr>
        <td><a href="#home">Home</a></td>
        <td><a href="#about">About</a></td>
        <td><a href="#gallery">Gallery</a></td>
        <td><a href="#media">Media</a></td>
        <td><a href="#contact">Contact</a></td>
        <td><a href="#login">Login</a></td>
        <td><a href="#registration">Registration</a></td>
    </tr>
</table>

<!-- Sections -->
<section id="home">
    <h2>Home Page</h2>
    <p>Welcome to the Home Page! This page shows only the home content.</p>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Welcome to our company! We are committed to providing the best service.</p>
    <p>Our Team:</p>
    <ul>
        <li>John Doe - CEO</li>
        <li>Jane Smith - Marketing Head</li>
        <li>Ali Khan - Lead Designer</li>
    </ul>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <p>Check out our amazing pictures and collections.</p>
    <img src="ChatGPT Image May 17, 2025, 12_17_53 PM.jpg" alt="Khan" width="70"><br><br>
    <img src="ChatGPT Image May 17, 2025, 12_17_53 PM.jpg" alt="Khan" width="70">
</section>

<section id="media">
    <h2>Media</h2>
    <p>Latest news, videos, and press releases.</p>
    <ul>
        <li>Video 1: <a href="https://youtu.be/GZkbK1NXuas?si=oL7X29se7eV8C9PA">Watch</a></li>
        <li>Video 2: <a href="https://youtu.be/uCmUImK2ecw?si=HIX7XPd5ae3XwLpL">Watch</a></li>
        <li>News Article 1: <a href="https://www.express.com.pk/epaper/Index.aspx?Issue=NP_FSB">Read</a></li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@example.com<br>Phone: +123456789<br>Address: 123 Main Street, City</p>
</section>

<section id="login">
    <h2>Login</h2>
    <form>
        Username: <input type="text" name="username"><br><br>
        Password: <input type="password" name="password"><br><br>
        <input type="submit" value="Login">
    </form>
</section>

<section id="registration">
    <h2>Registration</h2>
    <form>
        Full Name: <input type="text" name="fullname"><br><br>
        Email: <input type="email" name="email"><br><br>
        Password: <input type="password" name="password"><br><br>
        <input type="submit" value="Register">
    </form>
</section>

</body>
</html>

