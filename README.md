# remark-theme

CSS theme of [remark](http://remarkjs.com).

## Sample

* [Blue Standard](https://sfc-arch.github.io/remark-theme/blue_standard/sample/sample.html)

## Usage

Just add a link to the theme CSS to your remark HTML file.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Title</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <script src="https://sfc-arch.github.io/remark/downloads/remark-latest.min.js"></script>
    <link rel="stylesheet" type="text/css" href="https://sfc-arch.github.io/remark-theme/blue_standard/remark_theme_blue_standard.css"/>
  </head>
  <body>
    <script>
      var slideshow = remark.create({ sourceUrl: 'slide.md' });
    </script>
  </body>
</html>
```
