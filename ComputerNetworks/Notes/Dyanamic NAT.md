Dynamic NAT maps private IP addresses to public IP addresses dynamically from a pool of available public IPs. Unlike static NAT, dynamic NAT does not have a one-to-one mapping. Instead, a device on the local network is assigned a public IP address only when it initiates traffic to the internet.

##### Key Features:
- **Many-to-Many Mapping**: Multiple devices on the local network are mapped to a pool of public IP addresses. The mapping is temporary and changes as devices make new connections.
- **IP Pool**: Dynamic NAT uses a pool of public IP addresses, and when a device needs to access the internet, it picks an available address from the pool. Once the connection is terminated, the address can be reassigned to another device.
- **Efficient Use of IPs**: Dynamic NAT allows for the reuse of public IP addresses, making it more efficient than static NAT when a large number of devices access the internet but don’t need to maintain a fixed address.
##### Use Case:
- Dynamic NAT is useful in environments where many devices need occasional access to the internet but don't require permanent, fixed public IPs.
##### Example:
- Pool of Public IPs: 203.0.113.1 - 203.0.113.20
- Private IP: 192.168.1.20 initiates an internet connection and is dynamically assigned 203.0.113.5 from the pool. Once the session ends, 203.0.113.5 can be reassigned to another device.