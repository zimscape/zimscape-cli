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
$ zimscape [COMMAND] [ARGS]
running command...
$ zimscape (-v|--version|version)
zimscape-cli/0.0.1 linux-x64 node-v11.10.1
$ zimscape --help [COMMAND]
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`zimscape login`](#zimscape-login)
* [`zimscape ls`](#zimscape-ls)
* [`zimscape push [REMOTE]`](#zimscape-push-remote)
* [`zimscape logs [REMOTE]`](#zimscape-logs-remote)

## `zimscape login`

Login to zimscape.com

```
EXAMPLE
$ zimscape login
Login in to your Zimscape.com account
Account email: email@gmail.com
Password: *********
one moment please...
Login successful :)
```

## `zimscape ls`

List development environments on Zimscape.com

```
EXAMPLE
$ zimscape ls
one moment please...
Product   Project                       Domain                        Type       Status 
PHP       zimscape.com                  php.zimscape.com              staging    active 

```

## `zimscape push [REMOTE]`

Use git to push current code base to chosen environment

```
EXAMPLE
$ zimscape push php.zimscape.com
one moment please...
Reset branch 'staging'
remote: Ref refs/heads/staging received. Deploying 'staging' branch...        
remote: Already on 'staging'        
remote: Ref refs/heads/staging received and successfully deployed to staging        
To gitserver.zimscape.com:php-project.git
   303588a..b2e830e  staging -> staging

```

## `zimscape logs [REMOTE]`

List development environments on Zimscape.com

```
EXAMPLE
$ zimscape logs php.zimscape.com
one moment please...
Sun Apr 19 12:36:31 UTC 2020 Ref refs/heads/staging received. Deploying 'staging' branch...
Sun Apr 19 12:36:31 UTC 2020 Ref refs/heads/staging received and successfully deployed to staging

```

<!-- commandsstop -->
