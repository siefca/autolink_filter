Autolink Filter
===============

Adds a filter to automatically link known taxonomy terms from selected vovabularies.

== Features ==

 * Term phrases support (terms consisting of multiple words)
 * Tooltips generation support (based on a tooltip field or a description field)
 * Taxonomy synonyms support
 * Virtual synonyms support (terms consisting of other terms in taxonomy paths and their synonyms)
 * First letter of a sentence awareness when matching
 * Various filtering options:
  * Exclusion of specific words
  * Exclusion based on HTML enclosing tags
  * Exclusion based on HTML enclosing classes
  * Exclusion based on minimum and maximum length of a term (or a virtual term)
  * Adjustable limit of links for single term instances (including synonyms)
  * Adjustable limit of links for single word instances
  * Explicite inclusion of terms (with optional field added to taxonomy terms)
  * Explicite rejection of terms (with optional field added to taxonomy terms)
  * Children-only filtering mode (uses only leaves of taxonomy tree)

== TODO ==

- change DOM parser to faster (that allows to memorize data in objects to shorten paths - cache misses and hits).
- add an option for skipping terms that have no description at all (field_autolink does that?)
- add JS for tooltips

Tooltips:

- http://lamovo.com/support/the-tooltip
- http://jqueryfordesigners.com/coda-popup-bubbles/
- http://craigsworks.com/projects/qtip
- http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/  ***
- http://craigsworks.com/projects/simpletip/#  **
