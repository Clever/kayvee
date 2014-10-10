kayvee
======

Kayvee translates an object into a human and machine parseable string, with a "key=val" format.

## Tests

The `tests.json` file is a specification for the methods supported by kayvee.

The `version` tag is used to track when this specification is modified, particularly notable if there are any breaking changes. It follows [semantic versioning](http://semver.org/).

Each test includes:

- `title` - describes what the test covers
- `input` - arguments to pass to the tested method
- `output` - expected output string, given above input

## Changelog

- v0.0.1 - Initial version
- v0.0.2 - 2014-10-10 - `format` test for "allows empty data"
- v0.0.3 - 2014-10-10 - `format` test cases for single-quote, double-quote
