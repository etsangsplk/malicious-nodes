# Planning

## Meeting notes

All of our meeting notes have been placed into the [meeting notes](./meeting-notes) directory.

We will try to reference these notes through out the documentation to explain how we have made certain decisions.


## Node ideas

We have come up with X ideas for malicious nodes:

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
* ? nodes

### Categories

To break this list down into smaller groups of nodes, we came up with five different categories and assigned nodes to them.

**Game theory**: Non-market prioritization, byzantine attack and uneven node prioritization

**Product specific**: Invalid secret shares

**MITM**: External handshake

**Network level**: Port flooding, unexpected port forwarding, buffer overflows, dead-locks and live-locks, network fragmentation, remote access explotis

**Denial of service**: Delta fragment spamming, package dropping, ? 