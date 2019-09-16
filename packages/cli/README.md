forklift-cli
============



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/forklift-cli.svg)](https://npmjs.org/package/forklift-cli)
[![Downloads/week](https://img.shields.io/npm/dw/forklift-cli.svg)](https://npmjs.org/package/forklift-cli)
[![License](https://img.shields.io/npm/l/forklift-cli.svg)](https://github.com/Artmann/forklift-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g forklift-cli
$ forklift COMMAND
running command...
$ forklift (-v|--version|version)
forklift-cli/1.0.0 win32-x64 node-v10.15.0
$ forklift --help [COMMAND]
USAGE
  $ forklift COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`forklift hello [FILE]`](#forklift-hello-file)
* [`forklift help [COMMAND]`](#forklift-help-command)

## `forklift hello [FILE]`

describe the command here

```
USAGE
  $ forklift hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ forklift hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/Artmann/forklift-cli/blob/v1.0.0/src\commands\hello.ts)_

## `forklift help [COMMAND]`

display help for forklift

```
USAGE
  $ forklift help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src\commands\help.ts)_
<!-- commandsstop -->
