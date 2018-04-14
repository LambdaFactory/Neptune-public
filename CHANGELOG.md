### 1.1.2 - 14.04.2018
* Fix test reporting for NUnit's TestSource
* Add icon for `Go to test` command
* Fix test reporting for NUnit/XUnit tests ending with `(Some text)`

### 1.1.0 - 11.04.2018
* Add support for NUnit's TestSource
* Add `Go to test` command to command palette
* Add display mode that uses also projects and files
* Add commands to run tests in particular project or file

### 1.0.8 - 01.04.2018
* Expecto test detection - don't treat `failtest` and `skiptest` helpers as a functions
* Expecto test detection - add support for `test` CE test cases
* Create outnput channel for Expecto
* Fix bug in error message aggregation for Expecto runner

### 1.0.7 - 01.04.2018
* Add support for FsCheck attributes

### 1.0.6 - 29.03.2018
* Make sure tests are not detected multiple times by different detectors.

### 1.0.5 - 29.03.2018
* Fix problem with running XUnit test for Full Framework, old style projects.

### 1.0.2 - 28.03.2018

* Initial release
* Support for NUnit, XUnit and Expecto
* Support for .Net Framework and .Net Core
* Tree Explorer
* Integration with VSCode decorations and error panel
* CodeLenses for running and debugging tests
