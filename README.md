# fairy1
i never forget
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat Interface</title>
    <style>
        /* CSS styles for the chat interface */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .chat-container {
            width: 400px;
            margin: 50px auto;
            border: 1px solid #ccc;
            border-radius: 5px;
            overflow: hidden;
        }
        .chat-messages {
            padding: 10px;
            height: 300px;
            overflow-y: scroll;
        }
        .message {
            margin-bottom: 10px;
        }
        .message .user {
            font-weight: bold;
        }
        .message .text {
            margin-left: 10px;
        }
        .chat-input {
            display: flex;
        }
        .chat-input input[type="text"] {
            flex: 1;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px 0 0 5px;
        }
        .chat-input button {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 0 5px 5px 0;
            background-color: #007bff;
            color: #fff;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="chat-container">
        <div class="chat-messages" id="chat-messages">
            <!-- Chat messages will be displayed here -->
        </div>
        <div class="chat-input">
            <input type="text" id="message-input" placeholder="Type your message...">
            <button onclick="sendMessage()">Send</button>
        </div>
67890
4590
