# wherearemycolleagues?

Our little group is made of RSEs that work on many different projects across the University. Although we are based in a specific office, we move a lot to meet our collaborators and it can be difficult to know where everybody is!

This is a simple Web API (Application Programming Interface) to tell the location of our members. So if your desperately need software research engineering expertise at the minute... you know where to run to!

# Available endpoints

|endpoint | Description |
| ------- | ------------|
|`GET /list` |Lists the IDs for all of the RSEs|
|`GET /location/$id`|Get the location of a single RSE|
|`GET /calendar/$id`|Get the calendar for a particular RSE|
|`GET /conference/$conf-id`|Get the calendar for a particular RSE|

# Example

```
$ curl https://rse-api.my-university.com/rse-api/list
  ["RSE-002", "RSE-443", "RSE-231"]
 
