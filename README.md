<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>André Silva - GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 10px;
            padding: 30px;
            margin-bottom: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        h1 {
            color: #58a6ff;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            color: #f0f6fc;
            margin: 20px 0 15px 0;
            padding-bottom: 10px;
            border-bottom: 1px solid #30363d;
        }
        
        h3 {
            color: #58a6ff;
            margin: 15px 0;
        }
        
        .intro {
            font-size: 1.1rem;
            margin-bottom: 20px;
            text-align: center;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        
        .social-links a {
            color: #c9d1d9;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: #58a6ff;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .skill-item {
            background-color: #238636;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .stat-card {
            background-color: #21262d;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        .stat-value {
            font-size: 1.8rem;
            font-weight: bold;
            color: #58a6ff;
            margin: 10px 0;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #8b949e;
        }
        
        .divider {
            height: 1px;
            background-color: #30363d;
            margin: 25px 0;
        }
        
        .language-stats {
            background-color: #21262d;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
        }
        
        .language-bar {
            height: 10px;
            background-color: #238636;
            border-radius: 5px;
            margin: 10px 0;
        }
        
        @media (max-width: 768px) {
            .stats-grid {
                grid-template-columns: 1fr;
            }
            
            .skills {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi 👋, I'm André Silva</h1>
            <p class="intro">Welcome to my GitHub profile! I'm a back-end developer. I'm currently expanding my knowledge in software development and love working on interesting projects.</p>
        </header>
        
        <div class="social-links">
            <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
            <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
            <a href="#" title="Twitter"><i class="fab fa-twitter"></i></a>
        </div>
    </div>
    
    <div class="container">
        <h2>About Me</h2>
        <ul>
            <li>🔭 I’m currently working on expanding my knowledge in software development</li>
            <li>🌱 I’m currently learning advanced back-end technologies</li>
            <li>👯 I’m looking to collaborate on interesting projects</li>
            <li>💬 Ask me about back-end development</li>
        </ul>
    </div>
    
    <div class="container">
        <h2>Languages and Tools</h2>
        <div class="skills">
            <div class="skill-item"><i class="fab fa-cuttlefish"></i> C</div>
            <div class="skill-item"><i class="fab fa-csharp"></i> C#</div>
            <div class="skill-item"><i class="fab fa-js"></i> JavaScript</div>
            <div class="skill-item"><i class="fab fa-react"></i> React</div>
            <div class="skill-item"><i class="fas fa-database"></i> MySQL</div>
            <div class="skill-item"><i class="fab fa-node-js"></i> Node.js</div>
            <div class="skill-item"><i class="fab fa-html5"></i> HTML</div>
            <div class="skill-item"><i class="fab fa-css3-alt"></i> CSS</div>
        </div>
    </div>
    
    <div class="container">
        <h2>GitHub Statistics</h2>
        
        <div class="stats-grid">
            <div class="stat-card">
                <div class="stat-value">0</div>
                <div class="stat-label">Total Stars Earned</div>
            </div>
            <div class="stat-card">
                <div class="stat-value">0</div>
                <div class="stat-label">Total Commits (2025)</div>
            </div>
            <div class="stat-card">
                <div class="stat-value">0</div>
                <div class="stat-label">Total PRs</div>
            </div>
            <div class="stat-card">
                <div class="stat-value">0</div>
                <div class="stat-label">Total Issues</div>
            </div>
        </div>
        
        <div class="divider"></div>
        
        <h3>Most Used Languages</h3>
        <div class="language-stats">
            <p>Currently no language data available. Start coding to see your language statistics here!</p>
            <!--
            <div class="language-bar" style="width: 45%">JavaScript 45%</div>
            <div class="language-bar" style="width: 30%">Python 30%</div>
            <div class="language-bar" style="width: 15%">HTML 15%</div>
            <div class="language-bar" style="width: 10%">CSS 10%</div>
            -->
        </div>
    </div>
    
    <div class="container">
        <h2>Connect with me</h2>
        <p>Feel free to reach out if you want to collaborate on a project or just want to chat about technology!</p>
        
        <div class="social-links">
            <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="#" title="Email"><i class="fas fa-envelope"></i> Email</a>
            <a href="#" title="Twitter"><i class="fab fa-twitter"></i> Twitter</a>
        </div>
    </div>
</body>
</html>
