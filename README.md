# ink README

Support for Inkle's [Ink](https://github.com/inkle/ink) language in Visual Studio Code with extended support for action lines of the [Game Grumps: Joint Justice project](https://github.com/Studio-Lovelies/GG-JointJustice-Unity/wiki/Scripting-Basics-using-Inky#actions).

## Features

- Support for [action lines](https://github.com/Studio-Lovelies/GG-JointJustice-Unity/wiki/Scripting-Basics-using-Inky#actions)
- Syntax highlighting using the .tmLanguage file included in the Ink source repository.
- Accurate word count in Ink files. Ignores comments, knot/stitch declarations and logic blocks, counting only actual content text.
- IntelliSense completion for divert targets.
- Show definition support for knots
- Node (knot/stitch) count in Ink files.
- Sensible language configuration defaults for Ink.

## Release Notes

### 1.4.0
- Support for [action lines](https://github.com/Studio-Lovelies/GG-JointJustice-Unity/wiki/Scripting-Basics-using-Inky#actions)

### 1.3.0
- Completions now support labels
- Show definitions now works on knots as divert targets

### 1.2.0
- Add basic support for IntelliSense, providing completions for knots and stitches of the current knot; triggered by typing ->

### 1.1.0
- Add word/node count feature.

### 1.0.0

Initial release.

# License

MIT. See LICENSE.
