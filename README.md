# Module Server Examples
Provides module examples for Module Server.

## Example Modules

| Location                | Name                                | Description                                                        |
| ----------------------- | ----------------------------------- | ------------------------------------------------------------------ |
| `/`                     | [NPM Module](#npm-module)           | Top-level NPM require that includes a single JS file               |
| '/no-submodule/'        | [No Submodules](#no-submodules)     | An NPM subdirectory that doens't require other modules.            |

### NPM Module

A top level module in a repository, that can be used to test NPM requires.  The module contains
a single JavaScript file that outputs a static string.

### No Submodules

A module in a subdirectory of an NPM module, that contains a single JavaScript file that outputs
a static string.
