# Kirby Cachebuster Plugin

This plugin will append modification timestamps to your css and js files as query string, 
as long as they are embedded with the css() and js() helpers.

## Requirements

This plugin requires Kirby 2.3.

Please note that this plugin doesn't add caching headers to your CSS and JS files.

## Installation

To use this plugin, add the cachebuster.php to `site/plugins`. 

Now you can activate the plugin with following line in your `config.php`.

```
c::set('cachebuster', true);
```
## Notes
This fork of the Cache Buster plugin do not require rewrite rules for Webserver
## Authors

Bastian Allgeier <bastian@getkirby.com> & Lukas Bestle <lukas@getkirby.com>