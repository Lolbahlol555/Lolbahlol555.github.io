<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Specify favicon -->
    <link rel="icon" href="Images/star.png" type="image/png">
    <title>Mohamed A. Cherif - Personal Webpage</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: "Tiny5", Arial, sans-serif; /* Using Tiny5 font as the main font */
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 20px;
            border-bottom: 1px solid #ffffff;
        }
        header h1 {
            margin: 0;
            font-size: 36px; /* Increased font size for the header */
        }
        header p {
            font-size: 18px; /* Smaller font size for additional text */
            margin-top: 10px; /* Adjusted margin for spacing */
        }
        .alias-text {
            font-size: 20px; /* Larger font size for the alias text */
        }
        main {
            padding: 20px;
        }
        .section-title {
            font-size: 24px;
            margin-top: 20px;
            margin-bottom: 10px;
            text-align: center;
            position: relative;
        }
        .about-me .section-title::before,
        .about-me .section-title::after {
            content: "??";
            margin: 0 10px;
        }
        .projects .section-title::before,
        .projects .section-title::after {
            content: "??";
            margin: 0 10px;
        }
        .contact .section-title::before,
        .contact .section-title::after {
            content: "??";
            margin: 0 10px;
        }
        .about-me {
            text-align: center;
        }
        .contact, .projects {
            text-align: center;
            margin-top: 20px;
        }
        .contact a, .projects a {
            color: #00ff00; /* Green colored links */
            text-decoration: none;
            margin: 0 10px;
            display: inline-block;
            font-family: Arial, sans-serif; /* Resetting font for links */
        }
        .contact img {
            vertical-align: middle;
            margin-right: 5px;
        }
        .map-container {
            text-align: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mohamed A. Cherif</h1> <!-- Updated name here -->
	<img src="images/MA.png" alt="Map of the Kingdom of Morocco, Sahara included">
        <p>Age: 15 | Country of Origin: Morocco | City: Marrakesh</p>
        <p>Description: Ligma Balls</p>
        <p class="alias-text">Under the alias "555"</p>
    </header>
    <main>
        <div class="about-me">
            <h2 class="section-title">About me</h2>
            <p>I'm just a student in Marrakesh.</p>
        </div>
        <div class="projects">
            <h2 class="section-title">Projects</h2>
            <p>
                <a href="https://gamejolt.com/games/BWSS_2/904130" target="_blank">Bowser's West Side Story 2</a><br>
                <a href="https://gamejolt.com/games/BWSS/854506" target="_blank">Bowser's West Side Story</a><br>
                <a href="https://gamejolt.com/games/Snake-Game/821110" target="_blank">Snake Game</a><br>
                +More insignificant games at <a href="https://gamejolt.com/@444ProductionsWare" target="_blank">@444ProductionsWare</a> in Gamejolt
            </p>
        </div>
        <div class="contact">
            <h2 class="section-title">Contact</h2>
            <p>
                <a href="https://www.facebook.com/simoaitcherif" target="_blank">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Icon" width="20" height="20"> Simo Ait Cherif
                </a>
                <a href="https://twitter.com/simomario159" target="_blank">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Logo_of_Twitter.svg" alt="Twitter Icon" width="20" height="20"> @simomario159
                </a>
            </p>
        </div>
    </main>
</body>
</html>
