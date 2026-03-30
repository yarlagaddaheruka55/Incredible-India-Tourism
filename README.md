# Incredible-India-Tourism
This is my first HTML Page creation showcasing the famous tourist places in India a basic web design


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Incredible India Tourism</title>
    <style>
        /* Light Sky Blue Theme */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff; /* Alice Blue - very light sky blue */
            color: #333;
        }

        /* Header Area */
        header {
            background-color: #87ceeb; /* Sky Blue */
            color: white;
            padding: 30px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0;
            font-size: 32px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        /* Navigation Links */
        nav {
            margin-top: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        /* Main Content Container */
        .container {
            width: 85%;
            max-width: 900px;
            margin: 30px auto;
        }

        /* Place Card Styling */
        .place-card {
            background-color: white;
            margin-bottom: 40px;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            border: 1px solid #d1e9ff;
        }

        /* Image Styling */
        .place-card img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            display: block;
        }

        /* Text inside the card */
        .info {
            padding: 25px;
        }

        .info h2 {
            margin-top: 0;
            color: #0077b6; /* Deep Sky Blue for titles */
        }

        .info p {
            line-height: 1.6;
            color: #555;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 25px;
            background-color: #e1f5fe;
            color: #0277bd;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Discover Incredible India</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Destinations</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <div class="container">

        <div class="place-card">
            <img src="https://images.unsplash.com/photo-1564507592333-c60657eea523?w=800" alt="Taj Mahal">
            <div class="info">
                <h2>1. Taj Mahal, Agra</h2>
                <p>One of the Seven Wonders of the World, this white marble masterpiece was built by Emperor Shah Jahan. It is the ultimate symbol of love and India's most famous landmark.
				Completed around 1653, this UNESCO World Heritage site is a masterpiece of Indo-Islamic architecture, renowned for its symmetry, white marble, and intricate gemstone inlay work.</p>
            </div>
        </div>

        <div class="place-card">
            <img src="https://images.unsplash.com/photo-1599661046289-e31897846e41?w=800" alt="Jaipur">
            <div class="info">
                <h2>2. The Pink City, Jaipur</h2>
                <p>Famous for its terracotta-pink buildings, Jaipur is home to the stunning Hawa Mahal and majestic Amber Fort. It offers a deep look into India's royal history.
				A key part of India's "Golden Triangle" tourist circuit (Delhi-Agra-Jaipur).</p>
            </div>
        </div>

        <div class="place-card">
            <img src="https://images.unsplash.com/photo-1602216056096-3b40cc0c9944?w=800" alt="Kerala">
            <div class="info">
                <h2>3. Kerala Backwaters</h2>
                <p>Known as "God's Own Country," Kerala is famous for its peaceful houseboat cruises through palm-fringed canals and lush green landscapes.
				The backwaters are fed by 38 rivers and form a unique brackish water ecosystem, supporting fishing and farming (notably below-sea-level farming in Kuttanad).</p>
            </div>
        </div>

        <div class="place-card">
            <img src="C:\Users\pavan\Downloads\Varnasi.jpg" alt="Varanasi">
            <div class="info">
                <h2>4. Spiritual Varanasi</h2>
                <p>One of the oldest living cities in the world. Experience the magical Ganga Aarti ceremony at sunset along the sacred banks of the River Ganges.
				Often called the cultural capital of India, it is a center of arts, music, and learning, hosting the Banaras Hindu University.</p>
            </div>
        </div>

        <div class="place-card">
            <img src="https://images.unsplash.com/photo-1581791534721-e599df4417f7?w=800" alt="Ladakh">
            <div class="info">
                <h2>5. Leh-Ladakh</h2>
                <p>A paradise for adventure seekers, Ladakh offers breathtaking mountain views, crystal-clear blue lakes, and ancient Buddhist monasteries high in the Himalayas.
				The peak tourist season is from November to February, offering pleasant weather for beach activities.</p>
            </div>
        </div>

        <div class="place-card">
            <img src="https://images.unsplash.com/photo-1512343879784-a960bf40e7f2?w=800" alt="Goa">
            <div class="info">
                <h2>6. Beaches of Goa</h2>
                <p>Goa is the perfect place for sun, sand, and relaxation. It features beautiful beaches, Portuguese architecture, and a very laid-back holiday vibe.</p>
            </div>
        </div>

        <div class="place-card">
            <img src="C:\Users\pavan\Downloads\Mysore palace.avif" alt="Mysore">
            <div class="info">
                <h2>7. Mysore Palace, Karnataka</h2>
                <p>One of the most spectacular palaces in India, the Mysore Palace is a marvel of Indo-Saracenic architecture, especially when illuminated at night.</p>
            </div>
        </div>

        <div class="place-card">
            <img src="C:\Users\pavan\Downloads\golden temple.jpg" alt="Golden Temple">
            <div class="info">
                <h2>8. Golden Temple, Amritsar</h2>
                <p>The holiest shrine in Sikhism, the Golden Temple is known for its stunning gold-covered exterior and its peaceful atmosphere of equality and service.</p>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 Incredible India Tourism | Visit us for more adventures!</p>
    </footer>

</body>
</html>
