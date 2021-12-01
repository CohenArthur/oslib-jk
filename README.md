# oslib-jk

OS specific library for the jinko programming language.

# __WARNING__

This library is currently only available on linux!

# Usage

Add the following line to your script in order to use this library:

```
incl oslib
```

# Adding an OS

In order to add a new OS to the list of supported OSes, the OS-specific library should
define the following functions:

|Name|Description|
|---|---|
|`shell_execute_string`|Execute a command string using the OS's shell environment and return an integer exit code|

OS specific libraries are directories located in the root directory and named `<os>_jk/`
