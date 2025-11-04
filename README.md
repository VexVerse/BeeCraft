<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vexa Stream</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: #0d3c36;
            margin: 0;
            padding: 0;
            color: #fff;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .header {
            font-size: 3rem;
            color: #94f8eb;
            margin-bottom: 1rem;
        }
        .stream-area {
            display: flex;
            justify-content: space-between;
            width: 80%;
            margin: 20px 0;
        }
        .chat-box {
            background: rgba(0, 0, 0, 0.7);
            width: 60%;
            height: 400px;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0px 0px 15px rgba(0, 255, 255, 0.5);
        }
        .stream-window {
            background: #1f3b34;
            width: 35%;
            height: 400px;
            border-radius: 10px;
            border: 5px solid #94f8eb;
            box-shadow: 0px 0px 15px rgba(0, 255, 255, 0.5);
        }
        .footer {
            display: flex;
            justify-content: space-between;
            width: 80%;
            margin-top: 20px;
        }
        .donate, .info-box {
            background: #2e5a53;
            padding: 10px;
            border-radius: 10px;
            width: 45%;
            box-shadow: 0px 0px 10px rgba(0, 255, 255, 0.4);
        }
        .rules, .emotes {
            display: flex;
            flex-wrap: wrap;
            margin-top: 10px;
        }
        .rules div, .emotes div {
            margin-right: 10px;
            margin-top: 5px;
            background: #2e5a53;
            padding: 8px;
            border-radius: 5px;
        }
        .personality {
            display: flex;
            flex-direction: column;
            margin-top: 20px;
        }
        .personality span {
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">Vexa's Stream</div>
        <div class="stream-area">
            <div class="chat-box">
                <h3>CHAT</h3>
                <!-- Chat messages will appear here -->
            </div>
            <div class="stream-window">
                <h3>Stream Window</h3>
                <!-- Stream video will be displayed here -->
            </div>
        </div>
        <div class="footer">
            <div class="donate">
                <h3>Donate</h3>
                <p>Support the stream!</p>
            </div>
            <div class="info-box">
                <h3>Info Box</h3>
                <p>Welcome to Vexa's Stream!</p>
            </div>
        </div>
        <div class="rules">
            <div>English Only</div>
            <div>No Spamming</div>
            <div>Be Kind</div>
        </div>
        <div class="emotes">
            <div>Emote 1</div>
            <div>Emote 2</div>
            <div>Emote 3</div>
        </div>
        <div class="personality">
            <span>Energy: High</span>
            <span>Drama: Moderate</span>
            <span>Creative: High</span>
            <span>Friendly: Very Friendly</span>
        </div>
    </div>
</body>
</html>
