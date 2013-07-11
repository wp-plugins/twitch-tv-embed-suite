=== Twitch TV Embed Suite ===
Contributors: plumwd
Donate link: http://www.plumeriawebdesign.com
Tags: live stream, twitch tv, gaming
Requires at least: 2.0.2
Tested up to: 3.5.2
Stable Tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Twitch TV Embed Suite allows easy placement of a twitch tv stream and/or chat anywhere on your WordPress site.  
== Description ==

Twitch TV Embed Suite is a plugin that allows for fast and easy embedded of twitch tv stream and chat on your WordPress site. The plugin features an easy to configure 
settings area that allows the user to preview the stream prior to placement on your site.

* Specify stream width and height
* Autoplay
* Stream volume
* Display alternate content for viewers who cannot view FLASH *(Twitch is working on an HTML5 version. We will upgrade once this is available)*
* Choose to allow full screen
* Set background color
* Choose wmode options
* Decide whether or not to show chat
* Specifiy chat width and height
* Test your stream from the admin dashboard

== Installation ==

1. Download and unzip the file.
2. Place the entire contents of the directory into your `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Settings
2. Widget 
3. Stream with Chat 
4. Stream Icon for WYSIWYG Editor
4. Chat Icon for WYSIWYG Editor


== Shortcode Usage ==

1. To add a stream to your posts, pages, or widgets use the following code:
    [plumwd_twitch_stream]
2. To add a stream to your WordPress theme use the following code inside your template: `echo do_shortcode('[plumwd_twitch_stream]');`
3. Use the icon from the WYSIWYG editor to insert into a post or page.

1. To add twitch chat to your posts, pages, or widgets use the following code:
    [plumwd_twitch_chat]
2. To add chat to your WordPress theme use the following code inside your template: `echo do_shortcode('[plumwd_twitch_chat]');`
3. Use the icon from the WYSIWYG editor to insert into a post or page.


1.To add a Twitch TV stream list to your posts, pages, or widgets use the following shortcode:
  [plumwd_twitch_streamlist]
2. To add the Twitch TV stream plugin to your WordPress theme use the following shortcode inside your template:
    echo do_shortcode('[plumwd_twitch_streamlist]');

The plugin also supports several attributes for the shortcode, below is a listing of the attributes and what their purpose is:

1. channel -> this must be set or the feed will not display. Usage:
    [plumwd_twitch_streamlist channel="plumwd"]
2. videonum -> The number of streams to display. Will return the most recent streams in order from newest to oldest. Usage:
    [plumwd_youtube_display channel="plumwd" videonum="4"]
3. display -> accepts two different options: horizontal or vertical. Usage:
    [plumwd_twitch_streamlist channel="plumwd" display="horizonal"]
 
== Frequently Asked Questions ==

For help please visit http://www.plumeriawebdesign.com

== Changelog ==

= 1.0.2 =
* Fixed undefined index error

= 1.0.1 =
* Fixed footer credits