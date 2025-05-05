# Ex.07 Restaurant Website
## Date: 05.05.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home (THE FILOXENIA SIPS)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .hero {
            background-image: url('home.png');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        .hero h1 {
            font-size: 6em;
        }
        .hero p {
            font-size: 1.2em;
            margin: 20px 0;
        }
        .hero button {
            padding: 10px 20px;
            background-color: #ffda79;
            color: #333;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .section {
            padding: 40px 20px;
            text-align: center;
        }
        .section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 20px;
	    width: 250px; 
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .product-image {
            width: 100%;
            height: 150px; 
            object-fit: cover;
            border-radius: 10px;
           margin-bottom: 15px;
       }

       .card h3 {
    		margin: 10px 0 5px;
    		font-size: 1.2em;
	}
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="hero">
        <h1>Home</h1>
        <p>Enjoy the finest coffee and pastries in town</p>
    </header>

    <section class="section">
        <h2>About Us</h2>
        <p>At south pride BBQ,where the scent of slow-smoked ribs and hickory fills the air. Our pitmasters serve up tender brisket, fall-off-the-bone ribs, and all the fixings—cornbread, coleslaw, and southern-style mac & cheese. </p>
    </section>

    <section class="section">
        <h2>Our shop</h2>
        <div class="cards">
            <div class="card">
		<img src="pc3.png" alt="Outdoor Dinning" class="product-image">
                <h3>Outdoor Dinning</h3>
            </div>
            <div class="card">
		<img src="pc6.png" alt="Indoor Dinning" class="product-image">
                <h3>Indoor Dinning</h3>
            </div>
            <div class="card">
		<img src="PIC.png" alt="BUFFET" class="product-image">
                <h3>Art Station</h3>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed and Developed by prathikshaa S<p>
    </footer>
</body>
</html>
```

```
menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu(THE ART) </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        .hero {
            background-image: url('home.png');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 120px 10px;
        }
        .hero h1 {
            font-size: 3em;
        }

        .menu-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 40px;
        }

        .menu-item {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 300px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .menu-item h3 {
            margin: 15px 0 5px;
            font-size: 20px;
        }

        .menu-item p {
            font-size: 14px;
            color: #777;
            padding: 0 10px;
        }

        .menu-item .price {
            font-size: 18px;
            font-weight: bold;
            color: #ff5722;
            margin: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        footer a {
            color: #ffda79;
            text-decoration: none;
        }

        footer .footer-links {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin: 20px 0;
            font-size: 14px;
        }

        footer .footer-links div {
            text-align: left;
        }

        footer .footer-links h4 {
            margin-bottom: 10px;
            font-size: 16px;
            color: #ffda79;
        }
    </style>
</head>
<body>
    <header class="hero">
        <h1>Menu</h1>
    </header>

    <div class="menu-container">
        <div class="menu-item">
            <img src="a1.png" alt="Dish 1">
            <h3>BIRYANI</h3>
            <p>The MOST Authentic Chennai Biryani</p>
            <div class="price">SGD 2.70</div>
        </div>
        <div class="menu-item">
            <img src="a2.png" alt="Dish 2">
            <h3>French Fries</h3>
            <p>A perfect sidekick to any BBQ plate or sandwich</p>
            <div class="price">SGD 3.30</div>
        </div>
        <div class="menu-item">
            <img src="a3.png" alt="Dish 3">
            <h3>Brisket </h3>
            <p>Slow-smoked for up to 14 hours over hardwood, our brisket is tender, juicy, and packed with deep, smoky flavor.</p>
            <div class="price">SGD 3.75</div>
        </div>
        <div class="menu-item">
            <img src="a4.png" alt="Dish 4">
            <h3>Croissants</h3>
            <p>Flaky, buttery perfection that’s fresh out of the oven – the ultimate morning treat to start your day right.</p>
            <div class="price">SGD 2.25</div>
        </div>
        <div class="menu-item">
            <img src="a5.png" alt="Dish 5">
            <h3>BBQ platter</h3>
            <p>the signature dish</p>
            <div class="price">SGD 3.45</div>
        </div>
        <div class="menu-item">
            <img src="a6.png" alt="Dish 6">
            <h3>Lava cake</h3>
            <p>Experience the magic of rich, warm chocolate that oozes out with every bite – an irresistible indulgence.</p>
            <div class="price">SGD 4.20</div>
        </div>
    </div>

    <footer>
        <div class="footer-links">
            <div>
                <h4>Contact Us</h4>
                <p>123 Orchard Road, #05-12, Orchard Central, Singapore 238888</p>
                <p>contact@theart.sg | +65 9123 4567</p>
            </div>
            <div>
                <h4>Our Links</h4>
                <p>About Us | FAQ | Team | Testimonial</p>
            </div>
            <div>
                <h4>Our Services</h4>
                <p>Table Service | Quick Delivery | Fresh Food</p>
            </div>
        </div>
        <p>Designed and Developed by prathikshaa S</p>
    </footer>
</body>
</html>
```

```
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us (THE ART)</title>
    <style>
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

       .hero {
            background-image: url('home.png');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 20px 20px;
        }
        .hero h1 {
            font-size: 3em;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1em;
        }

        nav a:hover {
            color: #ffda79;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
	
	.contact-image {
            display: block;
            margin: 0 auto 20px;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact-details,
        .contact-form {
            margin: 20px 0;
        }

        .contact-details p {
            font-size: 1.1em;
        }

        .contact-form {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .form-group {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            margin-bottom: 15px;
        }

        .form-group div {
            flex: 1;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        textarea {
            resize: vertical;
            height: 100px;
        }

        button {
            display: block;
            width: 100%;
            background-color: #333;
            color: white;
            border: none;
            padding: 10px;
            font-size: 1.2em;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
    <script>
        
        function validateForm(event) {
            event.preventDefault(); 
            const firstName = document.getElementById("first-name").value;
            const email = document.getElementById("email").value;
            const message = document.getElementById("message").value;

            if (!firstName || !email || !message) {
                alert("Please fill in all required fields.");
                return;
            }
            alert("Your message has been submitted. Thank you!");
        }
    </script>
</head>
<body>

    <header class="hero">
        <h1>Contact Us</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Menu</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        
        <div class="contact-details">
            <h2>Contact Information</h2>
            <p>Email: <a href="mailto:contact@theart.sg">contact@theart.sg</a></p>
            <p>Phone: +65 9123 4567</p>
            <p>Address: Orchard Road, #05-12, Orchard Central, Singapore 238888</p>
        </div>

        
        <div class="contact-form">
            <h2>Send Us a Message</h2>
            <form onsubmit="validateForm(event)">
                <div class="form-group">
                    <div>
                        <label for="first-name">First Name</label>
                        <input type="text" id="first-name" placeholder="Enter your first name">
                    </div>
                    <div>
                        <label for="last-name">Last Name</label>
                        <input type="text" id="last-name" placeholder="Enter your last name">
                    </div>
                </div>
                <div class="form-group">
                    <div>
                        <label for="email">Email</label>
                        <input type="email" id="email" placeholder="Enter your email">
                    </div>
                </div>
                <div>
                    <label for="message">Message</label>
                    <textarea id="message" placeholder="Write your message"></textarea>
                </div>
                <button type="submit">Send</button>
            </form>
        </div>
    </div>

    <footer>
        <p>Designed and Developed by prathikshaa S</p>
    </footer>

</body>
</html>
```

```
staff.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADMINISTRATION (THE ART) </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        .hero {
            background-image: url('home.png');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 120px 10px;
        }
        .hero h1 {
            font-size: 3em;
        }

        .staff-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 40px;
        }

        .staff-item {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 300px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .staff-item img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }

        .staff-item h3 {
            margin: 15px 0 5px;
            font-size: 20px;
        }

        .staff-item p {
            font-size: 14px;
            color: #777;
            padding: 0 10px;
        }

        .staff-item .position {
            font-size: 18px;
            font-weight: bold;
            color: #ff5722;
            margin: 10px 0;
        }
  	footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        footer a {
            color: #ffda79;
            text-decoration: none;
        }

        footer .footer-links {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin: 20px 0;
            font-size: 14px;
        }

        footer .footer-links div {
            text-align: left;
        }

        footer .footer-links h4 {
            margin-bottom: 10px;
            font-size: 16px;
            color: #ffda79;
        }
    </style>
</head>
<body>
    <header class="hero">
        <h1>Administration</h1>
    </header>

    <div class="staff-container">
        <div class="staff-item">
            <img src="c1.png" alt="KARAN">
            <h3>nethra</h3>
            <p>nethra is responsible for the overall success of the cafe. Think finances, legalities, marketing, and building a team.</p>
            <div class="position">Cafe Owner</div>
        </div>
        <div class="staff-item">
            <img src="c2.png" alt="ZAARA">
            <h3>Zabir</h3>
            <p> Zabir oversees all aspects of a café's operations. This includes: selling food and drinks, hiring and scheduling staff, menu planning, and maintaining inventory. </p>
            <div class="position">Manager</div>
        </div>
        <div class="staff-item">
            <img src="c5.png" alt="Aarti Lucica Sequeira">
            <h3>naveen</h3>
            <p>naveen is responsible for keeping track of revenue and expenses, to keep the business on budget and in profit.</p>
            <div class="position">Cafe Accountant</div>
        </div>
        <div class="staff-item">
            <img src="c3.png" alt="Vikas Khanna">
            <h3>manasa</h3>
            <p>manasa asst.chef.</p>
            <div class="position">Executive Chef</div>
        </div>
        
        <div class="staff-item">
            <img src="c6.png" alt="Saransh Goila">
            <h3>janani</h3>
            <p>janani is head chef, and ensuring customer satisfaction.</p>
            <div class="position">Staff</div>
        </div>
    </div>    
    <footer>
        <div class="footer-links">
            <div>
                <h4>Contact Us</h4>
                <p>123 Orchard Road, #05-12, Orchard Central, Singapore 238888</p>
                <p>contact@filoxeniasips.sg | +65 9123 4567</p>
            </div>
            <div>
                <h4>Our Links</h4>
                <p>About Us | FAQ | Team | Testimonial</p>
            </div>
            <div>
                <h4>Our Services</h4>
                <p>Table Service | Quick Delivery | Fresh Food</p>
            </div>
        </div>
        <p>Designed and Developed by prathikshaa S</p>
    </footer>
</body>
</html>

```

```
book.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reservation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        .hero {
            background-image: url('home.png');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h1 {
            font-size: 3em;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1em;
        }

        nav a:hover {
            color: #ffda79;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
        }

        .reservation-form {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .form-group {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            margin-bottom: 15px;
        }

        .form-group div {
            flex: 1;
        }

        label {
            font-weight: bold;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        textarea {
            resize: vertical;
            height: 100px;
        }

        button {
            display: block;
            width: 100%;
            background-color: #333;
            color: white;
            border: none;
            padding: 10px;
            font-size: 1.2em;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
    <script>
        
        function validateReservationForm(event) {
            event.preventDefault();
            const name = document.getElementById("name").value;
            const email = document.getElementById("email").value;
            const phone = document.getElementById("phone").value;
            const date = document.getElementById("date").value;
            const time = document.getElementById("time").value;
            const guests = document.getElementById("guests").value;

            if (!name || !email || !phone || !date || !time || !guests) {
                alert("Please fill in all required fields.");
                return;
            }
            alert("Your reservation has been successfully submitted. Thank you!");
        }
    </script>
</head>
<body>

    <header class="hero">
        <h1>Make A Reservation</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="contact.html">Contact</a>
        <a href="reservation.html">Reservation</a>
    </nav>

    <div class="container">
        <div class="reservation-form">
            <h2>Reserve a Table</h2>
            <form onsubmit="validateReservationForm(event)">
                <div class="form-group">
                    <div>
                        <label for="name">Name</label>
                        <input type="text" id="name" placeholder="Enter your name" required>
                    </div>
                    <div>
                        <label for="email">Email</label>
                        <input type="email" id="email" placeholder="Enter your email" required>
                    </div>
                </div>
                <div class="form-group">
                    <div>
                        <label for="phone">Phone Number</label>
                        <input type="tel" id="phone" placeholder="Enter your phone number" required>
                    </div>
                    <div>
                        <label for="date">Date</label>
                        <input type="date" id="date" required>
                    </div>
                </div>
                <div class="form-group">
                    <div>
                        <label for="time">Time</label>
                        <input type="time" id="time" required>
                    </div>
                    <div>
                        <label for="guests">Number of Guests</label>
                        <select id="guests" required>
                            <option value="">Select</option>
                            <option value="1">1</option>
                            <option value="2">2</option>
                            <option value="3">3</option>
                            <option value="4">4</option>
                            <option value="5">5</option>
                            <option value="6+">6+</option>
                        </select>
                    </div>
                </div>
                <div>
                    <label for="special-requests">Special Requests (optional)</label>
                    <textarea id="special-requests" placeholder="Any specific preferences or requests"></textarea>
                </div>
                <button type="submit">Submit Reservation</button>
            </form>
        </div>
    </div>

</body>
</html>
```


## OUTPUT:

![alt text](<pp/restappp/static/Screenshot 2025-05-05 135158.png>)

![alt text](<pp/restappp/static/Screenshot 2025-05-05 135229.png>)

![alt text](<pp/restappp/static/Screenshot 2025-05-05 135125.png>)

![alt text](<pp/restappp/static/Screenshot 2025-05-05 135031.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
