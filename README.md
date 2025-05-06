# chatbot
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RVR & JC College of Engineering</title>
  <link rel="stylesheet" href="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/themes/df-messenger-default.css">
  <script src="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/df-messenger.js"></script>
  <style>
    df-messenger {
      z-index: 999;
      position: fixed;
      --df-messenger-font-color: #000;
      --df-messenger-font-family: Google Sans;
      --df-messenger-chat-background: #f3f6fc;
      --df-messenger-messag1e-user-background: #d3e3fd;
      --df-messenger-message-bot-background: #fff;
      bottom: 16px;
      right: 16px;
    }

    /* Set the background image for the header */
    .header {
      background-image: url('https://rvrjcce.ac.in/ximage/RVR.jpg'); /* Replace this with your image URL */
      background-size: cover;  /* Ensures the image covers the entire element */
      background-position: center; /* Centers the image */
      height: 400px; /* Adjust this height as needed */
      text-align: center;
      color: white;
      padding: 20px;
    }

    h1 {
      color: white;
    }

    /* Styling for the footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      position: relative;
      bottom: 0;
      width: 100%;
      font-size: 14px;
      margin-top: 20px;  /* Adds some space between content and footer */
    }

    footer h1 {
      color: white;
    }
  </style>
</head>
<body>

  <!-- Existing website content -->
  <div class="header">
    <h1></h1>
  </div>

  <!-- Chatbot Integration -->
  <df-messenger
    project-id="proud-outpost-392806"
    agent-id="f17e48bf-1b9f-4258-b150-79ed9e78c73a"
    language-code="en"
    max-query-length="-1"
    allow-feedback="all">
    <df-messenger-chat-bubble
      chat-title="RVRJC_CHATBOT">
    </df-messenger-chat-bubble>
  </df-messenger>

  <!-- Footer Section -->
  <footer>
    <h1>Welcome to RVR & JC College of Engineering</h1>
  </footer>

</body>
</html>
