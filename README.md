# The Zimscape CLI Issues Repo

Welcome to the public issues repo for the Zimscape CLI. Feel free to create valid issues and we'll get right to them. Take note of the available issue templates for straight to the point collaboration.

Zimscape-CLI Docs
=================

The Zimscape CLI used to manage development environments on https://zimscape.com

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/zimscape-cli.svg)](https://npmjs.org/package/zimscape-cli)
[![Downloads/week](https://img.shields.io/npm/dw/zimscape-cli.svg)](https://npmjs.org/package/zimscape-cli)
[![License](https://img.shields.io/npm/l/zimscape-cli.svg)](https://github.com/vuskhoza/zimscape-cli/blob/master/package.json)

<!-- toc -->
* [Installation](#installation)
* [Commands](#commands)
<!-- tocstop -->
# Installation
<!-- usage -->
```sh-session
$ npm install -g zimscape-cli
$ zimscape COMMAND
running command...
$ zimscape (-v|--version|version)
zimscape-cli/0.0.5 linux-x64 node-v11.10.1
$ zimscape --help [COMMAND]
USAGE
  $ zimscape COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`zimscape help [COMMAND]`](#zimscape-help-command)
* [`zimscape login`](#zimscape-login)
* [`zimscape logs [REMOTE]`](#zimscape-logs-remote)
* [`zimscape ls`](#zimscape-ls)
* [`zimscape push [REMOTE]`](#zimscape-push-remote)

## `zimscape help [COMMAND]`

display help for zimscape

```
USAGE
  $ zimscape help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_

## `zimscape login`

Login to zimscape.com

```
USAGE
  $ zimscape login

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ zimscape login
```

_See code: [src/commands/login.ts](https://github.com/vuskhoza/zimscape-cli/blob/v0.0.5/src/commands/login.ts)_

## `zimscape logs [REMOTE]`

Tail logs from a zimscape.com environment

```
USAGE
  $ zimscape logs [REMOTE]

EXAMPLE
  $ zimscape logs php.domain.com
```

_See code: [src/commands/logs.ts](https://github.com/vuskhoza/zimscape-cli/blob/v0.0.5/src/commands/logs.ts)_

## `zimscape ls`

List development environments on Zimscape.com

```
USAGE
  $ zimscape ls

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ zimscape envs
```

_See code: [src/commands/ls.ts](https://github.com/vuskhoza/zimscape-cli/blob/v0.0.5/src/commands/ls.ts)_

## `zimscape push [REMOTE]`

Use git to push current code base to chosen environment

```
USAGE
  $ zimscape push [REMOTE]

EXAMPLE
  $ zimscape push project.domain
```

_See code: [src/commands/push.ts](https://github.com/vuskhoza/zimscape-cli/blob/v0.0.5/src/commands/push.ts)_
<!-- commandsstop -->
