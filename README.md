# LoldexProtocol

Loldex is an open protocol that facilitates trustless, purely smart contract driven, low friction exchange of Ethereum-based assets. 
Harnessing the power of unlimited side chains to power the future of digital assets finance. For more information on how it works, check out the protocol specification.

## Developed Smart Contracts 

### LOLB Token Burn  
Smart contract that burns LOLB tokens when trade is completed
https://ropsten.etherscan.io/tx/0xb6bb4d3a7a96fd3fd5774b4e1f9463341c18b4a6c1150bb4312634f38808a8c2
Target burn https://etherscan.io/token/0x833a2d1bf71d2dcfd66071aafc7ac827d6eb5ebc - To be confirmed 
### LOLB WETH 
Our own WETH variant to trade ETH
### LOLB Basic Exchange Mechanism
Basic Smart contract to trade and support our front end 
### LOLB Fast Orderbook and Audit Sidechain
Ethereum POA Side Chain and Smart contracts to improve the exchange mechanism and support our automation features. Will be public-private blockchain model 
https://github.com/loldexio/LoldexProtocol/wiki

## In Progress

### Automated Trading with connection to our side chain design 
Smart contract to run your own Initial Exchange Offering or run your own liquidity pool using pubic-private blockchain model 
Smart contract to pair with non ERC20 tokens i.e. Bitcoin Cash SLP tokens, WAVES and BNB tokens.  
Smart contract to pull real time market data through our side chain APis i.e. 0x

Dependencies

https://github.com/simpleledger/Electron-Cash-SLP
https://github.com/simpleledger/slp-specifications

## LIPs LOLDEX Improvement Proposals

Inspired by Ethereum Improvement Proposals (EIPs) describe standards for the Ethereum platform, including core protocol specifications, client APIs, and contract standards, LOLDEX has its own LIPs 
 
This repository protocol smart contracts and numerous developer tools. If you're developing or are interested in using infrastructure in the future, please join our developer mailing list for updates on our website www.loldex.io

You can propose LIPs - Loldex improvement proposals and contribute 

### Contributing Methodology

Review LIP-1.
Fork the repository by clicking "Fork" in the top right.
Add your LIP to your fork of the repository.  
Submit a Pull Request to LOLDEX repository.
Your first PR should be a first draft of the final. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new LIP and assign it a number before merging it. Make sure you include a discussions-to header with the URL to a discussion forum or open GitHub issue where people can discuss.

If it requires images, the image files should be included in a subdirectory of the assets folder for that as follow: assets/lip-X (for lip X). When linking to an image in the EIP, use relative links such as ../assets/lip-X/image.png.


### LIP Status Terms

Draft - first publish version that is undergoing rapid iteration 
Last Call - ready for final review by a wide audience after all feedback gathered  
Accepted - LIP that the Core Devs have decided to implement 
Deferred - not being considered for immediate adoption. May be reconsidered in the future 
 
