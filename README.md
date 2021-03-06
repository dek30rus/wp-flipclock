WP Flipclock
============

The repository for WP Flipclock on Github.

Description
-----------
WP Flipclock is a plugin that allows you to quickly and easily add a flipclock to your site’s posts and pages via a shortcode.

The plugin allows you to count down or up from a specific date, as well as choose whether you count down days, hours or minutes.

This plugin uses the [Flipclock.js](http://www.flipclockjs.com) library from [ObjectiveHTML](https://www.objectivehtml.com/).

Demo
----
On the [WP Flipclock](http://winwar.co.uk/plugins/wp-flipclock/) page.

Installation
------------
1. Upload the plugin (unzipped) into `/wp-content/plugins/`.
2. Activate the plugin under the “Plugins” menu.

Usage
-----
To use the plugin in your site, all you need to add to the page is the [flipclock] shortcode. There are various attributes you can add as well:-

* **name** - Give the flipclock a name. Default is “flipclock”. If you have more than one flipclock on any page it’s useful to give them unique names.
* **countdown (True/False)** - Allows you to count down to a date (true), or count up from a date (false). Default is *false*.
* **date** – Any date string, formatted how you like, which the clock will count up from/down to. Default is *none*.
* **face (days/hours/minutes)** - The face of the clock. Default is hours. Options are:-
⋅⋅*days – Days : Hours : Minutes : Seconds
⋅⋅*hours - Hours : Minutes : Seconds
⋅⋅*minutes - Minutes : Seconds