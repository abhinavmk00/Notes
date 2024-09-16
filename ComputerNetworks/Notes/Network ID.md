- The **Network ID** represents the specific network to which an IP address belongs.
- It is used by routers to determine where to send packets when routing across networks.
- All devices on the same local network share the same network ID.
- The number of bits allocated to the network ID depends on the subnet mask or CIDR notation.
##### Example:
- In the IP address **192.168.1.10/24**, the `/24` indicates that the first 24 bits represent the network portion.
- In binary, the IP address is: 11000000.10101000.00000001.00001010 
- With a `/24` subnet mask, the first 24 bits (**11000000.10101000.00000001**) are the **Network ID**.