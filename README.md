# JSON-LD Module

Lightweight quick and easy to use JSON-LD Module for Drupal.

Has basic options for content types and general org rendering if they are not selected.

Follows standards as outline here: https://developers.google.com/search/docs/guides/mark-up-content

Config at: admin/config/search/json-ld

### Public functions:

#### Add output to the header:

```
json_ld_add_output($node);
```
This is useful if you are in a view or other multi node output situations.  the $node var is the fully loaded $node object.
