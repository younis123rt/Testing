<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Border Roleplay</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #181818;
      color: #ffffff;
    }

    /* Header */
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 20px;
      background-color: #222222;
      border-bottom: 1px solid #333;
    }

    header .logo {
      display: flex;
      align-items: center;
    }

    header .logo img {
      height: 40px;
      margin-right: 10px;
    }

    header .menu-icon {
      font-size: 24px;
      cursor: pointer;
    }

    /* Sidebar */
    .sidebar {
      width: 250px;
      height: 100vh;
      background-color: #141414;
      position: fixed;
      top: 0;
      left: 0;
      padding: 20px;
      overflow-y: auto;
      border-right: 1px solid #333;
    }

    .sidebar h2 {
      font-size: 18px;
      margin-bottom: 20px;
      color: #f39c12;
    }

    .sidebar ul {
      list-style-type: none;
      padding: 0;
    }

    .sidebar ul li {
      margin-bottom: 15px;
    }

    .sidebar ul li a {
      text-decoration: none;
      color: #ffffff;
      font-size: 16px;
      display: flex;
      align-items: center;
    }

    .sidebar ul li a:hover {
      color: #f39c12;
    }

    .sidebar ul li a i {
      margin-right: 10px;
    }

    /* Content Area */
    .content {
      margin-left: 270px;
      padding: 20px;
    }

    .content h1 {
      color: #f39c12;
      margin-bottom: 20px;
    }

    .content p {
      font-size: 16px;
      line-height: 1.6;
    }

    /* Footer */
    footer {
      background-color: #222222;
      color: #777;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }

    footer a {
      color: #f39c12;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <img src="https://via.placeholder.com/40" alt="Logo">
      <span>Border Roleplay</span>
    </div>
    <div class="menu-icon">☰</div>
  </header>

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>BORDER ROLEPLAY</h2>
    <ul>
      <li><a href="#"><i>🏠</i> Home</a></li>
      <li><a href="#"><i>ℹ️</i> About Us</a></li>
    </ul>
    <h2>IMPORTANT</h2>
    <ul>
      <li><a href="#"><i>📖</i> Regulations</a></li>
      <ul>
        <li><a href="#"><i>🎮</i> Discord Regulations</a></li>
        <li><a href="#"><i>🕹️</i> In-Game Regulations</a></li>
      </ul>
      <li><a href="#"><i>🛈</i> Information</a></li>
    </ul>
    <h2>ROLEPLAY</h2>
    <ul>
      <li><a href="#"><i>🛒</i> Store</a></li>
      <li><a href="#"><i>📁</i> Departments</a></li>
    </ul>
    <h2>MISC</h2>
    <ul>
      <li><a href="#"><i>📜</i> Policies</a></li>
      <li><a href="#"><i>❤️</i> Credits</a></li>
    </ul>
    <p>Powered by GitBook</p>
  </div>

  <!-- Content -->
  <div class="content">
    <h1>Regulations</h1>
    <p>
      Welcome to the regulations page! To access the rules, please click on the
      appropriate button for either Discord or In-Game regulations.
    </p>
    <h2>Choose a category:</h2>
    <button>Discord Regulations</button>
    <button>In-Game Regulations</button>
    <br>
    <p>Join us on Discord: <a href="https://discord.gg/UXYZAHxurE" target="_blank">https://discord.gg/UXYZAHxurE</a></p>
  </div>

  <!-- Footer -->
  <footer>
    <p>Last updated 1 month ago | Powered by <a href="https://gitbook.io" target="_blank">GitBook</a></p>
  </footer>
</body>
</html>
