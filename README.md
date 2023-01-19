# PrivateSales
# XXXXXXXXXXXX
The Means Private Sales


###Nakamoto Card Silver Edition###

1 - A snapshot of The Means Creator collections holders was taken by downloading transactions from its address (0xc66c81d5e0bbf8b54dd2a5359d18ecbd69bd2bfe) to other addresses (https://etherscan.io/token/0x495f947276749ce646f68ac8c248420045cb7b5e?a=0xc66c81d5e0bbf8b54dd2a5359d18ecbd69bd2bfe) resulting in file 

https://github.com/TheMeansCreator/PrivateSales/blob/main/NakamotoCardSilverEdition/export-token-nft1155-0x495f947276749ce646f68ac8c248420045cb7b5e.csv


2 - Holder addresses were extracted with command line 'cut -f6 -d"," export-token-nft1155-0x495f947276749ce646f68ac8c248420045cb7b5e.csv > meanslist.txt' resulting in file

https://github.com/TheMeansCreator/PrivateSales/blob/main/NakamotoCardSilverEdition/meanslist.txt


3 - Holders addresses were deduplicated using command line "cat meanslist.txt | sort -u > sortedmeanslist.txt" resulting in file 

https://github.com/TheMeansCreator/PrivateSales/blob/main/NakamotoCardSilverEdition/sortedmeanslist.txt


4 - Privileged addresses (such as project members) were removed resulting in file

https://github.com/TheMeansCreator/PrivateSales/blob/main/NakamotoCardSilverEdition/meanscustomerslist.txt

5 - 22 lucky winners were selected by using command line "shuf -n22 meanscustomerslist.txt > meanscustomerslist22winners.txt" resulting in file

https://github.com/TheMeansCreator/PrivateSales/blob/main/NakamotoCardSilverEdition/meanscustomerslist22winners.txt


6 - Private sales will be put up on OpenSea for each of the winner addresses starting at 15.30 UTC (10th Jan 2023) for a price of 0.02 ETH

https://opensea.io/collection/themeanswhatdoyoumean
