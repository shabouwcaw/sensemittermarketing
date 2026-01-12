<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Development & Research Services</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --hover-color: #1d4ed8;
            --bg-color: #f8fafc;
            --text-color: #1e293b;
            --card-bg: #ffffff;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 40px 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 60px;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #0f172a;
        }

        p.subtitle {
            font-size: 1.1rem;
            color: #64748b;
        }

        .section-title {
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 10px;
            margin-top: 40px;
            margin-bottom: 20px;
            font-size: 1.25rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            color: #475569;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
            text-decoration: none;
            color: var(--text-color);
            border: 1px solid #e2e8f0;
            transition: transform 0.2s, box-shadow 0.2s, border-color 0.2s;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
            border-color: var(--primary-color);
            color: var(--primary-color);
        }

        .card span {
            font-weight: 600;
            font-size: 1.1rem;
        }

        footer {
            margin-top: 60px;
            text-align: center;
            font-size: 0.9rem;
            color: #94a3b8;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Game Development Hub</h1>
            <p class="subtitle">Creative Services, Data Science, and Strategic Growth</p>
        </header>

        <h2 class="section-title">Production & Marketing</h2>
        <div class="grid">
            <a href="Game_Design.html" class="card">
                <span>Game Design</span>
            </a>
            <a href="Creative.html" class="card">
                <span>Creative</span>
            </a>
            <a href="ASO.html" class="card">
                <span>ASO</span>
            </a>
            <a href="Playtesting.html" class="card">
                <span>Playtesting</span>
            </a>
        </div>

        <h2 class="section-title">Research & Science</h2>
        <div class="grid">
            <a href="Science_Research.html" class="card">
                <span>Science Research</span>
            </a>
            <a href="User_Research.html" class="card">
                <span>User Research</span>
            </a>
        </div>

        <h2 class="section-title">Company & Team</h2>
        <div class="grid">
            <a href="About_Us.html" class="card">
                <span>About Us</span>
            </a>
            <a href="Executives.html" class="card">
                <span>Executives</span>
            </a>
            <a href="Marketers.html" class="card">
                <span>Marketers</span>
            </a>
            <a href="Pricing.html" class="card">
                <span>Pricing</span>
            </a>
        </div>

        <footer>
            &copy; 2026 Shabouwcaw Games. All rights reserved.
        </footer>
    </div>

</body>
</html>
