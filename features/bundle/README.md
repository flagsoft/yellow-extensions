Bundle 0.8.1
============
Bundle CSS and JavaScript.

<p align="center"><img src="bundle-screenshot.png?raw=true" alt="Screenshot"></p>

## How to install extension

1. [Download and install Datenstrom Yellow](https://github.com/datenstrom/yellow/).
2. [Download extension](https://github.com/datenstrom/yellow-extensions/raw/master/zip/bundle.zip). If you are using Safari, right click and select 'Download file as'.
3. Copy `bundle.zip` into your `system/plugins` folder.

To uninstall delete the [extension files](update.ini).

## How to bundle CSS and JavaScript

The extension bundles and minifies files for a better loading time. Your website may contain multiple CSS and JavaScript. Usually these files will be cached in the browser, but nevertheless each file has to be checked. This is where a file bundler comes in. It looks for included files and replaces them with one single bundle for CSS and one for JavaScript.

The extension uses [Minify v1.3.60](https://github.com/matthiasmullie/minify) by Matthias Mullie. It's licensed under [MIT license](https://opensource.org/licenses/MIT).

## Example

Website with unbundled CSS and JavaScript files:

```
<!DOCTYPE html>
<html>
<head>
<title>Example page</title>
<link rel="stylesheet" type="text/css" media="all" href="/user/mark/media/plugins/gallery.css" />
<link rel="stylesheet" type="text/css" media="all" href="/user/mark/media/plugins/twitter.css" />
<link rel="stylesheet" type="text/css" media="all" href="/user/mark/media/themes/assets/flatsite.css" />
<script type="text/javascript" defer="defer" src="/user/mark/media/plugins/gallery-photoswipe.min.js"></script>
<script type="text/javascript" defer="defer" src="/user/mark/media/plugins/gallery.js"></script>
<script type="text/javascript" defer="defer" src="/user/mark/media/plugins/twitter.js"></script>
</head>
<body>
<h1>Hello world</h1>
</body>
</html>
```

Website with bundled CSS and JavaScript files:

```
<!DOCTYPE html>
<html>
<head>
<title>Example page</title>
<link rel="stylesheet" type="text/css" media="all" href="/media/themes/assets/bundle-04a833a199.min.css" />
<script type="text/javascript" defer="defer" src="/media/themes/assets/bundle-efe3f521b6.min.js"></script>
</head>
<body>
<h1>Hello world</h1>
</body>
</html>
```

## Developer

Datenstrom featuring Matthias Mullie. [Get support](https://developers.datenstrom.se/help/support).
