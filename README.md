<div align="center">
<h1>asdf-ocaml 🐫</h1>
OCaml plugin for ASDF version manager
</div>
<hr />

## Prerequirements

- All environments require `curl`, `git` and `tar`.

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
asdf plugin-add ocaml https://github.com/asdf-ocaml/asdf-ocaml.git
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.
