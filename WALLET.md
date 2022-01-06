# Wallet

## Introduction

With the wallet app circle members are able to make transactions. A current, but not exhaustive, list of features is:

* Make private transactions
* Make transactions
* Convert T$ to fiat
* Convert fiat to T$

```
TODO

[ ] Should private transactions be possible? Or should everything be on the ledger? From a transparency perspective this is beneficial, but from a privacy perspective it is not.
[ ] Should transactions on the ledger be traceable to circle participants?
```

## Private transactions

Cash transactions are under pressure in the current fiat environment, which is sad, because they allow the participant to make transactions without being concerned about privacy.
Privacy from government institutions or banks, but also from spouses.

What properties of fiat cash transactions could we transfer to the circle cash payments? Let us first take a closer look at what the cash process looks like:

1. Participant A makes a €50 single bank note cash withdrawal from an ATM
2. Participant A then pays participant B €20
3. Participant A receives a €20 and a €10 bank notes totalling €30
4. Participant A pays participant C €20
5. Participant A keeps the remainder of the money
6. Participant B pays participant C €20
7. Participant B does not have any cash money left
8. Participant C makes a €40 cash deposit at the bank

What properties can we distill from this list?

* A participant needs to go somewhere to make the cash withdrawal (limits withdrawal tendency in current high card payment availability and low atm availability)
* A withdrawal results in a subtraction from a bank account and an addition to the participants' wallet
* It is assumed the bank notes serial numbers are recorded at time of the withdrawal and deposit and possibly linked to the participant
* The more notes are withdrawed, the more entropy is applied until notes are deposited at the bank again
* Notes follow a path among participants that is unknown to the bank upon deposit
* Notes have a clear denomination for both sender as receiver
* A participant needs to go somewhere to make the cash deposit (limits deposit tendency in current low deposit location availability)
* Upon receiving a bank note with a greater denomination than the amount owed, a bank note exchanged earlier is transferred to the payer
* Someone could steal the bank notes
* A deposit results in a subtraction from a wallet and an addition to the participants' bank account
* Notes not in the posession cannot be deposited
* If the payee does not have change money, the transaction cannot proceed (but could be overridden)
* If the payer does not have the amount asked, the transaction cannot proceed (but could be overridden)
* Bank notes are difficult to forge and have serial numbers
* The payee can verify the authenticity of the bank note
* Upon deposit the bank notes leave the cash economy
* Upon withdrawal bank notes enter the cash economy

Thinking about this, using cryptocurrencies a private transaction could be the exchange of private keys. Lets take a look at what the private transaction looks like:

1. Participant A converts 50 T$ to a single private key
2. Participant A then pays participant B 20T$, transferring the private key
3. Participant A then receives a 30T$ private key from participant B
4. Participant B pays participant C 20T$, transferring the private key
5. Participant B does not have any private keys left
6. Participant A gets a new private key for the remainder of the money
7. Participant C converts the private keys to 40T$

```
TODO

[ ] Think about denominations for private keys, for example 1/60T$, 1/12T$, 1/4T$, 1/2T$, 1T$, 2T$, 5T$, 10T$, 20T$, 50T$, 100T$, 200T$, 500T$ and 1000T$. Note the 
1/60, 1/12, 1/4 and 1/2 denominations. They stand for 1 minute, 5 minutes, 15 minutes and half an hour worth of T$.
[ ] Think about how to protect against participant A claiming the private key after transferring it to participant B. 
[ ] Think about how to limit exchanging the private key to T$, which contributes the privacy of transactions. The more hops a private key makes, the more obscure the spending chain (tree, actually).
[ ] Verify if all properties of cash transactions are present in the crypto private transactions.
```

## Decentralization

The current censorship environment, excessive Big Tech influence on the success or failure of initiatives and disruptive nature of this project leads to a completely
decentralized architecture.

Thinking about this, the backbone of the architecture should be a cryptocurrency architecture. Cryptocurrencies have evolved considerably and could easily be the interface 
to fiat as well.

Features:
* All wallets are nodes in the network.
* Anyone interested in this initiative could host a [full node](https://bitcoin.org/en/full-node) to support the network.
* The cryptocurrency should be able to create T$ as needed, as circle participants are contributing more and more hours to the community.
* All nodes should be rewarded for being on the network.
* Full nodes should be rewarded greatly for contributing to the network.
* The network should not be sustained by lots of computing power like the Bitcoin protocol.
* Selection of the best fitting [consensus mechanism](https://cointutor.org/crypto-proof-of-work-pow-proof-of-stake-pos-other-proofs) is an essential part to the success of
the initiative.
* It should be easy for circle participants to use the wallet app. It should be a no brainer.
* It should be easy for circle participants to convert T$ to fiat (bank account) and back again.
* It should be oblivious to circle participants that blockchain technology is at work.
* Cryptocurrency exchanges should not be used front facing to convert T$ to fiat and back again.
* It should be impossible for outsiders and malevolent to attack the network. One such attack vector could be a rich actors buying large sums of T$.
* The price of T$ should be pegged to an equivalent amount of money in the fiat economy and not be influenced by supply and demand. One such peg could be the average hourly salary (See: https://www.cbs.nl/nl-nl/visualisaties/dashboard-arbeidsmarkt/ontwikkeling-cao-lonen/uurloon).

```
TODO

[ ] Converting to fiat and back again should be protected against sudden inflationary circumstances. Average hourly salaries are calculated once a year. Could we use monthly inflation numbers to correct? How to deal with hyperinflationary scenario's?
```

Infrastructure should be created to facilitate these wishes:
* the cryptocurrency network
* apps (Web, Windows, iOS, Android, MacOS, Linux)
