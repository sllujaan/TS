# TheSlider

```js
try {
    var slider = new TheSlider(); 
    slider
      .config({
        target: targetElment,
        renderImages: 6,
        images: [
          { path: "image1.jpg", link: "link1" },
          { path: "image2.jpg", link: "link2" },
          { path: "image3.jpg", link: "link3" },
          { path: "image4.jpg", link: "link4" },
          { path: "image5.jpg", link: "link5" },
          ...
        ],
      })
      .init();
} catch (err) {
    console.error(err);
}
```
