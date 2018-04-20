@heroku-cli/plugin-config
=========================



[![Version](https://img.shields.io/npm/v/@heroku-cli/plugin-config.svg)](https://npmjs.org/package/@heroku-cli/plugin-config)
[![CircleCI](https://circleci.com/gh/heroku/heroku-cli-plugin-config/tree/master.svg?style=shield)](https://circleci.com/gh/heroku/heroku-cli-plugin-config/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/heroku/heroku-cli-plugin-config?branch=master&svg=true)](https://ci.appveyor.com/project/heroku/heroku-cli-plugin-config/branch/master)
[![Codecov](https://codecov.io/gh/heroku/heroku-cli-plugin-config/branch/master/graph/badge.svg)](https://codecov.io/gh/heroku/heroku-cli-plugin-config)
[![Downloads/week](https://img.shields.io/npm/dw/@heroku-cli/plugin-config.svg)](https://npmjs.org/package/@heroku-cli/plugin-config)
[![License](https://img.shields.io/npm/l/@heroku-cli/plugin-config.svg)](https://github.com/heroku/heroku-cli-plugin-config/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @heroku-cli/plugin-config
$ oclif-example COMMAND
running command...
$ oclif-example (-v|--version|version)
@heroku-cli/plugin-config/0.0.0 darwin-x64 node-v8.11.1
$ oclif-example --help [COMMAND]
USAGE
  $ oclif-example COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`oclif-example config:edit`](#oclif-example-configedit)

## `oclif-example config:edit`

interactively edit config vars

```
USAGE
  $ oclif-example config:edit

OPTIONS
  -a, --app=app        (required) app to run command against
  -r, --remote=remote  git remote of app to use
```

_See code: [src/commands/config/edit.ts](https://github.com/heroku/heroku-cli-plugin-config/blob/v0.0.0/src/commands/config/edit.ts)_
<!-- commandsstop -->
