# jabberd2-auth-linux.patch

Support for [glibc2](https://ftp.gnu.org/old-gnu/Manuals/glibc-2.2.3/html_node/libc_650.html) crypt() MD5 (salt $1$) algorithm for authentication for the [jabberd2](https://jabberd2.org/) 2.3.6 server. This is a small modification to support the standard Linux MD5 crypt salt. Additional cases can be added for other algorithms.

## License

Copyright 2016 Rodolfo González González

[![License: GPL v2](https://img.shields.io/badge/License-GPL_v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
