**Range**: `128.0.0.0` to `191.255.255.255`

**Default Subnet Mask**: `255.255.0.0` (/16)

**Network Bits**: 16 bits

**Host Bits**: 16 bits

**Number of Networks**: 16,384 (2^14, since the first two bits are fixed at 10)

**Number of Hosts per Network**: 65,534 (2^16 - 2)

**Purpose**: Used for medium to large-sized networks, such as universities, large businesses, and government institutions.

**Example:**
- **IP Address**: `172.16.4.2`
    - **Network ID**: `172.16.0.0`
    - **Host ID**: `4.2`

The first two bits of a Class B address are always **10**, and the first octet ranges from 128 to 191. Class B provides a good balance between the number of networks and the number of hosts.