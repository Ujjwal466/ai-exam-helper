<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Exam Helper</title>
</head>
<body style="font-family: Arial; text-align:center; padding:20px;">
  <h1>📘 AI Exam Helper</h1>
  <p>Ask me anything about your exams!</p>

  <!-- Simple chatbot box (AI will be added later) -->
  <textarea id="question" placeholder="Type your question here..." rows="3" cols="40"></textarea><br><br>
  <button onclick="answer()">Ask</button>
  
  <h3>Answer:</h3>
  <div id="response" style="border:1px solid #ccc; padding:10px; width:300px; margin:auto;"></div>

  <script>
    function answer() {
      let q = document.getElementById("question").value;
      document.getElementById("response").innerText = "Thanks for asking: " + q + ". (AI coming soon...)";
    }
  </script>

  <hr>
  <p><a href="about.html">About Us</a> | <a href="contact.html">Contact</a> | <a href="privacy.html">Privacy Policy</a></p>
</body>
</html>
