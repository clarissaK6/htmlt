```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>🌐 Extended Internal Navigation Page</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: #fdfdfd;
        }
        nav {
            background-color: #f0f0f0;
            padding: 15px;
            position: fixed;
            top: 0;
            width: 100%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            z-index: 999;
        }
        nav a {
            margin: 0 12px;
            text-decoration: none;
            color: #333;
            font-size: 17px;
            font-weight: bold;
        }
        nav a:hover {
            color: #007acc;
        }
        section {
            padding: 100px 20px;
            margin-top: 70px;
        }
        h2 {
            text-align: center;
            font-size: 30px;
            color: #222;
        }
        p {
            text-align: center;
            font-size: 18px;
            max-width: 800px;
            margin: auto;
            line-height: 1.6;
        }
        ul {
            max-width: 700px;
            margin: 20px auto;
            font-size: 17px;
            line-height: 1.6;
        }
    </style>
</head>
<body>

    <!-- Navigation Menu -->
    <nav>
        <a href="#section1">📘 Introduction</a>
        <a href="#section2">🔍 Details</a>
        <a href="#section3">💡 Tips</a>
        <a href="#section4">📞 Contact</a>
        <a href="#section5">🎨 Design</a>
        <a href="#section6">📚 Resources</a>
    </nav>

    <!-- Section 1 -->
    <section id="section1">
        <h2>📘 Introduction</h2>
        <p>
            Welcome! This page demonstrates internal navigation using anchor links and IDs.
        </p>
    </section>

    <!-- Section 2 -->
    <section id="section2">
        <h2>🔍 Details</h2>
        <p>
            HTML internal navigation helps users quickly jump to different parts of a single page.
        </p>
    </section>

    <!-- Section 3 -->
    <section id="section3">
        <h2>💡 Tips</h2>
        <ul>
            <li>Use unique IDs for each section like <code>id="section1"</code>.</li>
            <li>Link to them using <code>&lt;a href="#section1"&gt;</code>.</li>
            <li>Use CSS to style and organize content clearly.</li>
            <li>Keep the navigation menu fixed for easier access.</li>
        </ul>
    </section>

    <!-- Section 4 -->
    <section id="section4">
        <h2>📞 Contact</h2>
        <p>
            You can contact us at <strong>8045697801</strong> or visit our office for more details.
        </p>
    </section>

    <!-- Section 5 -->
    <section id="section5">
        <h2>🎨 Design</h2>
        <p>
            Design your webpage using consistent fonts, colors, and spacing to improve user experience.
        </p>
    </section>

    <!-- Section 6 -->
    <section id="section6">
        <h2>📚 Resources</h2>
        <p>
            Check out these helpful resources to learn more:
        </p>
        <ul>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">MDN Web Docs – HTML</a></li>
            <li><a href="https://www.w3schools.com/html/" target="_blank">W3Schools HTML Tutorial</a></li>
        </ul>
    </section>

</body>
</html>
