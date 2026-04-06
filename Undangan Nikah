<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Invitation - Huo Yuhao & Tang Wutong</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .invitation-container {
            background: linear-gradient(to bottom, #fff8f3, #fffaf5);
            max-width: 700px;
            width: 100%;
            border-radius: 15px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
            animation: slideIn 0.8s ease-out;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .header {
            background: linear-gradient(135deg, #e84393 0%, #c2185b 50%, #d946ef 100%);
            padding: 60px 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 1px, transparent 1px);
            background-size: 50px 50px;
            animation: moveBackground 20s linear infinite;
        }

        @keyframes moveBackground {
            0% { transform: translate(0, 0); }
            100% { transform: translate(50px, 50px); }
        }

        .header-content {
            position: relative;
            z-index: 1;
            color: white;
        }

        .decorative-top {
            font-size: 40px;
            margin-bottom: 20px;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .header h1 {
            font-size: 28px;
            font-weight: 300;
            letter-spacing: 2px;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .header p {
            font-size: 16px;
            letter-spacing: 1px;
            margin-top: 10px;
            opacity: 0.95;
        }

        .couple-names {
            font-size: 42px;
            font-weight: bold;
            margin: 30px 0;
            color: #fff;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.2);
        }

        .ampersand {
            font-size: 48px;
            color: #ffd700;
            margin: 0 10px;
            display: inline-block;
        }

        .body-content {
            padding: 50px 40px;
            text-align: center;
        }

        .intro-text {
            font-size: 18px;
            color: #333;
            margin-bottom: 40px;
            line-height: 1.8;
            font-style: italic;
        }

        .accent-line {
            width: 60px;
            height: 3px;
            background: linear-gradient(to right, #e84393, #d946ef);
            margin: 0 auto 30px;
            border-radius: 2px;
        }

        .details-section {
            background: linear-gradient(135deg, #f5f7fa 0%, #eef2f7 100%);
            padding: 40px;
            border-radius: 10px;
            margin: 30px 0;
            border-left: 5px solid #e84393;
        }

        .detail-item {
            margin: 25px 0;
            position: relative;
        }

        .detail-label {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #c2185b;
            font-weight: bold;
            margin-bottom: 8px;
        }

        .detail-value {
            font-size: 20px;
            color: #333;
            font-weight: 500;
        }

        .location-details {
            background: linear-gradient(135deg, #fff5e1 0%, #ffe0b2 100%);
            padding: 30px;
            border-radius: 10px;
            margin: 30px 0;
            border-right: 5px solid #ff9800;
        }

        .location-details .detail-label {
            color: #e65100;
        }

        .special-message {
            margin-top: 40px;
            padding: 30px;
            background: linear-gradient(135deg, #e1f5fe 0%, #b3e5fc 100%);
            border-radius: 10px;
            border-top: 4px dashed #0277bd;
            font-size: 16px;
            color: #01579b;
            line-height: 1.8;
            font-style: italic;
        }

        .honor-section {
            margin: 30px 0;
            padding: 25px;
            background: linear-gradient(135deg, #f3e5f5 0%, #e1bee7 100%);
            border-radius: 8px;
            font-size: 15px;
            color: #4a148c;
            line-height: 1.8;
        }

        .footer {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            padding: 40px;
            text-align: center;
            color: white;
        }

        .footer-text {
            font-size: 16px;
            margin: 15px 0;
            line-height: 1.8;
        }

        .blessings {
            font-size: 20px;
            margin: 20px 0;
            font-style: italic;
            color: #ffd700;
        }

        .footer-decoration {
            font-size: 30px;
            margin: 20px 0;
        }

        .response-note {
            margin-top: 30px;
            padding: 20px;
            background: rgba(255,255,255,0.1);
            border-radius: 8px;
            font-size: 14px;
            line-height: 1.7;
        }

        .flower-divider {
            text-align: center;
            font-size: 24px;
            color: #e84393;
            margin: 30px 0;
            letter-spacing: 10px;
        }

        @media (max-width: 600px) {
            .header {
                padding: 40px 20px;
            }

            .couple-names {
                font-size: 32px;
            }

            .body-content {
                padding: 30px 20px;
            }

            .details-section {
                padding: 25px;
            }
        }
    </style>
</head>
<body>
    <div class="invitation-container">
        <div class="header">
            <div class="header-content">
                <div class="decorative-top">💕 ✨ 💕</div>
                <h1>Together Forever</h1>
                <p>Join us in Celebrating</p>
                <div class="couple-names">
                    Huo Yuhao
                    <span class="ampersand">&</span>
                    Tang Wutong
                </div>
            </div>
        </div>

        <div class="body-content">
            <p class="intro-text">
                With gratitude and joy, we invite you to share in this sacred moment as two hearts unite as one.
            </p>

            <div class="flower-divider">🌸 ❤️ 🌸</div>

            <div class="details-section">
                <div class="detail-item">
                    <div class="detail-label">📅 Date</div>
                    <div class="detail-value">Saturday, April 12th, 2026</div>
                </div>

                <div class="detail-item">
                    <div class="detail-label">🕖 Time</div>
                    <div class="detail-value">6:00 PM</div>
                </div>

                <div class="detail-item">
                    <div class="detail-label">📍 Location</div>
                    <div class="detail-value">Kebumen Village</div>
                    <div class="detail-value" style="font-size: 16px; margin-top: 8px; opacity: 0.85;">
                        Kebumen, Central Java, Indonesia
                    </div>
                </div>
            </div>

            <div class="accent-line"></div>

            <div class="location-details">
                <div class="detail-label">📌 Venue Information</div>
                <div class="detail-value" style="margin-top: 15px; font-size: 18px;">
                    Kebumen Community Hall & Gardens
                </div>
                <div style="margin-top: 15px; font-size: 14px; color: #e65100;">
                    Reception to follow the ceremony with celebrations and traditional feasting
                </div>
            </div>

            <div class="honor-section">
                <strong>We request the honor of your presence</strong> at the marriage of our beloved couple as they embark on their beautiful journey together. Your presence and blessings would mean the world to us.
            </div>

            <div class="special-message">
                "Two souls with but a single thought,<br>
                two hearts that beat as one."<br>
                <br>
                Together we celebrate their eternal love
            </div>

            <div class="flower-divider">✨ 💎 ✨</div>
        </div>

        <div class="footer">
            <div class="footer-decoration">💒 ✨ 💒</div>
            
            <div class="footer-text">
                With Love & Gratitude
            </div>

            <div class="blessings">
                Huo Yuhao & Tang Wutong
            </div>

            <div class="response-note">
                <strong>RSVP Requested by:</strong> April 5th, 2026<br>
                Please confirm your attendance by contacting us at your earliest convenience.<br>
                <br>
                <strong>Contact:</strong> +62 8XX XXXX XXXX<br>
                <strong>Email:</strong> huoyuhao.tangwutong@wedding.com
            </div>

            <div style="margin-top: 30px; font-size: 28px;">
                💕 🙏 💕
            </div>
        </div>
    </div>
</body>
</html>
