# Start commands ccMiner and XMRig Zergpool
Check also our [YouTube](https://www.youtube.com/@bloxylabs "YouTube") channel for instructions and other related information.

If you had fun with the projects, please consider giving us a Super Thanks on YouTube or buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") ☕.

<h3><u>Start command ccMiner Verushash alorithm</u></h3>
When you are in the ccminer directory of your Pi, use the following command:

```
./ccminer -a verus -o stratum+tcp://verushash.eu.mine.zergpool.com:3300 -u <wallet> -p c=LTC,ID=<workername> -t 4
```

<h3><u>Start command XMRig Ghostrider algorithm</u></h3>
When you are in the build directory of XMRig, use the following command:

```
./xmrig -a ghostrider -o stratum+tcp://ghostrider.eu.mine.zergpool.com:5354 -u <WALLET> -p c=LTC,ID=<workername>
```
