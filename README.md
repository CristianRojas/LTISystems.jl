# SystemsBase

[![Unix][unix-img]][unix-link]
[![Windows][win-img]][win-link]
[![Coveralls][ca-img]][ca-link]
[![Codecov][cc-img]][cc-link]
[![Documentation][docs-latest-img]][docs-latest-link]
[![Gitter][gitter-img]][gitter-link]

[unix-img]: https://img.shields.io/travis/JuliaSystems/SystemsBase.jl/master.svg?label=unix
[unix-link]: https://travis-ci.org/JuliaSystems/SystemsBase.jl
[win-img]: https://img.shields.io/appveyor/ci/aytekinar/systemsbase-jl/master.svg?label=windows
[win-link]: https://ci.appveyor.com/project/aytekinar/systemsbase-jl/branch/master
[ca-img]: https://img.shields.io/coveralls/JuliaSystems/SystemsBase.jl/master.svg?label=coveralls
[ca-link]: https://coveralls.io/github/JuliaSystems/SystemsBase.jl?branch=master
[cc-img]: https://img.shields.io/codecov/c/github/JuliaSystems/SystemsBase.jl/master.svg?label=codecov
[cc-link]: https://codecov.io/gh/JuliaSystems/SystemsBase.jl?branch=master
[docs-latest-img]: https://img.shields.io/badge/documentation-latest-blue.svg?colorB=1954a6
[docs-latest-link]: https://systemsbase.readthedocs.io/en/latest
[gitter-img]: https://img.shields.io/gitter/room/JuliaSystems/SystemsBase.jl.svg?colorB=1954a6
[gitter-link]: https://gitter.im/JuliaSystems/SystemsBase.jl

Core functionality for **identifying**, **analyzing** and **designing** control
systems in `Julia`.

### Description

This repository is meant to provide a basic set of tools, *i.e.*, *transfer
function* and *state space* types as well as the basic mathematical operations
defined on them, in a way that other tools for [identifying][juliasys-sysid] or
[analyzing][juliasys-ct] control systems would use the same set of functionality
in a transparent, coherent way.

[juliasys-sysid]: https://github.com/JuliaSystems/IdentificationToolbox.jl
[juliasys-ct]: https://github.com/JuliaSystems/ControlToolbox.jl
