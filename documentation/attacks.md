# Attacks

The project will be divided into self-contained reports on different designs of malicious nodes.

## Node ideas

We have come up with 14 ideas for malicious nodes currently. Each node will have its own Github issue and directory with a README, which will also link to a Github issue.

* [Non-market prioritization](../attacks/non-market-prioritization)
* [Byzantine attack](../attacks/byzantine-attack)
* [Uneven node prioritization](../attacks/uneven-node-prioritization)
* [Invalid secret shares](../attacks/invalid-secret-shares)
* [External handshake](../attacks/external-handshake)
* [Port flooding](../attacks/port-flooding)
* [Unexpected port forwarding](../attacks/unexpected-port-forwarding)
* [Buffer overflows](../attacks/buffer-overflows)
* [Dead-locks / live-locks](../attacks/dead-live-locks)
* [Network fragmentation](../attacks/network-fragmentation)
* [Remote access exploits](../attacks/remote-access-exploits)
* [Delta fragment spamming](../attacks/delta-fragment-spamming)
* [Packet dropping](../attacks/packet-dropping)
* [0-cost nodes](../attacks/zero-cost-nodes)


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
