# miner-burst
modded Blagominer by modding a modded version from Quibus :-)

Added a couple of thing to the Blagominer modded by Quibus:

-automatically switch from POC1 to POC2 depending on block height
-added config item "POC2HFBlock":500000 (block height to be confirmed)
-added second cache parameter as shuffling needs more cache to perform (less seeks)
-added config item "CacheSize2" : 1000000
-added ability to include POC2 filenames (no stagger in filename)
-ability to run the miner on mixed POC1 & POC2 files
-abbility to run POC2 files in a POC1 world & vice versa
