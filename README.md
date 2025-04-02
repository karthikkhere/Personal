# Personal

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Holiday Travels - Your gateway to unforgettable vacation packages and experiences.">
    <title>Holiday Travels</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Holiday Travels</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#destinations">Destinations</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="banner">
            <h2>Discover the World with Us</h2>
            <p>Your perfect holiday is just a click away.</p>
            <a href="#destinations" class="cta-button">Explore Destinations</a>
        </div>
    </section>

    <section id="destinations">
        <div class="container">
            <h2>Top Destinations</h2>
            <div class="destination-cards">
                <div class="card">
                    <img src="https://via.placeholder.com/300" alt="Beach">
                    <h3>Maldives</h3>
                    <p>Explore the serene beaches and crystal-clear waters of the Maldives.</p>
                </div>
                <div class="card">
                    <img src="https://via.placeholder.com/300" alt="Paris">
                    <h3>Paris</h3>
                    <p>Discover the romance and elegance of the city of lights, Paris.</p>
                </div>
                <div class="card">
                    <img src="https://via.placeholder.com/300" alt="Tokyo">
                    <h3>Tokyo</h3>
                    <p>Experience the vibrant culture and exciting lifestyle of Tokyo.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>At Holiday Travels, we specialize in creating memorable travel experiences. Whether you're looking for a relaxing beach getaway, an adventure in the mountains, or a cultural city tour, we have the perfect package for you.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Holiday Travels | All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
