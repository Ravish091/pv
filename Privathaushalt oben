<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photovoltaik für Ihr Zuhause - Eine lohnenswerte Investition</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #2c3e50;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        .hero-section {
            text-align: center;
            margin-bottom: 80px;
            background: white;
            padding: 60px 40px;
            border-radius: 20px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }

        .hero-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: linear-gradient(90deg, #3498db, #2ecc71, #f39c12);
        }

        .hero-title {
            font-size: 2.8rem;
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 30px;
            line-height: 1.2;
        }

        .hero-subtitle {
            font-size: 1.2rem;
            color: #5a6c7d;
            max-width: 900px;
            margin: 0 auto;
            line-height: 1.8;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
            margin-bottom: 80px;
        }

        .benefit-card {
            background: white;
            padding: 40px 30px;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
            transition: all 0.3s ease;
            border-left: 5px solid transparent;
            position: relative;
        }

        .benefit-card:nth-child(1) {
            border-left-color: #3498db;
        }

        .benefit-card:nth-child(2) {
            border-left-color: #2ecc71;
        }

        .benefit-card:nth-child(3) {
            border-left-color: #f39c12;
        }

        .benefit-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.12);
        }

        .benefit-icon {
            width: 60px;
            height: 60px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            margin-bottom: 25px;
            color: white;
        }

        .benefit-card:nth-child(1) .benefit-icon {
            background: linear-gradient(135deg, #3498db, #2980b9);
        }

        .benefit-card:nth-child(2) .benefit-icon {
            background: linear-gradient(135deg, #2ecc71, #27ae60);
        }

        .benefit-card:nth-child(3) .benefit-icon {
            background: linear-gradient(135deg, #f39c12, #e67e22);
        }

        .benefit-title {
            font-size: 1.4rem;
            font-weight: 600;
            color: #2c3e50;
            margin-bottom: 20px;
            line-height: 1.3;
        }

        .benefit-description {
            color: #5a6c7d;
            line-height: 1.7;
            font-size: 1rem;
        }

        .cta-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 40px;
            margin-top: 60px;
        }

        .cta-card {
            background: white;
            padding: 50px 40px;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .cta-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #3498db, #2ecc71);
        }

        .cta-title {
            font-size: 1.3rem;
            font-weight: 600;
            color: #2c3e50;
            margin-bottom: 25px;
            line-height: 1.4;
        }

        .cta-button {
            display: inline-block;
            padding: 15px 35px;
            background: linear-gradient(135deg, #3498db, #2980b9);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(52, 152, 219, 0.4);
            background: linear-gradient(135deg, #2980b9, #3498db);
        }

        .cta-button.secondary {
            background: linear-gradient(135deg, #2ecc71, #27ae60);
            box-shadow: 0 4px 15px rgba(46, 204, 113, 0.3);
        }

        .cta-button.secondary:hover {
            background: linear-gradient(135deg, #27ae60, #2ecc71);
            box-shadow: 0 8px 25px rgba(46, 204, 113, 0.4);
        }

        .highlight-text {
            color: #3498db;
            font-weight: 600;
        }

        .stats-highlight {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 8px 16px;
            border-radius: 25px;
            display: inline-block;
            font-weight: 600;
            color: #2c3e50;
            margin: 0 5px;
            border: 2px solid #dee2e6;
        }

        @media (max-width: 768px) {
            .container {
                padding: 40px 15px;
            }

            .hero-section {
                padding: 40px 25px;
                margin-bottom: 50px;
            }

            .hero-title {
                font-size: 2.2rem;
            }

            .hero-subtitle {
                font-size: 1.1rem;
            }

            .benefits-grid {
                grid-template-columns: 1fr;
                gap: 25px;
                margin-bottom: 50px;
            }

            .benefit-card {
                padding: 30px 25px;
            }

            .cta-section {
                grid-template-columns: 1fr;
                gap: 25px;
            }

            .cta-card {
                padding: 35px 25px;
            }
        }

        .feature-highlight {
            background: linear-gradient(135deg, rgba(52, 152, 219, 0.1), rgba(46, 204, 113, 0.1));
            padding: 4px 12px;
            border-radius: 15px;
            font-weight: 600;
            color: #2c3e50;
            display: inline-block;
            margin: 2px;
        }

        .environmental-badge {
            display: inline-flex;
            align-items: center;
            background: linear-gradient(135deg, #2ecc71, #27ae60);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
            margin: 10px 5px;
        }

        .environmental-badge::before {
            content: "🌱";
            margin-right: 8px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hero-section">
            <h1 class="hero-title">Photovoltaik für Ihr Zuhause – Eine lohnenswerte Investition</h1>
            <p class="hero-subtitle">
                Mit einer Photovoltaikanlage senken Sie Ihre Stromkosten und machen sich unabhängig von steigenden Energiepreisen. Durch staatliche 
                <span class="highlight-text">Förderungen und Steuervorteile</span> wird die Anschaffung zusätzlich attraktiv. Ökologisch gesehen leisten Sie einen wichtigen Beitrag zum Klimaschutz, 
                indem Sie den <span class="environmental-badge">CO₂-Ausstoß reduzieren</span> und auf saubere Sonnenenergie setzen. Langfristig steigern Sie den Wert Ihrer Immobilie und profitieren von 
                einer nachhaltigen, grünen Energiequelle.
            </p>
        </div>

        <div class="benefits-grid">
            <div class="benefit-card">
                <div class="benefit-icon">⚡</div>
                <h3 class="benefit-title">Energieeinsparung & Unabhängigkeit</h3>
                <p class="benefit-description">
                    Mit einer hochwertigen Photovoltaikanlage senken Sie Ihre Stromkosten um bis zu <span class="stats-highlight">80%</span> und machen sich 
                    langfristig unabhängig von steigenden Energiepreisen – für <span class="feature-highlight">finanzielle Planungssicherheit</span> und 
                    <span class="feature-highlight">grünes Gewissen</span>.
                </p>
            </div>

            <div class="benefit-card">
                <div class="benefit-icon">🚀</div>
                <h3 class="benefit-title">Zukunftssichere Erweiterbarkeit</h3>
                <p class="benefit-description">
                    Starten Sie jetzt mit Ihrer Basis-PV-Anlage und erweitern Sie das System später mühelos um 
                    <span class="feature-highlight">Batteriespeicher</span> oder eine <span class="feature-highlight">Wallbox für Ihr E-Fahrzeug</span> – 
                    damit Ihre Eigenverbrauchsquote und Rendite weiter steigen.
                </p>
            </div>

            <div class="benefit-card">
                <div class="benefit-icon">📱</div>
                <h3 class="benefit-title">Smartes Monitoring</h3>
                <p class="benefit-description">
                    Behalten Sie Ertrag und Performance Ihrer Anlage jederzeit im <span class="highlight-text">Blick</span> – per 
                    <span class="feature-highlight">Smartphone-App</span>. So sichern Sie maximale Verfügbarkeit und 
                    <span class="feature-highlight">sorgfreie Stromproduktion</span>.
                </p>
            </div>
        </div>

        <div class="cta-section">
            <div class="cta-card">
                <h3 class="cta-title">
                    Berechnen Sie jetzt Ihre Energieersparnis und erfahren Sie, 
                    wie viel Sie mit einer Photovoltaikanlage auf Ihrem Dach 
                    sparen können!
                </h3>
                <a href="https://www.alabenergiesysteme.de/privatehaushalte" class="cta-button" target="_blank">Zum Solarrechner</a>
            </div>

            <div class="cta-card">
                <h3 class="cta-title">
                    Fordern Sie jetzt Ihre kostenlose 
                    Wirtschaftlichkeitsanalyse an und 
                    lassen Sie uns gemeinsam Ihre 
                    Energieversorgung optimieren!
                </h3>
                <a href="https://www.alabenergiesysteme.de/angebot-einholen" class="cta-button secondary" target="_blank">Angebot einholen</a>
            </div>
        </div>
    </div>
</body>
</html>
