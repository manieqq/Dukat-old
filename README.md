----
# Welcome to Dukat! #

----
# DukatCoin - Proof of Stake - Cryptocurrency with its own blockchain based on NXT


## What is DukatCoin? ##
DukatCoin (DUK) is a revolutionary digital money system. DUKAT can be a very profitable and safe way to invest. Built on Proof of Stake (PoS), which is a method of confirming transactions in the blockchain. This means that the more coins a miner has, the more mining power he has.

- Website: https://dukatcoin.pl
- Website wallet: http://dukatcoin.pl:7876

----
## Get it! ##

  - *dependencies*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

----
## Run it! ##

  - click on the Dukat icon, or start from the command line:
  - Unix: `./start.sh`
  - Window: `run.bat`

  - wait for the JavaFX wallet window to open
  - on platforms without JavaFX, open http://localhost:7876/ in a browser

----
## Compile it! ##

  - if necessary with: `./compile.sh`
  - you need jdk-8 as well

----
## Troubleshooting the NRS (Dukat Reference Software) ##

  - How to Stop the NRS Server?
    - click on Dukat Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on BitBucket

  - Permissions Denied?
    - no spaces and only latin characters in the path to the NRS installation directory
    - known jetty issue

  - If you don't find any peers, add n.motive.network 

----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder

----

## License
* This program is distributed under the terms of the Jelurida Public License version 1.1 for the Ardor Public Blockchain Platform.

