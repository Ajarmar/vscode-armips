# armips README

Syntax highlighting for GBA assembly code using the [ARMIPS](https://github.com/Kingcom/armips) assembler.

## Features

Includes syntax highlighting for

- Strings
- Constants
- Variables defined with the __equ__ directive
    - Although ARMIPS supports upper/lowercase characters, numbers and underscores in variable names, variable names will not be highlighted if they use lowercase characters (because otherwise every single word would be considered a variable name)
- Directives
- Labels
    - Different highlighting for global, static and local labels
- Folding on .area/.endarea pairs

\!\[Syntax highlighting example\]\(images/example.png\)

## Known Issues

- Branch instructions are not recognized as instructions

## Release Notes

### 1.0.0

Initial release