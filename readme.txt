=== Busted ===
Contributors: brainstormmedia, pdclark
Plugin URI: https://github.com/brainstormmedia/disable-browser-cache
Author URI: http://brainstormmedia.com
Tags: browser, cache, develop, debug, client, clear, empty, bust, break, refresh
Requires at least: 3.4
Tested up to: 3.7.1
Stable tag: 1.1
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Force browsers to load the most recent file if modified.

== Description ==

Saves you from asking "have you emptied your cache?".

**Features**

* Safe to leave running on live sites.
* Only refreshes browser cache for a file if it has been modified.
* Resolves caching issues with Content Delivery Networks (CDNs) as well. No need to purge your CDN cache.
* "Just works" — no configuration necessary.

**Requirements**

Requires scripts use any of the below functions to load. Almost all files meet these requirements. The only case it doesn't account for is when URLs are hard-coded. This shouldn't ever be done, since it can break sites for other reasons.

* [wp_enqueue_style](http://codex.wordpress.org/Function_Reference/wp_enqueue_style)
* [wp_enqueue_script](http://codex.wordpress.org/Function_Reference/wp_enqueue_script)
* [get_stylesheet_uri](http://codex.wordpress.org/Function_Reference/get_stylesheet_uri)

== Installation ==

1. Search for "Busted" under `WordPress Admin > Plugins > Add New`
1. Install the plugin.
1. Activate the plugin.

== Changelog ==

= 1.1 =
* Only refresh cache if file has been modified. Thanks [@unserkaiser](https://twitter.com/unserkaiser/status/402995947430375424).

= 1.0 =
* Initial public release.

== Upgrade Notice ==

= 1.1 =
* Only refresh cache if file has been modified. Thanks [@unserkaiser](https://twitter.com/unserkaiser/status/402995947430375424).