=== Recent Custom Posts ===
Contributors: mmattner
Donate link:
Plugin URI: http://mikemattner.com/2011/09/creating-the-recent-custom-posts-wordpress-widget/
Author: Mike Mattner
Author URI: http://www.mikemattner.com
Tags: custom post types, post types, latest posts, sidebar widget, plugin
Requires at least: 2.8
Tested up to: 3.2.1
Stable tag: 1.0.1

Multi-widget for displaying recent posts of custom post types.

== Description ==

This plugin provides a way to display the most recent posts from multiple custom post types in multiple widgetized areas. In function, it is much like the default Recent Posts widget, as it is a multi-widget for displaying recent posts, but it allows you to choose what post types to display.

== Features ==
* Choose which custom post type(s) to display the most recent posts from.
* Choose the number of posts to display.
* Custom title text.

== Installation ==

1. Unzip and upload the folder `/recent-custom-posts/` to the `/wp-content/plugins/` directory of your WordPress installation.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Add as many 'Recent Custom Posts' widgets as you'd like to your available sidebars, and adjust each widget's settings accordingly.

== Frequently Asked Questions ==

= How do I select multiple post types? =

The widget uses a select box in order to display the post types. Click the first post type, then ctrl or cmd click the additional post types you wish to include.

== Screenshots ==

1. The widget in action.

== Changelog ==

= 1.0.1 =
* Plugin was generating the same id for the ul tag in each widget. This was leftover from development, and has been eliminated.
* Widget display now correctly handled by theme.
* Changed widget id base from `widget_recent_custom_posts` to `rcp_recent_custom_posts`.
* Cleaned up some of the code.

= 1.0 =
* This is the first version

== Upgrade Notice ==

= 1.0.1 =