# SimpleAuction-smart-contract
This is a Simple Auction Smart Contract that can be used in any auction sale for transparency,security and accountability
It is useful for the government or any business that decides to go the auction sale wa
The contract contains the addresses of the beneficiary(participants that didnt win the auction) and the address of the highest bidder(winner)
and the unsigned integers of the highest bid and the unix timestamp that the auction will end.
There is also a mapping function that allows the beneficiaries that didnt win to be able to withdraw back their money,the time when the 
auction will end and the events that will mark the time when the highest bid increases.
There is also the bid function that requires two conditions before the bidder can bid.
These conditions are
(1)The current time must be less than or equal to the auction end time
(2)The msg.value that is the bid of the bidder must be greater than the current highest bid
The withdrawal function and auctionEnd functions are written with some neccessary conditions too.
