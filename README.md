<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DecodeLabs - Frontend Development Project 1</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background: #f4f7fb;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        nav {
            background: #ffffff;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        nav a {
            text-decoration: none;
            margin: 0 15px;
            color: #2a5298;
            font-weight: bold;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: 30px auto;
        }

        section {
            background: white;
            margin-bottom: 25px;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }

        h2 {
            color: #1e3c72;
            margin-bottom: 15px;
        }

        ul {
            margin-left: 20px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
            gap: 20px;
        }

        .card {
            background: #eef4ff;
            padding: 20px;
            border-radius: 10px;
            border-left: 5px solid #2a5298;
        }

        .hero-image {
            width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }

        footer {
            background: #1e3c72;
            color: white;
            text-align: center;
            padding: 25px;
        }

        .badge {
            display: inline-block;
            background: #2a5298;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            margin-top: 10px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>DecodeLabs Frontend Development</h1>
    <p>Industrial Training Kit 2026 - Project 1</p>
    <span class="badge">Static Webpage Design 🎨</span>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#goal">Goal</a>
    <a href="#requirements">Requirements</a>
    <a href="#skills">Skills</a>
    <a href="#guidelines">Guidelines</a>
</nav>

<div class="container">

    <section id="about">
        <h2>Welcome to the Team 🚀</h2>
        <p>
            Step into the role of a Frontend Developer at DecodeLabs.
            This project focuses on building a static webpage using
            semantic HTML and clean CSS styling. The objective is to
            establish strong fundamentals before moving to advanced
            frontend concepts.
        </p>

        <img
            class="hero-image"
            src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=1200"
            alt="Frontend Development">
    </section>

    <section id="goal">
        <h2>Project Goal</h2>
        <p>
            Create a static webpage using HTML and CSS that demonstrates
            proper structure, readability, and semantic design principles.
        </p>
    </section>

    <section id="requirements">
        <h2>Key Requirements</h2>

        <div class="cards">
            <div class="card">
                <h3>HTML Structure</h3>
                <p>Use semantic elements such as header, nav, section, and footer.</p>
            </div>

            <div class="card">
                <h3>Headings & Sections</h3>
                <p>Organize content with proper heading hierarchy and sections.</p>
            </div>

            <div class="card">
                <h3>Images</h3>
                <p>Include relevant images with descriptive alt attributes.</p>
            </div>

            <div class="card">
                <h3>Readable Layout</h3>
                <p>Ensure spacing, typography, and alignment create a clean design.</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Key Skills Covered</h2>

        <ul>
            <li>HTML Fundamentals</li>
            <li>Semantic HTML</li>
            <li>CSS Styling</li>
            <li>Page Layout Design</li>
            <li>Responsive Web Design Basics</li>
        </ul>
    </section>

    <section id="guidelines">
        <h2>Qualification Criteria</h2>

        <ul>
            <li>Complete Project 1 successfully.</li>
            <li>Project quality must be verified.</li>
            <li>Project 1 is mandatory before unlocking future projects.</li>
            <li>Demonstrate understanding of structure and styling.</li>
        </ul>
    </section>

    <section>
        <h2>Conclusion</h2>
        <p>
            Frontend development is best learned through practical experience.
            Experiment with layouts, typography, spacing, and the CSS box model.
            Every project contributes to a professional portfolio and strengthens
            design-to-code skills.
        </p>
    </section>

</div>

<footer>
    <h3>DecodeLabs</h3>
    <p>Frontend Development Training Program 2026</p>
    <p>🌐 www.decodelabs.tech</p>
    <p>📧 decodelabs.tech@gmail.com</p>
</footer>

</body>
</html>
