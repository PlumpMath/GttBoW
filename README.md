# GttBoW
Transparent Git to the Bash on Windows.

It lets you use the git installed on bash on windows as native windows git, without installing git again with silly mingw ssh tools.

# Built with
 - golang
  - Because it produces binary without installing entire visual studio monster.

# Installation (Currently not working yet)
 - Get `git.exe` by manual building or downloading prebuilt binary release
 - Move `git.exe` into `%WINDIR%\System32\` or `$env:WINDIR\System32\` or just any PATH environment variable directs.

# Simpler Batch Usage
 - Copy all `sbash.bat` file under `batch` directory to `%WINDIR%\system32\`.
 - Do the same with `git.bat` or others to use it like native windows binary.
 - Feel free to open `git.bat` and create link batch to any other bash binaries. It's clean short and easy.
