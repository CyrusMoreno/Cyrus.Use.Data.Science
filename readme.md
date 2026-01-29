<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio: Codes & Notes Log</title>
    <style>
        :root {
            --primary-bg: #f4f7f6;
            --card-bg: #ffffff;
            --text-color: #333;
            --date-color: #888;
            --accent-blue: #007acc;
            --code-bg: #2d2d2d;
            --code-text: #f8f8f2;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--primary-bg);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        h1 {
            text-align: center;
            color: var(--accent-blue);
            border-bottom: 2px solid var(--accent-blue);
            padding-bottom: 10px;
        }

        /* Box styling */
        .box {
            background: var(--card-bg);
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            position: relative;
        }

        /* Date stamp styling */
        .date-stamp {
            font-size: 0.85rem;
            color: var(--date-color);
            text-align: right;
            display: block;
            margin-bottom: 10px;
            font-style: italic;
        }

        /* Text paragraph styling */
        .content-text {
            font-size: 1.1rem;
        }

        /* Code snippet styling */
        pre {
            background-color: var(--code-bg);
            color: var(--code-text);
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            font-family: 'Consolas', 'Monaco', monospace;
            border-left: 5px solid var(--accent-blue);
        }

        code {
            display: block;
            white-space: pre;
        }

        .label {
            font-weight: bold;
            text-transform: uppercase;
            font-size: 0.8rem;
            color: var(--accent-blue);
            margin-bottom: 5px;
            display: block;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to @Cyrus.Use.Data.Science github!</h1>

        <div class="box">
            <span class="date-stamp">Posted on: January 30, 2025</span>
            <span class="label">How to use this site?</span>
            <p class="content-text">
                This repo contains all codes I use in my channel. For Excel, use this <a href="https://1drv.ms/f/c/581dc08bd5488e5a/IgB61Ha6QfrYRaY1Euyjf5sqAdAcWOzWrh__BG4cvu6LQBE?e=lRLeMI">one drive link</a>.
            </p>
        </div>

<!-- 
        <div class="box">
            <span class="date-stamp">Posted on: December 29, 2025</span>
            <span class="label">Notes</span>
            <p class="content-text">
                Today I focused on structuring my HTML document. It is important to keep the CSS separate or at least organized within the style tags to ensure the layout remains responsive and clean across different devices.
            </p>
	    <pre><code>def calculate_area(radius):
    import math
    return math.pi * (radius ** 2)

print(f"Area: {calculate_area(5):.2f}")</code></pre>
        </div>

        <div class="box">
            <span class="date-stamp">Updated: December 28, 2025</span>
            <span class="label">JavaScript Snippet</span>
            <pre><code>function greetUser(name) {
    console.log(`Hello, ${name}! Welcome to your dashboard.`);
}

greetUser('Developer');</code></pre>
        </div>

        <div class="box">
            <span class="date-stamp">Archive: December 20, 2025</span>
            <span class="label">Python Snippet</span>
            <pre><code>def calculate_area(radius):
    import math
    return math.pi * (radius ** 2)

print(f"Area: {calculate_area(5):.2f}")</code></pre>
        </div>

    </div>
 -->
</body>
</html>
