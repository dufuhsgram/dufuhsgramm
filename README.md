/dufuhsgram
  ├── index.html
  ├── style.css
  └── script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dufuhsgram</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Dufuhsgram</h1>
    </header>

    <!-- Post Feed Section -->
    <section id="feed">
        <h2>Post Feed</h2>
        <div id="post-feed" class="repeater">
            <!-- Posts will be dynamically inserted here -->
        </div>
    </section>

    <!-- Chat Section -->
    <section id="chat">
        <h2>Chat</h2>
        <div id="chat-box" class="repeater">
            <!-- Chat messages will be dynamically inserted here -->
        </div>
        <input type="text" id="messageInput" placeholder="Type your message...">
        <button id="sendButton">Send</button>
    </section>

    <script src="script.js"></script>
</body>
</html>
