## Background
CryptoPunks launched as a fixed set of 10,000 items in mid-2017 and became one of the inspirations for the ERC-721 standard. They have been featured in places like The New York Times, Christie’s of London, Art|Basel Miami, and The PBS NewsHour.

OpenSea analytics has a collection of data and charts such as:
<img src="https://github.com/jiunnhwa/NFT-Price-Volume-Chart-Python-Moralis-Web3/blob/main/CryptoPunks%20Analytics%20-%20Collection%20OpenSea.png" width=60% >

https://opensea.io/collection/cryptopunks/analytics

## Application
This program generates a similar chart to the one in opensea analytics showing the volume and average trading price of cryptopunks for the past 7 days; 
using https://docs.moralis.io/reference/getnftcontracttransfers to get the transfers, or traded volume.

Parameter required is the NFT contract address which we we can get from Etherscan:
<img src="https://github.com/jiunnhwa/NFT-Price-Volume-Chart-Python-Moralis-Web3/blob/main/Etherscan-Cryptopunk-Wallet.png" width=50% >
https://etherscan.io/token/0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb

### Sample Chart
Last 14 days:

<img src="https://github.com/jiunnhwa/NFT-Price-Volume-Chart-Python-Moralis-Web3/blob/main/Figure_1.png" width=70% >


## Installs
pip install moralis

pip3 install python-dateutil [ModuleNotFoundError: No module named 'dateutil.easter']


## Reference
NFT Data Analysis with Python and Moralis Web3 SDK - https://www.youtube.com/watch?v=9kP8bqycrqw
