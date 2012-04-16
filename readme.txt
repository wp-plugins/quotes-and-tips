=== Quotes and Tips ===
Contributors: bestwebsoft
Donate link: https://www.2checkout.com/checkout/purchase?sid=1430388&quantity=10&product_id=13
Tags: quote, tip, information, hints, quotes, tips, additional info, statements
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: 1.03

This plugin allows you to implement quotes & tips block into your web site.

== Description ==

This plugin allows you to create and publish quotes of your customers about your work and helpful tips for the website visitors.

<a href="http://wordpress.org/extend/plugins/quotes-and-tips/faq/" target="_blank">FAQ</a>
<a href="http://bestwebsoft.com/plugin/quotes-and-tips/" target="_blank">Support</a>

= Features =

* Display: it is possible to use bakground image for block, change background color and text color.
* Actions: possibility to add quotes & tips to any place on your website .
* Label: There is a possibility to change the label for quotes block and tips block - user custom label or title from quotes & tips posts.

= Translation =

* Russian (ru_RU)

If you create your own language pack or update the existing one, you can send <a href="http://codex.wordpress.org/Translating_WordPress" target="_blank">the text of PO and MO files</a> for <a href="http://bestwebsoft.com/" target="_blank">BWS</a> and we'll add it to the plugin. You can download the latest version of the program for work with PO and MO files  <a href="http://www.poedit.net/download.php" target="_blank">Poedit</a>.

= Technical support =

Dear users, if you have any questions or propositions regarding our plugins (current options, new options, current issues) please feel free to contact us. Please note that we accept requests in English only. All messages on another languages wouldn't be accepted. 

== Installation ==

1. Upload `quotes-and-tips` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Site wide Settings are located in 'BWS Plugins', 'Quotes and Tips'.

== Frequently Asked Questions ==

= How to use plugin? =

1. Choose 'Add New' from the 'Quotes' menu and fill in your page.
1. Choose 'Add New' from the 'Tips' menu and fill in your page.
2. Add this code in your theme where you'd like to show the block 'Quotes and Tips' `&lt;?php if( function_exists( 'qtsndtps_get_random_tip_quote' ) ) qtsndtps_get_random_tip_quote();  ?&gt;`. 
3. Use settings on the page 'BWS Plugins', 'Quotes and Tips'.

= How to change background or text color? =

1. Go to the Settings Page, which is in the menu 'BWS Plugins', 'Quotes and Tips'.
2. Choose `Additional options`.
3. Make the necessary settings (choose the text color, background color, upload a background image).

= What should I do if I don't want to use a block background image anymore? =

1. Go to the Settings Page, which is in the menu'BWS Plugins', 'Quotes and Tips'.
2. Choose`Additional options`.
3. Deselect the item `Use background image`.

= I want to choose a background image position. How can I do that? =

1. Go to the Settings Page, which is in the menu'BWS Plugins', 'Quotes and Tips'.
2. Choose `Additional options`.
3. Use the necessary settings in the blocks Background image repeat, Background image horizontal align, Background image vertical align.

= How to use the other language files with the Quotes and Tips? = 

Here is an example for German language files.

1. In order to use another language for WordPress it is necessary to set the WP version on the required language and in the configurational wp file - `wp-config.php` in the line `define('WPLANG', '');` write `define('WPLANG', 'de_DE');`. If everything is done properly the admin panel will be in German.

2. Make sure that there are files `de_DE.po` and `de_DE.mo` in the plugin (the folder languages in the root of the plugin).

3. If there are no these files it will be necessary to copy other files from this folder (for example, for Russian or Italian language) and rename them (you should write `de_DE` instead of `ru_RU` in the both files).

4. The files are edited with the help of the program Poedit - http://www.poedit.net/download.php - please load this program, install it, open the file with the help of this program (the required language file) and for each line in English you should write the translation in German.

5. If everything is done properly all lines will be in German in the admin panel and on front-end.

== Screenshots ==

1. Basic option for Quotes and Tips.
2. Basic and Additional options for Quotes and Tips.
3. Frontend page with Quotes and Tips block.

== Changelog ==

= V1.03 - 05.04.2012 =
* Bugfix : The conflict of our javascript with javascript of other plugins is fixed. 
* Changed : BWS plugins section. 

= V1.02 - 12.03.2012 =
* Changed : BWS plugins section. 

= V1.01 - 01.03.2012 =
* NEW : Additional options for pluign are added.
* NEW : Russian language file is added to the plugin.

== Upgrade Notice ==

= V1.03 =
The conflict of our javascript with javascript of other plugins is fixed. BWS plugins section. 

= V1.02 =
BWS plugins section has been changed. 

= V1.01 =
Additional options for Settings plugin page are added. Added Russian language file is added to the plugin.