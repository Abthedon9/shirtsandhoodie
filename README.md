<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Shirts and hoodies from Team Impact. Check out unique designs and shop now!">
    <title>Shirts & Hoodies</title>
    <style>
        /* Reset some basic styles */
        body, h1, p {
            margin: 0;
            padding: 0;
        }

        /* Basic styles for the body */
        body {
            font-family: Arial, sans-serif;
            background-color: #000000; /* Black background for the body */
            color: #fff; /* White text for the body */
            line-height: 1.6;
            padding: 20px; /* Add padding around the entire body */
            margin: 0;
            padding-bottom: 50px; /* Add space at the bottom for the footer */
        }

        /* Header styles */
        header {
            background-color: #660000; /* Darker red background for header */
            color: #fff; /* White text color for header */
            text-align: center;
            padding: 20px;
            margin-bottom: 20px;  /* Add space below the header */
        }

        /* Navigation menu styles */
        nav ul {
            list-style: none;
            text-align: center;
            background-color: #310000;
            padding: 10px 0;
            margin: 0;
            margin-bottom: 20px;  /* Add space below the navigation */
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        /* Split the body into two sections: Image on the left, text on the right */
        .content-container {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            gap: 20px;  /* Add some space between the image and the content */
        }

        /* Image styles */
        .side-image {
            width: 45%; /* The image takes up 45% of the page width */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        /* About Me section with black background */
        .about-me {
            width: 45%; /* The About Me section takes up 45% of the page width */
            padding: 20px;
            background-color: #000; /* Black background for About Me */
            color: #fff; /* White text color for About Me */
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        /* Footer styles */
        footer {
            background-color: #000000;
            color: #fff;
            text-align: center;
            padding: 10px;
            width: 100%;
            position: fixed;
            bottom: 0; /* Fixes footer to the bottom of the page */
        }

        /* Button styles */
        button {
            background-color: #5C6BC0;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #3F4B8F;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .content-container {
                flex-direction: column; /* Stack the sections vertically on small screens */
                align-items: center;
            }

            .side-image, .about-me {
                width: 80%; /* Both sections take up most of the page */
                margin-bottom: 20px;
            }

            nav ul {
                text-align: left;
            }

            nav ul li {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>S&H 4 $$</h1>
        <p>Shirts and hoodies from TEAM IMPACT</p>
        <p>Look around, maybe you'll find something!</p>
    </header>

    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Content Section -->
    <section id="home">
        <h2>Home</h2>

        <!-- Flexbox Layout for Image and Text -->
        <div class="content-container">
            <!-- Image Section -->
            <img src="OIP.jpeg" alt="Shirts & Hoodies" class="side-image">
            <img src="one.jpg" alt="Shirts & Hoodies" class="side-image">
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <div class="about-me">
            <p>Owner: Kashif, Abdullah</p>
            <p>Team: Abdullah, Abdullah (Chota), Mahad, and Zaid</p>
            <p>Known for: Best shirt and hoodie designs in the world</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Reaching out:</p>
        <p>abdullahhk120@gmail.com</p>
        <p>951-***-****</p>

        <p><a href="https://www.instagram.com/dontt_abdullah" target="_blank" style="color: white; text-decoration: none;">Follow me on Instagram</a></p>

        <button onclick="showAlert()">Click Me!</button>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; Shirts & Hoodies by Kashif, Abdullah</p>
    </footer>

    <!-- JavaScript Section -->
    <script>
        function showAlert() {
            alert('lol buy something!');
        }
    </script>

</body>
</html>
