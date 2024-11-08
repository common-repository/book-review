=== Plugin Name ===
Contributors: wpreviewplugins, donnapep
Tags: deprecated, blog, affiliate, amazon, associates, book, book blog, book blogger, book blogging, book review, rating, review
Author URI: http://wpreviewplugins.com/
Plugin URI: http://wpreviewplugins.com/product/book-review/
Requires at least: 3.5
Tested up to: 4.8
Stable tag: 2.3.9
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Spend more time reading

== Description ==

NOTE: Given the imminent release of the Gutenberg editor in WordPress 5.0, the Book Review plugin is no longer being maintained. It has been replaced by [Book Review Block](https://wordpress.org/plugins/book-review-block/), which is intended to be used together with the Gutenberg editor.

= Save Time =
Book Review saves you time when writing your reviews. No more copying and pasting or manually entering the details of a book. Instead, you provide the ISBN, and Book Review will automatically populate information like title, author, and even the cover photo for you.

= Increase Traffic =
Book Review can help increase traffic to your site by making your Google search result stand out from the rest. And that means more users clicking through to visit your site.

See the [*Screenshots* tab](https://wordpress.org/plugins/book-review/screenshots/) for an example of what your Google search result might look like.

= Monetize Your Site =
If you’re interested in throwing monetization into the mix, Book Review can help with its custom links feature. Just enter the affiliate URLs for Amazon, Barnes & Noble, or any other online store, and Book Review will take care of adding the links to each of your reviews.

= Review More Than Just Books =
One of the most powerful features of Book Review is the ability to add custom fields to each of your reviews. Custom fields enable you to review movies, music, TV shows and so much more!

[Learn more about Book Review](http://wpreviewplugins.com/product/book-review/#utm_source=wordpress.org&utm_medium=partner&utm_campaign=book+review&utm_content=description)

= Internationalization =
This plugin supports the following translations (with credit to the translators):

* Arabic (منهل العدّاي‎)
* Chinese (Vahi Chen)
* Czech (Radek Volf)
* Dutch (Petran Liket)
* French (Guillaume Andreux)
* German (Linguasoft)
* Indonesian (Ardhi Sulaeman)
* Italian (James Garofalo)
* Norwegian (Harald Indgul)
* Portuguese (Wilson Rocha)
* Russian (Alexander Wolf)
* Serbian ([Ogi Djuraskovic](http://firstsiteguide.com/))
* Spanish (Jose Luis Parra)
* Swedish (Harald Indgul)
* Turkish (Atilla Öntaş)

If you would like to translate Book Review into another language, please see the instructions in the [documentation](http://wpreviewplugins.com/documentation/translate-book-review/).

= Resources =
* Official documentation for Book Review can be found at [WP Review Plugins](http://wpreviewplugins.com/documentation/).
* If you have problems, questions or suggestions, please post them to the [Book Review Support](http://wpreviewplugins.com/support/forum/general-support/) forum.
* For a comprehensive list of feature requests, or to vote for your favorites, please see the [Book Review Roadmap](https://trello.com/b/rlglE0Gf/book-review-roadmap).
* You can submit your own requests in the [Feature Requests forum](http://wpreviewplugins.com/support/forum/feature-requests/).
* Follow me on [Google+](https://plus.google.com/u/0/+DonnaPeplinskie/posts), [Twitter](https://twitter.com/donnapep) or [LinkedIn](http://www.linkedin.com/in/donnapeplinskie).

= About Me =
* I’m the founder of [WP Review Plugins](http://wpreviewplugins.com/), a company specializing in creating review plugins for WordPress.
* I blog about web and professional development at [donnapeplinskie.com](http://donnapeplinskie.com/).
* I'm an avid reader and a fan of young adult fiction.

== Installation ==

1. In WordPress, go to *Plugins* > *Add New*.
1. In the *Search Plugins* field, enter "Book Review".
1. Click *Install Now* to install the plugin.
1. Click *Activate Plugin* to activate the plugin.
1. Configure the settings by going to *Settings* > *Book Review*.

OR

1. Download the plugin and extract it.
1. Upload the `book-review` folder to the `/wp-content/plugins/` directory on your server.
1. Activate the plugin through the *Plugins* menu in WordPress.
1. Configure the settings by going to *Settings* > *Book Review*.

== Frequently Asked Questions ==

= Why do I receive an error message when clicking on the Get Book Info button? =

Please follow these steps to resolve the error:

1. Check that you have created a [Google API Key](http://wpreviewplugins.com/documentation/settings-advanced/), and that it has been entered correctly on the *Advanced* tab of the *Book Review Settings*.
1. Ensure that you have selected an appropriate value from the *Country* dropdown on the *Advanced* tab of the *Book Review Settings*.
1. Double-check that you have entered your server's IP address correctly in the [Google Developers Console](https://code.google.com/apis/console).
1. Try removing the IP address altogether and wait a few minutes before trying again.
1. If all else fails, please leave a message in the [Book Review Support](http://wpreviewplugins.com/support/forum/general-support/) forum. Be sure to include your website's URL and the IP address in your post.

= What is the Synopsis field for? =

The *Synopsis* field is meant to hold the summary or description of the book. It is not where you are intended to write your review. You should write your review in the WordPress editor at the top of the page, although if you prefer you can certainly write it inside the *Synopsis* editor instead. Be aware that if you do that, the custom links will show at the very bottom of your post, rather than directly below the book's description and cover image.

== Screenshots ==

1. Settings - Appearance
2. Settings - Rating Images
3. Settings - Links
4. Settings - Custom Fields
5. Settings - Advanced
6. Book Info
7. Sample Post
8. Archives by Title
9. Archives by Genre
10. Google Search Result

== Changelog ==

= 2.3.9 =
* Fix: Fix settings not displaying for PHP 7.1.x or higher.

= 2.3.8 =
* New: Remove admin notice that is shown when the plugin is activated.
* New: Remove link to Affiliate Linkalizer for Amazon on *Links* settings tab.
* Tweak: Remove call to `is_main_query` when displaying book details.
* Fix: Strip dashes in ISBN numbers before sending request to Google Books API.
* Fix: Don’t add CSS `border-style` property unless border width is > 1.

= 2.3.7 =
* Fix: Restore missing CSS files.

= 2.3.6 =
* New: Add Turkish translation.
* Fix: Fix countries not being translated on the *Advanced* tab.

= 2.3.5 =
* Fix: Update plugin homepage link.

= 2.3.4 =
* New: Add *Site Links* section to the *Links* settings tab to facilitate adding Goodreads and/or Barnes & Noble links.
* Tweak: Optimize Javascript and CSS files.
* Fix: Fix an issue where the review box could potentially be shown in undesirable locations.

= 2.3.3 =
* Tweak: Updated error message when retrieving book info.
* Tweak: Added documentation links to *Rating Images* and *Custom Fields* tabs.
* Tweak: Removed "by" in front of author name in archives.

= 2.3.2 =
* Fix: Add a new link in the *Book Review Settings*.

= 2.3.1 =
* New: Add new `book_review_links_meta` filter for returning links meta used in the *Book Info* meta box.
* Fix: Change `book_review_links` filter to return links HTML.

= 2.3.0 =
* New: Add support for custom fields.
* Tweak: Improved validation when saving settings and post meta.
* Tweak: Add filters when retrieving post meta.
* Tweak: Add filters when saving and retrieving settings.
* Fix: *Include post in archives* now saves when not checked.

= 2.2.3 =
* Tweak: Update admin notice that shows when plugin is first activated.

= 2.2.2 =
* New: Add Dutch translation.
* Tweak: Internationalize countries on *Advanced* tab.
* Fix: Fix *Format* not showing in review box.

= 2.2.1 =
* New: Add Serbian translation.
* New: Add `book_review_meta_box` hook for when *Book Info* meta box is added.
* Tweak: Update website links.
* Fix: Fix broken translation string on *Advanced* tab.

= 2.2.0 =
* New: Add ability to select post types to show book information for.
* Tweak: Remove Release Date Format field. Format is now controlled via the Date Format field in Settings > General.

= 2.1.14 =
* New: Add Country dropdown to Advanced tab of Book Review settings.
* Tweak: Apply WordPress CSS class names to input elements.
* Fix: Fix 403 error from Google Books API for some users.

= 2.1.13 =
* New: Add dismissible admin notice when plugin is first activated.
* New: Add link to Google Developers Console text on Advanced tab.

= 2.1.12 =
* New: Add Indonesian translation.
* New: Add `book_review_links` filter for rendering links in review box.
* Tweak: Eliminate use of `extract` function.
* Tweak: Don't close `<input>` or `<img>` tags.
* Fix: Escape all variables.
* Fix: Links defined in the *Book Info* meta box were not being removed when cleared.
* Fix: Spinner in *Book Info* meta box for WordPress 4.2 and higher.

= 2.1.11 =
* New: Added Swedish & Norwegian translation files.
* Fix: Fixed issue with styling of meta box for custom post types.
* Fix: Fixed issue processing the Google Books API response when some fields are not present.

= 2.1.10 =
* Fix: Fixed issue with rating images not showing for PHP versions older than 5.3.0.

= 2.1.9 =
* Added Review Box Border Width setting.
* Removed tooltips from Book Review Settings.
* Updated error message that displays when unable to retrieve book info.
* Updated links throughout plugin.

= 2.1.8 =
* Fixed data in Book Info section not updating when field cleared.
* Restructured code to conform to WordPress Plugin Boilerplate 3.0.

= 2.1.7 =
* Fixed broken schema markup so that ratings, author and published date show in a search engine results page.

= 2.1.6 =
* Changed Book Review Settings to be a tabbed interface.
* Removed limit of only being able to configure 5 custom links.
* Added ability to set individual custom links to inactive.
* Added custom hooks for developers.
* Added Czech translation files.

= 2.1.5 =
* Renamed Arabic translation files.

= 2.1.4 =
* Added Arabic & French translation files.
* Fixed bug with Google Books API text not translating.

= 2.1.3 =
* Added German translation files.

= 2.1.2 =
* Fixed some text not translating on the Book Review Settings page.
* Added Russian translation files.

= 2.1.1 =
* Refactored some of the code.
* Added Chinese translation files.

= 2.1.0 =
* Added support for schema.org.
* Cover image in archives now links to related post.

= 2.0.2 =
* Added Spanish translation files.
* Bug fixing - Fixed issue with URLs not saving for posts.

= 2.0.1 =
* Bug fixing - Removed obsolete public-facing Javascript and CSS.

= 2.0 =
* Added ability to auto-populate a book's details using the Google Books API.
* Added ability to format the Release Date.
* Refactored entire codebase.

= 1.9 =
* Added Rating column to the manage posts screen.

= 1.8 =
* Added support for custom post types.

= 1.7 =
* Added ability to show book cover thumbnails and rating images in archives.

= 1.6 =
* Bug fixing - Archives now work with multisite.

= 1.5 =
* Added Italian translation files.

= 1.4 =
* Added support for internationalization.
* Bug fixing - Ignore case when sorting archives by title.

= 1.3 =
* Added a shortcode for showing archives by title or genre.

= 1.2 =
* Added new *Review Box Position* setting.
* Renamed *Summary* field to *Synopsis* to reduce confusion.

= 1.1 =
* New Fields
    * Added optional *Genre*, *Format* and *Pages* fields.
* Bug Fixing
    * Included the book info above the post's content on the home page if Full Text is being displayed.
    * Included the book info in the RSS feed.

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 2.1.12 =
Addressed some security issues. Upgrade highly recommended.

= 2.1.6 =
Changed Book Review Settings to be a tabbed interface.
Removed limit of only being able to configure 5 custom links.
Added ability to set individual custom links to inactive.
Added custom hooks for developers.
Added Czech translation files.

= 2.0 =
Added ability to auto-populate a book's details using the Google Books API.
Added ability to format the Release Date.
Refactored entire codebase.
