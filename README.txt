Adds a filter to automatically link known taxonomy terms.

== Features ==

 * words exclusion
 * HTML tag-based and class-based exclusion
 * explicite inclusion support with optional switch added to taxonomy terms
 * tooltips generation support based on tooltip field or description
 * term phrases support (multiple words as terms)
 * taxonomy synonyms support
 * min/max lengths filtering
 * optional children-only filtering (using only leaves of taxonomy tree)
 * uses various parsing algorithms for different types of terms
 * memory-friendly

TODO:

- fix interpolation when multiword term starts a sentence

- test if main term is too long but its synonyms are ok
- also test if tooltips are generated
- also test if tooltips aren't duplicated if terms are appearing more than one time

- add an option for number of instances of a single term to be highlighted
- add an option for content type or content type / content field selection (e.g. 'articles only'),
- add an option for generating virtual terms with names containing all parent terms joint,
- add an option for case insensitive matching,
- add an option for case insensitive matching for first letter only,
- add class exclusion support (e.g. elements that are enclosed with some class are not highlighted),
- add an option to use tooltips field OR description,
- add JS for tooltips,
- reload html if overlaping terms are detected,
- remove limits from sql if no values are present,
- change DOM parser to faster.

Tooltips:

- http://lamovo.com/support/the-tooltip
- http://jqueryfordesigners.com/coda-popup-bubbles/
- http://craigsworks.com/projects/qtip
- http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/  ***
- http://craigsworks.com/projects/simpletip/#  **

