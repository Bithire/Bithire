Build instructions
===================

See readme-qt.rst for instructions on building Bithire QT, the
graphical user interface.

All of the commands should be executed in Terminal.app

```
sudo port install boost db48 openssl miniupnpc qrencode

cd bithire/src
make -f makefile.osx
```

```
./bithired --help  # for a list of command-line options.

./bithired -daemon # to start the bithire daemon.

./bithired help # When the daemon is running, to get a list of RPC commands
```
