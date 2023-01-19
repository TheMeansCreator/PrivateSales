# PrivateSales

The Means Private Sales

# Nakamoto Card Silver Edition

See Nakamoto Card Silver Edition Private Sale below

https://github.com/TheMeansCreator/PrivateSales/blob/2ndPrivateSale/NakamotoSilverCardEdition.md


# Nakamoto Card Gold Edition


1 - A snapshot of The Means Creator collection holders was taken by downloading owners of the following NFT IDs under smart contract 0x495f947276749ce646f68ac8c248420045cb7b5e (Open Sea Store smart contract). Free editions IDs were excluded.

https://github.com/TheMeansCreator/PrivateSales/blob/2ndPrivateSale/NakamotoCardGoldEdition/meansIDs.txt

2 - Snapshot was taken between 17:47 and 17:48 UTC on Jan 18th resulting in files below

https://github.com/TheMeansCreator/PrivateSales/blob/2ndPrivateSale/NakamotoCardGoldEdition/MeansHoldersHTMLFiles


3 - Holder addresses were extracted from the resulting HTML files with command line 'cat meansholdersNFTID*.html | tr '>' '\n' | grep Owner | cut -d'=' -f3 | cut -d"'" -f1 > meanslist.txt' resulting in file

https://github.com/TheMeansCreator/PrivateSales/blob/2ndPrivateSale/NakamotoCardGoldEdition/meanslist.txt


4 - Holders addresses were deduplicated using command line "cat meanslist.txt | sort -u > meansSorted.txt" resulting in file 

https://github.com/TheMeansCreator/PrivateSales/blob/2ndPrivateSale/NakamotoCardGoldEdition/meansSorted.txt


5 - Privileged addresses (such as project members) were removed from the previous file


6 - 22 lucky winners were selected by using command line "shuf -n22 meansSorted.txt > meansWinners.txt" resulting in file

https://github.com/TheMeansCreator/PrivateSales/blob/2ndPrivateSale/NakamotoCardGoldEdition/meansWinners.txt


7 - Private sales will be put up on OpenSea for each of the winner addresses starting at 16.30 UTC (19th Jan 2023) for a price of 0.0199 ETH

https://opensea.io/collection/themeanswhatdoyoumean
