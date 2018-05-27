# miner-burst
modded Blagominer by modding a modded version from Quibus :-)

Added a couple of thing to the Blagominer modded by Quibus:

-automatically switch from POC1 to POC2 depending on block height<BR>
-added config item "POC2StartBlock":502000 (block height to be confirmed)<BR>
-added second cache parameter as shuffling needs more cache to perform (less seeks)<BR>
-added config item "CacheSize2" : 1000000<BR>
-added ability to include POC2 filenames (no stagger in filename)<BR>
-ability to run the miner on mixed POC1 & POC2 files<BR>
-abbility to run POC2 files in a POC1 world & vice versa<BR>
