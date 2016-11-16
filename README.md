#White Elephant
An DApp that will provide a decentralized gift giving exchange. The gifts will most likely be different ERC tokens. 

##Goals
The holidays are a wonderful time of year. Whether you chose to spend your time with your family or friends, the holidays are about community. This dApp is meant to facilitate community within the Ethereum ecosystem. 

##What It Does
Based on decentralized exchanges that allows one to exchange all tokens that follow the ERC standard, this dApp will allow any member of the Ethereum community to give a gift, and in turn recieve a gift. The gift giving will occur just as a white elephant gift exchange does with some slight modifications.

###Rules
1. All participants must send a gift to the smart contract to be considered part of the white elephant gift exchange.
2. The gifts are checked, and if they meet some requirements, they are accepted. 
3. Once the gift giving time comes, everyone who is participating in the exchange is assigned a random number, and the gifts are "wrapped."
4. When a gift is "wrapped," it loses most of its identifying information - only maintaining the amount of ether it was worth when it was sent to white elephant smart contract. This is the equivilant of seeing a wrapped gift and only having an idea of what it is based on its size. (Some tweaks needed here so gift givers can't cheat.)
5. The person who was randomly chose to pick first picks a gift and "unwraps" it. This reveals what type of ERC token it is to all members of the gift exchange.
6. The second person to pick can either choose a new gift to "unwrap" or steal the first gift from the first person.
7. If the second person chooses to steal the first person's gift, then the first person can choose a new gift to "unwrap."
8. The third person can steal any gifts that have been unwrapped already, or choose a new one.
9. This continues until each person has chosen a gift, in which case the gifts are distributed.
10. The game ends. 

###Requirments for Gifts
1. Gifts must an ERC token
2. Gifts must be within a certain ether price range as defined by the deployer of the contract. (The mechanism for this is still being created.)
