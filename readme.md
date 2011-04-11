README for Save Me
===============
Save and search through articles that you bookmark.  I wanted something like pinboard.in or historio.us
that can save bookmarks and saves the content of the bookmark, allowing you to search through it.

Requirements
------------
- CodeIgniter 2.0.1
- [php-readability](https://github.com/feelinglucky/php-readability)
- [Tank Auth](http://konyukhov.com/soft/tank_auth/)

Instructions
-------------
1.  Put Readability.inc.php in controllers folder
2.  Run database.sql
3.  Edit config/autoload.php
	3.1  `$autoload['libraries'] = array('database');`
	3.2  `$autoload['helper'] = array('url');`
4.  Install Tank Auth

TODO
----
1.  More MVC: make article into a model
2.  Check for duplicate urls before inserting into database
3.  Finish design