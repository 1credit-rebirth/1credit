1Credit Core integration/staging tree
=====================================

https://1creditcoin.net

=======
1CRedit
=======

Launch date: April 21st, 2014

History:  1CRedit was created to be the 4th coin in the game 1BillionHex.
Although a game coin in the sense of that being the driver, it is a fully
functional cyber coin that can stand alone.

The genesis of the coin is to be something as stable as the current
Bitcoin/Litecoin codebase will allow.  A modified difficulty algorithm is used
to attempt to minimize difficulty swings due to pool or raider mining.

Long block times and high confirmation requirements should minimize fork
opportunities.  They will tend to make this an "investment" coin rather than a
"transaction" code.


----

Key stats:

Project started in mid April, 2014, after the first KGW exploit and a multitude of „pump and dump“ short term coins have come and gone.
Project updated February 2018 to Litecoin 0.15.1.0 and change to DGW
1 Coin payout.  1 Coin for block 1 and every block for the next 1623 Years
about 61594 1CR per year
Total coins:  200,000,000  max supported by current code, 100,000,000 after 1623 Years
512 second (~8.5 minute) block time – reducing stale minings block percentages to around 2%
156 new block confirms (~1 day confirms)
16 block transaction confirms (~2.3 hours)
ZERO Premine, ZERO special blocks
min relay tx fee 1000 µ1CR
transaction Max Fee 1 1CR
Hashing Algorithm:  Standard Scrypt
Difficulty Algorithm:  Dark Gravity Wave (as of block 102000)

Like Litecoin, 1CRedit is scrypt based

Ports:

Listen:   6666 (16666 for testnet)

JSON-RPC: 6667 (16667 for testnet)


What is 1Credit?
----------------

1Credit is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. 1Credit uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. 1Credit Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the 1Credit Core software, see [https://1creditcoin.net](https://1creditcoin.net).

License
-------

1Credit Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/1credit-rebirth/1credit/tags) are created
regularly to indicate new official, stable release versions of 1Credit Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).


Translations
------------

We only accept translation fixes that are submitted through [Bitcoin Core's Transifex page](https://www.transifex.com/projects/p/bitcoin/).
Translations are converted to 1Credit periodically.

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.


Credits
--------

Obviously, primary credit has to go to the Bitcoin and Litecoin development
teams without whome this project would never have been conceived of.  The
wallet code was cloned from the 0.8.6.2 release of Litecoin.  Addition credits
go to the links below:

http://devtome.com/doku.php?id=scrypt_altcoin_cloning_guide
https://bitcointalk.org/index.php?topic=149479.0

And all the folks responsible for QT, MingW32, and the other tools used to
build the Windows version of this.
