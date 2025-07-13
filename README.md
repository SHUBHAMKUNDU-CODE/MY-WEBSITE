# MY WEBSITE
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My First Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 1em 0;
      text-align: center;
    }
    nav {
      background: #444;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      padding: 2em;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      font-size: 1em;
      background: #007BFF;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <div class="container">
    <h2>Hello, Visitor!</h2>
    <p>This is a simple website built with HTML, CSS, and JavaScript.</p>
    <button onclick="showMessage()">Click Me!</button>
  </div>

  <script>
    function showMessage() {
      alert("Thanks for clicking the button!");
    }
  </script>

</body>
</html>

