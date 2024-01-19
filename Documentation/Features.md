# Features
With the new site, a lot of effort is going into remedying the shortcomings of the current website.  
For archive "features", check out the Archive Improvements document.

## Officially Supported Themes
* HTML 2.0 [Text Theme]
* HTML 3.2 [**Default Theme**]
* XHTML 1.0 [Theme ported from macintoshgarden.org]
* HTML 5.0 [Mobile]
* HTML 5.0 [Modern]

Each theme has different features, though the core experience remains the same.

## What the above means
The default theme offer a much lighter and faster browsing experience than ever before, miniscule amount traces of vanilla JS can be found which has zero impact on performance.

## Site Settings
Anonymous users and registered alike have access to the site settings via the menu, which offers the possibility of changing how the site look, feels and behaves!  

For registered users, this will mean that your settings will persist after logging in and applying the different settings, next time you log back on the settings are applied instantly.

In case one would want to reset any site settings made for whatever reason, a route called /reset will have to be called manually by the user - this will do things differently depending on if one is either logged in or browsing as an anonymous user. For anonymous users it will reset the session, cookies and all site settings; while for a logged in users it will do the same as well as reset the settings stored in the database to the website defaults.

## Control through subdomains
Graphics ain't your cup of tea? Apply the text subdomain and bypass the default theme / previous settings.

http://text.macintosh.garden

* The reset route can not be called from this subdomain, since there is nothing to reset to begin with.

## Other Features
* Access via HTTP, HTTPS (HTTP/2, HTTP/3, QUIC)
* Automatic fallback to the Text theme if a known text-based browser is detected
* Improved Quick Search with available prefixes
  * Search the archive for files
  * Search listed (website accessible) files
* Additional browsing / listing options.
* New (improved) Articles & Guides section
* New, from the ground up discussion board (site forums)
  * Bye-bye BBCode. Hello Markdown!
  * Mention users
  * Subscribe to threads
  * Offsite linked images automatically downloaded and cached
  * Improved new / unread / updated engine
* Fresh user functionality
  * Account control / ownership
   * Scrub account [equal to deleting digital footprint on website]
  * Friends system
  * Private messaging
  * Personal notepad
  * E-Mail notifications [disabled by default]
  * Page subscriptions, be notified when a page is updated
  * Forum subscriptions, be notified of replies or mentions
  * Improved guestbook
  * Stream access [twitter-like]
  * Personal profile
  * Privacy control
  * User blocking [staff not included]
  * Jabber Account
   * Create
   * Delete
   * Update
* Library
  * Books
  * Magazines
  * Videos
  * Audio
* DiskTracker database support
* DiskCatalogMaker database support
* User Hardware Compatibility Database (UHCD)
  * Title-bound user hardware compatibilty with software titles
  * Anyone can check the lists
  * Registered users can add to the lists
* Serials archive, for everything no longer sold or supported
* API (developers)
  * Application Data
  * Game Data
  * File Data
  * + More
