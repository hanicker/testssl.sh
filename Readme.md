
## Intro

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/drwetter/testssl.sh?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

`testssl.sh` is a free command line tool which checks a server's service on any port for the support of TLS/SSL ciphers, protocols as well as some cryptographic flaws. It's designed to provide clear output for a "is this good or bad" decision.

It is working on every Linux distribution out of the box with the limitations of disabled features from the openssl client. It also works on BSD and other Unices out of the box, supposed they have `/bin/bash` and standard tools like sed and awk installed. MacOS X and Windows (using MSYS2) work too. 

On github you will find in the master branch the development version of the software -- with new features and maybe some bugs. For the stable version and a more thorough description of the software please see [testssl.sh](https://testssl.sh/ "Go to the site with the stable version and more documentation"). 

New features in this release are / will be

* "only one cmd line option at a time": gone (starttls integration pending)
* certificate information: done, 
* more HTTP header infos: done.
* protocol check via bash sockets, SSLv2+v3: done
* maybe: cipher check via bash sockets: for now only with development option -q
* debug file handling: done so far
* BEAST: done, maybe needs some polishing for the output

Contributions, feedback, also bug reports are welcome. For contributions please note: One patch per feature -- bug fix/improvement.

Update notification here or @ [twitter](https://twitter.com/drwetter). 


