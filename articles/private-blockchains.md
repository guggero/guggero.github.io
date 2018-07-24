# comparisons

This is work in progress!

My goal is to provide arguments as to why I think private/permissioned blockchains are useless and a hype.

## what IS a blockchain?
* consistent (=hashed)
* append-only (=chain of hashes)
* ownable (=signed)
* agreeable state without central party (=consensus, canonical)

## ideology

### public blockchain
* open, borderless, global, permissionless, uncensorable
* real democracy in technology
* freedom vs. efficiency

### private blockchain
* intranet, disney version of the internet. because the internet is scary
* AOL, Compuserve, walled gardens
* transport hype words instead of what really makes it special
  * encryption, signatures, tamper proof, smart contracts (web: linked data, everything accessible, standardized representation)
  * vs.
  * everybody can participate; democratisation of money (web: democratisation of knowledge)
* boring, not interesting in the broader sense

## technology

### public blockchain
* security through external energy introduced into closed system
* work proves immutability (Proof of Work)
* trust in no entity
* financial incentive to participate

### private blockchain
* security through central authority
* trust in one or few entities
* without currency on top, the blockchain story falls apart
* with currency on top, you're probably running a scam (if it's not Bitcoin)
* no incentive for anyone to participate other than promises by consortium

## questions to ask if you want to create a private blockchain
* Do you want to make data immutable?
  * If only one or a few entities in a private blockchain can create blocks, there is no security of immutability.
    A party that wants to fake information, they can do with very low effort (because no proof of work was put in).
    If a party is trustworthy to not mutate the information, there is no need for a decentralized solution.
* Do you want to create transparency for your users?
  * Why would you store it in a private blockchain then?
* Do you want to create your own token?
  * You're probably running a scam.

## conclusions

* DDBMS have existed for ages

* consortium: trusting a few is not better than trusting one
* public data vs. data protection: if you need a central database to map the blockchain IDs to real world IDs, the distribution falls apart


# sources
* Andreas Antonopoulos
  * Bitcoin Q&A: What is the impact of private blockchains and coins? - Intranet vs. Internet
  * https://www.youtube.com/watch?v=t0gqSXEJz0E
* Rytis Bieliauskas (CoinGate)
  * Blockchain: Differences between public and private blockchains
  * https://www.youtube.com/watch?v=MRZGat-b6Fg
* Dr. C. Mohan
  * Permissioned Blockchains and Databases
  * https://www.youtube.com/watch?v=hfTiYOSPup0
