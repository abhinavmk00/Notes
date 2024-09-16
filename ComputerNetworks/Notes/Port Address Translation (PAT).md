Port Address Translation (PAT) allows multiple devices on a local network to share a single public IP address by using different port numbers. PAT is the most commonly used type of NAT in home and small business networks because it conserves IP addresses by allowing many devices to use one public IP.

##### Key Features:
- **Many-to-One Mapping**: Multiple private IP addresses can be mapped to a single public IP address. This is done by modifying the port numbers in the TCP/UDP headers of packets, allowing many devices to share the same public IP.
- **Port Differentiation**: When a device sends traffic to the internet, PAT assigns a unique port number to differentiate that device’s connection. For example, Device A might use port 12345, while Device B uses port 54321, but both share the same public IP.
- **Conserves Public IPs**: PAT is the most efficient in terms of IP address usage, as it allows many internal devices to be mapped to one public IP address.

##### Use Case:
- PAT is widely used in home networks where multiple devices (phones, laptops, smart devices) connect to the internet through a single public IP assigned by the ISP.

##### Example:
- Private IPs: 192.168.1.10, 192.168.1.11
- Public IP: 203.0.113.1
    - Device 192.168.1.10 might use public IP 203.0.113.1:50001.
    - Device 192.168.1.11 might use public IP 203.0.113.1:50002.

In this way, the router knows how to forward the returning traffic back to the correct internal device based on port numbers.