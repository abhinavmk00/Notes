**Range**: `1.0.0.0` to `126.255.255.255`

**Default Subnet Mask**: `255.0.0.0` (/8)

**Network Bits**: 8 bits

**Host Bits**: 24 bits

**Number of Networks**: 128 (2^7, since the first bit is fixed at 0)

**Number of Hosts per Network**: 16,777,214 (2^24 - 2)

**Purpose**: Designed for extremely large networks, such as ISPs, large corporations, or large-scale institutions.

**Example:**
- **IP Address**: `10.25.36.128`
    - **Network ID**: `10.0.0.0`
    - **Host ID**: `25.36.128`

The first bit of a Class A address is always **0**, and the first octet ranges from 1 to 126. This class has a large number of host addresses because 24 bits are available for the host.