# imahiro-plugins

A Claude Code plugin marketplace that collects the plugins by Takashi Imahiro.
Each plugin is developed in its own repository; this repository only lists them.

## Install

```
/plugin marketplace add imahiro-t/claude-plugins
/plugin install graph-ops@imahiro-plugins
```

## Plugins

| Plugin | Repository | Description |
|---|---|---|
| graph-ops | [imahiro-t/graph-ops](https://github.com/imahiro-t/graph-ops) | GraphOps ticket/graph workflow plugin |

## Maintaining

Each entry pins its plugin to a release tag (`ref`). When a plugin publishes a
new release, bump that entry's `ref` here as well, then run:

```
claude plugin validate .
```
