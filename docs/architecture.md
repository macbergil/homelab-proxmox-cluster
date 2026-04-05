# Architecture Overview

## Cluster Design

The cluster consists of 3 Proxmox nodes:

- node1
- node2
- node3

Each node contributes compute and storage resources.

## Storage

- ZFS pools on each node
- Replication between nodes
- Snapshot-based strategy

## Backup

- Dedicated Proxmox Backup Server
- Scheduled backups
- Retention policies

## Networking

- Management network
- Cluster network
- VM network (segregated)

## Future Improvements

- VLAN segmentation
- High availability tuning
- Monitoring integration