Copyright (c) 2009-2012 Bitcoin Developers

Copyright (c) 2014-2015 Rubycoin Developers

See readme-qt.rst for instructions on building Rubycoin QT, the
graphical user interface.

All of the commands should be executed in Terminal.app

```
sudo port install boost db48 openssl miniupnpc qrencode

cd rubycoin/src
make -f makefile.osx
```

```
./rubycoind --help  # for a list of command-line options.

./rubycoind -daemon # to start the rubycoin daemon.

./rubycoind help # When the daemon is running, to get a list of RPC commands
```
