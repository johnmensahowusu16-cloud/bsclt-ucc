<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BSc Laboratory Technology | UCC</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background: linear-gradient(180deg, #0a2e5c 0%, #1e4d8c 100%);
      min-height: 100vh;
      color: #fff;
      padding: 20px;
    }

    header {
      text-align: center;
      padding: 30px 10px 25px;
    }

    .logo-circle {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      background: #ffc72c;
      color: #0a2e5c;
      font-size: 38px;
      font-weight: bold;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 15px;
      box-shadow: 0 6px 20px rgba(255, 199, 44, 0.4);
    }

    header h1 {
      font-size: 24px;
      font-weight: 700;
      letter-spacing: 0.5px;
      margin-bottom: 6px;
    }

    header p {
      font-size: 14px;
      color: #c9dcf5;
      font-weight: 400;
    }

    .divider {
      width: 60px;
      height: 3px;
      background: #ffc72c;
      margin: 18px auto;
      border-radius: 3px;
    }

    .menu {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .menu a {
      display: flex;
      align-items: center;
      gap: 16px;
      background: rgba(255, 255, 255, 0.08);
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 14px;
      padding: 18px 20px;
      text-decoration: none;
      color: #fff;
      font-size: 16px;
      font-weight: 500;
      transition: all 0.2s ease;
      backdrop-filter: blur(6px);
    }

    .menu a:active {
      transform: scale(0.97);
      background: rgba(255, 199, 44, 0.15);
      border-color: #ffc72c;
    }

    .menu .icon {
      font-size: 24px;
      width: 40px;
      text-align: center;
    }

    .menu .label {
      flex: 1;
    }

    .menu .arrow {
      color: #ffc72c;
      font-size: 18px;
    }

    footer {
      text-align: center;
      padding: 30px 20px 20px;
      font-size: 12px;
      color: #8fb2d9;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo-circle">LT</div>
    <h1>BSc Laboratory Technology</h1>
    <p>University of Cape Coast</p>
    <div class="divider"></div>
  </header>

  <nav class="menu">
    <a href="slides.html">
      <span class="icon">📚</span>
      <span class="label">Course Slides & Past Questions</span>
      <span class="arrow">›</span>
    </a>

    <a href="courses.html">
      <span class="icon">📅</span>
      <span class="label">Course Structure (4 Years)</span>
      <span class="arrow">›</span>
    </a>

    <a href="voting.html">
      <span class="icon">🗳️</span>
      <span class="label">Student Elections</span>
      <span class="arrow">›</span>
    </a>

    <a href="handbook.html">
      <span class="icon">📖</span>
      <span class="label">Student Handbook</span>
      <span class="arrow">›</span>
    </a>

    <a href="books.html">
      <span class="icon">📕</span>
      <span class="label">Book Library</span>
      <span class="arrow">›</span>
    </a>

    <a href="complaints.html">
      <span class="icon">📝</span>
      <span class="label">Submit a Complaint</span>
      <span class="arrow">›</span>
    </a>
  </nav>

  <footer>
    © 2026 BSc Laboratory Technology<br>
    University of Cape Coast
  </footer>

</body>
</html>
