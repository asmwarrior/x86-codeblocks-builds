[![main](https://github.com/asmwarrior/x86-codeblocks-builds/actions/workflows/main64.yml/badge.svg)](https://github.com/asmwarrior/x86-codeblocks-builds/actions/workflows/main64.yml)

# General Introduction
Automatically built Code::Blocks binaries for both 32-bit and 64-bit Windows systems. You can always download the latest release at [Releases](https://github.com/asmwarrior/x86-codeblocks-builds/releases).
## Usage
Install the following packages in msys2(64-bit users please use 'x86_64' instead of 'i686'):
````
pacman -S mingw-w64-i686-toolchain            \
          mingw-w64-i686-boost                \
          mingw-w64-i686-hunspell             \
          mingw-w64-i686-wxwidgets3.2-common  \
          mingw-w64-i686-wxwidgets3.2-msw     \
          mingw-w64-i686-drmingw              \
          mingw-w64-i686-tinyxml
````

Then extract the archive into /opt/codeblocks, export /opt/codeblocks/bin to PATH.
Run codeblocks!

## Note
Basically, the release package contains all the `exe` files and `dll` files need to run the Code::Blocks.
Also, it is recommanded that the `CbLauncher.exe` is executed instead of `codeblocks.exe`. Because when you start Code::Blocks by running `CbLauncher.exe`, it is in portable mode, the settings will be stored in the same folder as `codeblocks.exe` in the sub-folder `AppData`.

The built Code::Blocks has many other my own patches, so please see the commit log here:
[asmwarrior/codeblocks_sfmirror: Unofficial auto-updated GIT mirror of C::B repo in SourceForge. Does NOT accept patches nor pull requests.](https://github.com/asmwarrior/codeblocks_sfmirror/tree/master)
