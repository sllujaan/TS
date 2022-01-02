# TheSlider

<p align="center">
  <img src="https://user-images.githubusercontent.com/31973579/147652876-cb2c440a-0216-40b1-95fa-76eee0c4ca7a.png" alt="Sublime's custom image"/>
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/31973579/147653253-9f9c79d0-1948-4a13-9261-faa9a8750889.png" alt="Sublime's custom image"/>
</p>

# Features

- Fully Responsive.
- Touch Support.
- Supports large number of images. Tested with 50,000 images.
- Redirection when clicked on images.
- Fast performance. Minimum use of javascript & event handlers
- Shows current and total number of images.
- Option of render maximum number of images.
- Smooth Swipe.
- Easy to debug if got any errors when initializing the slider. (Added Validation)
- Good looking UI.
- More features can be added on demand. (Like Full-Screen Mode)

# Installation

**For Commonjs & ESModules:**

```js
// in commonjs & ESModules
import TheSlider from "TheSlider.js";
// or
// in commonjs
const TheSlider = require("TheSlider.js");
```

**In Plain Javascript:**

```html
<!-- in html file -->
<head>
  ...
  <script src="TheSlider.js"></script>
  ...
</head>
<body>
  ...
  <script type="text/javascript">
    // code
  </script>
</body>
```

# Use

```html
<!-- in html file -->
<head>
  ...
  <style>
    .container {
      background-color: black;
      width: 100%;
      height: 400px;
      border-radius: 20px;
      overflow: hidden;
      max-width: 750px;
    }
  </style>
</head>
<body>
  <div class="container"></div>
  ...
</body>
```

```js
// in script tag or index.js file
const targetElment = document.querySelectorAll(".container")[0];

try {
  const slider = new TheSlider();
  slider
    .config({
      target: targetElment,
      renderImages: 10,
      images: [
        { path: "image1.jpg", link: "link1" },
        { path: "image2.jpg", link: "link2" },
        { path: "image3.jpg", link: "link3" },
        { path: "image4.jpg", link: "link4" },
        { path: "image5.jpg", link: "link5" },
        ...
      ]
    })
    .init();
}
catch (err) {
  console.error(err);
}
```

**Or**

```js
try {
  const slider = new TheSlider();
  const config = slider.config({
    target: targetElment,
    renderImages: 10,
    images: [
      ...
    ]
  });
  config.init();
}
catch (err) {
  console.error(err);
}
```

**Or**

```js
try {
  new TheSlider({
    target: targetElment,
    renderImages: 10,
    images: [
      ...
    ]
  }).init();
}
catch (err) {
  console.error(err);
}
```

## [Click Here to See Live Demo](https://sllujaan.github.io/TS/)🚀

# Get

[![button](https://user-images.githubusercontent.com/31973579/147866642-b3697624-ff2f-4e87-a829-bf2cc9473a66.png)](https://github.com/sllujaan/TS)

# About

Salman Altaf (sllujaan44@gmail.com).



