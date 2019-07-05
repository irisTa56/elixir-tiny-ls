# ElixirTinyLS

ElixirTinyLS is a VS Code extension providing additional Elixir language support 1) syntax highlighting in markdown code block and 2) highlight some Croma's macros.

## Features

- Elixir syntax highlighting in fenced code blocks in markdown files.
- Highlight `defun`, `defunp`, `defunpt` of [Croma](https://github.com/skirino/croma).

![image](./image.png)

## Requirements

- [vscode-elixir](https://github.com/fr1zle/vscode-elixir)

## Extension Settings

None for now...

## Known Issues

None for now...

## Release Notes

- 0.0.1
  - initial release
- 0.1.0
  - injecting to the existing Elixir syntax rather than defining a new language
- 0.1.1
  - fix colorless arguments
- 0.1.2
  - highlight `defpt` macro of Croma as the same with a native function.
