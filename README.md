# Assessment-Code-V2
Second Version Of Assessment Code.


<!DOCTYPE html>
<html lang="en">
<head>
  <title>Technology News.</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://w3schools.com">
  <style>
    html {
      background-color: lightgrey;
    }

    /* New class for the purple boxes */
    .purple-box {
      background-color: rgb(110, 5, 151);
      color: white;
      border-radius: 8px;
      padding: 16px;
    }

    /* Updated button style so it stands out inside the purple box */
    .card-btn {
      background-color: white;
      color: rgb(110, 5, 151);
      font-weight: bold;
      padding: 10px 20px;
      margin-bottom: 16px;
      border-radius: 4px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav class="w3-bar w3-black">
    <a href="#home" class="w3-button w3-bar-item">Home.</a>
    <a href="#band" class="w3-button w3-bar-item">About Us.</a>
    <a href="#contact" class="w3-button w3-bar-item">Contact</a>
  </nav>

  <!-- Main Content -->
  <div class="w3-container">
    <!-- Top title and description stay right here -->
    <h1>Technology News.</h1>
    <p>Get all the latest on all of the newest technology related news, whether it be the newest device, updated guidelines or news about AI!</p>

    <!-- Grid of Purple Boxes -->
    <div class="w3-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 16px;">
      
      <div class="w3-container w3-card purple-box">
        <h2>Newest in AI!.</h2>
        <p>Explore the latest on whats happening with the newest artificial technology</p>
        <a href="Jobs.html" class="w3-button card-btn">Explore</a>
      </div>

      <div class="w3-container w3-card purple-box">
        <h2>Jobs.</h2>
        <p>How can Technology be used in art, food, and architecture?</p>
        <a href="ai-news.html" class="w3-button card-btn">Explore</a>
      </div>

      <div class="w3-container w3-card purple-box">
        <h2>Too much?</h2>
        <p>When does some Technology become too much Technology?</p>
        <a href="too-much.html" class="w3-button card-btn">Explore</a>
      </div>

    </div>
  </div>

</body>
</html>
