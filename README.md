<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<style>
    @page {
        size: A4;
        margin: 20mm;
        background-color: #ffffff;
    }
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        color: #333;
        margin: 0;
        padding: 0;
    }
    .header {
        background-color: #2c3e50;
        color: white;
        padding: 30px;
        text-align: center;
        border-bottom: 5px solid #f39c12;
    }
    .header h1 {
        margin: 0;
        font-size: 24pt;
    }
    .header p {
        margin: 10px 0 0;
        font-size: 14pt;
        opacity: 0.9;
    }
    .section {
        margin: 20px 0;
        padding: 15px;
    }
    h2 {
        color: #2c3e50;
        border-left: 5px solid #f39c12;
        padding-left: 10px;
        font-size: 18pt;
        margin-bottom: 15px;
    }
    h3 {
        color: #e67e22;
        font-size: 14pt;
        margin-top: 20px;
    }
    ul {
        padding-left: 20px;
    }
    li {
        margin-bottom: 8px;
    }
    .grid {
        display: block;
        width: 100%;
    }
    .footer {
        text-align: center;
        font-size: 9pt;
        color: #7f8c8d;
        border-top: 1px solid #eee;
        margin-top: 30px;
        padding-top: 10px;
    }
    .highlight-box {
        background-color: #f9f9f9;
        border: 1px solid #ddd;
        padding: 15px;
        border-radius: 5px;
    }
</style>
</head>
<body>
    <div class="header">
        <h1>📞 Call Center Analysis Dashboard</h1>
        <p>Strategic Insights through Data Visualization</p>
    </div>

    <div class="section">
        <h2>📊 Project Overview</h2>
        <p>This project features a comprehensive Power BI dashboard designed to monitor and analyze call center operations. It provides actionable insights into key performance indicators (KPIs) such as service levels, agent performance, and customer satisfaction metrics to drive operational efficiency. [cite: 1, 3]</p>
    </div>

    <div class="section">
        <h2>🛠️ Dashboard Architecture</h2>
        <div class="highlight-box">
            <h3>Executive Summary</h3>
            <ul>
                <li>Provides a high-level view of total calls and answer rates. [cite: 1, 3]</li>
                <li>Tracks abandoned call percentages to identify service gaps. [cite: 1, 3]</li>
            </ul>

            <h3>Agent Analytics</h3>
            <ul>
                <li>Offers a detailed breakdown of individual agent metrics. [cite: 1, 3]</li>
                <li>Monitors efficiency through Average Handle Time (AHT) and resolution rates. [cite: 1, 3]</li>
            </ul>

            <h3>Trend Analysis</h3>
            <ul>
                <li>Visualizes call volume patterns by hour and day. [cite: 1, 3]</li>
                <li>Assists in workforce scheduling by identifying peak arrival times. [cite: 1, 3]</li>
            </ul>

            <h3>Customer Experience</h3>
            <ul>
                <li>Analyzes post-call survey data to gauge service quality. [cite: 1, 3]</li>
                <li>Tracks satisfaction scores (CSAT) to improve customer retention. [cite: 1, 3]</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <h2>⚙️ Technical Implementation</h2>
        <h3>Data Modeling & Security</h3>
        <ul>
            <li>Built on a robust <strong>DataModel</strong> designed for high-performance querying. [cite: 4, 21]</li>
            <li>Implements specific <strong>SecurityBindings</strong> to manage data access and integrity. [cite: 4]</li>
            <li>Utilizes an organized <strong>DiagramLayout</strong> to manage complex table relationships. [cite: 1, 27]</li>
        </ul>

        <h3>Visual Design & Branding</h3>
        <ul>
            <li>Employs the professional <strong>Solar</strong> built-in theme for a high-contrast, accessible interface. [cite: 3]</li>
            <li>Integrated custom branding assets, specifically the <strong>PwC logo</strong>. [cite: 3]</li>
            <li>Utilizes the <strong>CY23SU11</strong> base theme to ensure modern UI standards. [cite: 3]</li>
        </ul>

        <h3>Data Transformation & Package Structure</h3>
        <ul>
            <li>Leverages Power Query to clean and reshape metadata and connection settings. [cite: 1, 3]</li>
            <li>Manages various static resources and registered assets to maintain a consistent report layout. [cite: 3]</li>
            <li>Structured with internal components including Content_Types, Settings, and Versioning for stable deployment. [cite: 1, 27]</li>
        </ul>
    </div>

    <div class="section">
        <h2>📈 Insights & Impact</h2>
        <ul>
            <li><strong>Optimized Staffing:</strong> Identified peak call hours to allow for better workforce alignment and scheduling. [cite: 1, 3]</li>
            <li><strong>Reduced Wait Times:</strong> Highlighted high abandonment rates during specific shifts to target coaching. [cite: 1, 3]</li>
            <li><strong>Automated Reporting:</strong> Replaced manual tracking with a real-time, automated data solution using defined connection strings. [cite: 27]</li>
        </ul>
    </div>

    <div class="section">
        <h2>📂 Repository Structure</h2>
        <ul>
            <li><strong>Call Center Analysis Dashboard.pbix:</strong> The primary Power BI file containing the data model, transformations, and visual reports. [cite: 1]</li>
            <li><strong>Static Resources:</strong> Includes organizational logos (PwC) and custom theme JSON files (Solar) used for the dashboard's visual identity. [cite: 3]</li>
            <li><strong>Metadata & Settings:</strong> Configuration files that define report versions and data connection properties. [cite: 3, 27]</li>
        </ul>
    </div>

    <div class="footer">
        Portfolio Project Documentation | Call Center Analysis
    </div>
</body>
</html>
