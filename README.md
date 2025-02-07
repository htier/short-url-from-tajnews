=== Short URL from TajNews ===
Contributors: tajnews
Donate link: https://tajnews.org/short-url-from-tajnews/
Tags: short url, YOURLS, link shortener, copy link
Requires at least: 5.0
Tested up to: 6.7
Stable tag: 1.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Short URL from TajNews is a free plugin to automatically create short links via YOURLS. 
Works with a default domain or your own YOURLS service, includes a shortcode, meta box, and automatic link insertion.

== Description ==

**Short URL from TajNews** is originally developed for our internal use, but we decided 
to share it publicly for everyone’s benefit. It automatically generates short URLs (via 
YOURLS) for each post and can append the link at the bottom of your content, as well as 
provide a `[tajnews_shortlink]` shortcode to place the link anywhere in your post.

= Features =
* Auto-generate short links on publish/update
* Embed short URLs manually via shortcode `[tajnews_shortlink]`
* Meta box in the post editor for quick copying
* Supports default domain (g00g.link) or your own YOURLS domain + signature

== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory, or install via 
   the Plugins > Add New in your WordPress admin.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. (Optional) Go to 'Settings' -> 'TajNews ShortURL' to configure your custom YOURLS domain 
   and signature key. If you leave these fields blank, the plugin will use our default 
   domain and key.

== Frequently Asked Questions ==

= Can I use my own YOURLS server? =
Yes. Simply enter your YOURLS Domain and Signature Key on the settings page and save. 
All future short links will be created using your YOURLS installation.

= Does it work with custom post types? =
Currently, it’s optimized for standard 'post' type. You can extend or adapt it via 
filter hooks if needed.

== Screenshots ==

1. **Screenshot #1** - Settings page with custom YOURLS domain/key.
2. **Screenshot #2** - Short link appended at the bottom of a post.
3. **Screenshot #3** - Meta box displaying the short link in the editor.

== Changelog ==

= 1.4 =
* Added fallback to default domain (g00g.link) if user fields are blank
* Auto-append short link to the bottom of posts
* Improved “Copy link” JavaScript

== Upgrade Notice ==
No special steps required. Simply replace old files with the new version and reactivate.
