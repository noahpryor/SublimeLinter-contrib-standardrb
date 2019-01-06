# SublimeLinter-contrib-standardrb
-----------------------------------------------------------------

[![Build Status](https://travis-ci.org/noahpryor/SublimeLinter-contrib-standardrb.svg?branch=master)](https://travis-ci.org/SublimeLinter/SublimeLinter-contrib-standardrb)

This linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to [standardrb](__linter_homepage__). It will be used with files that have the “ruby” syntax.

Based on the SublimeLinter [plugin template](https://github.com/SublimeLinter/SublimeLinter-template) and [SublimeLinter-rubocop](https://github.com/SublimeLinter/SublimeLinter-rubocop)

## Installation
SublimeLinter must be installed in order to use this plugin.

Please use [Package Control](https://packagecontrol.io) to install the linter plugin.

Before installing this plugin, you must ensure that `standardrb` is installed on your system.

```bash
gem install standardrb
```

In order for `standardrb` to be executed by SublimeLinter, you must ensure that its path is available to SublimeLinter. The docs cover [troubleshooting PATH configuration](http://sublimelinter.readthedocs.io/en/latest/troubleshooting.html#finding-a-linter-executable).

## Settings
- SublimeLinter settings: http://sublimelinter.readthedocs.org/en/latest/settings.html
- Linter settings: http://sublimelinter.readthedocs.org/en/latest/linter_settings.html

Additional SublimeLinter-standardrb settings:

|Setting            |Description    |
|:--------------    |:--------------|
|use_bundle_exec    |Use bundle exec for executing standardrb    |

