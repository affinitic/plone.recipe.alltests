Changelog
=========

1.5 (unreleased)
----------------

- Nothing changed yet.


1.4 (2014-03-02)
----------------

- Flush stdout after printing status before and after running tests.

- Added ``exclude-groups`` and ``include-groups`` so entire package groups
  can be easily included or excluded from the test run.

- Added the ``default-policy`` setting which makes it possible to exclude
  packages by default, unless explicitly listed in ``include``.


1.3 - 2013-10-08
----------------

- Make it possible to run a single test group by specifying the --group= option.
  This can aid with debugging test isolation problems.
  [davisagli]


1.2 - 2009-11-06
----------------

- Refactor test summary somewhat to make it easier to parse.
  [hannosch]

- Exclude ``distribute`` by default from the test runs. Clarify that we always
  run tests for all dependencies of the packages listed in the eggs option.
  [hannosch]


1.1 - 2009-08-19
----------------

- Added bin/test as default for test-script option.  And [test]'s eggs (if the
  part is available) are used if the eggs option isn't specified explicitly.
  [reinout]


1.0 - 2009-08-02
----------------

- Added support for grouping multiple packages into one test group, avoiding
  some of the shared test setup cost.
  [hannosch]

- Added total test time to the output.
  [hannosch]

- Automatically extend the test path with the package location.
  [hannosch]

- Allow the use of regular expressions in the exclude list.
  [hannosch]

- Initial implementation.
  [hannosch]
