SuisseCoin
=========
SuisseCoin is a token protocol [transport layer] using outputs from two or more different cryptocoins [for ex - bitcoin[client]and dogecoin[host]] The user generates wallet chains using the same seed for at least two separate blockchains.

Let’s take a second to clarify an important point: tokens != protocols.

Tokens are the form that issued credentials take to be transported, from authority to client and from client to resource.
Protocols detail the ceremony that apps use to send users to authenticate to an authority and/or clients use for sending tokens to apps for gaining authenticated access. In other words, protocols are used for moving tokens.

A Proof Token allows the requestor to use a key that’s locked in a token encrypted for somebody else and communicates the session key to the requestor in a format that it can understand.

A Bearer Token is security token with the property that any party in possession of the token (a "bearer") can use the token in any way that any other party in possession of it can. Using a bearer token does not require a bearer to prove possession of cryptographic key material (proof-of-possession).

SuisseCoin operates similar to the proverbial 'swiss numbered account': a user can move, exchange, modify and perform any number of operations on funds using a password or token for access. In the conventional model, the bank is the token authenticating/issuing authority - more specifically, the bank's host servers/databases in concert with the clients [human bank teller/ATM or online account]. SuisseCoin applies the same user-client-host authentication schema - using Bitcoin blockchain as the 'client-ATM/teller' and the altcoin blockchain [aux-chain] as the 'host-server'. The orders / transactions made using SuisseCoin [transport layer] can be Bitcoin, other cryptocurrency, stocks, or physical assets like bullion, vehicles, equipment, or real-estate exchanged in bearer-proof token form.

A 'Suisse wallet' consists of a deterministic wallet seed used to generate at least two sets of coin walllets [Bitcoin, DOGE, Litecoin, PPC]
SuisseCoin bearer-proof tokens are virtual or tangible asset digitally signed with the SuiseCoin 'master key' and a transaction id / proof-of-purchase/order from the counterparty 

A potential use-case is for brokers to exchange, collateralize, or authenticate message types, op codes, & syntax like SWIFT [Society for Worldwide Interbank Financial Telecommunication] and FIX [Financial Info Exchange] 

SWIFT/FIX-Link works by encoding SWIFT/FIX opcodes, semantics into transactions, and then spending to the corresponding addresses. Link specifies a format for creating transactions which conform to the protocol, and therefore can be indexed by clients and SWIFT/FIX trannsport layer. ProofChain parses Link formatted messages to or from blockchain[s] for various market order, query/scraping, and broadcast applications.

SuisseCoin bearer-proof tokens could be considered validated to the networks once a few proof criteria are met: 1. A merchant must obtain two wallets [on separate blockchains] and some quantity of cryptocoins in order to 'mint' or generate new bearer/proof tokens. 2.Users / customers place orders for Suisse bearer-proof tokens using bitcoin sent to the merchant's public 'Suisse' bitcoin address using prescribed opcodes[tags]. 3. Merchant then registers/signs the BTC transaction id/blankhash to the bearer-proof token address, broadcasts the transaction into the aux-chain ['atomic chain' trading may or may not be used here]. 4. At this point, the customer can demonstrate 'ownership' of the bearer-proof token  because its last input is a receipt / proof-of-purchase signed by merchant op-codes & transaction id from the customer's address [*conditions apply depending on wallet/client used]

see also:
http://www.cloudidentity.com/blog/2014/03/03/principles

http://www.cloudidentity.com/blog/2008/01/02/on-prooftokens/

http://tools.ietf.org/html/rfc6750

https://en.bitcoin.it/wiki/Atomic_cross-chain_trading#Solution_using_specialized_altchain

https://github.com/TSavo/Link

https://github.com/abeltje/Business-IBAN-Validator

https://github.com/arthurdejong/python-stdnum/blob/master/getiban.py

http://www.fixtradingcommunity.org/pg/structure/tech-specs/fix-version/50

https://code.google.com/p/libfenc/

http://atdl4j.org/

https://github.com/quickfix/quickfix

http://www.iso20022.org/full_catalogue.page



