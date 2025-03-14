## Overview
This project is an implementation of the **Kademlia Distributed Hash Table (DHT)** in C++. Kademlia is a decentralized, peer-to-peer (P2P) network protocol that enables efficient key-value lookups without relying on a central authority. It is widely used in systems like BitTorrent for peer discovery.

## Features
- **Node Discovery**: Implements the Kademlia node lookup algorithm.
- **Routing Table**: Maintains an efficient routing table using the XOR metric.
- **Message Handling**: Implements Kademlia's key message types (`PING`, `STORE`, `FIND_NODE`, `FIND_VALUE`).
- **Bootstrap Mechanism**: Allows nodes to join the network dynamically.

## Why Kademlia?
Kademlia DHT is a fundamental component of decentralized applications, enabling:
- **Efficient Peer Discovery**: Used in BitTorrent, IPFS, and other decentralized networks.
- **Fault Tolerance**: The network remains operational even if some nodes leave.
- **Scalability**: Performs well with large numbers of nodes.

## How It Works
1. **Node Lookup**: Uses XOR-based distance metric for efficient routing.
2. **Data Storage & Retrieval**: Peers store and retrieve values based on a distributed key system.
3. **Joining the Network**: New nodes bootstrap by connecting to existing peers.

This project is part of: https://github.com/amit19singh/GgBitTorrent-Client 
