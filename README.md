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
            position: relative;
        }
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                linear-gradient(rgba(30, 30, 30, 0.9), rgba(30, 30, 30, 0.9)),
                url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100'%3E%3Cg fill-rule='evenodd'%3E%3Cg fill='%23424242' fill-opacity='0.4'%3E%3Cpath opacity='.5' d='M96 95h4v1h-4v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4h-9v4h-1v-4H0v-1h15v-9H0v-1h15v-9H0v-1h15v-9H0v-1h15v-9H0v-1h15v-9H0v-1h15v-9H0v-1h15v-9H0v-1h15v-9H0v-1h15V0h1v15h9V0h1v15h9V0h1v15h9V0h1v15h9V0h1v15h9V0h1v15h9V0h1v15h9V0h1v15h9V0h1v15h4v1h-4v9h4v1h-4v9h4v1h-4v9h4v1h-4v9h4v1h-4v9h4v1h-4v9h4v1h-4v9h4v1h-4v9zm-1 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-9-10h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm9-10v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-9-10h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm9-10v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-9-10h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm9-10v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-10 0v-9h-9v9h9zm-9-10h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9zm10 0h9v-9h-9v9z'/%3E%3Cpath d='M6 5V0H5v5H0v1h5v94h1V6h94V5H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
            z-index: -1;
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
            position: relative;
            overflow: hidden;
        }
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange)), 
                        linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange));
            background-size: 60px 60px;
            background-position: 0 0, 30px 30px;
            opacity: 0.1;
            z-index: -1;
        }
        .animated-title {
            font-size: 48px;
            color: var(--fl-orange);
            position: relative;
            z-index: 1;
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
            position: relative;
        }
        section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle, transparent 20%, var(--fl-black) 20%, var(--fl-black) 80%, transparent 80%, transparent), 
                        radial-gradient(circle, transparent 20%, var(--fl-black) 20%, var(--fl-black) 80%, transparent 80%, transparent) 50px 50px;
            background-size: 100px 100px;
            opacity: 0.05;
            z-index: -1;
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
            position: relative;
            overflow: hidden;
        }
        .aspect-item::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(to bottom right, rgba(255, 255, 255, 0.1) 0%, rgba(255, 255, 255, 0.05) 50%, transparent 50%, transparent 100%);
            transform: rotate(45deg);
            z-index: 1;
        }
        .beat-pad {
            background-color: var(--fl-dark-gray);
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px 0;
            position: relative;
            overflow: hidden;
        }
        .beat-pad::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange)), 
                linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange));
            background-size: 60px 60px;
            background-position: 0 0, 30px 30px;
            opacity: 0.1;
            z-index: 0;
        }
        .beat-pad p {
            position: relative;
            z-index: 1;
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
            position: relative;
            overflow: hidden;
        }
        .career-item::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(to bottom right, rgba(255, 255, 255, 0.1) 0%, rgba(255, 255, 255, 0.05) 50%, transparent 50%, transparent 100%);
            transform: rotate(45deg);
            z-index: 1;
        }
        .career-item ul {
            list-style-type: none;
            padding: 0;
            position: relative;
            z-index: 2;
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
            position: relative;
            overflow: hidden;
        }
        .testimonial::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange));
            background-size: 10px 10px;
            opacity: 0.1;
            z-index: 0;
        }
        .testimonial p {
            font-size: 1.1em;
            margin-bottom: 10px;
            position: relative;
            z-index: 1;
        }
        .testimonial cite {
            font-style: italic;
            font-size: 0.9em;
            position: relative;
            z-index: 1;
        }
        footer {
            background-color: var(--fl-dark-gray);
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
            position: relative;
            overflow: hidden;
        }
        footer::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange)), 
                linear-gradient(45deg, var(--fl-orange) 25%, transparent 25%, transparent 75%, var(--fl-orange) 75%, var(--fl-orange));
            background-size: 20px 20px;
            background-position: 0 0, 10px 10px;
            opacity: 0.1;
            z-index: 0;
        }
        footer p {
            position: relative;
            z-index: 1;
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
            position: relative;
            overflow: hidden;
        }
        .cta-button:hover {
            background-color: var(--fl-light-gray);
            color: var(--fl-orange);
        }
        .cta-button::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(to bottom right, rgba(255, 255, 255, 0.2) 0%, rgba(255, 255, 255, 0.1) 50%, transparent 50%, transparent 100%);
            transform: rotate(45deg);
            transition: 0.3s;
        }
        .cta-button:hover::after {
            top: -100%;
            left: -100%;
        }
    </style>
</head>
<body>
    <!-- The rest of the HTML remains unchanged -->
</body>
</html>
