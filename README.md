# SatelliteToolbox

[![Build Status](https://travis-ci.org/JuliaSpace/SatelliteToolbox.jl.svg?branch=master)](https://travis-ci.org/JuliaSpace/SatelliteToolbox.jl)
[![Build status](https://ci.appveyor.com/api/projects/status/x7ogyjfx1x5yj78j/branch/master?svg=true)](https://ci.appveyor.com/project/ronisbr/satellitetoolbox-jl/branch/master)
[![codecov](https://codecov.io/gh/JuliaSpace/SatelliteToolbox.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaSpace/SatelliteToolbox.jl)
[![Coverage Status](https://coveralls.io/repos/github/JuliaSpace/SatelliteToolbox.jl/badge.svg?branch=master)](https://coveralls.io/github/JuliaSpace/SatelliteToolbox.jl?branch=master)
[![](https://img.shields.io/badge/docs-stable-blue.svg)][docs-stable-url]
[![](https://img.shields.io/badge/docs-dev-blue.svg)][docs-dev-url]

This package contains several functions to build simulations related with
satellites. It is used on a daily basis on projects at the [Brazilian National
Institute for Space Research (INPE)](http://www.inpe.br), and it is the engine
of the [FOrPlan Satellite Simulator](http://old.esaconferencebureau.com/docs/default-source/16c11-secesa-docs/39_chagas_presentation.pdf?sfvrsn=2).

## Requirements

* Julia >= 1.0
* Crayons >= 4.0.0
* Interpolations >= 0.11.2
* Parameters >= 0.10.3
* OptionalData >= 0.2.1
* PolynomialRoots >= 0.2.0
* ReferenceFrameRotations >= 0.5.1
* RemoteFiles >= 0.2.1
* StaticArrays >= 0.10.3

## Installation

This package can be installed using:

```julia-repl
julia> using Pkg
julia> Pkg.add("SatelliteToolbox")
```

## Usage

See the [package documentation][docs-dev-url].

[docs-dev-url]: https://juliaspace.github.io/SatelliteToolbox.jl/dev
[docs-stable-url]: https://juliaspace.github.io/SatelliteToolbox.jl/stable
