SwissCoin
=========

Class-based proof token implementation for HoboNickels & proofchain.info

http://académiesuisse.org

proof-of-work [coin A - PoW mined, unspent]

proof-of-stake [coin B - PoS minted, unspent]

proof-of-burn [coin C - any spent output - A or B coin changes to C / burnt state - until eligible for new stake / reassigned to B state]

proof-of-tx [A or B proof token exchange clearsigned on merge-mine blockchain]

Scrypt
333,333,333,333 swc
33 second block time
PoW Reward: 333 thirding every 333,333 blocks
PoS Reward: ~33% stake begins on day day 33 

rpc Port: 3333
p2p Port: 4444

Proof of Stake explained: 100.00 swc mature over a 33-day period.
From Day 1 through Day 33, there is no change, but the coins "age" in the background.
On Day 33, the coins become eligible for PoS minting.
From Day 34 through Day 99, the chances of hitting a PoS block increase. After day 99, the stake potential plateaus.
When a Stake block is hit, the input that was used gets locked for 33 blocks as the POS block matures. It is moved to the stake column and a transaction will appear in the wallet for 33 swc.
After 33 blocks the 100 swc is returned and 33 swc is confirmed leaving 133 swc in the wallet.


