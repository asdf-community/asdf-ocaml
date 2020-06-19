# asdf-ocaml

[OCaml](https://ocaml.org) plugin for asdf version manager

**Note**: To be honest, the use of this plugin is **NOT** recommended. It's
definitely better to use opam to manage your environment. We recommend using
opam unless you use it for a specific reason or for a specific purpose.

## Build History

[![Build history](https://buildstats.info/github/chart/asdf-community/asdf-ocaml?branch=master)](https://github.com/asdf-community/asdf-ocaml/actions)

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

## License

Licensed under the
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
