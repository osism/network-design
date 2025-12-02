# network-design
Example network designs for cloud deployments

## netlab examples

- netlab-frr-l3-core-vrf

Leaf/spine topology of FRR devices with different VRFs for "leaf" and "border" servers.

TODOs:
- activate "address-family l2vpn evpn" on spine/leaf/border BGP sessions
- work without IPv4 addresses on all interfaces
- make spine use the same ASN without having to add an IGP?
- create port-channel between spines?
