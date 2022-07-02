# Default Theme Template

A packaged version of the Pale Moon Default Theme, including OS-specific styling and other niceties third-party themes have been known to come with. Use this as a base for making your own theme.

## Building
Simply download the contents of the "src" folder  and pack the contents into a .zip file. Then, rename the file to .xpi and drag into the browser.

On Unix systems (or Windows 10, with [WSL](https://docs.microsoft.com/en-us/windows/wsl/about)) you can optionally run `build.sh` instead. Running this as-is will produce a .xpi file ending in `-dev`, and if run from the command line and appending a number (e.g. `./build.sh 2`) will append that number to the filename instead.

## Download
You can grab the latest release from the Releases section of this repository.
