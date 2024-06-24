---
title: Main CC
---

Main suggestion command; allows users to create/update/delete suggestions in addition to allowing admins to manage suggestions.

For more information about the suggestion system, see [this](overview) page.

## Trigger

**Type:** `Regex`<br />
**Trigger:** `\A(\-\s?|<@!?204255221017214977>\s*)((del(ete)?|edit)?suggest(ion)?|(sa|suggestadmin)\s+((?:mark)?dupe|deny|implement(ed)?|archive|approved?|comment))(\s+|\z)`

## Usage

See the [suggestion system overview](overview/#commands) for more information about how to use this command.

## Configuration

Again, see the [suggestion package overview](overview/#configuration) for more information about how to configure this command.

## Code

```gotmpl file=../../../src/suggestion/suggestion.go.tmpl

```

## Author

This custom command was written by [@Satty9361](https://github.com/Satty9361).
