PR: Add `unused` to JSHint config

Also noticed that when running the tests from the CLI, `nojshint` is set to
`true`. This also seems to be the case for Travis.

It appears that the browser version of jshint currently in ember-dev is
not working. I have updated it to version 2.5.0