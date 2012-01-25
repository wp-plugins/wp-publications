=== wp-publications ===
Contributors: monperrus
Tags: publications, research, academia
Stable Tag: trunk

== Description ==
wp-publications enables research groups and individuals to add publication lists in Wordpress. The publication lists are generated on the fly from bibtex files using [bibtexbrowser](http://www.monperrus.net/martin/bibtexbrowser). 

One just has to create a post/page containing a short code such as:

+ [wp-publications bib="mybibliography.bib" all=true] 
+ [wp-publications bib="mybibliography.bib" year=2011] 
+ [wp-publications bib="mybibliography.bib" author="Martin Monperrus"] 

One can also mix options:

+ [wp-publications bib="mybibliography.bib" all=true academic=true] 
+ [wp-publications bib="mybibliography.bib" year=2011 author="Martin Monperrus" academic=true] 

Notes:

1. The short code options exactly correspond to [bibtexbrowser](http://www.monperrus.net/martin/bibtexbrowser) queries.
1. The mybibliography.bib should be encoded in UTF-8 if diacritics are not LaTeX-escaped

== Installation ==

1. Activate the plugin through the 'Plugins' menu in WordPress
1. Download bibtexbrowser at http://www.monperrus.net/martin/bibtexbrowser.php.txt, copy it into wp-content/plugins/wp-publications/bibtexbrowser.php (without .txt) and chmod it to be readable by PHP
1. Create a post or a page with a short code such as  [wp-publications bib="publications.bib" all=true]