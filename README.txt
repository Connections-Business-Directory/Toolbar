=== Connections Business Directory Toolbar ===
Contributors: shazahm1@hotmail.com
Donate link: https://connections-pro.com/
Tags: addresses, address book, addressbook, bio, bios, biographies, business, businesses, business directory, business-directory, business directory plugin, directory plugin, directory widget, church, contact, contacts, connect, connections, directory, directories, hcalendar, hcard, ical, icalendar, image, images, list, lists, listings, member directory, members directory, members directories, microformat, microformats, page, pages, people, profile, profiles, post, posts, plugin, shortcode, staff, user, users, vcard, wordpress business directory, wordpress directory, wordpress directory plugin, wordpress business directory, admin bar, adminbar, administration, connections business directory
Requires at least: 5.6
Tested up to: 6.1
Requires PHP: 5.6.20
Stable tag: 1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds useful admin links and resources for the Connections Business Directory plugin to the WordPress Toolbar / Admin Bar.

== Description ==

This is an extension plugin for the [Connections Business Directory Plugin](http://wordpress.org/plugins/connections/). Quick click access without having to scroll to all of Connections admin pages from either the admin or the front end for easy management. You can even go to a specific settings tab of filter the entry list with a single click making you life easier.

Why not just include this with the plugin as an option? Two reasons, the admin bar has limited space and to limit the amount of core plugin options and code.

Here are some other great **free extensions** (with more on the way) that enhance your experience with the business directory:

**Utility**

* [Toolbar](http://wordpress.org/plugins/connections-toolbar/) :: Provide quick links to the admin pages from the admin bar.
* [Login](http://wordpress.org/plugins/connections-business-directory-login/) :: Provides a simple-to-use login shortcode and widget.

**Custom Fields**

* [Business Hours](http://wordpress.org/plugins/connections-business-directory-hours/) :: Add the business open hours.
* [Income Level](http://wordpress.org/plugins/connections-business-directory-income-levels/) :: Add an income level.
* [Education Level](http://wordpress.org/plugins/connections-business-directory-education-levels/) :: Add an education level.
* [Languages](http://wordpress.org/plugins/connections-business-directory-languages/) :: Add languages spoken.

**Misc**

* [Face Detect](https://wordpress.org/plugins/connections-business-directory-face-detect/) :: Applies face detection before cropping an image.

**Premium Extensions**

* [Authored](http://connections-pro.com/add-on/authored/) :: Displays a list of blog posts written by the entry on their profile page.
* [Contact](http://connections-pro.com/add-on/contact/) :: Displays a contact form on the entry's profile page to allow your visitors to contact the entry without revealing their email address.
* [CSV Import](http://connections-pro.com/add-on/csv-import/) :: Bulk import your data in to your directory.
* [Custom Category Order](http://connections-pro.com/add-on/custom-category-order/) :: Order your categories exactly as you need them.
* [Form](http://connections-pro.com/add-on/form/) :: Allow site visitor to submit entries to your directory. Also provides frontend editing support.
* [Link](http://connections-pro.com/add-on/link/) :: Links a WordPress user to an entry so that user can maintain their entry with or without moderation.
* [ROT13 Encryption](http://connections-pro.com/add-on/rot13-email-encryption/) :: Protect email addresses from being harvested from your business directory by spam bots.
* [SiteShot](http://connections-pro.com/add-on/siteshot/) :: Show a screen capture of the entry's website.
* [Widget Pack](http://connections-pro.com/add-on/widget-pack/) :: A set of feature rich, versatile and highly configurable widgets that can be used to enhance your directory.

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

== Frequently Asked Questions ==

= Why doesn't it show up for me? =

This will only show up in the admin bar if the user logged in has the `manage_options` capability.

== Screenshots ==

[Screenshots can be found here.](http://connections-pro.com/add-on/toolbar/)

== Credits ==

This plugin was inspired by the [EDD Toolbar](http://wordpress.org/plugins/edd-toolbar/) plugin by�[daveshine (David Decker)](http://profiles.wordpress.org/daveshine/).

== Changelog ==

= 1.3 10/31/2022 =
* TWEAK: Remove use of deprecated `cnFormObjects::tokenURL()` method replaced with `_nonce::url()`.
* TWEAK: Qualifier can be replaced with an import.
* OTHER: Update README.txt header.
* OTHER: Correct misspellings.

= 1.2 07/13/2021 =
* TWEAK: Support the new Taxonomy API. Custom Taxonomies will now display in the Manage menu branch.
* BUG: Fix the link to the Categories admin page, utilizing the Taxonomy API vs a hard coded link.

= 1.1.1 05/03/2021 =
* OTHER: Update support links.
* OTHER: Change `http` to `https` in links.
* OTHER: Removed use of unused declared variable.
* OTHER: Remove used of deprecated tag attribute.
* DEV: phpDoc correction.
* DEV: Update plugin header.
* DEV: Update the README.txt header.

= 1.1 11/12/2015 =
* BUG: Fix admin URLs.
* OTHER: Minor phpDoc fixes.
* OTHER: Update copyright date.
* OTHER: Readme file updates.
* DEV: Update the .git* files.
* DEV: Code beautification.

= 1.0.1 05/05/2014 =
* BUG: Fix the manage page moderation filter links.
* TWEAK: Removed the action which would deactivate Toolbar if Connections was not activate.
* TWEAK: The plugin now hooks into the cn_loaded action rather than plugins_loaded.

= 1.0 09/01/2013 =
* Initial release.

== Upgrade Notice ==

= 1.1.1 =
It is recommended to back up before updating. Requires WordPress >= 5.1 and PHP >= 5.6.20 PHP version >= 7.2 recommended.

= 1.2 =
It is recommended to back up before updating. Requires WordPress >= 5.1 and PHP >= 5.6.20 PHP version >= 7.2 recommended.

= 1.3 =
It is recommended to back up before updating. Requires WordPress >= 5.6 and PHP >= 5.6.20 PHP version >= 7.4 recommended.
