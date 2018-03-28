# Neptune - unit testing for VSCode

Visual Studio Code extension adding first class support for F# unit testing for both .Net Framework and .Net Core. Extension can be downloaded from [VSCode Extension Marketplace](https://marketplace.visualstudio.com/items?itemName=LambdaFactory.neptune).

**Neptune is paid extension, license can be bought on [product webpage](https://gumroad.com/l/NeptunePlugin). Downloading plugin from VSCode Extensions Marketplace you agree on our [License](LICENSE.md) and have access to 7 days, free evaluation period.**

![](Img/Screenshot%20from%202018-03-27%2000.32.40.png)

## Requirements

* VSCode (1.21.0+)
* Ionide-FSharp (3.18.0 +)
* C# extension (1.14.0 +)
* .Net Core (2.0.0 +)

## Current features

#### Integration with most popular test frameworks

* NUnit
* XUnit
* Expecto

#### Test explorer integrated with VSCode UI

![](Img/Screenshot%20from%202018-03-27%2000.26.58.png)

#### Debugging support (.Net Core only)

![](Img/Screenshot%20from%202018-03-27%2014.35.14.png)

#### CodeLenses for running and debugging single test or test list

![](Img/Screenshot%20from%202018-03-27%2000.41.55.png)

#### Showing test failures in VSCode error panel and editor ruler.

![](Img/Screenshot%20from%202018-03-27%2000.48.44.png)

## Support matrix

The below table represents current state of the support for different types of runtimes and different operating systems:

|                                  | Linux / MacOS | Windows |
| ------------- |:-------------:| -----:|
| **.Net Core**                        | Running and Debugging | Running and Debugging |
| **Full Framework, new project file** | Running (only Expecto) | Running |
| **Full Framework, old project file** | Running | Running |

The state of support is impacted by multiple 3rd part vendors - for example Debugging support is provided by C# extension team, or running XUnit and NUnit tests on full framework with new project file on Linux / MacOS is not possible due to [bug in `dotnet test`](https://github.com/Microsoft/vstest/issues/1284)
