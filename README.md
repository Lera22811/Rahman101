# 𝒰𝒳 𝓈𝒶𝓃𝒯
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #333;
      color: #fff;
      padding: 15px;
      text-align: center;
    }
    nav {
      background: #444;
      padding: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
    }
    main {
      padding: 20px;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    button {
      padding: 10px 15px;
      background: #008cba;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background: #005f73;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Simple Website</h1>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
  <main>
    <h2>Hello!</h2>
    <p>This is a simple website example with HTML, CSS, and JavaScript.</p>
    <button onclick="showMessage()">Click Me</button>
    <p id="message"></p>
  </main>
  <footer>
    <p>&copy; 2026 My Website</p>
  </footer>

  <script>
    function showMessage() {
      document.getElementById("message").innerText = "You clicked the button!";
    }
  </script>
</body>
</html>

