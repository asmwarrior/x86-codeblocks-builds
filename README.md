[![main](https://github.com/asmwarrior/x86-codeblocks-builds/actions/workflows/main64.yml/badge.svg)](https://github.com/asmwarrior/x86-codeblocks-builds/actions/workflows/main64.yml)

# General Introduction
Automatically built Code::Blocks binaries for both 32-bit and 64-bit Windows systems. You can always download the latest release at [Releases](https://github.com/asmwarrior/x86-codeblocks-builds/releases).

# Usage
Then extract the archive into a folder, and run the `CbLauncher.exe` in the `bin` folder.

Basically, the release package contains all the `exe` files and `dll` files need to run the Code::Blocks.
Also, it is recommanded that the `CbLauncher.exe` is executed instead of `codeblocks.exe`.
Because when you start Code::Blocks by running `CbLauncher.exe`, it is in portable mode, the settings will be stored in the same folder as `codeblocks.exe` in the sub-folder `AppData`.

# Note
The built Code::Blocks release has many my own patches, so please see the commit log here about my own patches:
[asmwarrior/codeblocks_sfmirror: Unofficial auto-updated GIT mirror of C::B repo in SourceForge. Does NOT accept patches nor pull requests.](https://github.com/asmwarrior/codeblocks_sfmirror/tree/master)
