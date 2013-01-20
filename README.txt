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

- disable synonyms when synonyms are disabled for a given vocabulary (global setting) - use join on vocabulary ID
- add an option to use tooltips field OR description,

Tests:

- test if main term is too long but its synonyms are ok
- also test if tooltips are generated
- also test if tooltips aren't duplicated if terms are appearing more than one time

- add an option for content type or content type / content field selection (e.g. 'articles only'),
- add an option for generating virtual terms with names containing all parent terms joint,
- add an option for case insensitive matching,
- add an option for case insensitive matching of first letter only,
- add JS for tooltips,

- change DOM parser to faster.

Tooltips:

- http://lamovo.com/support/the-tooltip
- http://jqueryfordesigners.com/coda-popup-bubbles/
- http://craigsworks.com/projects/qtip
- http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/  ***
- http://craigsworks.com/projects/simpletip/#  **

- bs: automatyczna bibliografia do newsa czy artykułu
- bs: dodać RSS z polskimi (np. CERT, zaufana3strona) do kokpitu 

