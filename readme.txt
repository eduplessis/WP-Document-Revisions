=== WP Document Revisions ===
Contributors: benbalter
Donate link: http://ben.balter.com/donate/
Tags: documents, uploads, attachments, document management, enterprise, version control, revisions, collaboration, journalism, government, files, revision log, document management, intranet, digital asset management, dam
Requires at least: 3.2
Tested up to: 3.4
Stable tag: 1.3.1

A document management and version control plugin that allows teams of any size to collaboratively edit files and manage their workflow.

== Description ==

[WP Document Revisions](http://wordpress.org/extend/plugins/wp-document-revisions/) is a [document management](http://en.wikipedia.org/wiki/Document_management_system) and [version control](http://en.wikipedia.org/wiki/Revision_control) plugin. Built for time-sensitive and mission-critical projects, teams can collaboratively edit files of any format -- text documents, spreadsheets, images, sheet music... anything -- all the while, seamlessly tracking the document's progress as it moves through your organization's existing workflow.

**WP Document Revisions is three things:**

1. A **document management system** (DMS), to track, store, and organize files of any format
2. A **collaboration tool** to empower teams to collaboratively draft, edit, and refine documents
3. A **file hosting solution** to publish and securely deliver files to a team, to clients, or to the public

[youtube http://www.youtube.com/watch?v=VpsTNSiJKis]

**Powerful Collaboration Tools** - *With great power does not have to come great complexity.* Based on a simple philosophy of putting powerful but intuitive tools in the hands of managers and content creators, WP Document Revisions leverages many of the essential WordPress features that, for more than eight years, have been tested and proven across countless industries -- posts, attachments, revisions, taxonomies, authentication, and permalinks -- to make collaborating on the creation and publication of documents a natural endeavor. Think of it as an [open-source and more intuitive version](http://ben.balter.com/2011/04/04/when-all-you-have-is-a-pair-of-bolt-cutters/) of the popular Microsoft collaboration suite, [Sharepoint.](http://sharepoint.microsoft.com/en-us/Pages/default.aspx)

**Document History** - At each step of the authoring process, WP Document Revisions gives you an instant snapshot of your team's progress and the document's history. It even gives you the option to revert back to a previous revision -- so don't fret if you make a mistake -- or receive updates on changes to the document right in your favorite feed reader.

**Access Control** - Each document is given a persistent URL (e.g., yourcompany.com/documents/2011/08/TPS-Report.doc) which can be private (securely delivered only to members of your organization), password protected (available only to those you select such as clients or contractors), or public (published and hosted for the world to see). If you catch a typo and upload a new version, that URL will continue to point to the latest version, regardless of how many changes you make.

**Enterprise Security** - Worried about storing propriety or sensitive information? WP Document Revisions was built from the first line of code with government- and enterprise-grade security in mind. Each file is masked behind an anonymous 128-bit [MD5 hash](http://en.wikipedia.org/wiki/MD5) as soon as it touches the server, and requests for files are transparently routed through WordPress's time-tested URL rewriting, authentication, and permission systems (which can even [integrate with existing enterprise active directory](http://wordpress.org/extend/plugins/active-directory-integration/) or [LDAP servers](http://wordpress.org/extend/plugins/simple-ldap-login/)). Need more security? WP Document Revisions allows you to store documents in a folder above the `htdocs` or `public_html` [web root](http://httpd.apache.org/docs/2.0/mod/core.html#documentroot), further ensuring that only those you authorize have access to your work.

**Customization** - WP Document Revisions recognizes that no two teams are identical, and as a result, molds to your firm's needs, not the other way around. Need to track additional information associated with a document? Departments, editors, issues, sections, even arbitrary key-value pairs -- whatever you can throw at it, it can handle. Development and customization costs are further minimized by its extensive plugin API, and the [WordPress Custom Taxonomy Generator](http://themergency.com/generators/wordpress-custom-taxonomy/) makes it easy for even the uninitiated to add custom  taxonomies to documents. Need an audit trail to track check-ins and check-outs? User-level permissions based on the document's state or another custom taxonomy? Support for third-party encryption? Check out the [WP Document Revisions Code Cookbook](https://github.com/benbalter/WP-Document-Revisions-Code-Cookbook) for sample code. Looking for even more advanced control of your workflow? WP Document Revisions will detect the popular workflow plugin [Edit Flow](http://editflow.org), if installed, and will automatically pull [Edit Flow’s advanced workflow management tools](http://ben.balter.com/2011/10/24/advanced-workflow-management-tools-for-wp-document-revisions/) into WP Document Revisions. Simply put, virtually every aspect of the plugin's functionality from workflow states to user-level permissions can be fully customized to your team's unique needs.

**Future Proof** - Switching costs a concern? WP Document Revisions is built with tomorrow's uncertainty in mind. Equally at home in an in-house server room as it is in the cloud, moving individual files or entire document repositories in and out of WP Document Revisions is a breeze (history and all). And since the software is open-source, you can easily add tools to automate the process of moving to or integrating with future third-party systems.

**The Vitals:**

* Support for any file type (docs, spreadsheets, images, PDFs -- anything!)
* Securely stores unlimited revisions of your business's essential files
* Provides a full file history in the form of a revision log, accessible via RSS
* Helps you track and organize documents as they move through your organization's existing workflow
* Each file gets a permanent, authenticated URL that always points to the latest version
* Each revision gets its own unique url (e.g.,TPS-Report-revision-3.doc) accessible only to those you deem
* Files are intuitively checked out and locked to prevent revisions from colliding
* Toggle documents between public, private, and password protected with a single mouse click
* Runs in-house or in the cloud
* Secure: filenames are hashed on upload and files are only accessible through WordPress's proven authentication system  
* Can move document upload folder to location outside of web root to further ensure government- and enterprise-grade security
* Documents and Revisions shortcodes, Recently Revised Documents widget
* Multisite and Windows (XAMPP) support
* French and Spanish language support (easily translated to your language)
* Integration with [Edit Flow](http://editflow.org)

**Features Available via the [Code Cookbook](https://github.com/benbalter/WP-Document-Revisions-Code-Cookbook):**

* **Audit Trail** - creates check in / check out audit trail for all documents
* **State Permissions** - allows setting user-level permissions based on a custom taxonomy such as workflow state or other document status
* **Third Party Encryption** - example of how to integrate at rest encryption using third-party tools
* **Rename Documents** - changes all references to "Documents" in the interface to any label of your choosing
* **State Change Notification** - how to use document api to allow users to receive notification whenever documents change workflow state
* **Bulk Import** - how to batch import a directory (or other list) of files as documents
* **Filetype Taxonomy** - Adds support to filter by filetype
* **Track Changes** - Auto-generates and appends revision summaries for changes to taxonomies, title, and visibility
* **Remove Workflow States** - Completely removes Workflow state taxonomy backend and UI
* **Change Tracker** - Auto-generates and appends revision summaries for changes to taxonomies, title, and visibility

**Translations:**

* French - [Hubert CAMPAN](http://omnimaki.com/)
* Spanish - [TradiArt](http://www.tradiart.com/) and [elarequi](http://www.labitacoradeltigre.com)

*WP Document Revisions was developed by a [law student and a business student](http://ben.balter.com) with a [grant from Google](http://code.google.com/soc/), and in close coordination with and under the watchful eye of WordPress.org's lead developers (Although neither relationship should imply an endorsement). Special thanks to Jon Cave, Aaron Jorbin, Mitcho Erlewine, and Andrew Nacin for their guidance.*

[Photo via [antphotos](http://www.flickr.com/photos/antphotos/3903433061/)]

== Links ==

* [Source Code](https://github.com/benbalter/WP-Document-Revisions/) (GitHub)
* [Development version](https://github.com/benbalter/WP-Document-Revisions/tree/develop) ([Build Status](http://travis-ci.org/#!/benbalter/WP-Document-Revisions))
* [Code Cookbook](https://github.com/benbalter/WP-Document-Revisions-Code-Cookbook)
* [Translations](http://translations.benbalter.com/projects/wp-document-revisions/) (GlotPres)
* [User support forums](http://wordpress.org/tags/wp-document-revisions)
* [Submit a bug/feature request](https://github.com/benbalter/WP-Document-Revisions/issues)

== Donate ==

Enjoy using WP Document Revisions? Please consider [making a small donation](http://ben.balter.com/donate/?utm_source=readme&utm_medium=donate&utm_campaign=wp-document-revisions) to support the project's continued development.

== How to Contribute ==

WP Document Revisions is an open source project and is supported by the efforts of an entire community. We'd love for you to get involved. Whatever your level of skill or however much time you can give, your contribution is greatly appreciated.

* **Users** - download the latest [development version](https://github.com/benbalter/WP-Document-Revisions/tree/develop) of the plugin, and [submit bug/feature requests](https://github.com/benbalter/WP-Document-Revisions/issues).
* **Non-English Speaking Users** - [Contribute a translation](http://translations.benbalter.com/projects/wp-document-revisions/) using the GlotPress web interface - no technical knowledge required ([how to](http://translations.benbalter.com/projects/how-to-translate)).
* **Developers** - [Fork the development version](https://github.com/benbalter/WP-Document-Revisions/tree/develop) and submit a pull request

== Useful Plugins ==

* [Members](http://wordpress.org/extend/plugins/members/)
* [Edit Flow](http://editflow.org)
* [Custom Taxonomy Generator](http://themergency.com/generators/wordpress-custom-taxonomy/)

== Screenshots ==
1. A typical WP Document Revisions edit document screen.

== Installation ==

= Automatic Install =
1. Login to your WordPress site as an Administrator, or if you haven't already, complete the famous [WordPress Five Minute Install](http://codex.wordpress.org/Installing_WordPress)
2. Navigate to Plugins->Add New from the menu on the left
3. Search for WP Document Revisions
4. Click "Install"
5. Click "Activate Now"

= Manual Install =
1. Download the plugin from the link in the top left corner
2. Unzip the file, and upload the resulting "wp-document-revisions" folder to your "/wp-content/plugins directory" as "/wp-content/plugins/wp-document-revisions"
3. Log into your WordPress install as an administrator, and navigate to the plugins screen from the left-hand menu
4. Activate WP Document Revisions

== Frequently Asked Questions ==

Please see the [Frequently Asked Questions Wiki](https://github.com/benbalter/WP-Document-Revisions/wiki/Frequently-Asked-Questions)

== Changelog ==

= 1.3.1 =
* Better permalink support for draft and pending documents
* Whenever possible browser will attempt to display documents in browser, rather than prompting with save as dialog (e.g., PDFs)
* Fix for function `get_file_type()` breaking the global `$post` variable when no document argument is supplied
* Improved Spanish translation with additional strings (special thanks, [elarequi](http://www.labitacoradeltigre.com))

= 1.3 =
* Plugin now includes unit tests to ensure security and stability, and [undergoes extensive testing](http://travis-ci.org/#!/benbalter/WP-Document-Revisions) (WordPress 3.2/3.3/Trunk, Multisite/single, PHP 5.3/5.4) via continuous integration service Travis CI prior to release.
* Translations now curated on [collaborative editing platform GlotPress](http://translations.benbalter.com/projects/wp-document-revisions/) if any user would like to submit a translation ([no technical knowledge necessary](http://translations.benbalter.com/projects/how-to-translate))
* If you would like to help out by testing early releases, please try the continuously updated [development version](https://github.com/benbalter/WP-Document-Revisions/tree/develop). Any [feedback](https://github.com/benbalter/WP-Document-Revisions/issues?direction=desc&sort=created&state=open), technical or prose is helpful.
* Added Spanish Translation Support (es_ES -- special thanks to [TradiArt](http://www.tradiart.com/))
* Document URL slug (used for archive and prefixing all documents) now customizable via settings page and translatable. (e.g., http://domain.com/documentos/2012/04/test.txt rather than /documents/)
* Subscribers and unauthenticated users no longer have the ability to read revisions by default (you can override this setting using the [Members plugin](http://wordpress.org/extend/plugins/members/).
* Attempts to access unauthorized files now properly respond with HTTP code 403 (rather than 500 previously). Note: attempting to access private documents will continue to result in 404s.
* Enhanced authentication prior to serving files now provides developers more granular control of permissions via `serve_document_auth` filter.
* Better Edit Flow support (can now toggle document support on and off using native Edit Flow user interface). Note: You may need to manually toggle on custom status support for documents after upgrading.
* Default document upload directory now honors WordPress-wide defaults and features enhanced multisite support
* Ability to separate documents on server by site subfolder on multisite installs

= 1.2.4 =
* Better support for custom document upload directories on multisite installs
* Gallery, URL, and Media Library links now hidden from media upload popup when uploading revisions
* Fix for plugin breaking media gallery when filtered by mimetype (MySQL ambiguity error)
* Fix for upload new version button appearing for locked out users in WordPress 3.3
* Fix for upload new version button not appearing after document lock override on WordPress 3.3

= 1.2.3 =
* Owner metabox no longer displays if user does not have the ability to `edit_others_documents`
* Fix for serving documents via SSL to Internet Explorer version 8 and earlier
* GPL License now distributed with plugin
* Code cleanup, minor bug fixes, and additional inline documentation

= 1.2.2 =
* Plugin [posted to Github](https://github.com/benbalter/WP-Document-Revisions) if developers would like to fork and contribute 
* Documents shortcode now accepts additional parameters. See the FAQ for a full list.
* Performance and scalability improvements to backend; files attached to documents are now excluded from media lists by join statements rather than subqueries
* If plugin is unable to locate requested file on server, standard theme's 404 template is served (rather than serving "404 -- file not found" via `wp_die()` previously) and E_USER_NOTICE level error is thrown. Diagnostic information will be available via debug bar (if WP_DEBUG is enabled) or in the standard PHP error log
* `/documents/` now supports pagination
* Support for linking to revisions with ugly permalinks
* Custom post type's `has_archive` property changed to `true` to help with theme compatibility
* Fix for fatal error when user without `read_document_revisions` capability called `wp_get_attachment_url()` on file attached to a revision
* Fix for broken permalink returned when get_permalink is called multiple times on the same document revision
* Fix for wp_get_attachment_image_src returning broken URLs or the direct path to the document
* Fix for "`Call-time pass-by-reference has been deprecated`" error when running certain versions of PHP
* General code cleanup

= 1.2.1 =
* French translation (Special thanks to [Hubert CAMPAN](http://omnimaki.com/))
* Enhanced support for running on WAMP systems (XAMPP, etc.)
* Improved integration with WordPress 3.3's new upload handler
* Significant performance improvements to `verify_post_type()` method
* Document requests no longer canonically 301 redirect with a trailing slash
* Fix for wp_get_attachment_url returning the attachment URL, rather than the document permalink when called directly
* Menu item now reads "All Documents" (rather than simply "Documents") for clarity
* Fix for E_WARNING level error on edit-tags.php with custom taxonomies
* Taxonomy counts (e.g., workflow states) now reflects non-published documents
* Better translation support (see the [FAQ](http://wordpress.org/extend/plugins/wp-document-revisions/faq/) if you are interested in translating the plugin into your language)
* Compatibility fix for WordPress SEO's "Clean Permalinks" mode

= 1.2 =
* Added shortcode to display list of documents meeting specified criteria
* Added shortcode to display a document's revisions (formerly in code cookbook)
* Added widget to display recently revised documents (formerly in code cookbook)
* Created new global `get_documents()` and `get_document_revisions()` functions to help build and customize themes and plugins
* Added filter to `wp_get_attachment_url` to force document/revision urls when attachments are queried directly
* Better organization of plugin files within plugin folder
* Fixed bug where revision summary would not display under certain circumstances 

= 1.1 =
* Added support for the [Edit Flow Plugin](http://wordpress.org/extend/plugins/edit-flow/) if installed 
* Added "Currently Editing" column to documents list to display document's lock holder, if any
* Added support for new help tabs in WordPress versions 3.3 and greater
* Fixed bug where media library would trigger an SQL error when no documents had been uploaded
* Fixed bug where owner dropdown on edit screen would only list "author" level users
* "- Latest Revision" only appended to titles on feeds

= 1.0.5 =
* Fixed bug where password-protected documents would not prompt for password under certain circumstances

= 1.0.4 =
* Significant performance improvements (now relies on wp_cache)
* Feed improvements (performance improvements, more consistent handling of authors and timestamps)
* Workflow States in documents list are now link to a list of all documents in that workflow state
* Changed "Author" column heading to "Owner" in documents list to prevent confusion
* If a revision's attachment ID is unknown, the plugin now defaults to the latest attached file, rather than serving a 404

= 1.0.3 =
* A list of all documents a user (or visitor) has permission to view is now available at yourdomain.com/documents/
* Changed functions get_latest_version and get_latest_version_url to "revision" instead of "version" for consistency
* Forces get_latest_revision to rely on get_revisions to fix inconsistencies in WP revision author bug
* Support for ugly permalink structures
* Changing metabox options does not enable the publish button on non-document pages
* Changing the title or other text fields enables the update button
* Fix for authors not having capability to edit documents by default
* No longer displays attachment ID when posts are queried via the frontend

= 1.0.2 =
* Fixed bug where RSS feeds would erroneously deny access to authorized users in multisite installs

= 1.0.1 =
* Better handling of uploads in WordPress versions 3.3 and above
* Added shadow to document menu icon (thanks to Ryan Imel of WPCandy.com)
* Fixed E_WARNING level error for undefined index on workflow_state_nonce when saving posts with WP_DEBUG on
* Corrected typos in contextual help dropdown
* Fixed permission issue where published documents were not accessible to non-logged in users
* Fixed last-modified author not displaying the proper author on document-edit screen

= 1.0 =
* Stable Release

= 0.6 =
* Release Candidate 1
* [Revision Log](http://gsoc.trac.wordpress.org/log/2011/BenBalter)

= 0.5 =
* Initial beta

= 0.1 =
* Proof of concept prototype

== Upgrade Notice ==

= 1.3 = 
* Spanish translation support, more granular permission control, more accurate HTTP headers, better Edit Flow support, better multisite support for custom upload directories, document slug now customizeable

= 1.2 =
* Widgets, shortcodes, and templating functions, oh my!

= 1.1 =
* Edit Flow support, bug fixes, ui improvements

= 1.0.5 =
* Fixed bug where password-protected documents would not prompt for password under certain circumstances

= 1.0.4 =
* Significant performance improvements, interface improvements, better feed handling, and bug fixes

= 1.0.3 =
* Minor improvements to revision handling, permalinks, permissions, the edit document screen, and front-end compatibility

= 1.0.2 =
* Fix for authentication of RSS feeds in multisite installs

= 1.0.1 =
* Minor fixes and improvements
