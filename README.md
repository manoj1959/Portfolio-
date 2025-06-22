<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Manoj Kumar Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #333;
    }
    nav {
      display: flex;
      justify-content: space-between;
      padding: 20px 10%;
      background: #f8f8f8;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    nav ul li a, .btn {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .btn {
      background: #ff5b77;
      color: white;
      padding: 10px 15px;
      border-radius: 6px;
    }
    .hero {
      display: flex;
      align-items: center;
      padding: 50px 10%;
      flex-wrap: wrap;
    }
    .left {
      flex: 1;
      min-width: 300px;
    }
    .right {
      flex: 1;
      min-width: 300px;
      text-align: center;
    }
    .profile-pic {
      border-radius: 50%;
      width: 250px;
    }
    .badge {
      margin-top: 15px;
      font-weight: bold;
      color: #ff5b77;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class="logo">ManuPortfolio</div>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Skills</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <a href="#" class="btn">Hire Me</a>
    </nav>
  </header>

  <section class="hero">
    <div class="left">
      <p class="tag">Pharma Professional</p>
      <h1>Hi! I Am <span>Manoj Kumar</span></h1>
      <p class="desc">
        Capsule Filling Specialist | Best Operator Award Winner
      </p>
      <div class="buttons">
        <a href="#" class="btn">Let's Talk</a>
        <a href="#" class="btn-outline">Portfolio</a>
      </div>
    </div>
    <div class="right">
      <img src="https://i.imgur.com/s8rl4zT.png" alt="Manoj Kumar Photo" class="profile-pic" />
      <div class="badge">🏆 Best Operator Award</div>
    </div>
  </section>
</body>
</html>
