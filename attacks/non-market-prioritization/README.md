# Non-market order prioritization

> Category: Game theory

[Github Issue](https://github.com/republicprotocol/malicious-nodes/issues/2)

This directory will contain any source code written to implement and test this attack.

## Attack summary

Market-based order prioritization refers to matching orders with higher fees above other orders. Because matching orders with higher fees should be more profitable for the node, it is expected that nodes use market-based order prioritization.

Non-market prioritazion, therefore, refers to mathing orders by a metric not based maximisuni fees.

Reasons why a node might use non-market prioritization include:

* To undercut other nodes and attract more orders.
* Coordinating with traders to receive a fee outside of the system that doesn't get shared with the other nodes in the network.
* To disrupt the network (may be profitable for a dark pool competitor).

The protocol already makes these attacks expensive and difficult by requiring that nodes form a consensus about orders that are matched. If the behaviour of a single node diverges from that of all other nodes, it will not be able to influence the network.
