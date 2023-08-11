---
title: "About"
---

Orderly is our reproducible reporting framework, initially via the R package [`orderly`](https://vaccineimpact.org/orderly) which we are in the process of rewriting and making work with more languages.

It has been built by us at [RESIDE](https://reside-ic.github.io) to support teaching activities within the [MRC Centre for Global Infectious Disease Analysis](https://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/)

It is composed of many moving parts, most of which are in a state of flux

* [`orderly`](https://github.com/vimc/orderly), the original implementation, now frozen
* [`orderly2`](https://github.com/mrc-ide/orderly2), the new implementation, currently in beta testing
* [`OrderlyWeb`](https://github.com/vimc/orderly-web), the original web interface
* [`Packit`](https://github.com/mrc-ide/packit), the new web interface
* [`outpack`](https://github.com/mrc-ide/outpack), the specificiation that all new implementations conform to
* [`outpack-py`](https://github.com/reside-ic/outpack), the Python implementation
* [`outpack_server`](https://github.com/mrc-ide/outpack_server), the Rust implementation and server
* [`orderly.db`](https://github.com/mrc-ide/orderly.db), database support for `orderly2` (as used by VIMC)
* [`outpack.orderly`](https://github.com/mrc-ide/outpack.orderly), migration support for orderly1 users
* [`orderly.helper`](https://github.com/mrc-ide/orderly.helper), compatibility support for users of both orderly1 and orderly2 on different projects
* [`outpack.sharepoint`](https://github.com/mrc-ide/outpack.sharepoint) a sharepoint location driver
