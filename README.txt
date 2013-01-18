Adds a filter to automatically link known taxonomy terms.

== Features ==

 * words exclusion
 * HTML tag-based and class-based exclusion
 * manual inclusion when special boolean field is added to taxonomy terms
 * tooltips generation support based on tooltip field or description
 * taxonomy synonyms support

TODO:

- test if main term is too long but its synonyms are ok.
- also test if tooltips are generated
- also test if tooltips aren't duplicated if terms are appearing more than one time

- add setting for number of instances of a single term to be highlighted
- add setting for content type or content type / content field selection (e.g. 'articles only'),
- add class exclusion support (e.g. elements that are enclosed with some class are not highlighted),
- add an option to use tooltips field OR description,
- add JS for tooltips,
- in multiple words substitution allow first word to be matched case-insensitively,
- change DOM parser to faster.

Tooltips:

- http://lamovo.com/support/the-tooltip
- http://jqueryfordesigners.com/coda-popup-bubbles/
- http://craigsworks.com/projects/qtip
- http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/  ***
- http://craigsworks.com/projects/simpletip/#  **

