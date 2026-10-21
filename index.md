<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shivam Sharma - Semantic Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        /* Semantic Header */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1.2rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        /* Semantic Nav */
        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        /* Layout wrapper for Main and Aside */
        .container {
            max-width: 1050px;
            margin: 2rem auto;
            padding: 0 1rem;
            display: flex;
            gap: 2rem;
        }
        /* Semantic Main Content */
        main {
            flex: 3;
            background: white;
            padding: 2.5rem;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        /* Semantic Aside (Sidebar) */
        aside {
            flex: 1;
            background: white;
            padding: 1.5rem;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
            height: fit-content;
        }
        h1, h2, h3, h4 {
            color: #2c3e50;
        }
        h1 {
            margin-top: 0;
            font-size: 2rem;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 10px;
        }
        /* Semantic Article & Section */
        article {
            margin-bottom: 2rem;
        }
        .image-gallery {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 1rem;
        }
        .image-card {
            background: #fafafa;
            border: 1px solid #ddd;
            padding: 10px;
            border-radius: 6px;
            text-align: center;
            flex: 1;
            min-width: 200px;
        }
        .image-card img {
            border-radius: 4px;
            max-width: 100%;
            height: auto;
        }
        .image-card p {
            font-size: 0.85rem;
            color: #555;
            margin-top: 8px;
        }
        ul {
            padding-left: 20px;
        }
        li {
            margin-bottom: 6px;
        }
        /* Semantic Footer */
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #2c3e50;
            color: white;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <!-- Semantic Header -->
    <header>
        <div class="logo">Shivam's Portfolio</div>
        <!-- Semantic Nav -->
        <nav aria-label="Main Navigation">
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="college-info.html">College Info</a>
        </nav>
    </header>

    <!-- Page Content Container -->
    <div class="container">

        <!-- Semantic Main Content Area -->
        <main>
            <!-- Semantic Section 1: Introduction -->
            <section>
                <h1>Welcome to My Semantic Portfolio</h1>
                <article>
                    <h2>Introduction</h2>
                    <p>Hello! My name is <strong>Shivam Sharma</strong>. This webpage has been restructured using modern <strong>Semantic HTML5 elements</strong> (`&lt;header&gt;`, `&lt;nav&gt;`, `&lt;main&gt;`, `&lt;section&gt;`, `&lt;article&gt;`, and `&lt;aside&gt;`) to improve code readability, search engine optimization (SEO), and web accessibility for screen readers.</p>
                </article>
            </section>

            <!-- Semantic Section 2: Portfolio Gallery with Accessible Images -->
            <section>
                <h2>Project & Interest Gallery</h2>
                <article>
                    <h3>Visual Highlights</h3>
                    <p>Below are snapshots representing my projects, outdoor activities, and workspace environment, complete with meaningful accessibility `alt` text:</p>
                    
                    <div class="image-gallery">
                        <figure class="image-card">
                            <img src="images/image1.jpg" alt="A scenic view of a mountain trekking trail surrounded by green hills in Uttarakhand" width="240" height="160">
                            <figcaption><p>Mountain Trekking Trail</p></figcaption>
                        </figure>
                        
                        <figure class="image-card">
                            <img src="images/image2.jpg" alt="A clean workspace desk setup with a laptop displaying HTML code lines and a notebook" width="240" height="160">
                            <figcaption><p>Web Development Setup</p></figcaption>
                        </figure>
                        
                        <figure class="image-card">
                            <img src="images/image3.jpg" alt="Dumbbells arranged neatly on a metal rack inside a fitness gym training room" width="240" height="160">
                            <figcaption><p>Gym Training Gear</p></figcaption>
                        </figure>
                    </div>
                </article>
            </section>
        </main>

        <!-- Semantic Aside (Sidebar) -->
        <aside>
            <h3>Quick Links</h3>
            <p>External developer resources:</p>
            <ul>
                <li><a href="https://www.developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a></li>
                <li><a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub Platform</a></li>
            </ul>

            <h4 style="margin-top: 1.5rem;">Core Skills</h4>
            <ul>
                <li>HTML5 Semantics</li>
                <li>CSS Styling</li>
                <li>Git Version Control</li>
            </ul>
        </aside>

    </div>

    <!-- Semantic Footer -->
    <footer>
        <p>&copy; 2026 Shivam Sharma. Assignment 3.4 — Semantic HTML & Accessibility.</p>
    </footer>

</body>
</html>