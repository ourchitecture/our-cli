@ourchitecture/our-cli
======================

Ourchitecture CLI with plug-ins

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@ourchitecture/our-cli.svg)](https://npmjs.org/package/@ourchitecture/our-cli)
[![CircleCI](https://circleci.com/gh/https://github.com/ourchitecture/our-cli/our-cli/tree/master.svg?style=shield)](https://circleci.com/gh/https://github.com/ourchitecture/our-cli/our-cli/tree/master)
[![Codecov](https://codecov.io/gh/https://github.com/ourchitecture/our-cli/our-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/https://github.com/ourchitecture/our-cli/our-cli)
[![Downloads/week](https://img.shields.io/npm/dw/@ourchitecture/our-cli.svg)](https://npmjs.org/package/@ourchitecture/our-cli)
[![License](https://img.shields.io/npm/l/@ourchitecture/our-cli.svg)](https://github.com/https://github.com/ourchitecture/our-cli/our-cli/blob/master/package.json)

<!-- toc -->
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
@ourchitecture/our-cli/0.0.1 win32-x64 node-v10.15.3
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

_See code: [src\commands\hello.ts](https://github.com/ourchitecture/our-cli/blob/v0.0.1/src\commands\hello.ts)_

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
