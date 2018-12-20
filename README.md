# _Purely_ static Dash
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?longCache=true&style=flat-square)](//github.com/semantic-release/semantic-release)
[![ISC License](https://img.shields.io/badge/license-ISC-brightgreen.svg?longCache=true&style=flat-square)](//www.isc.org/downloads/software-support-policy/isc-license/)
[![Build Status](https://travis-ci.org/concatime/umurmur-zero.svg?branch=master)](//travis-ci.org/concatime/umurmur-zero)

Package | Version | Latest available
:------:|---------|-
Musl    | 1.1.20  | [![](https://repology.org/badge/latest-versions/musl.svg)](//git.musl-libc.org/cgit/musl/tree/WHATSNEW)
Dash    | 0.5.10.2| ![](https://repology.org/badge/latest-versions/dash.svg)

By default, jemalloc is now disabled since it causes boilerplate.

The script (`dash-zero`) requires:
 - gcc or clang>=3.5 (otherwise, `ld: cannot find -l-user-{start,end}`)
 - make

To clone:
`git clone --recurse-submodules -j8 https://github.com/concatime/dash-zero.git`

To install, simply download the binary file called `dash`.
