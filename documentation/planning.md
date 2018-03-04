# Planning

## Meeting notes

All of our meeting notes have been placed into the [meeting notes](./meeting-notes) directory.

We will try to reference these notes through out the documentation to explain how we have made certain decisions.


## Node ideas

We have come up with 14 ideas for malicious nodes currently. Each node will have its own Github issue and directory with a README.

* Non-market prioritization
* Byzantine attack
* Uneven node prioritization
* Invalid secret shares
* External handshake
* Port flooding
* Unexpected port forwarding
* Buffer overflows
* Dead-locks / live-locks
* Network fragmentation
* Remote access exploits
* Delta fragment spamming
* Packet dropping
* 0-cost nodes

### Categories

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
