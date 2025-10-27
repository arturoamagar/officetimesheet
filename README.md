
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Activity Dashboard - Welcome</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .hero {
            text-align: center;
            color: white;
            margin-bottom: 50px;
            animation: fadeInDown 0.8s ease;
        }
        
        .hero h1 {
            font-size: 3.5em;
            margin-bottom: 10px;
            text-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        
        .hero p {
            font-size: 1.3em;
            opacity: 0.9;
            margin-bottom: 30px;
        }
        
        .cta-button {
            display: inline-block;
            background: white;
            color: #667eea;
            padding: 18px 50px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 1.1em;
            transition: all 0.3s ease;
            box-shadow: 0 8px 25px rgba(0,0,0,0.2);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 35px rgba(0,0,0,0.3);
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }
        
        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
            animation: fadeInUp 0.8s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
        }
        
        .feature-icon {
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        
        .feature-title {
            font-size: 1.3em;
            color: #333;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        .feature-text {
            color: #666;
            line-height: 1.6;
        }
        
        .info-section {
            background: white;
            padding: 40px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            animation: fadeInUp 0.8s ease;
        }
        
        .info-section h2 {
            color: #667eea;
            margin-bottom: 20px;
            font-size: 1.8em;
        }
        
        .info-section h3 {
            color: #333;
            margin-top: 20px;
            margin-bottom: 15px;
            font-size: 1.2em;
        }
        
        .info-section p {
            color: #666;
            line-height: 1.8;
            margin-bottom: 15px;
        }
        
        .step-list {
            list-style: none;
            counter-reset: step-counter;
        }
        
        .step-list li {
            counter-increment: step-counter;
            margin-bottom: 15px;
            padding-left: 40px;
            position: relative;
            color: #666;
            line-height: 1.6;
        }
        
        .step-list li:before {
            content: counter(step-counter);
            position: absolute;
            left: 0;
            top: 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 600;
        }
        
        .code-block {
            background: #f5f5f5;
            border-left: 4px solid #667eea;
            padding: 15px;
            border-radius: 8px;
            font-family: 'Courier New', monospace;
            overflow-x: auto;
            margin: 15px 0;
            color: #333;
        }
        
        .footer {
            text-align: center;
            color: white;
            padding: 30px;
            opacity: 0.8;
        }
        
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .github-link {
            color: #667eea;
            text-decoration: none;
            font-weight: 600;
        }
        
        .github-link:hover {
            text-decoration: underline;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.2em;
            }
            
            .hero p {
                font-size: 1em;
            }
            
            .cta-button {
                padding: 15px 40px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Hero Section -->
        <div class="hero">
            <h1>📊 Activity Dashboard</h1>
            <p>Professional analytics and employee activity tracking with real-time insights</p>
            <a href="https://arturoamagar.github.io/officetimesheet/activity_dashboard%20(1).html" class="cta-button">🚀 Go to Dashboard</a>
        </div>
        
        <!-- Features Grid -->
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">📈</div>
                <div class="feature-title">Interactive Charts</div>
                <div class="feature-text">Beautiful visualizations with Bar and Line charts for comprehensive data analysis</div>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">🔍</div>
                <div class="feature-title">Advanced Filtering</div>
                <div class="feature-text">Filter by user, date, and work hours for precise data exploration</div>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">⚡</div>
                <div class="feature-title">Real-time Updates</div>
                <div class="feature-text">Upload CSV files and see your data instantly without any delays</div>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">🎨</div>
                <div class="feature-title">Modern Design</div>
                <div class="feature-text">Power BI and Tableau-style interface with responsive layout</div>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">📱</div>
                <div class="feature-title">Responsive</div>
                <div class="feature-text">Works seamlessly on desktop, tablet, and mobile devices</div>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">⚙️</div>
                <div class="feature-title">No Setup Required</div>
                <div class="feature-text">Pure HTML, CSS, and JavaScript - runs in any modern browser</div>
            </div>
        </div>
        
        <!-- Getting Started -->
        <div class="info-section">
            <h2>🚀 Getting Started</h2>
            
            <h3>Quick Start (30 seconds)</h3>
            <ol class="step-list">
                <li><strong>Click the button above</strong> "Go to Dashboard" to open the activity dashboard</li>
                <li><strong>Load Sample Data</strong> - The dashboard comes pre-loaded with example data</li>
                <li><strong>Upload Your CSV</strong> - Click "Load CSV File" to import your own activity data</li>
                <li><strong>Explore & Analyze</strong> - Use filters and charts to analyze employee activity</li>
            </ol>
            
            <h3>Required CSV Format</h3>
            <p>Your CSV file must include these columns:</p>
            <div class="code-block">
User,Login Time,Logout Time,Work Time
adrian,2025-10-20 08:09:00,2025-10-20 17:02:00,08:53
ajimenez,2025-10-20 08:38:00,2025-10-20 16:56:00,08:16
            </div>
            
            <h3>Column Descriptions</h3>
            <ul class="step-list">
                <li><strong>User</strong> - Employee name or ID</li>
                <li><strong>Login Time</strong> - Timestamp format: YYYY-MM-DD HH:MM:SS</li>
                <li><strong>Logout Time</strong> - Timestamp format: YYYY-MM-DD HH:MM:SS (or "-" if incomplete)</li>
                <li><strong>Work Time</strong> - Duration format: HH:MM</li>
            </ul>
        </div>
        
        <!-- Features Explained -->
        <div class="info-section">
            <h2>✨ Features Explained</h2>
            
            <h3>📊 Summary Statistics</h3>
            <p>Get instant insights with key metrics displayed at the top:</p>
            <ul class="step-list">
                <li>Total Users - Count of unique employees</li>
                <li>Records - Total activity records in your data</li>
                <li>Average Work Time - Mean working hours per record</li>
                <li>Total Work Hours - Sum of all work hours</li>
            </ul>
            
            <h3>📈 Interactive Charts</h3>
            <p>Visual representations of your data with two main charts:</p>
            <ul class="step-list">
                <li><strong>Work Time by User</strong> - Bar chart showing total hours per employee</li>
                <li><strong>Work Time by Date</strong> - Line chart displaying daily activity trends</li>
            </ul>
            
            <h3>🔍 Smart Filtering</h3>
            <p>Combine multiple filters for precise data analysis:</p>
            <ul class="step-list">
                <li>Filter by specific user</li>
                <li>Filter by specific date (MM/DD/YYYY format)</li>
                <li>Filter by minimum work hours</li>
                <li>Mix and match filters for custom views</li>
            </ul>
            
            <h3>📋 Detailed Records</h3>
            <p>Modern card-based view of individual activity records with:</p>
            <ul class="step-list">
                <li>Employee name and date</li>
                <li>Login and logout times</li>
                <li>Work hours in decimal format</li>
                <li>Real-time filter results</li>
            </ul>
        </div>
        
        <!-- Troubleshooting -->
        <div class="info-section">
            <h2>🔧 Troubleshooting</h2>
            
            <h3>Dashboard won't load from GitHub</h3>
            <p><strong>Solution:</strong> Make sure to enable GitHub Pages in your repository settings:</p>
            <ol class="step-list">
                <li>Go to Settings → Pages</li>
                <li>Select "Deploy from a branch"</li>
                <li>Choose "main" branch</li>
                <li>Access your dashboard at: <code>https://yourusername.github.io/repo-name/dashboard.html</code></li>
            </ol>
            
            <h3>CSV file won't upload</h3>
            <p><strong>Solution:</strong> Verify your CSV has the correct format with all required columns and proper date/time formatting.</p>
            
            <h3>Dates appear wrong</h3>
            <p><strong>Solution:</strong> Ensure dates in your CSV are in YYYY-MM-DD format exactly as specified.</p>
        </div>
        
        <!-- Footer -->
        <div class="footer">
            <p>📊 Activity Dashboard v1.0 | Made with ❤️ for data analytics</p>
            <p style="margin-top: 10px; font-size: 0.9em;">All in one file • No backend • Free to use</p>
        </div>
    </div>
</body>
</html>
