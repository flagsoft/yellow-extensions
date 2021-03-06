Core 0.8.1
==========
Core functionality for your website.

<p align="center"><img src="core-screenshot.png?raw=true" alt="Screenshot"></p>

## How to install extension

1. [Download and install Datenstrom Yellow](https://github.com/datenstrom/yellow/).
2. [Download extension](https://github.com/datenstrom/yellow-extensions/raw/master/zip/core.zip). If you are using Safari, right click and select 'Download file as'.
3. Copy `core.zip` into your `system/plugins` folder.

Do not delete the [extension files](update.ini), they are always required.

## How to use the core

The extension provides the core functionality for your website. It takes care of requests from the web browser and access to the file system. You can use the [web browser](https://github.com/datenstrom/yellow-extensions/tree/master/features/edit) or the [command line](https://github.com/datenstrom/yellow-extensions/tree/master/features/command) to show website version and updates. You can also show the current version directly on your website. See example below.

## How to configure the core

The following settings can be configured in file `system/config/config.ini`:

`Sitename` = name of the website  
`Author` = webmaster's name  
`Email` = webmaster's email  
`Language` = default language  
`Timezone` = default timezone  
`MultiLanguageMode` = enable [multi language mode](https://developers.datenstrom.se/help/language-configuration#multi-language-mode), 1 or 0  
`SafeMode` = enable [safe mode](https://developers.datenstrom.se/help/security-configuration#safe-mode) with restrictions, 1 or 0  

These are the most important settings. For a complete list see [configuration file](https://github.com/datenstrom/yellow/blob/master/system/config/config.ini).

## Example

Content file with website version:

```
---
Title: Example page
---
This website is made with [yellow].
```

Content file with website version, including extensions:

```
---
Title: Example page
---
This website is made with [yellow].

[yellow version]
```

## Developer

Datenstrom. [Get support](https://developers.datenstrom.se/help/support).
