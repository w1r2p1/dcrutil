The code from this repository has been split into various packages to fix a
cyclic dependency with the dcrd project.  See below for the new locations of
dcrutil code:

* `base58` package: moved to [github.com/decred/base58](https://github.com/decred/base58)

* `bloom` package: moved to [github.com/decred/dcrd/bloom](https://github.com/decred/dcrd/tree/master/bloom)

* `hdkeychain` package: moved to [github.com/decred/dcrd/hdkeychain](https://github.com/decred/dcrd/tree/master/hdkeychain)

* `NewTLSCertPair` func: moved to [github.com/decred/dcrd/certgen](https://github.com/decred/dcrd/tree/master/certgen)

* Everything else from `dcrutil` package: moved to [github.com/decred/dcrd/dcrutil](https://github.com/decred/dcrd/tree/master/dcrutil)

Please update your projects accordingly.
