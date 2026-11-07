# erin-the-black-plugins

A Claude Code plugin marketplace.
Each plugin is developed in its own repository; this repository only lists them.

## Install

```
/plugin marketplace add imahiro-t/claude-plugins
/plugin install graph-ops@erin-the-black-plugins
/plugin install quick-actions@erin-the-black-plugins
/plugin install session-compass@erin-the-black-plugins
```

## Plugins

| Plugin | Repository | Description |
|---|---|---|
| graph-ops | [imahiro-t/graph-ops](https://github.com/imahiro-t/graph-ops) | GraphOps ticket/graph workflow plugin |
| quick-actions | [imahiro-t/quick-actions](https://github.com/imahiro-t/quick-actions) | Icon actions on the selected transcript text and on the conversation |
| session-compass | [imahiro-t/session-compass](https://github.com/imahiro-t/session-compass) | A band above the prompt with what the session is about and buttons to step through your prompts |

## Maintaining

Each entry pins its plugin to a release tag (`ref`). When a plugin publishes a
new release, bump that entry's `ref` here as well, then run:

```
claude plugin validate .
```
