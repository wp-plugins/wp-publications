=== wp-publications ===
Contributors: monperrus
Tags: publications, research, academia, wp-publications, bibtexbrowser
Stable tag: trunk
Tested up to: trunk

== Description ==
wp-publications enables research groups and individuals to add publication lists in Wordpress. The publication lists are generated on the fly from bibtex files using [bibtexbrowser](http://www.monperrus.net/martin/bibtexbrowser). 

One just has to create a post/page containing a short code such as:

+ [wp-publications bib="sample.bib" all=true] 
+ [wp-publications bib="sample.bib" year=2001] 
+ [wp-publications bib="sample.bib" author="Doe"] 

One can also mix options:

+ [wp-publications bib="sample.bib" year=2001 author="Bar"] 

Notes:

1. The bibtex file is expected in directory at the root of the wordpress installation or in wp-content/plugins/wp-publications 
1. The short code options exactly correspond to [bibtexbrowser](http://www.monperrus.net/martin/bibtexbrowser) queries.
1. The mybibliography.bib should be encoded in UTF-8 if diacritics are not LaTeX-escaped
1. Please use complete refresh when uploading a new bibtex file (generally Ctrl-F5 or Shift-F5)

== Installation ==

1. Activate the plugin through the 'Plugins' menu in WordPress
1. Create a post or a page with a short code such as  [wp-publications bib="publications.bib" all=true]

== Credits ==

Sjoerd OP 'T LAND
Ayesh Alshukri