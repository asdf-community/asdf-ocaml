<div align="center">
<h1>asdf-ocaml 🐫</h1>
<span><a href="https://ocaml.org">OCaml</a> plugin for asdf version manager</span>
</div>
<hr />

[![Main workflow](https://github.com/asdf-community/asdf-ocaml/workflows/Main%20workflow/badge.svg)](https://github.com/asdf-community/asdf-ocaml/actions)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/asdf-community/asdf-ocaml.svg)](https://isitmaintained.com/project/asdf-community/asdf-ocaml "Average time to resolve an issue")
[![Percentage of issues still open](https://isitmaintained.com/badge/open/asdf-community/asdf-ocaml.svg)](https://isitmaintained.com/project/asdf-community/asdf-ocaml "Percentage of issues still open")
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-ocaml?color=brightgreen)](https://github.com/asdf-community/asdf-ocaml/blob/master/LICENSE)

## Prerequirements

- Make sure you have the required dependencies installed:
  - A C++ compiler
  - GNU make
  - curl
  - git
  - tar

- The GNU C Compiler (gcc) is recommended, as the bytecode interpreter takes
  advantage of GCC-specific features to enhance performance. gcc is the standard
  compiler under Linux, OS X, and many other systems.

- If you do not have write access to `/tmp`, you should set the environment
  variable `TMPDIR` to the name of some other temporary directory.

- Under HP/UX, the GNU C Compiler (gcc), the GNU Assembler (gas), and GNU Make
  are all _required_. The vendor-provided compiler, assembler and make tools
  have major problems.

- Under Cygwin, the `gcc-core` and `make` packages are required. `flexdll` is
  necessary for shared library support. `libX11-devel` is necessary for graph
  library support and `libintl-devel` is necessary for the `ocamlobjinfo` tool
  to be able to process `.cmxs` files. `diffutils` is necessary to run the test
  suite.

## Installation

```bash
asdf plugin-add ocaml https://github.com/asdf-community/asdf-ocaml.git
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.
