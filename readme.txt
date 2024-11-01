=== Simple NoAI and NoImageAI ===
 
Contributors: the9mm
Tags: noai, noimageai
Requires at least: 1.2
Tested up to: 6.6
Stable tag: 1.6.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
  
This plugin very simply adds a line of code to your header that tells AIs not to use anything on your website for indexing. It can also be configured to add disallow rules to your robots.txt file.
  
== Description ==
  
This plugin is very simple: It adds a line of code in high priority to the header of every page on your site that politely asks AI crawlers not to use your content for AI training purposes.

For more information on how the meta tag works, you can check out the blog post [what is DeviantArt’s new “noai” and “noimageai” meta tag and how to install it.](https://www.aimeecozza.com/noai-noimageai-meta-tag-how-to-install/)

New in 1.6: Alterations to robots.txt is now included, and includes popular crawlers like GPTBot and Google-Extended. More crawlers will be added as they are created or discovered.

== Installation ==
  
1. Upload the plugin folder to your /wp-content/plugins/ folder.
2. Go to the **Plugins** page and activate the plugin.
  
== Frequently Asked Questions ==

= Will this protect me against AI data scraping? =
  
While the plugin has the ability to ask nicely of well-behaved bots to not use your website or content on it for AI purposes, it is not all inclusive and is not an absolute measure to stop AI data scraping. The technology used to ask bots to skip your site is the same technology used to ask that of search engine crawlers. Badly behaved bots can (and often will) entirely bypass these rules and access your website anyway. Please do your due diligence to ensure you are protecting sensitive assets and data. May I suggest using Glaze for protection on your images? 
  
= How do I use this plugin? =
  
Simply activate the plugin for the noai and noimageai to be added to the header of your entire site and the robots.txt file will be appended with appropriate crawler blocks.
  
= How to uninstall the plugin? =
  
Simply deactivate and delete the plugin. 
  
== Changelog ==
= 1.6.4 =
* Supports WordPress 6.6

= 1.6.3 =
* Added support for AppleBot-Extended, Bytespider, Cohere-ai, Diffbot, ImagesiftBot, PerplexityBot, FacebookBot, and Omigili.

= 1.6.2 =
* Supports WordPress 6.5

= 1.6.1 =
* Plugin now opts out by default on activation if no other option is selected.

= 1.6 =
* Plugin updated to support WordPress 6.4.1
* Now includes Robots.txt support for GPTBot, ChatGPT-User, Google-Extended, GoogleOther, CCBot, and Anthropic-AI

= 1.5 =
* Plugin updated to support WordPress 6.3.
* Settings page (Under settings) added to allow selecting which pages the meta directive is added to, as well as which meta directive(s) you want.

= 1.0 =
* Plugin released. 