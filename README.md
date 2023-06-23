# HTML-CSS-Essentials-Bootcamp2
Assignment - HTML &amp; CSS Essentials Bootcamp

# HTML FILE
<!DOCTYPE html>
<html>
<head>
  <title>Photo Gallery</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <h1>Photo Gallery</h1>

  <div class="gallery">
    <img src="image1.jpg" alt="Image 1">
    <img src="image2.jpg" alt="Image 2">
    <img src="image3.jpg" alt="Image 3">
    <!-- Add more images as needed -->
  </div>
</body>
</html>


# CSS FILE
h1 {
  text-align: center;
}

.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.gallery img {
  border: 2px dotted #999;
  margin: 10px;
  transition: border-color 0.3s ease-in-out;
}

.gallery img:hover {
  border-color: #ff0000;
}
