Disqus 0.7.5
============
Add Disqus comments to blog. [See demo](https://developers.datenstrom.se/features/blog/made-for-people).

<p align="center"><img src="disqus-screenshot.png?raw=true" alt="Screenshot"></p>

## How to install extension

1. [Download and install Datenstrom Yellow](https://github.com/datenstrom/yellow/).
2. [Download and install blog extension](https://github.com/datenstrom/yellow-extensions/tree/master/features/blog).
3. [Download extension](https://github.com/datenstrom/yellow-extensions/raw/master/zip/disqus.zip). If you are using Safari, right click and select 'Download file as'.
4. Copy `disqus.zip` into your `system/plugins` folder.

To uninstall delete the [extension files](update.ini).

## How to show comments

[Disqus](http://disqus.com) is a comment service for websites. To use the extension open file `system/config/config.ini` and change `DisqusShortname: website`. You can find the name of your website in the Disqus dashboard. Comments are shown on blog pages. To show comments on other pages add a `[disqus]` shortcut to a page.

The extension uses an online service, use the [comments extension](https://github.com/wunderfeyd/yellow-comments) as an alternative.

## Developer

Datenstrom. [Get support](https://developers.datenstrom.se/help/support).

