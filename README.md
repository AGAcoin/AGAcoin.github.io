## Welcome to AGAcoin

AGAcoin is an open source peer-to-peer Litecoin-derived cryptocurrency for the [Commodore Amiga](https://en.wikipedia.org/wiki/Amiga) community and others. Originally known as Amigacoin, the project is undergoing a community resurgence, so the information on this page is subject to change.

### Coin Specifications

- Originally based on [Litecoin](https://litecoin.com/)
- 2 minute block targets
- 2 billion total coins
- 100 to 1000 random coins per block
- 1440 blocks to retarget difficulty

In addition to being able to earn coins through mining, AGAcoin is distributed among Amiga fans (stay tuned for info).

## Wallets and Downloads

- [Executables for Linux (Ubuntu/Debian)](http://web.archive.org/web/20161028115121/http://www.amigacoin.org/downloads/amigacoin_linux.zip)
- [Executables for Mac OS X](http://web.archive.org/web/20161028115121/http://www.amigacoin.org/downloads/amigacoin_mac.zip)
- [Executables for Windows](http://web.archive.org/web/20161028115121/http://www.amigacoin.org/downloads/amigacoin_windows.zip)
- [Paper Wallet](https://walletgenerator.net/?currency=AGAcoin)
- [AGAcoin on GitHub](https://github.com/AGAcoin)
- [Original project GitHub](https://github.com/sonountaleban/amigacoin)

## Exchanges

- [Cryptopia](https://www.cryptopia.co.nz/Exchange/?market=AGA_BTC)

## Blockchain Explorers

- <del>[aga.dromland.se](http://aga.dromland.se)</del>
- [prohashing.com](https://prohashing.com/explorer/amigacoin)
- [cryptopia.co.nz](https://www.cryptopia.co.nz/CoinInfo/?coin=AGA)

## Discussion

- [Bitcointalk.org](https://bitcointalk.org/index.php?topic=539974.0)
- [Cryptocointalk.com](https://cryptocointalk.com/topic/12040-AGAcoin-aga-information)
- [aros-exec.org](http://aros-exec.org/modules/newbb/viewtopic.php?viewmode=compact&order=DESC&topic_id=8695&forum=4&menumode=0)

## Current Nodes

The seed nodes are:

```
addnode=seed1.agacoin.dk:22112
addnode=seed2.agacoin.dk:22112
```

You can also try these nodes, the bottom two are the same as seed2 and seed1.

```
addnode=162.243.134.24:22112
addnode=98.115.147.74:22112
addnode=80.241.218.56:22112
addnode=149.210.128.213:22112
addnode=109.201.140.97:22112
addnode=62.59.168.89:22112
```
more nodes may be available at: https://cryptocointalk.com/topic/12040-AGAcoin-aga-information

## Mining Pools

- [coincave.nl](http://coincave.nl)
- [gcpool.eu](http://gcpool.eu/amiga/public/index.php?page=statistics&action=pool)

## Mining
If you are an AROS x86 user, you can use [AMiner](http://web.archive.org/web/20161028115121/http://www.amigacoin.org/downloads/AMiner.zip), a single-threaded CPU miner based on cpuminer. Otherwise you will need a Linux or Windows platform:on a PC without a powerful gfx card you should use [cpuminer](http://sourceforge.net/projects/cpuminer/) (on Windows use <a href="downloads/cgminer-3.7.2-windows.zip">cgminer 3.7.2</a>), instead of <a href="https://github.com/veox/sgminer">sgminer</a> (for ATI Radeon HD) or similar miner in the case with a proper gfx card.

cgminer/sgminer:
```
cgminer
--scrypt -o stratum+tcp://poolAGAcoin.org:22113 -u yourAGAcoinaddress -p x
-I 10
```

cpuminer:
```
minerd
--url=stratum+tcp://poolAGAcoin.org:22113 --userpass=yourAGAcoinaddress:x
```


