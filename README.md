# SophiaPlayroom
Where to put all [sophia](https://github.com/Strikingwolf/Sophia) packages

## Submitting
To submit a package to the playroom you must make a pull request. The structure of the PR must be:
* There is a json file with the name of your project
* The json file must be of the format displayed in the [sophia](https://github.com/Strikingwolf/SophiaPlayroom/blob/master/playroom/example.json) file

## Naming Rules
Packages can be named anything, however there are two rules for naming packages

1. The "first element" in the package name, should be controlled by a specific person or organization who registers it
2. nobody should ever check in a package whose path corresponds to a file in another repo

For example, it's ok for there to be a package emily.ffi.cpp, and a package emily.ffi.cpp.clang as long there's no clang file in emily.ffi.cpp

These rules are not enforced by Sophia! They are social rules and not adhering to them is bad practice.
