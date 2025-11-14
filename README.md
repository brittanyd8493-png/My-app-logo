<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My App</title>
  <style>
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #fce4ec, #f3e5f5);
      font-family: 'Arial', sans-serif;
      text-align: center;
      overflow: hidden;
    }
    h1 {
      margin-top: 20px;
      color: #6a1b9a;
      font-size: 2em;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.2);
    }
    img {
      max-width: 250px;
      width: 50%;
      height: auto;
      animation: float 3s ease-in-out infinite;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      border-radius: 20px;
    }
    p {
      color: #555;
      max-width: 400px;
      margin-top: 10px;
      font-size: 1.1em;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }
  </style>
</head>
<body>
  <!-- Replace 'logo.png' with your logo file -->
  <img src="logo.png" alt="My Logo">
  <h1>Welcome to My App</h1>
  <p>Check out my shiny new logo! Floaty, glossy, and impossible to ignore.</p>
</body>
</html>
