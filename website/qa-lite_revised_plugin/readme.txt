=== Feature Suggestion Page based on Q&A Lite ===
Contributors: CompendiumNG, WPMUDEV
Tags: features, suggestions, ideas, community, wordpress-plugins
Requires at least: 3.1
Tested up to: 3.4.1
Stable tag: trunk

Q&A Lite allows any WordPress site to have a fully featured questions and answers section - just like StackOverflow, Yahoo Answers, Quora and more...

== Description ==

Q&A allows any WordPress site to have a fully featured questions and answers section - just like StackOverflow, Yahoo Answers, Quora and more...except better :)

You've seen how engaging, informative, and just plain fun Q&A sites such as Quora can be.

With this plugin, you can bring full Questions and Answers functionality to any WordPress or BuddyPress site in mere minutes!

Chock-full of features such as:

* Full **front-end** capability - users don't ever have to see your site's admin back-end
* **WYSIWYG** editing of both questions and answers
* Snazzy **voting** for both questions and answers
* Integrated **reputation points** system
* Dedicated **user profile** pages
* Easy theme integration using **widgets**
* Fully **customizable** using dedicated template files

This powerful plugin covers all the question and answer bases right out of the box. It’s easy to install and fully operational in moments, and highly customizable too!

= Pro Version =

Q&A Lite is an entirely functional but limited version of our <a href='http://premium.wpmudev.org/project/qa-wordpress-questions-and-answers-plugin'>full Q&A plugin</a>.

Here are some features that come *only* with the PRO version:

**Categories**, in addition to tags, can be assigned to questions (separate from the normal post categories). Very handy when you have a few broad areas that you would like to distinguish between.

**Anonymous visitors** can also post question and answers, which will be published after they have successfully logged in (which is easier to do than usual). This lowers the barrier to entry, making your community grow faster.

Users can **subscribe** to questions, receiving emails when new answers are posted. This is a great way to engage users and leads to better answers overall.

<a href='http://premium.wpmudev.org/project/qa-wordpress-questions-and-answers-plugin'>**Upgrade to the full version now &raquo;**</a>

== Installation ==

1. Activate plugin.
2. Go to Questions -> Settings to assign capabilities to the roles of your choosing.
3. Go to http://yoursite.com/questions/ask/ to create your first question.

= Styling =

Copy the php files from default-templates into your theme folder and start customizing.

To disable the default CSS, add the following line to your theme's functions.php file:

`add_theme_support( 'qa_style' );`

To disable the default JavaScript, add the following line to your theme's functions.php file:

`add_theme_support( 'qa_script' );`

When you feel that the Q&A section is ready for primetime, if your theme supports [custom menus](http://en.support.wordpress.com/menus/), you could add direct links to http://yoursite.com/questions/ and even to http://yoursite.com/questions/ask/ to your main menu.

== Upgrading from Q&A Lite to Q&A ==
1. Deactivate Q&A Lite
2. Install Q&A.
3. Uninstall Q&A Lite. Your previous plugin settings in Q&A Lite are preserved.
Note: If you modified template files, they will NOT be preserved. Before uninstall, backup them and upload after installing Q&A.

== Changelog ==

= 1.3.0 =
* Buddypress support
* Theme mods support
* Added full width Q&A pages selection option
* Added Users with Highest Reputation widget
* Questions Per Page is now adjustable
* Question status count included in admin Right Now Dashboard box
* Added possibility to save questions in pending mode for all user levels
* Added possibility to remove commenting in Buddypress activity stream
* Css settings can be set using admin panel now
* Added wp_editor filter, post filter and several other filter hooks to control how questions are saved and messages are sent 
* Disabling of WP editor is now possible
* Answers per page can be set from admin side
* Admin UI improved
* More explanatory reply in case of a duplicate question submission
* Added proper uninstall functionality
* Default capabilities are now better set during installation
* Fixed unauthorized users accessing question pages. They are now redirected to a selectable page instead
* Fixed css issue for accepted answer icon
* Fixed notices displayed in WP Debug mode
* Fixed redundant plugin php file in the plugin folder
* Fixed non logged in users accessing pages beyond their authority
* activity-action class is included in css file to prevent links become invisible
* Features synchronized with Q&A full version

= 1.1.x and V 1.2.x =
- Not released and not available -

= 1.0.4 =
* Switch frontend WYSIWYG editor to TinyMCE and Quicktags
* WordPress 3.3 compatibility

= 1.0.3 =
* Fixed: BP Default theme issues
* Fixed: BP Default child theme issues
* Fixed: BP 1.5 compatibility
* Fixed: 404 error in ask page

= 1.0.2 =
* Added update code

= 1.0.1 =
* show message when non-logged-in user tries to vote
* fix reputation points bug
* load archive-question.php template even when there are no unanswered questions

= 1.0 =
* initial release

144448-1358567312
