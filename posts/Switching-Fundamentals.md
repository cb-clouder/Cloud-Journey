In this lesson I learned about switches which are a lot like routers in the sense that they direct traffic. Switches forward frames using MAC addresses within a local network, while routers forward packets using IP addresses between networks.
I also learned the difference between access ports and trunk prots. Access ports carry untagged frames for a single local network and keep each device’s traffic isolated. Trunk ports carry tagged frames for multiple local networks using the IEEE 802.1Q standard, allowing networks to extend across multiple switches without compromising separation or security.

## Terms to know:

- Access Port: A switch port that connects to a single end device and carries untagged frames for one local network.

- Broadcast Frame: A frame sent to the special MAC address FF:FF:FF:FF:FF:FF, meaning it is delivered to all devices within the same VLAN or broadcast domain.

- Filtering: The process a switch uses to control which frames are forwarded, flooded, or dropped in order to reduce unnecessary traffic and improve network efficiency.

- Flooding: A Layer 2 process in which a switch sends a frame out of all ports within a VLAN, except the incoming port, when the destination MAC address is unknown.

- IEEE 802.1Q: An Ethernet standard that defines how network devices add and remove tags from frames, allowing multiple local networks to share one link while keeping traffic separate.

- Multicast Filtering: A switch process that forwards multicast frames only to ports that have requested to join the multicast group, reducing unnecessary network traffic and improving efficiency.

- Multicast Frame: A frame sent to multiple devices that belong to a specific multicast group, allowing one sender to reach many recipients efficiently.

- Trunk Port: A switch port that connects switches or routers and carries tagged frames for multiple local networks on the same physical link.

-Unknown Unicast: A frame whose destination MAC address is not yet listed in the switch’s MAC address table. The switch temporarily floods the frame until it learns the correct destination.
