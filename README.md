# readme_cli

## Description

This Ocaml based generator creates a structured and informative README.md file. It uses user prompts to create each section based on user prompts, and generates a table of contents for the repo.

![badmath](https://img.shields.io/github/languages/top/kjevaji-PC/readme_cli)  
![badmath](https://img.shields.io/github/issues/kjevaji-PC/readme_cli)  
![badmath](https://img.shields.io/github/forks/kjevaji-PC/readme_cli)  
![badmath](https://img.shields.io/github/stars/kjevaji-PC/readme_cli)  
## Table of Contents

- [Installation-Instructions](#installation-instructions)
- [Usage-Instructions](#usage-instructions)
- [License](#license)
- [Author](#author)


## Installation-Instructions
Getting Started with Opam on macOS
```sh
brew install opam
opam init
eval $(opam env)

opam switch create readme_cli
eval $(opam env)

opam install dune
```

Clone the Repo
```sh
cd readme_cli
```

## Usage-Instructions
Build with dune and run using dune exec
```sh
dune build && dune exec ./main.exe
```

Output file is ./README-output.md
## License

MIT License

Copyright (c) 2024 Kartik Jevaji

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Author

Kartik Jevaji

kjevaji@phasechange.ai

