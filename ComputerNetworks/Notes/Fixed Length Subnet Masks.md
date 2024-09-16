In **Fixed-Length Subnet Masking (FLSM)**, all subnets have the same size, meaning the same number of available host addresses in each subnet. FLSM is simpler to manage but can result in inefficient use of IP addresses.

**Advantages**:
* Easier to manage and calculate.
* Consistent size for subnets.

**Disadvantages**:
* Not flexible, which can lead to wasted IP addresses if the subnets don’t need the same number of hosts.
* Can be inefficient in cases where different subnets have different host requirements.

**Example**: Dividing a Class C network `192.168.1.0/24` into 4 subnets using FLSM:
- Subnet 1: `192.168.1.0/26` (64 addresses)
- Subnet 2: `192.168.1.64/26` (64 addresses)
* Subnet 3: `192.168.1.128/26` (64 addresses)
* Subnet 4: `192.168.1.192/26` (64 addresses)