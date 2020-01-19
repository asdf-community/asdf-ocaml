<div align="center">
<h1>asdf-ocaml</h1>
<span><a href="https://ocaml.org">OCaml</a> plugin for asdf version manager</span>
</div>
<hr />

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/asdf-community/asdf-ocaml/Main%20workflow?style=flat-square)](https://github.com/asdf-community/asdf-ocaml/actions)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-ocaml?style=flat-square&color=brightgreen)](https://github.com/asdf-community/asdf-ocaml/blob/master/LICENSE)

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

## Contributors

Thanks goes to these wonderful people
([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://bsky.moe"><img src="https://avatars3.githubusercontent.com/u/38746192?v=4" width="100px;" alt=""/><br /><sub><b>BSKY</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-ocaml/commits?author=imbsky" title="Code">💻</a> <a href="https://github.com/asdf-community/asdf-ocaml/commits?author=imbsky" title="Documentation">📖</a> <a href="#maintenance-imbsky" title="Maintenance">🚧</a> <a href="#infra-imbsky" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://nzws.me"><img src="https://avatars0.githubusercontent.com/u/14953122?v=4" width="100px;" alt=""/><br /><sub><b>nzws / ねじわさ</b></sub></a><br /><a href="#infra-nzws" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the
[all-contributors](https://github.com/all-contributors/all-contributors)
specification. Contributions of any kind welcome!

## License

Licensed under the
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
