# Attacks

The project will be divided into self-contained reports on different designs of malicious nodes.

For every attack, we will:

1. Research the attack vector
2. Implement the malicious node
3. If the attack is successful, implement safeguards against it
4. Write a report on the attack

## Node ideas

We have come up with 14 ideas for malicious nodes currently. Each node will have its own Github issue and directory with a README, which will also link to a Github issue. 

- [ ] [BGP attack](../attacks/bgp-attack) (20th March 2018)
  - [ ] [Lazy Node Attack] (../attacks/byzantine-attack/lazy-nodes) 
  - [ ] [Selfish Node Attack] (../attacks/byzantine-attack/selfish-nodes) 
- [ ] [Non-market prioritization](../attacks/non-market-prioritization) (27th March 2018)
- [ ] [Invalid secret shares](../attacks/invalid-secret-shares) 
- [ ] [Dead-locks / live-locks](../attacks/dead-live-locks)
- [ ] [Delta fragment spamming](../attacks/delta-fragment-spamming)
- [ ] [0-cost nodes](../attacks/zero-cost-nodes)

### Optional

- [ ] [Unexpected port forwarding](../attacks/unexpected-port-forwarding)
- [ ] [External handshake](../attacks/external-handshake)
- [ ] [Port flooding](../attacks/port-flooding)
- [ ] [Packet dropping](../attacks/packet-dropping)
- [ ] [Buffer overflows](../attacks/buffer-overflows)
- [ ] [Remote access exploits](../attacks/remote-access-exploits)

## Categories

> References: [Meeting on February 28th](./meeting-notes/feb28.md)

Categorizing the different attacks into smaller groups makes it easier identify possible connections between them and draw connections that help us to improve and combine the different attack vectors.

#### **Game theory**

Game theory attacks don't rely on network or implementation vulnerabilities. Instead, they modify the behaviour of their nodes or attempt to influence other nodes in order to achieve their desired outcome.

> * *Non-market prioritization*
> * *Byzantine attack*
> * *Uneven node prioritization*

#### Man-In-The-Middle

Man in the middle attacks (MITM) involve a node placing itself in between the communications of two other nodes in order to gain access to information or to affect the operation of the other nodes.

> * *External handshake*

#### Implementation level

Implementation level attacks are technical exploits that attempt to identify and take advantage of security flaws in the node software.

> * *Buffer overflows*
> * *Dead-locks and live-locks*
> * *Remote access explotis*

#### Network level

Network level attacks. A subcategory of the network attacks is Denial of Service, where a malicious node attempts to prevent other nodes from participating in the network.

> * *Network fragmentation*
> * *Unexpected port forwarding*
> * *Port flooding*
> * *Delta fragment spamming*
> * *Package dropping*
> * *0-cost nodes*

#### Product specific

This category contains attacks that don't fit into the other categories, due to being overly specific to dark pool's protocol.

> * *Invalid secret shares*
