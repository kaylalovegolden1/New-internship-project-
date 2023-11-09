# New-internship-project-
<!DOCTYPE html>
<html>
<head>
  <title>Design program software</title>
  <style>
    /* Add your custom CSS styles here */
    canvas {
      border: 1px solid black;
    }
  </style>
</head>
<body>
  <header>
    <h1>Design program software</h1>
  </header>

  <main>
    <canvas id="canvas" width="800" height="600"></canvas>
  </main>

  <script>
    // Add your JavaScript code here
    const canvas = document.getElementById('canvas');
    const ctx = canvas.getContext('2d');

    // Example: Draw a rectangle
    ctx.fillStyle = 'red';
    ctx.fillRect(100, 100, 200, 150);
  </script>
</body>
</html>
