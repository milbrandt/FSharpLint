##### 0.13.1.1 (Backport of 0.13.3) - February 25 2020

* Fix for suppression comment parsing

##### 0.13.1

* Use structured comments for warning suppression
* Use Argu library for command line argument parsing

##### 0.13.0 - February 20 2020

* Add `-format` flag to specify output format (standard or MSBuild).

##### 0.12.10 - January 23 2020

* Return non-zero error code when there are lint warnings

##### 0.12.9 - January 23 2020

* Fix linting of solution in non-Windows systems

##### 0.12.8 - January 13 2020

* Pass release configuration to dotnet proj info

##### 0.12.7 - January 7 2020

* Add `-c` flag for specifying MSBuild release configuration

##### 0.12.6 - December 5 2019

* Update FCS to 33.0 [@baronfel]

##### 0.12.5 - October 7 2019

* Addressed issue: <https://github.com/fsprojects/FSharpLint/issues/367> [@jrr]

##### 0.12.4 - October 5 2019

* Update FCS to 32.0 [@Krzysztof-Cieslak]

##### 0.12.3 - August 15 2019

* Update FCS to 31.0 [@baronfel]

##### 0.12.2 - July 3 2019

* Add API to convert XmlConfiguration to new config type [@milbrandt]
* Ignore active patterns in PublicValues naming conventions rule
* Update FCS to 30.0 [@baronfel]
* Use Newtonsoft.Json for config parsing

##### 0.12.1 - May 31 2019

* Implement linting of all projects in solution using `-sol` flag, or programmatically using `lintSolution` function
* Return non-zero exit code if lint warnings exist
* Fix bug in converting XML config with no hints defined
* Add `XmlConfiguration.tryLoadConfigurationForProject` to support backwards compatability in external applications

##### 0.12.0 - May 29 2019

* Update `FSharp.Compiler.Service`

##### 0.11.1 - May 14 2019

* Fix issue in loading default configuration

##### 0.11.0 - May 14 2019

* Add ability to disable previously defined hints
* Ignore members implementing interface when checking member naming
* Change config from XML to JSON
* Refactor and redesign linter internals

##### 0.10.8 - April 1 2019

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/323,> by jgardella
* Update `FSharp.Compiler.Service`, by enricosada

##### 0.10.7 - February 26 2019

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/304>

##### 0.10.6 - February 26 2019

* Update `FSharp.Compiler.Service`

##### 0.10.5 - February 13 2019

* Update `FSharp.Compiler.Service`, by baronfel

##### 0.10.4 - February 11 2019

* Improve tuple item spacing check, by jgardella
* Ignore pattern matching in function parameters, by jgardella
* Fix using FSharpLint.Core targeting `net`, by enricosada
* Fix match indentation calculation, by jgardella
* Produce tuple type string correctly, by jgardella
* Fix false positive for tuple instantiation with cons operator, by jgardella
* Take comments into account when checking spacing, by jgardella

##### 0.10.3 - January 29 2019

* Update configuration defaults to exclude formatting rules for now.

##### 0.10.2 - December 20 2018

* API C# interop, thanks to [@jgardella](https://github.com/jgardella)
* Fix guard indentation in FormattingMatchExpressionIndentation rule, thanks to [@jgardella](https://github.com/jgardella)
* Command line interface improvements.

##### 0.10.1 - November 18 2018

* Pack console application as tool.

##### 0.10.0 - October 07 2018

* Move solution to dotnet core.

##### 0.9.1-beta - February 22 2018

* Fixed <https://github.com/fsprojects/FSharpLint/issues/256> by [@SteveGilham](https://github.com/SteveGilham)
* Fixed <https://github.com/fsprojects/FSharpLint/issues/252> by [@SteveGilham](https://github.com/SteveGilham)

##### 0.9.0 - January 28 2018

* .net standard 2.0 support, thanks to [@enricosada](https://github.com/enricosada)

##### 0.9.0-beta - October 19 2017

* .net standard 2.0 support, thanks to [@enricosada](https://github.com/enricosada)

##### 0.8.1 - October 10 2017

* Fixed <https://github.com/fsprojects/FSharpLint/issues/240>

##### 0.8.0 - September 05 2017

* Updated `FSharp.Compiler.Service`

##### 0.7.7 - August 20 2017

* Fixed <https://github.com/fsprojects/FSharpLint/issues/237>

##### 0.7.6 - July 02 2017

* Fixed <https://github.com/fsprojects/FSharpLint/issues/229>
* Fixed <https://github.com/fsprojects/FSharpLint/issues/227>
* Updated `FSharp.Compiler.Service`

##### 0.7.5-beta - March 31 2017

* Updated `FSharp.Compiler.Service`

##### 0.7.4-beta - March 03 2017

* Updated `FSharp.Compiler.Service`

##### 0.7.3-beta - February 23 2017

* Updated `FSharp.Compiler.Service`

##### 0.7.2-beta - February 23 2017

* Updated `FSharp.Compiler.Service`

##### 0.7.1-beta - February 20 2017

* Added suggestion for redundant usages of the `new` keyword.

##### 0.7.0-beta - February 12 2017

* Type checks performed at end of lint in parallel
* Linter now cancellable.

##### 0.6.5-beta - February 11 2017

* Updated `FSharp.Compiler.Service`
* New hints by [@ErikSchierboom](https://github.com/ErikSchierboom)

##### 0.6.4-beta - January 30 2017

* Updated `FSharp.Compiler.Service`

##### 0.6.3-beta - January 22 2017

* Improved performance of naming analyser.

##### 0.6.2-beta - January 21 2017

* Added suggested fixes for naming rules.
* New hint by [@smoothdeveloper](https://github.com/smoothdeveloper): <https://github.com/fsprojects/FSharpLint/pull/207>

##### 0.6.1-beta - January 17 2017

* Naming rules now customisable thanks to [@Krzysztof-Cieslak](https://github.com/Krzysztof-Cieslak).

##### 0.5.1-beta - December 31 2016

* Introduced automated fix information to API.

##### 0.4.12 - November 16 2016

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/191>

##### 0.4.11 - November 10 2016

* Bug fixed by [@rexcfnghk](https://github.com/rexcfnghk): <https://github.com/fsprojects/FSharpLint/issues/189>

##### 0.4.10 - October 24 2016

* Updated FSharp.Compiler.Service

##### 0.4.9 - October 8 2016

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/184>

##### 0.4.8 - September 13 2016

* Updated wording of warnings.
* Disabled `RecordFieldNamesMustBePascalCase` naming rule by default.

##### 0.4.7-beta - September 9 2016

* Included FSharp.Core.sigdata and FSharp.Core.optdata in the FSharpLint.MSBuild package.

##### 0.4.6 - August 21 2016

* Bug fixed by [@Krzysztof-Cieslak](https://github.com/Krzysztof-Cieslak): <https://github.com/fsprojects/FSharpLint/issues/172>

##### 0.4.5 - August 5 2016

* Added missing app.config file to FSharpLint.MSBuild package

##### 0.4.5-beta - August 4 2016

* Run linter in separate AppDomain in MSBuild package so that we can add binding redirects to get the correct version of FSharp.Core

##### 0.4.4 - July 23 2016

* Fixed structure of FSharpLint.MSBuild package

##### 0.4.3 - July 23 2016

* Updated FSharp.Compiler.Service

##### 0.4.2 - July 16 2016

* Fixed name convention bug which warned for DU names inside patterns.

##### 0.4.2-beta - July 14 2016

* Added required project cracker files to FSharpLint.Fake package.

##### 0.4.1-beta - July 09 2016

* Updated FSharp.Compiler.Service
* Brought back configuration manager api.
* Targets FSharp.Core 4.4.0.0

##### 0.4.0-beta - June 26 2016

* Added initial dotnet core support.

##### 0.3.0-beta - June 19 2016

* Improved overall performance of linter.
* Updated default configuration to have opinionated rules off by default.

##### 0.2.7 - September 27 2015

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/126>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/125>
* Added feature - now able to write a message as a suggestion in hints: <https://github.com/fsprojects/FSharpLint/issues/117>
* Added feature - nulls can now be matched against in hints: <https://github.com/fsprojects/FSharpLint/commit/89050c3bc6020477b3b9d50a4ce541aa09b9a270>
* Fixed bug - lambda length warnings would be repeated for each argument: <https://github.com/fsprojects/FSharpLint/commit/bc49dd6d58ebbbe8f2cdb4857e011fcaf14d9982>
* Enhancement - display operators as symbols in eta reduction suggestions: <https://github.com/fsprojects/FSharpLint/commit/1b2f115e71b560ccf8019ef5f14df79f0fd62201>
* Enhancement - updated warning messages: <https://github.com/fsprojects/FSharpLint/commit/49e579ca35de70902def6bb30835593140be7abd>
* Partially fixed bug (fixed when type checking enabled): <https://github.com/fsprojects/FSharpLint/issues/113>
* Partially fixed bug (fixed when type checking enabled): <https://github.com/fsprojects/FSharpLint/issues/109>
* Configuration can now be written back to XML.
* Configuration API updated to provide management of configuration files.

##### 0.2.6 - July 18 2015

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/108>
* `Default` property now static: <https://github.com/fsprojects/FSharpLint/pull/107>

##### 0.2.5 - July 7 2015

* FSharp.Core.dll is now included again

##### 0.2.4 - July 6 2015

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/101>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/100>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/99>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/103>

##### 0.2.3 - July 2 2015

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/98>

##### 0.2.2 - June 9 2015

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/97>
* XmlDoc rules now configurable to apply to code with certain access levels e.g. private or public. Thanks goes to Jon Hamm for implementing this feature

##### 0.2.1 - May 31 2015

* Included FSharp.Core
* Fixed bug where hints would accidentally match named parameters and property initialisers

##### 0.2.0 - May 31 2015

* Configuration has been updated to be simpler and verifiable via an XSD.
* Type checking is now optional and off by default to speed up the linting.
* More XML documentation rules have been added thanks to [jhamm](https://github.com/jhamm)
* Files can now be ignored by specifying git ignore like globs in the configuration file.
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/78>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/90>

##### 0.1.16 - March 11 2015

* Handling of project files is now performed by FSharp.Compiler.Service

##### 0.1.15 - February 08 2015

* Added `Enabled` config option to all analysers.

##### 0.1.14 - January 18 2015

* Added a new rule `CanBeReplacedWithComposition` to the `FSharpLint.FunctionReimplementation` analyser: <http://fsprojects.github.io/FSharpLint/FSharpLint.FunctionReimplementation.html>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/63>

##### 0.1.13 - January 11 2015

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/63>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/57>
* Files can now be ignored via the .fsproj file: <https://github.com/fsprojects/FSharpLint/issues/55>
* FAKE task now reports on how many files were linted and how many warnings were found.
* FAKE task now includes more detailed information on failure.
* FAKE task now includes an option to fail the build if any warnings are found.

##### 0.1.12 - December 16 2014

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/57>

##### 0.1.11 - November 23 2014

* FSharp.Compiler.Service now included as a strongly named assembly.
* TargetFrameworkVersion now taken from the project file: <https://github.com/fsprojects/FSharpLint/issues/52>

##### 0.1.10 - November 19 2014

* Dropped MSBuild tools back down from 12 to 4 to support VS2010

##### 0.1.9 - November 17 2014

* Updated `FSharp.Compiler.Service` for compatibility with VisualFSharpPowerTools: <https://github.com/fsprojects/FSharpLint/issues/51>

##### 0.1.8 - November 15 2014

* FSharp.Core lookup now supports F# 4, the package is now a single click install in VS 2015 preview

##### 0.1.7 - November 14 2014

* Added support for SuppressMessageAttribute for the Typography analyser
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/48>
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/47>
* Attempted to fix assembly resolution issues by including FParsec built against FSharp.Core 4.3.0.0
* Added FAKE task to the nuget package

##### 0.1.6 - October 25 2014

* Added `FSharpLint.Binding.TupleOfWildcards` rule
* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/38>

##### 0.1.5 - October 24 2014

* Added support for `SuppressMessageAttribute` for all analysers except `FSharpLint.Typography`
* Added FAKE task, thanks to [@archaeron](https://github.com/archaeron) for this contribution

##### 0.1.4 - October 21 2014

* Fixed bug: <https://github.com/fsprojects/FSharpLint/issues/36>

##### 0.1.3 - October 16 2014

* Implemented new analyser: `FSharpLint.RaiseWithTooManyArguments`
* Implemented new rule: `FSharpLint.Binding.WildcardNamedWithAsPattern`

##### 0.1.2 - October 14 2014

* More hints and support added for matching if statements, tuples, lists, array, and patterns with hints

##### 0.1.1 - September 28 2014

* Fixed bug: literals in pattern matches were generating lint warnings saying that they should be camel case, whereas they must be pascal case.

##### 0.1.0 - September 25 2014

* First release
