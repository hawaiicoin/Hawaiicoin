Hawaiicoin - A slice of Aloha!
================================

Copyright (c) 2009-2017 Hawaiicoin Developers

What is Hawaiicoin?
----------------

Hawaiicoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Hawaiicoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Hawaiicoin is also the name of the open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Hawaiicoin client software, see http://www.hicoin.org.

License
-------

Hawaiicoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Hawaiicoin is based on Bitcoin.
Its development tracks Bitcoin's and the following information applies to Bitcoin's developemnt.
Development process
-------------------

Compilation instructions for Linux

Daemon:
cd src
make -f makefile.unix test
strip hawaiicoind

Wallet:
cd src
qmake
make
strip hawaiicoind
