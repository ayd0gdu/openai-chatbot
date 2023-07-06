Selam millet openai api kullanarak oluşturmuş olduğum chat-botunu paylaşıyorum.. <br>
Dip not: Ancak openai 'den ücret karşılğı api key almak zorundasınız yoksa bot çalışmaz!!!..

index.html>>>>>>>>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot in JavaScript | Aydogdu</title>
    <link rel="stylesheet" href="chatbot.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
    <script src="chatbot.js" defer></script>
</head>
<body>
    <button class="chatbot-toggler">
        <span class="material-symbols-outlined">mode_comment</span>
        <span class="material-symbols-outlined">close</span>
    </button>
    <div class="chatbot">
        <header>
            <h2>Chatbot</h2>
            <span class="close-btn material-symbols-outlined">close</span>
        </header>
        <ul class="chatbox">
            <li class="chat incoming">
                <span class="material-symbols-outlined">smart_toy</span>
                <p>Merhaba 👋 <br> Bugün sana nasıl yardımcı olabilirim?</p>
            </li>
        </ul>
        <div class="chat-input">
            <textarea placeholder="Mesajını gir..." required></textarea>
            <span id="send-btn" class="material-symbols-outlined">Send</span>
        </div>
    </div>
</body>
</html>
