A **private IP address** is an IP address that is used within a local area network (LAN) or private network and is not routable over the Internet. Private IP addresses are used for internal communication within a network, such as in homes, offices, or schools.

- **Reserved for Internal Use**: Private IP addresses are reserved by **IANA (Internet Assigned Numbers Authority)** and can be used freely within a private network. However, devices using private IP addresses cannot communicate directly with the Internet without **Network Address Translation (NAT)**.
- **NAT (Network Address Translation)**: NAT allows devices on a private network to share a single public IP address for Internet access by translating private IP addresses to a public IP address when communicating externally.
- **Private IP Address Ranges** (defined by RFC 1918):
    - **Class A**: `10.0.0.0` to `10.255.255.255` (16,777,216 addresses)
    - **Class B**: `172.16.0.0` to `172.31.255.255` (1,048,576 addresses)
    - **Class C**: `192.168.0.0` to `192.168.255.255` (65,536 addresses)

**Usage**: Private IP addresses are typically used for devices that communicate only within a local network, such as computers, printers, smartphones, and other internal devices. They are common in homes, offices, and enterprise networks where multiple devices connect to the same router but do not need unique public IP addresses.