# [Sublime Text 3] - Installed Packages & Settings

### Included Packages
  - [SublimeLinter 3]
  - [SublimeLinter-contrib-standard] for the [JavaScript Standard Style]
  - [StandardFormat] for automatic formatting ('Format On Save' disabled by default)

### Requirements

  - [Sublime Text 3]
  - [Package Control]
  - [Git]
  - [Node.js] (v 4.3.1 LTS recommended)

### Installation
  - Change directory to the Settings-User location (on Windows: *%APPDATA%\Sublime Text 3\Packages\User*)
  - Run the following git commands from the Bash prompt:

```sh
$ git init
$ git remote add origin https://github.com/jrmull/sublime-packages
$ git fetch
$ git reset origin/master
```

  - Install **standard** and **standard-format** to the global path using npm (included with Node.js):

```sh
$ npm install -g standard
$ npm install -g standard-format
```

### Resources
  - [Package Control Docs - Syncing]


[Git]: <https://git-scm.com/>
[JavaScript Standard Style]: <http://standardjs.com/>
[Node.js]: <https://nodejs.org>
[Package Control]: <https://packagecontrol.io/>
[Package Control Docs - Syncing]: <https://packagecontrol.io/docs/syncing>
[StandardFormat]: <https://github.com/bcomnes/sublime-standard-format>
[SublimeLinter 3]: <http://www.sublimelinter.com/>
[SublimeLinter-contrib-standard]: <https://github.com/Flet/SublimeLinter-contrib-standard>
[Sublime Text 3]: <https://www.sublimetext.com/>

