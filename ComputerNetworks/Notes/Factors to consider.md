##### 1. **Number of Subnets Required**:
- To create subnets, you need to borrow bits from the host portion of the IP address and assign them to the network portion.
- The number of bits you borrow determines how many subnets you can create.
- **Formula**: 2n2^n2n (where nnn is the number of borrowed bits).
- More borrowed bits = more subnets, but fewer host addresses per subnet.

##### 2. **Number of Hosts per Subnet**:
- The number of hosts in a subnet is determined by the remaining bits that are left for the host portion after subnetting.
- **Formula**: 2h−22^h - 22h−2 (where hhh is the number of bits left for hosts).
    - The `-2` is because one address is used for the **network ID** and one for the **broadcast address**.
- Fewer bits for hosts = fewer available addresses per subnet.

##### 3. **Block Size**:
- The **block size** refers to the range of IP addresses in each subnet.
- It’s determined by subtracting the subnet mask value from 256.
- **Formula**: 256−subnet mask256 - \text{subnet mask}256−subnet mask
- This value indicates how many IP addresses are available within each subnet range.

##### 4. **Number of Valid Hosts in Each Subnet**:
- The valid hosts are calculated by determining the total number of addresses in a subnet and subtracting 2 (network ID and broadcast address).
- **Formula**: Total IP addresses in a block (determined by block size) - 2.

##### 5. **Broadcast Address for Each Subnet**:
- The broadcast address is the last IP address in each subnet.
- It is reserved for broadcasting messages to all hosts in the subnet.
- It’s always the highest address in the subnet range.