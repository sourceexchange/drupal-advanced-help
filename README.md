drupal-advanced-help
====================
The advanced help module allows module developers to store their help outside the module system, in pure .html files. The files can be easily translated simply by copying them into the right translations directory. The entire system can appear in a popup or not as the module prefers (and by taking away access to view the popups, a site can force the popups to not exist).

The system ties into Drupal's search system and is fully indexed, so the entire contents can be searched for keywords. the help files can be placed in a hierarchy as well, allowing for top down navigation of the help.

By itself, this module doesn't do much; it requires another module to support it, but it does come with a nice little sample of text from Wikipedia to demonstrate the system.
Accessing Advanced_help

When this module is installed, users with the view advanced help index permission can access the advanced help index by going to Administer -> Advanced Help (http://www.example.com/admin/advanced_help). Additional view advanced help popup and view advanced help topic permissions enable them to access the actual help pages and popups.
