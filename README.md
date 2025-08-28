<!DOCTYPE html>
<html>
<head>
  <title>ROYAL SCHOOL APP</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; background: #f4f4f4; }
    h1 { color: #2c3e50; }
    .menu {
      margin: 30px auto;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    button {
      padding: 15px 30px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      background: #3498db;
      color: white;
      transition: 0.3s;
    }
    button:hover { background: #2980b9; }
  </style>
</head>
<body>
  <h1>ROYAL SCHOOL APP</h1>
  <p>Select a feature to continue:</p>

  <div class="menu">
    <button onclick="location.href='students.html'">👩‍🎓 Students</button>
    <button onclick="location.href='cbt.html'">📝 CBT Test</button>
    <button onclick="location.href='report.html'">📊 Report Card</button>
  </div>
</body>
</html>
