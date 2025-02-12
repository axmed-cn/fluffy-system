<!DOCTYPE html>
<html lang="so">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Mohamed Yusuf Cllaahi</title>
    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #1e3c72, #2a5298);
            color: white;
            text-align: center;
        }

        /* Header */
        .header {
            background: rgba(0, 0, 0, 0.5);
            padding: 100px 0;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .header h1 {
            font-size: 3em;
            animation: fadeIn 2s ease-in-out;
        }

        /* Main Container */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Sections */
        .section {
            margin-top: 50px;
            padding: 40px;
            background-color: rgba(255, 255, 255, 0.9);
            color: #333;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

        .section:hover {
            transform: scale(1.05);
        }

        /* Warning Section (Sigaarka) */
        .warning {
            background-color: #ffcccc;
            border-left: 5px solid #ff0000;
            color: black;
            font-weight: bold;
        }

        /* Button */
        .button {
            background-color: #1e3c72;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: background-color 0.3s ease;
            display: inline-block;
            margin-top: 10px;
        }

        .button:hover {
            background-color: #2a5298;
        }

        /* Image Styling */
        .image {
            max-width: 250px;
            margin-top: 20px;
            border-radius: 50%;
            border: 5px solid #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-50px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* New Features */
        .highlight {
            background-color: #ffeb3b;
            color: #000;
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
            margin: 10px 0;
        }

        .testimonial {
            background-color: #e3f2fd;
            color: #000;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }

        .testimonial p {
            font-style: italic;
        }

        .testimonial-author {
            font-weight: bold;
            margin-top: 10px;
        }

        @media (max-width: 768px) {
            .header h1 { font-size: 2em; }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <h1>WELCOME</h1>
    </div>

    <!-- Main Container -->
    <div class="container">

        <!-- About Section -->
        <div class="section">
            <img src="content://com.android.externalstorage.documents/tree/primary%3AM.y.c/document/primary%3AM.y.c%2FIMG-20250211-WA0000.jpg" alt="" class="image" width="3" height="3"/>
            <h2>About Me</h2>
            <p>Welcome to my personal site. Here you will find information about my services, skills, and work.</p>
            <a href="#" class="button">Learn More</a>
        </div>

        <!-- Highlight Section -->
        <div class="section">
            <h2>What I Offer</h2>
            <p>Here are some of the services I provide:</p>
            <div class="highlight">Web Development</div>
            <div class="highlight">Graphic Design</div>
            <div class="highlight">Consulting</div>
        </div>

        <!-- Testimonial Section -->
        <div class="section">
            <h2>What People Say</h2>
            <div class="testimonial">
                <p>"Mohamed is a highly skilled professional with a great eye for detail. Highly recommended!"</p>
                <div class="testimonial-author">- John Doe</div>
            </div>
            <div class="testimonial">
                <p>"Working with Mohamed was a pleasure. He delivered beyond my expectations."</p>
                <div class="testimonial-author">- Jane Smith</div>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="section">
            <h2>Contact</h2>
            <p>If you would like to get in touch, feel free to reach out to me through the contact section.</p>
            <a href="#" class="button">Contact Me</a>
        </div>

        <!-- Awareness Section (Sigaarka) -->
        <div class="section warning">
            <h2>🚫 Digniin: Khatarta Sigaarka</h2>
            <p>🚭 Sigaarku wuxuu sababi karaa cudurro badan sida kansarka, cudurrada sanbabada, iyo wadnaha.</p>
            <p>Caafimaadkaaga ilaali, ka fogow sigaar cabidda!</p>
            <img src="smoking-danger.jpg" alt="Sigaarka Khatartiisa" class="image">
        </div>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Mohamed Yusuf Cllaahi | All Rights Reserved</p>
    </footer>

</body>
</html>
