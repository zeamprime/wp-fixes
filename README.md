Fixes for Word Press
====================

This is a fix to add MySQLi support to WordPress 2.7.  It's based on code someone else first wrote (see the comments for details) but improved for safety and updated to work with WP 2.7.

I did a quick Google search and found a WordPress support forums topic that also has a similar solution for WP 2.7.1. (http://wordpress.org/support/topic/mysqli).  At the time I wrote this there was not good working solution, so the best I could do was fix the example I found.

This db.php file should be installed in /path/to/blog/wp-content/db.php where WP will know to find it.

I have not done any work on this past WP 2.7.0 since I've been playing with my own blogging software since then (which is not very good presently but is very similar in concept to Jekyll).

