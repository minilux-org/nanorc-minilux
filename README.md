# nanorc-minilux
Syntax Highlighting for the Minilux programming language in the nano editor.

## Installation

1. Copy `minilux.nanorc` to your home directory or a dedicated nanorc directory:
   ```bash
   cp minilux.nanorc ~/.minilux.nanorc
   ```

2. Include it in your `.nanorc` file:
   ```bash
   echo 'include "~/.minilux.nanorc"' >> ~/.nanorc
   ```

## Features

Supports:
- Keywords (`if`, `while`, `func`, etc.)
- All Minilux built-in functions
- Variable highlighting (`$var`)
- String interpolation awareness
- Comments and Shebangs
