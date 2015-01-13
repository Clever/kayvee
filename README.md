kayvee
======

Kayvee translates an object into a human and machine parseable string, with a "key=val" format.  Currently the format used is `json`.


## Implementations

 * [Go](https://github.com/Clever/kayvee-go)
 * [Javascript/Node](https://github.com/Clever/kayvee-js)
 * [Python](https://github.com/Clever/kayvee-python)

## Tests

The `tests.json` file is a specification for the methods supported by kayvee.

The `version` tag is used to track when this specification is modified, particularly notable if there are any breaking changes. It follows [semantic versioning](http://semver.org/).

Each test includes:

- `title` - describes what the test covers
- `input` - arguments to pass to the tested method
- `output` - expected output string, given above input

## Changelog

- v1.0.0 - 2014-12-09 - all formatting functions output stringified JSON - this an intermediate approach to ease string parsing and forwarding within Heka.
- v0.0.3 - 2014-10-10 - `format` test cases for single-quote, double-quote
- v0.0.2 - 2014-10-10 - `format` test for "allows empty data"
- v0.0.1 - Initial version
