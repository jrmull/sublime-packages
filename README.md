# [Sublime Text 3] - Installed Packages & Settings

### Included Packages
  - [SublimeLinter 3] - plugin for Sublime Text 3 that provides a framework for linting code
  - [SublimeLinter-contrib-standard] linter plugin for the [JavaScript Standard Style]
  - [StandardFormat] for automatic formatting ('Format On Save' disabled by default)

### User Preferences
  - Font: Adobe's [Source Code Pro] - Size: 12, Windows-specific [directwrite] enabled

### Requirements

  - [Sublime Text 3] - recommend Build 3107+ for JavaScript improvements (performance, syntax highlighting, ES6 support)
  - [Package Control]
  - [Git]
  - [Node.js] - v 4.3.1 LTS and up recommended
  - [Source Code Pro] - OpenType (OTF) recommended

### Installation
  - Change directory to the Settings-User location (on Windows: *%APPDATA%\Sublime Text 3\Packages\User*)
  - Run the following git commands from the Bash prompt:

```sh
$ git clone https://github.com/jrmull/sublime-packages.git
$ mv sublime-packages/* sublime-packages/.* ./
$ rm -rf sublime-packages
```

  - Install **standard** and **standard-format** to the global path using npm (included with Node.js):

```sh
$ npm install -g standard
$ npm install -g standard-format
```

### Resources
  - [Package Control Docs - Syncing]


[directwrite]: <https://msdn.microsoft.com/en-us/library/windows/desktop/dd371554(v=vs.85).aspx>
[Git]: <https://git-scm.com/>
[JavaScript Standard Style]: <http://standardjs.com/>
[Node.js]: <https://nodejs.org>
[Package Control]: <https://packagecontrol.io/>
[Package Control Docs - Syncing]: <https://packagecontrol.io/docs/syncing>
[Source Code Pro]: <https://github.com/adobe-fonts/source-code-pro>
[StandardFormat]: <https://github.com/bcomnes/sublime-standard-format>
[SublimeLinter 3]: <http://www.sublimelinter.com/>
[SublimeLinter-contrib-standard]: <https://github.com/Flet/SublimeLinter-contrib-standard>
[Sublime Text 3]: <https://www.sublimetext.com/>
