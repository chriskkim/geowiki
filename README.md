# GeoWiki
Automatic Location Parser for Wikipedia. Demo available at http://geowiki.ckprototype.com.

# Technologies
Geowiki was built (and depends) on the following server-side technologies:

* Linux (Ubuntu)
* Apache
* PHP
* MySQL

# Notes
The following is the list of notable code snippets:

* Lines 19 to 150 in **/index.php**: identifying and hyperlinking geolocation tags in Wikipedia texts
* Lines 130 to 288 in **/js/script.js**: creating a plain text version of each Wikipedia text, and identifying various occurrences of each geolocation tag throughout the text