# wp comment get

Get data of a single comment.

### OPTIONS

&lt;id&gt;
: The comment to get.

[\--field=&lt;field&gt;]
: Instead of returning the whole comment, returns the value of a single field.

[\--fields=&lt;fields&gt;]
: Limit the output to specific fields. Defaults to all fields.

[\--format=&lt;format&gt;]
: Render output in a particular format.
\---
default: table
options:
  - table
  - csv
  - json
  - yaml
\---

### EXAMPLES

    # Get comment.
    $ wp comment get 21 --field=content
    Thanks for all the comments, everyone!


