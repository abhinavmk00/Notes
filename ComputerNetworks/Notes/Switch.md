**Definition**: A switch is a network device that connects devices within a single network segment and uses MAC addresses to forward data to the correct destination. It operates primarily at the data link layer (Layer 2) of the OSI model.

[[MAC Address Table]]

##### 1. Learn

**Learning** is the process by which a switch discovers and records the MAC addresses of devices connected to its ports. Here’s how it works:

- **Frame Reception:** When a switch receives a frame on one of its ports, it examines the source MAC address in the frame’s header.
- **Updating the MAC Address Table:** The switch records this MAC address along with the port number where the frame was received in its MAC address table (also known as the forwarding table). This tells the switch which MAC addresses are reachable through which ports.
- **Address Aging:** To manage the MAC address table size and account for devices that may disconnect or move, the switch uses a timer to age out entries. If no frames are received from a MAC address within a certain period, the entry is removed.

##### 2. Flood

**Flooding** occurs when the switch does not have an entry for the destination MAC address in its MAC address table. Here’s what happens during flooding:

- **Unknown Destination:** If the switch receives a frame with a destination MAC address that is not in the MAC address table, it doesn’t know which port to use to forward the frame.
- **Broadcasting the Frame:** The switch will broadcast the frame to all ports (except the one it was received on) in an attempt to reach the destination device. This means the frame is sent to every device on the network segment.
- **Learning from Responses:** When the destination device receives the frame, it responds, allowing the switch to learn the MAC address of the destination device and update its MAC address table accordingly. Future frames to this MAC address will be forwarded directly to the appropriate port.

##### 3. Forward

**Forwarding** is the process by which a switch directs frames to the appropriate port based on the information in the MAC address table. Here’s how forwarding works:

- **Destination Lookup:** When a switch receives a frame, it looks up the destination MAC address in its MAC address table.
- **Direct Forwarding:** If the MAC address is found in the table, the switch forwards the frame only to the port associated with that address. This targeted forwarding reduces unnecessary traffic on other ports.
- **Efficient Data Delivery:** By forwarding frames only to the specific port, the switch optimizes network performance and ensures that data is delivered quickly and efficiently to the intended device.

[[VLANs]]
[[Multiple Swithces]]