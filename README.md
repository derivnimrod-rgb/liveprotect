<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CyberGuard | Incident Response & Digital Security</title>
    <style>
        :root {
            --bg-color: #0a0f1d;
            --text-color: #e2e8f0;
            --accent-color: #00ff66; /* Secure Green */
            --alert-color: #ff3333;  /* Emergency Red */
            --card-bg: #141f36;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background-color: rgba(20, 31, 54, 0.8);
            backdrop-filter: blur(10px);
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            border-bottom: 1px solid #1e293b;
        }

        .logo {
            font-weight: bold;
            font-size: 24px;
            color: var(--accent-color);
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: radial-gradient(circle at center, #1e293b 0%, #0a0f1d 70%);
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            color: #94a3b8;
            max-width: 600px;
            margin: 0 auto 30px auto;
        }

        .btn-emergency {
            background-color: var(--alert-color);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 0 15px rgba(255, 51, 51, 0.4);
        }

        .services {
            padding: 60px 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .services h2 {
            text-align: center;
            margin-bottom: 40px;
            color: var(--accent-color);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 30px;
            border-radius: 8px;
            border: 1px solid #1e293b;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-color);
        }

        .card h3 {
            margin-top: 0;
            color: white;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            background-color: #070a14;
            color: #64748b;
            border-top: 1px solid #1e293b;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">[ CYBERGUARD ]</div>
    </header>

    <section class="hero">
        <h1>Under Cyber Attack?</h1>
        <p>We provide immediate containment, forensic remediation, account recovery, and robust defense systems to secure your digital footprint.</p>
        <a href="#contact" class="btn-emergency">Report an Incident Now</a>
    </section>

    <section class="services">
        <h2>Technical Assistance & Cyber Defense</h2>
        <div class="grid">
            <div class="card">
                <h3>1. Emergency Incident Response</h3>
                <p>Fast containment for actively hacked servers, websites, or personal networks. We trace the threat actor and stop the breach in its tracks.</p>
            </div>
            <div class="card">
                <h3>2. Account Recovery & Hardening</h3>
                <p>Securing compromised email architecture, cloud networks, and administrative accounts. Implementation of flawless multi-factor structures.</p>
            </div>
            <div class="card">
                <h3>3. Vulnerability Auditing</h3>
                <p>Proactive mapping, network scanning, and systems patch-testing to ensure your business assets are fortified against future exploits.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 CyberGuard Services. Securing networks globally.</p>
    </footer>

</body>
</html>

