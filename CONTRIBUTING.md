# How to contribute

You can contribute in many different ways, for example report a bug or come up with an idea for improvement. If you are good at programming you could also provide a fix for bugs or pull requests with improvements.

## Finding information

General information can be found in the Readme file at the root of the project. Developer-facing types live beside the copied CUE.NET, RGB.NET Corsair provider, Open CUE Service, and cuesdk Python sources.

## Writing code

This workspace consists of two major language tracks. C# covers native interop, LED groups, Game SDK HTTP handlers, and Corsair device providers. Python covers the ctypes CueSdk binding and device dump sample.

The examples only show how to use the libraries and what can be configured. Single parts, such as ProfileManager or CorsairDeviceProvider, can be used without shipping a full desktop suite, by calling the public API of these classes.

Public methods should stay documented. Always use descriptive names for variables, only use acronyms if they are well known and frequently used.

## Sketches and profiles

Lighting Protocol examples are used by most users as a template which they only modified slightly, so basic samples should stay simple. Game SDK profiles must be exported with lighting effects selected, and names must not be renamed after export.
