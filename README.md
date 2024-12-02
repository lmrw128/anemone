
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Paintings</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    header {
      text-align: center;
      padding: 20px;
      background-color: #4a90e2;
      color: white;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .painting {
      margin: 15px;
      text-align: center;
    }
    .painting img {
      max-width: 300px;
      height: auto;
      border: 3px solid #ccc;
      border-radius: 5px;
    }
    .painting h3 {
      margin-top: 10px;
      font-size: 1.1em;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Art Gallery</h1>
    <p>Welcome to my collection of paintings!</p>
  </header>
  <div class="gallery">
    <div class="painting">
      <img src="artsy/painting1.png" alt="Painting 1">
      <h3>Title of Painting 1</h3>
    </div>
    <div class="painting">
      <img src="artsy/painting2.png" alt="Painting 2">
      <h3>Title of Painting 2</h3>
    </div>
    <div class="painting">
      <img src="artsy/painting3.jpg" alt="Painting 3">
      <h3>Title of Painting 3</h3>
    </div>
    <!-- Add more paintings as needed -->
  </div>
</body>
</html>
