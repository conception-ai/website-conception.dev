---
layout: none
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conception.dev - Coming Soon</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'SF Mono', Monaco, 'Cascadia Code', 'Roboto Mono', Consolas, 'Courier New', monospace;
            background: #0d1117;
            color: #c9d1d9;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            line-height: 1.6;
        }

        .container {
            max-width: 600px;
            padding: 2rem;
            text-align: center;
        }

        .logo {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1rem;
            margin-bottom: 3rem;
        }

        .logo-symbol {
            width: 48px;
            height: 48px;
            background: #fff;
            color: #000;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: 600;
        }

        .logo-text {
            font-size: 2.5rem;
            font-weight: 300;
            letter-spacing: -0.02em;
        }

        .tagline {
            font-size: 1.5rem;
            color: #fff;
            margin-bottom: 2rem;
            font-weight: 400;
        }

        .description {
            font-size: 1rem;
            color: #8b949e;
            margin-bottom: 3rem;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }

        .status {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.75rem 1.5rem;
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.15);
            border-radius: 8px;
            font-size: 0.9rem;
            color: #c9d1d9;
            margin-bottom: 3rem;
        }

        .dot {
            width: 8px;
            height: 8px;
            background: #58a6ff;
            border-radius: 50%;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        .buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            text-decoration: none;
            font-size: 0.9rem;
            font-weight: 500;
            transition: all 0.2s;
            display: inline-block;
        }

        .btn-primary {
            background: #238636;
            color: #fff;
        }

        .btn-primary:hover {
            background: #2ea043;
            transform: translateY(-1px);
        }

        .btn-secondary {
            background: transparent;
            color: #58a6ff;
            border: 1px solid #58a6ff;
        }

        .btn-secondary:hover {
            background: rgba(88, 166, 255, 0.1);
            transform: translateY(-1px);
        }

        .contact {
            font-size: 0.9rem;
            color: #666;
        }

        .contact a {
            color: #fff;
            text-decoration: none;
            border-bottom: 1px solid rgba(255, 255, 255, 0.3);
            transition: border-color 0.2s;
        }

        .contact a:hover {
            border-color: #fff;
        }

        @media (max-width: 640px) {
            .container {
                padding: 1rem;
            }
            
            .logo {
                font-size: 2rem;
                margin-bottom: 2rem;
            }
            
            .logo-text {
                font-size: 2rem;
            }
            
            .buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 200px;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <div class="logo-symbol">C</div>
            <div class="logo-text">Conception.dev</div>
        </div>
        
        <div class="tagline">
            The missing piece between AI hype and shipping code
        </div>
        
        <div class="description">
            AI coding feels like magic until you try to build something real. We bridge that gap with the interface that makes them actually usable - from drafting crystal clear specs to development with AI agents.
        </div>
        
        <div class="status">
            <div class="dot"></div>
            Site under construction
        </div>
        
        <div class="buttons">
        </div>
    </div>
</body>
</html>
