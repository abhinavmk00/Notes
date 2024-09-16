**Classful IP addressing** is an early method of dividing the IPv4 address space into predefined classes. It was designed to simplify IP address allocation by defining fixed boundaries between the **network ID** and **host ID**.

The system divides the IP address space into five classes:
[[Class A]]
[[Class B]]
[[Class C]]
[[Class D]]
[[Class E]]

| Class | Range of First Octet | Binary Representation (First Bits) | Subnet Mask         | Use Case                                   |
| ----- | -------------------- | ---------------------------------- | ------------------- | ------------------------------------------ |
| A     | 1 to 126             | 0xxxxxxx                           | 255.0.0.0 (/8)      | Very large networks (e.g., ISPs)           |
| B     | 128 to 191           | 10xxxxxx                           | 255.255.0.0 (/16)   | Medium-sized networks (e.g., universities) |
| C     | 192 to 223           | 110xxxxx                           | 255.255.255.0 (/24) | Small networks (e.g., home networks)       |
| D     | 224 to 239           | 1110xxxx                           | N/A                 | Multicasting                               |
| E     | 240 to 255           | 1111xxxx                           | N/A                 | Experimental use                           |
