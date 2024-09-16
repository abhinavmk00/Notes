Static NAT is a one-to-one mapping between a private IP address and a public IP address. It provides a fixed translation of IP addresses, meaning that a specific private IP address will always be mapped to the same public IP address.

##### Key Features:
- **One-to-One Mapping**: A single private IP address is mapped to a single public IP address. This means each private IP has a corresponding public IP.
- **Consistent Access**: Since the mapping is fixed, this type of NAT is useful when a device inside the local network needs to be consistently accessible from the internet. For example, a web server or an email server inside a network.
- **Limited to Specific Devices**: Static NAT is typically used for devices that need a permanent address and are expected to receive incoming traffic from the internet.

##### Use Case:
- Servers (like web or email servers) that must be reachable from external networks or clients require static NAT. For example, a web server with a private IP of 192.168.1.10 will always be reachable using its corresponding public IP address.

##### Example:
- Private IP: 192.168.1.10
- Public IP: 203.0.113.10
- This mapping is fixed, so whenever traffic comes in for 203.0.113.10, it is directed to 192.168.1.10.