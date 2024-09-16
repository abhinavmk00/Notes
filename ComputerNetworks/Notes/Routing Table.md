A **routing table** is a database maintained by a router or a network device that contains information about how to reach different network destinations. Each entry in the routing table represents a route to a particular network or host and includes information such as:

- **Destination Network:** The IP address range or network identifier of the destination.
- **Subnet Mask:** Defines the network portion and host portion of the IP address.
- **Next Hop:** The IP address of the next router or gateway to which packets should be forwarded.
- **Interface:** The network interface through which the packet should be sent.
- **Metric:** A value that indicates the cost or distance to the destination, used to determine the best route.

##### Directly Connected Routes
**Directly connected routes** are routes to networks that are directly attached to the router's interfaces. These routes are automatically added to the routing table when an interface is configured with an IP address and subnet mask. Here’s how it works:

- **Automatic Addition:** When a router's interface is assigned an IP address, the network connected to that interface is added to the routing table as a directly connected route.
- **No Configuration Needed:** There is no need to manually configure these routes since they are automatically recognized by the router.
- **Example:** If a router has an interface with IP address `192.168.1.1/24`, the network `192.168.1.0/24` is considered directly connected.

##### Static Routes
**Static routes** are manually configured routes that provide a specific path to a destination network. These routes do not change unless manually updated. Here’s how static routes work:

- **Manual Configuration:** Network administrators manually enter static routes into the routing table. This is done using configuration commands or through network management interfaces.
- **No Automatic Updates:** Static routes do not change automatically; they must be updated manually if network changes occur.
- **Usage:** Static routes are useful for defining specific paths, controlling traffic, or setting up routes for particular destinations. They are also used for security purposes or to manage traffic efficiently.

##### Dynamic Routes
**Dynamic routes** are automatically learned and updated by routing protocols. These protocols enable routers to share information about network reachability and topology changes. Here’s how dynamic routes work:

- **Routing Protocols:** Dynamic routing protocols such as RIP (Routing Information Protocol), OSPF (Open Shortest Path First), and EIGRP (Enhanced Interior Gateway Routing Protocol) are used to exchange routing information between routers.
- **Automatic Updates:** Routers automatically update their routing tables based on information received from other routers. This allows for adaptive routing where routes can change in response to network topology changes.
- **Metrics and Algorithms:** Dynamic routing protocols use various metrics and algorithms to determine the best path to a destination. For example, OSPF uses link-state information to build a complete map of the network, while RIP uses hop count as a metric.