To make a button act as a link in HTML, you can wrap the button element inside an anchor (`<a>`) tag. Here's an example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Button Link Example</title>
  <style>
    /* Optional: Add some basic styling for the button */
    .button-link {
      display: inline-block;
      padding: 10px 20px;
      text-decoration: none;
      background-color: #3498db;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .button-link:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>

  
  <a href="https://www.example.com" class="button-link">
    Click me
  </a>

</body>
</html>
```

In this example:

- The `<a>` tag is used to create a link.
- The `href` attribute in the `<a>` tag specifies the destination URL.
- The button is styled using a combination of HTML and CSS for a basic appearance.
- You can customize the styling based on your design preferences.

Now, when the button is clicked, it will navigate to the URL specified in the `href` attribute.
