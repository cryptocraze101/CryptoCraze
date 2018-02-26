# CryptoCraze

Copyright (c) 2013-2017 CryptoCraze Developers
Copyright (c) 2013 NovaCoin Developers
Copyright (c) 2011-2012 Bitcoin Developers
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
CryptoCraze is a free open source project derived from NovaCoin, with
the goal of providing a long-term energy-efficient Proof of Stake based crypto-currency.
Built on the foundation of Bitcoin and NovaCoin, innovations such as proof-of-stake
help further advance the field of crypto-currency.

Setup
-----
Unpack the files into a directory and run:
 bin/32/cryptocrazed (headless, 32-bit)
 bin/64/cryptocrazed (headless, 64-bit)

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 

18775 (TCP) to your computer so you can receive
incoming connections.  cryptocraze works without incoming connections,
but allowing incoming connections helps the cryptocraze network.

Upgrade
-------
All you existing coins/transactions should be intact with the upgrade.
To upgrade first backup wallet
cryptocrazed backupwallet <destination_backup_file>
Then shutdown cryptocrazed by
cryptocrazed stop
Start up the new cryptocrazed.


See the cryptocraze site:
  http://cryptocraze.io
for help and more information.

Wallet themes
-------

| HyperBlue     | PoloniexNight | PoloniexDay   |
| ------------- | ------------- | ------------- |
| [![HyperBlue](https://github.com/zeewolfik/CryptoCraze/raw/master/src/qt/res/screenshots/cryptocraze-hyperblue-theme-th.png)](https://github.com/zeewolfik/CryptoCraze/raw/master/src/qt/res/screenshots/cryptocraze-hyperblue-theme.png) | [![PoloniexNight](https://github.com/zeewolfik/CryptoCraze/raw/master/src/qt/res/screenshots/cryptocraze-poloniexnight-theme-th.png)](https://github.com/zeewolfik/CryptoCraze/raw/master/src/qt/res/screenshots/cryptocraze-poloniexnight-theme.png) | [![PoloniexNight](https://github.com/zeewolfik/CryptoCraze/raw/master/src/qt/res/screenshots/cryptocraze-poloniexday-theme-th.png)](https://github.com/zeewolfik/CryptoCraze/raw/master/src/qt/res/screenshots/cryptocraze-poloniexday-theme.png) |


Build Instructions (Linux)
-------
### Dependencies required for CryptoCraze with or without GUI:
`sudo apt-get install build-essential libtool autotools-dev autoconf pkg-config libssl-dev libboost-all-dev libdb5.3-dev libdb5.3++-dev libminiupnpc-dev automake`

`./autogen.sh`

### Configure without GUI:
`./configure --with-incompatible-bdb --with-gui=no`

### Configure with GUI:
`sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler libqrencode-dev`

`./configure --with-incompatible-bdb --with-gui=qt5`

### Compile
`make`


# cryptocraze
# CryptoCraze
# CryptoCraze