Network Address Translation (NAT) is a method used in networking to modify the IP address information in the header of packets as they pass through a router or firewall. The primary purpose of NAT is to enable multiple devices on a local network (LAN) to share a single public IP address when accessing external networks, such as the internet.

##### How NAT Works
When a device on the LAN wants to access an external resource (e.g., a website), the following happens:
- The device sends the packet to the router.
- The router modifies (translates) the private IP address of the device into its public IP address.
- The router also modifies the source port (in the case of **Port Address Translation** or PAT) and keeps track of this mapping in a translation table.
- When the response comes back from the external server, the router uses the translation table to match the incoming response with the original request and sends it back to the correct device in the LAN by reversing the translation.

##### Types of NAT:
[[Static NAT]]
[[Dyanamic NAT]]
[[Port Address Translation (PAT)]]

##### Benefits of NAT:
- **IP Address Conservation**: Reduces the number of public IP addresses needed by allowing many devices to share a single public IP.
- **Security**: Hides the internal IP addresses from the outside world, providing a layer of security.

##### Drawbacks of NAT:
- **Breaks End-to-End Connectivity**: NAT can interfere with some protocols or applications, especially those that require peer-to-peer connections or embed IP address information in the payload.
- **Complex Configuration**: Some services may require port forwarding or NAT traversal techniques to work properly.