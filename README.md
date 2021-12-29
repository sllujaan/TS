# TheSlider
<p align="center">
  <img src="https://user-images.githubusercontent.com/31973579/147652876-cb2c440a-0216-40b1-95fa-76eee0c4ca7a.png" alt="Sublime's custom image"/>
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/31973579/147653253-9f9c79d0-1948-4a13-9261-faa9a8750889.png" alt="Sublime's custom image"/>
</p>


# Installation

**For Commonjs & ESModules:**

```js
import TheSlider from "TheSliderjs";
// or
const TheSlider = require("TheSliderjs");
```

**In Plain Javascript:**

```html
<!-- in html file -->
<head>
  ...
  <script src="TheSliderjs"></script>
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

```js
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
