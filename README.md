# Git Portable

Git Portable is a portable version of [Git for Windows ("thumbdrive edition")](https://git-scm.com/) packaged in [PortableApps.com Format](http://portableapps.com/about/what_is_a_portable_app).

[Visit Git Portable Homepage at PortableApps.com](https://portableapps.com/node/34685)

[Download Git Portable 2.27.0 Development Test 1](https://github.com/sheabunge/GitPortable/releases)

## Installing

The preferred method of installing Git Portable is the `.paf.exe` installer ([why?](https://portableapps.com/about/what_is_a_portable_app#whypaf)). It will download Git for Windows as part of the install process.

However, you can also install Git Portable manually:

1. Copy the `GitPortable` directory from this repository to a location of your choice.
2. Download Git for Windows Portable ("thumbdrive edition") from <https://git-scm.com/download/win> and extract it to the `GitPortable\App\Git` directory.
3. Run the `"GitPortable\App\Git\git-bash.exe" --no-needs-console --hide --no-cd --command=post-install.bat` command to complete installation.

The manual installation instructions can also be used to update the version of Git within an existing Git Portable installation.
