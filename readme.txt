=== Tamil Thirukkural Quotes Plugin ===
Contributors: roghithsam
Tags: Tamil, Thirukkural, Thirukkural in Tamil, daily quotes, quotes, daily quote, quote of the day, inspirational, agnostic, atheist, knowledge quotes, Tamil Classics, Rational quotes, couplets, daily kural, Tamil verses, Thiruvalluvar, atheist quotes, tamil, tamil widget, wordpress tamil, kural
Requires at least: 5.0
Tested up to: 6.6.2
Stable tag: 2.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

The Thirukkuṛaḷ is a classic Tamil Sangam literature consisting of 1330 couplets or Kurals. It was authored by Thiruvalluvar. The Thirukkuṛaḷ is one of the most important works in the Tamil language. This is reflected in some of the other names by which the text is given by such as Tamiḻ Maṟai (Tamil Bible); Poyyāmoḻi (words that never fail); and Teyva nūl (divine text). The work is dated to sometime between the third and first centuries BCE. Thirukkural represents the way of life through rational and humane values/principles. (Zilch religions)

The Tamil Thirukkural Quotes Plugin enables you to display Tamil Thirukkural quotes on your WordPress site. This plugin offers both widget and shortcode functionality to present Thirukkural quotes with various descriptions from different commentators.

**Features:**
- **Random Quote Widget:** Display a random Thirukkural quote in any widget area with an option to choose a commentator.
- **Shortcode Support:** Insert Thirukkural quotes into posts or pages using shortcodes with customizable parameters.
- **Multiple Commentators:** Get Thirukkural descriptions from different commentators, including MuVa, Salaman, and Kalaignar.

== Installation ==

1. Upload the `tamil-thirukkural-quotes` folder to your `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Add the widget to your sidebar or any widget area via 'Appearance' > 'Widgets'.
4. Use the shortcode `[Tamil_Thirukkural]` to display Thirukkural quotes in posts or pages.
4. Enjoy! :-D

== Usage ==

### Widget

1. Navigate to 'Appearance' > 'Widgets' in your WordPress admin dashboard.
2. Add the 'Tamil Thirukkural Quotes' widget to your desired widget area.
3. Configure the widget by setting the title and selecting the commentator.
4. Save the widget settings and view the Thirukkural quotes on your site.

### Shortcodes

You can use the following shortcodes to display Thirukkural quotes:

- **Display a Random Quote with a Specific Commentator:**
  [Tamil_Thirukkural display="rand" author="MuVa"]
- **Display a Specific Kural Number with a Specific Commentator:**
	[Tamil_Thirukkural kural="350" author="MuVa"]
- **Display a Random Quote with the Default Commentator:**
	[Tamil_Thirukkural author="MuVa"]
- **Display All Quotes with a Specific Commentator:**
	[Tamil_Thirukkural display="all" author="MuVa"]


== Frequently Asked Questions ==

Q1: Can I customize the list of Thirukkural quotes?

Yes, you can add or modify quotes and their descriptions by editing the get_Tamil_Thirukkural() function in the plugin file.

Q2: How do I change the list of commentators?

To change or add commentators, update the descriptions array in the get_Tamil_Thirukkural() function to include the new commentator names and their descriptions.

Q3: Is this plugin compatible with other plugins?

The plugin is designed to work with standard WordPress installations. If you experience compatibility issues with other plugins, please report them on the Support Forum.

== Changelog ==

= 2.0.0 =

Displaying random Thirukkural quotes via widget and shortcode, including different commentators.

= 1.0.0 =

Initial release with functionality for displaying random Thirukkural quotes via widget.

== Support ==

For support and issues, please visit the Support Forum.
