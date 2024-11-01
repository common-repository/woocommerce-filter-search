=== WooCommerce Filter Search ===
Contributors: nicolamustone
Tags: woocommerce, search, excerpt, content, title, filter
Requires at least: 3.8
Tested up to: 4.9.7
Stable tag: 1.0.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Change the search query behaviour searching only in the post/product title.

== Description ==

Change the search query behaviour searching only in the post/product title. You can add post types to the **not allowed** list using [this code](https://gist.github.com/SiR-DanieL/8ca1b1b33ab791836a59).

By default the unallowed post types are **product** and **shop_webhook**.

**NOTE**: This plugin will always search for products, but the keyword will be compared **only** with the product title.

= Usage =

Just activate the plugin.

== Installation ==

= Minimum Requirements =

* PHP version 7.0 or greater.

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t need to leave your web browser. To do an automatic install of WooCommerce Filter Search, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type “WooCommerce Filter Search” and click Search Plugins. Once you’ve found the plugin you can view details about it such as the point release, rating and description. Most importantly of course, you can install it by simply clicking “Install Now”.

= Manual installation =

The manual installation method involves downloading this plugin and uploading it to your web-server via your favourite FTP application. The WordPress codex contains [instructions on how to do this here](https://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

= Updating =

Automatic updates should work like a charm; as always though, ensure you backup your site just in case.

== Changelog ==

= 1.0.3 =
* Fix: error with PHP 7+ and values passed by reference.
* Fix: the code now uses PHP classes and only runs on the frontend.
* Tested with WooCommerce 3.4.4 and WordPress 4.9.7.


= 1.0.2 =
* Fix: replaced deprecated like_escape with esc_like.

= 1.0.1 =
* Fix: Bug in plugin logic.

= 1.0.0 =
* First release.
