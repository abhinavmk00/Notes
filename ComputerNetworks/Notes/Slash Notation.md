CIDR (Classless Inter-Domain Routing) notation, often referred to as **slash notation**, is a method used to denote IP addresses and their associated network prefixes. It replaces the older class-based IP addressing system and offers more flexibility in network allocation.

In CIDR notation, an IP address is followed by a forward slash (`/`) and a number, indicating how many bits of the IP address represent the network portion (or network prefix). The rest of the bits represent the host portion.


##### Example:
- **192.168.1.0/24**
    - **192.168.1.0** is the network address.
    - **/24** indicates that the first 24 bits are the network portion, leaving 8 bits for hosts.
    - This means the address range for hosts is from **192.168.1.1** to **192.168.1.254**

