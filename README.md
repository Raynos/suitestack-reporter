# suitestack-reporter

A reporter unit that supports mocha

## Example

    var test = require("suitestack"),
        reporter = require("suitestack-reporter")

    reporter("Spec", test)

    test("a test", function (test) {
        test("an inner test", function () {
            assert(true)
        })
    })