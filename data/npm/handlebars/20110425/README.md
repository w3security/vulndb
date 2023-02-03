## Overview
Previously, only < and > were escaped. This meant that any Handlebars template that used user input in an HTML attribute value was wide open to a trivial XSS exploit. Note that unquoted attribute values are still open to attack, but this set of characters at least brings Handlebars in line with other Mustache implementations and other template languages.

## References
- https://github.com/wycats/handlebars.js/pull/68
