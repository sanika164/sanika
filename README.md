<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website</title>
    <style>
        body {
            margin: 20px;
            font-family: Arial, sans-serif;
            box-sizing: border-box;
        }
        .container {
            display: flex;
            flex-direction: column;
            height: 100vh;
        }
        .top-frame {
            background: #014180;
            color: rgb(209, 194, 194);
            text-align: center;
            padding: 20px;
        }
        .top-frame img {
            max-width: 200px;
            height: auto;
        }
        .bottom-frame {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
        }
        .nav {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .nav a {
            text-decoration: none;
            color: #004080;
            font-weight: bold;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .gallery img {
            height: 150px;
            width: 200px;
            max-width: 100%;
            object-fit: cover;
        }
        .contact {
            text-align: center;
            padding: 20px;
            background: #fffffff0;
            width: 100%;
        }

        /* Media Queries for responsiveness */
        @media (max-width: 768px) {
            .top-frame h1 {
                font-size: 1.5rem;
            }
            .nav {
                gap: 15px;
            }
            .gallery img {
                height: 120px;
                width: 160px;
            }
        }

        @media (max-width: 480px) {
            .top-frame h1 {
                font-size: 1.2rem;
            }
            .nav a {
                font-size: 0.9rem;
            }
            .gallery img {
                height: 100px;
                width: 130px;
            }
            .contact p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="top-frame">
            <h1>Welcome to Our College</h1>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREiORWI6jWqWoAOXzrP6twO3Gtw1ba1eJh1-SGdFgzIR2mUA2FSkkA9q7Fefrl3gBk4PE&usqp=CAU" alt="College Logo" height="50px">
        </div>

        <div class="bottom-frame">
            <div class="nav">
                <a href="about.html" target="content-frame">About Us</a>
                <a href="learn more.html" target="content-frame">Course & Fees</a>
                <a href="event.html" target="content-frame">Events</a>
                <a href="faculty.html" target="content-frame">Faculty</a>
                <a href="facilities.html" target="content-frame">Facilities</a>
                <a href="admission.html" target="content-frame">Admission</a>
            </div>

            <div class="gallery">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-dapYkBuj4jhn5bjVKpZEq8eexzxKy3n_2A&s" alt="Activity 1">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhdnnChUgIe4b_oI4jH9LjdjW5wWe5b3iNUg&s" alt="Activity 2">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTZO-k8wSy93v9lbErbHpVJPuKZBNgXbkK45w&s" alt="Activity 3">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRoXW-G9Xot53Ad2wBxJsg27YHHTf1SgGyWdw&s" alt="Activity 4">
            </div>

            <div class="contact">
                <h3>Contact Us</h3>
                <p>Address: Kasaba Bawada, Kolhapur</p>
                <p>Email: www.dyppoly.com</p>
                <p>Phone: +91-7836xxxxxx</p>
            </div>
        </div>
    </div>
</body>
</html>
