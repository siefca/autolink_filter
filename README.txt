Autolink Filter
===============

Adds a filter to automatically link known taxonomy terms from selected vovabularies.

== Features ==

 * Term phrases support (terms consisting of multiple words)
 * Tooltips generation support (based on a tooltip field or a description field)
 * Taxonomy synonyms support
 * First letter of a sentence awareness when matching
 * Various filtering options:
  * Exclusion of specific words
  * Exclusion based on HTML enclosing tags
  * Exclusion based on HTML enclosing classes
  * Exclusion based on minimum and maximum length of a word
  * Adjustable limit of links for single term instances (including synonyms)
  * Adjustable limit of links for single word instances
  * Explicite inclusion of terms (with optional field added to taxonomy terms)
  * Children-only filtering mode (uses only leaves of taxonomy tree)

== TODO ==

- take care of leaves filtering manually (dpm on load)

- add an option for case insensitive matching,
- add an option for case insensitive matching of first letter only,
- change DOM parser to faster (that allows to memorize data in objects to shorten paths - cache misses and hits).

Tests:

- test if main term is too long but its synonyms are ok

- add JS for tooltips,

Tooltips:

- http://lamovo.com/support/the-tooltip
- http://jqueryfordesigners.com/coda-popup-bubbles/
- http://craigsworks.com/projects/qtip
- http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/  ***
- http://craigsworks.com/projects/simpletip/#  **
