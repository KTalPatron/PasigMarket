<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pasig Public Market Registration</title>
  <body background = "Pasig-bg.png"></body>
  <style>
    * {
      box-sizing: border-box;
    }
    
    
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      background-color: #7592ea;
      font-family: Arial, sans-serif;
      padding: 20px;
    }

    .logo {
      margin-bottom: 1px;
    }

    .logo img {
      width: 500px;
      height: auto;
    }

    .rectangle {
      width: 100%;
      max-width: 360px;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      text-align: center;
      margin: 15px;
    }

    .rectangle h2 {
      margin-bottom: 16px;
      font-size: 1.25rem;
    }

    input[type="password"] {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 16px;
    }

    input[type="text"] {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 16px;
    }

    button {
      width: 100%;
      padding: 12px;
      background-color: #2b16a3;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background-color: #282485;
    }

    
  </style>
</head>

  <div class="logo">
    <img src= "Pasig-logo.png" alt="Logo">
  </div>

  <div class="rectangle">
    <h2>Sign in</h2>
    <input type="text" placeholder="Your name" />
    <input type="password" placeholder="Password" />
    <form action="sign in.html" method="get">
        <button type="submit">Submit</button>
    </form>
  </div>

  <p> Don't have an account yet? <a href = "register.html">Register Now</a></p>
 



</body>
</html>
