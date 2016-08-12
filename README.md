# client-hooks

[![asciicast](https://asciinema.org/a/4agoit6uwkinwm0032phtayo6.png {width=600px})](https://asciinema.org/a/4agoit6uwkinwm0032phtayo6)

## Brief Introduction

client-hooks is a plugin-based client hooks management.

- **High performance:** `client-hooks` introduce competition meachanism.
  parallel execution plugin, once any of plugin error occurred, immediately
  locate the problem.

- **Automation:** no manulal run command. configuration tasks will be automation
  executed by `git`.

- **Plugin-based:** `client-hooks` merely provides a core mechanism. you can
  expand its functionality in the form of custome plugins.

- **Simple:** through plugin encapsulate complex logic inside. for `git`
  repository manager, only need care current repository wath features are 
  required.

## Getting Started

### Prerequisites

- The installation directory need is a `git` repository.
- Current system install `git`(version >= 2.9.0).
- Current system install `node`(version >= 6.3.1).

### Basci Installation

```bash
npm install --save-dev client-hooks
```
