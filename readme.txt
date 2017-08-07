=== Plugin Name ===

Contributors: Rob Douglass
Donate link: http://www.jmrwebsolutions.co.uk
Tags: weather, wxsim, forecast
Requires at least: 2.8
Tested up to: 3.0.1
Stable tag: 1.0

Displays WXSIM forecast on a specific page of your wordpress site.

== Description ==

This Plugin is just a port from Saratoga weather scripts for use in Wordpress

Original Concept: Ken True - http://www.saratoga-weather.org/index.php 

== Installation ==

1. Unzip and upload files the files to `/wp-content/plugins/WXSIMforecast/`
2. Activate the plugin
3. Go to Settings then WXSIM forecast
4. Specify weather station
5. Specify where to get the plaintext file from (this is the folder you upload to)
6. Temperature can either be Celsius or Fahrenheit
7. Language is by default English however you can download translations from http://www.saratoga-weather.org/
8. Max width can be either a percentage or pixel value and this is the space allowed for the forecast
9. Max Icons is the number of Icon you want to display which restricts the amount of days displayed
10. Minimum Probability of Precipitation(PoP) - PoP percentage must equal this value or above to display rain icon, otherwise the sky icon with PoP is displayed.
11. Display Beaufort - Set to V' for no Beaufort and set to 'T' for translated name

To add the widget to a posts and/or pages use the shortcode [forecast].

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

= What about foo bar? =

Answer to foo bar dilemma.

== Screenshots ==


== Changelog ==

= 1.0 - 21.10.2010  =
* Fixed numerous bugs in code
* Fixed CSS problems including all alignment issues
* Add three new option in the admin section
* Fixed Image alignment fault

= 0.2 - 07.10.2010  =
* upgrade to latest version of script from Ken
* Fixed a display problem with regarding the number of days forecast
* Implemented a CSS file and specified font size for plug in
* Fixed language problem.  Now shows the correct language.

= 0.1 - 17.03.2010  =
* initial release


== Upgrade Notice ==


== Arbitrary section ==


== A brief Markdown Example ==

Ordered list:

1. 

Unordered list:

* 

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`
