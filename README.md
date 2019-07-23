# Ourchitecture CLI
======================

Ourchitecture CLI with plug-ins

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@ourchitecture/our-cli.svg)](https://npmjs.org/package/@ourchitecture/our-cli)
[![CircleCI](https://circleci.com/gh/ourchitecture/our-cli.svg?style=svg)](https://circleci.com/gh/ourchitecture/our-cli)
[![codecov](https://codecov.io/gh/ourchitecture/our-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/ourchitecture/our-cli)
[![Downloads/week](https://img.shields.io/npm/dw/@ourchitecture/our-cli.svg)](https://npmjs.org/package/@ourchitecture/our-cli)
[![License](https://img.shields.io/npm/l/@ourchitecture/our-cli.svg)](https://github.com/ourchitecture/our-cli/blob/master/package.json)

<!-- toc -->
* [Ourchitecture CLI](#ourchitecture-cli)
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @ourchitecture/our-cli
$ our COMMAND
running command...
$ our (-v|--version|version)
@ourchitecture/our-cli/0.0.2-alpha.7 win32-x64 node-v10.15.3
$ our --help [COMMAND]
USAGE
  $ our COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`our hello [FILE]`](#our-hello-file)
* [`our help [COMMAND]`](#our-help-command)

## `our hello [FILE]`

describe the command here

```
USAGE
  $ our hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ our hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/ourchitecture/our-cli/blob/v0.0.2-alpha.7/src\commands\hello.ts)_

## `our help [COMMAND]`

display help for our

```
USAGE
  $ our help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.4/src\commands\help.ts)_
<!-- commandsstop -->
