<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name — Professional Troublemaker</title>
    <style>
        body {
            background-color: #f7f3ee; /* Soft parchment */
            color: #0b1d3a;
            font-family: Georgia, serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 60px 20px;
            line-height: 1.5;
        }
        /* Quirky floating nav */
        nav {
            display: flex;
            gap: 15px;
            margin-bottom: 80px;
            font-family: monospace;
            font-size: 0.9rem;
        }
        nav a {
            background: #0b1d3a;
            color: #f7f3ee;
            padding: 5px 10px;
            text-decoration: none;
            transform: rotate(-2deg);
            transition: transform 0.2s;
        }
        nav a:nth-child(even) {
            transform: rotate(2deg); /* Playful tilt */
        }
        nav a:hover {
            transform: scale(1.1) rotate(0deg);
        }
        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            font-weight: normal;
            letter-spacing: -1px;
        }
        .highlight {
            background-color: #ffde59; /* Bright marketing yellow accent */
            padding: 0 5px;
            font-style: italic;
        }
        .tagline {
            font-size: 1.3rem;
            max-width: 600px;
            margin-bottom: 40px;
        }
        /* A fun brutalist card */
        .marquee-box {
            border: 2px dashed #0b1d3a;
            padding: 15px;
            font-family: monospace;
            font-size: 0.85rem;
            display: inline-block;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <nav>
        <a href="index.html">[home]</a>
        <a href="about.html">[about]</a>
        <a href="work.html">[work]</a>
        <a href="photo.html">[photos]</a>
        <a href="contact.html">[ping me]</a>
    </nav>

    <main>
        <h1>I make campaigns <span class="highlight">work</span>, and websites for fun.</h1>
        <p class="tagline">I'm [Your Name]. A marketer who actually understands data, hates corporate jargon, and writes code primarily powered by panic and iced coffee.</p>
        
        <div class="marquee-box">
            ⚡ Status: Currently debugging code I don't fully understand.
        </div>
    </main>

</body>
</html>
