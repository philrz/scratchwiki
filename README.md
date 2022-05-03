# scratchwiki

test

For this primer we'll work with pull requests on this public repository via the
[Github API](https://docs.github.com/en/rest/reference/pulls#list-pull-requests).
Let's create a pool to store this data and use the field `created_at` as the
pool key, sorted in descending order:
