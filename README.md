<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineering Thru Beats: Exploring Music Engineering</title>
    <link href="https://fonts.googleapis.com/css2?family=Bangers&family=Permanent+Marker&family=Press+Start+2P&family=Russo+One&family=Special+Elite&display=swap" rel="stylesheet">
    <style>
        :root {
            --fl-orange: #ff8c00;
            --fl-dark-gray: #333333;
            --fl-light-gray: #4d4d4d;
            --fl-black: #1e1e1e;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: var(--fl-black);
            color: #ffffff;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: var(--fl-dark-gray);
            padding: 20px 0;
            text-align: center;
        }
        .animated-title {
            font-size: 48px;
            color: var(--fl-orange);
        }
        nav {
            background-color: var(--fl-light-gray);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            padding: 15px 20px;
        }
        nav ul li a {
            color: #ffffff;
            text-decoration: none;
        }
        section {
            padding: 50px 0;
        }
        h2 {
            color: var(--fl-orange);
        }
        .aspect-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .aspect-item {
            background-color: var(--fl-light-gray);
            padding: 20px;
            border-radius: 5px;
        }
        .beat-pad {
            background-color: var(--fl-dark-gray);
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px 0;
        }
        .careers-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .career-item {
            background-color: var(--fl-light-gray);
            padding: 20px;
            border-radius: 5px;
        }
        .career-item ul {
            list-style-type: none;
            padding: 0;
        }
        .career-item li {
            margin-bottom: 5px;
        }
        .dr-dre {
            font-family: 'Permanent Marker', cursive;
        }
        .benny-blanco {
            font-family: 'Press Start 2P', cursive;
        }
        .metro-boomin {
            font-family: 'Russo One', sans-serif;
        }
        .cash-cobain {
            font-family: 'Bangers', cursive;
        }
        .timbaland {
            font-family: 'Special Elite', cursive;
        }
        .career-item h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .testimonial {
            background-color: var(--fl-dark-gray);
            padding: 20px;
            margin-bottom: 20px;
            border-left: 5px solid var(--fl-orange);
        }
        .testimonial p {
            font-size: 1.1em;
            margin-bottom: 10px;
        }
        .testimonial cite {
            font-style: italic;
            font-size: 0.9em;
        }
        footer {
            background-color: var(--fl-dark-gray);
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: var(--fl-orange);
            color: var(--fl-black);
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s ease;
            margin-bottom: 20px;
        }
        .cta-button:hover {
            background-color: var(--fl-light-gray);
            color: var(--fl-orange);
        }
        .producer-image {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        .career-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .career-item ul {
            text-align: left;
        }
    </style>
</head>
<body>
    <header>
        <div class="animated-title">
            Engineering Thru Beats
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#intro">Intro</a></li>
            <li><a href="#aspects">Key Aspects</a></li>
            <li><a href="#beatpad">Beat Pad</a></li>
            <li><a href="#careers">Careers</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="why-beats.html">Why Beats?</a></li>
        </ul>
    </nav>

    <main class="container">
        <section id="intro">
            <h2>Welcome to the World of Music Engineering</h2>
            <p>Explore the fascinating intersection of technology and creativity that shapes the soundtrack of our lives.</p>
        </section>

        <section id="aspects">
            <h2>Key Aspects of Music Engineering</h2>
            <div class="aspect-grid">
                <div class="aspect-item">
                    <h3>Recording</h3>
                    <p>Capture pristine audio using state-of-the-art equipment and techniques.</p>
                </div>
                <div class="aspect-item">
                    <h3>Mixing</h3>
                    <p>Blend multiple tracks into a cohesive and balanced sonic masterpiece.</p>
                </div>
                <div class="aspect-item">
                    <h3>Mastering</h3>
                    <p>Polish and prepare your tracks for distribution across various platforms.</p>
                </div>
                <div class="aspect-item">
                    <h3>Sound Design</h3>
                    <p>Create unique audio elements that bring productions to life.</p>
                </div>
            </div>
        </section>

        <section id="beatpad">
            <h2>Create Your Own Beats</h2>
            <p>Ready to make some music? Try our interactive beat maker!</p>
            <a href="beat_maker.html" class="cta-button">Launch Beat Maker</a>
            <div class="beat-pad">
                <p>Beat Pad Preview</p>
            </div>
        </section>

        <section id="careers">
            <h2>Careers in Music Production</h2>
            <div class="careers-grid">
                <div class="career-item">
                    <img src="images/drdre.jpg" alt="Dr. Dre" class="producer-image">
                    <h3 class="dr-dre">Dr. Dre</h3>
                    <ul class="dr-dre">
                        <li>Real Name: Andre Romelle Young</li>
                        <li>Started as: DJ in the 1980s</li>
                        <li>Known for: Pioneering West Coast G-funk</li>
                        <li>Notable Acts: N.W.A, Eminem, Snoop Dogg</li>
                        <li>Estimated Net Worth: $820 million</li>
                    </ul>
                </div>
                <div class="career-item">
                    <img src="images/benny.jpg" alt="Benny Blanco" class="producer-image">
                    <h3 class="benny-blanco">Benny Blanco</h3>
                    <ul class="benny-blanco">
                        <li>Real Name: Benjamin Joseph Levin</li>
                        <li>Started: Producing in his teens</li>
                        <li>Known for: Pop and hip-hop production</li>
                        <li>Notable Acts: Ed Sheeran, Justin Bieber, Maroon 5</li>
                        <li>Estimated Net Worth: $50 million</li>
                    </ul>
                </div>
                <div class="career-item">
                    <img src="images/metro.jpg" alt="Metro Boomin" class="producer-image">
                    <h3 class="metro-boomin">Metro Boomin</h3>
                    <ul class="metro-boomin">
                        <li>Real Name: Leland Tyler Wayne</li>
                        <li>Started: Producing at age 13</li>
                        <li>Known for: Trap music production</li>
                        <li>Notable Acts: Future, 21 Savage, The Weeknd</li>
                        <li>Estimated Net Worth: $16 million</li>
                    </ul>
                </div>
                <div class="career-item">
                    <img src="images/cash.jpg" alt="Cash Cobain" class="producer-image">
                    <h3 class="cash-cobain">Cash Cobain</h3>
                    <ul class="cash-cobain">
                        <li>Known as: "The Sample God"</li>
                        <li>Started: In the New York drill scene</li>
                        <li>Known for: Innovative sampling in drill music</li>
                        <li>Notable Acts: Various NY drill artists</li>
                        <li>Estimated Net Worth: Not publicly available</li>
                    </ul>
                </div>
                <div class="career-item">
                    <img src="images/timb.jpg" alt="Timbaland" class="producer-image">
                    <h3 class="timbaland">Timbaland</h3>
                    <ul class="timbaland">
                        <li>Real Name: Timothy Zachary Mosley</li>
                        <li>Started: As part of production duo S.B.I.</li>
                        <li>Known for: Innovative rhythm and sound design</li>
                        <li>Notable Acts: Missy Elliott, Justin Timberlake, Aaliyah</li>
                        <li>Estimated Net Worth: $85 million</li>
                    </ul>
                </div>
                <div class="career-item">
                    <h3>General Career Info</h3>
                    <p>Music Producer Salary Range: $25,000 - $1,000,000+</p>
                    <p>Education: Degree in Music Production or Business can open doors to higher-paying opportunities</p>
                </div>
            </div>
        </section>

        <section id="testimonials">
            <h2>What the Pros Say</h2>
            <div class="testimonial dr-dre">
                <p>"The most important thing is to be true to yourself and make music that you love."</p>
                <cite>- Dr. Dre</cite>
            </div>
            <div class="testimonial benny-blanco">
                <p>"Don't be afraid to experiment. Some of the best sounds come from happy accidents."</p>
                <cite>- Benny Blanco</cite>
            </div>
            <div class="testimonial metro-boomin">
                <p>"If you want to be a producer, you gotta make at least five beats a day for three summers."</p>
                <cite>- Metro Boomin</cite>
            </div>
            <div class="testimonial cash-cobain">
                <p>"Sampling is an art form. It's about finding that perfect sound and flipping it into something new."</p>
                <cite>- Cash Cobain</cite>
            </div>
            <div class="testimonial timbaland">
                <p>"To make it in this industry, you need to have your own sound. Be innovative and push boundaries."</p>
                <cite>- Timbaland</cite>
            </div>
            <div class="testimonial">
                <p>"Engineering isn't just about technicality; it's about translating emotion into sound."</p>
                <cite>- Alex Turner, Platinum Record Producer</cite>
            </div>
            <div class="testimonial">
                <p>"My engineering degree gave me the edge in understanding both the art and science of music production."</p>
                <cite>- Samantha Lee, Grammy-nominated Engineer</cite>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Engineering Thru Beats. All rights reserved.</p>
    </footer>

    <script>
        // JavaScript for animations and interactivity would go here
    </script>
</body>
</html>
