Certainly! To include multiple images in a horizontal animation. Here's an example using three images:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Horizontal Images Animation</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      overflow: hidden;
    }
    img{
      margin-left: 20px;
      padding-right: 20px;
    }
    .animation-container {
      position: absolute;
      top: 0;
      left: 0;
      width: 300vw; /* Adjust the width based on the number of images */
      height: 100vh;
      overflow: hidden;
    }

    @keyframes horizontalMove {
      0% {
        transform: translateX(0);
      }
      100% {
        transform: translateX(-200%); /* Adjust based on the number of images */
      }
    }

    .animated-element {
      position: absolute;
      width: 100vw;
      height: 100vh;
      display: flex;
      animation: horizontalMove 60s linear infinite;
    }

    .animated-element img {
      width: 100%;
      height: auto;
    }
  </style>
</head>
<body>

  <!-- Animation container -->
  <div class="animation-container">
    <!-- Animated element with multiple images -->
    <div class="animated-element">
      <img src="image1.jpg" alt="Image 1">
      <img src="image2.jpg" alt="Image 2">
      <img src="image3.jpg" alt="Image 3">
    </div>
  </div>

</body>
</html>
```

Explanation:

- The `.animation-container` width is set to `300vw` to accommodate three images. Adjust it based on the number of images you have.
- The `@keyframes horizontalMove` is adjusted to translate by `-200%` at 100%, allowing for a continuous horizontal movement of the images.
- The `.animated-element` contains the images, and the `display: flex;` property is used to arrange them in a horizontal line.

Make sure to replace `"image1.jpg"`, `"image2.jpg"`, and `"image3.jpg"` with the actual file paths or URLs of your images. Adjust the duration, timing function, and other styles as needed.
