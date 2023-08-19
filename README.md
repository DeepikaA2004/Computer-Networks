# Computer-Networks
Computer Networks
# HUB 
A hub, in the context of networking and technology, refers to a basic networking device that connects multiple devices in a local area network (LAN) and forwards data between them. However, it's important to note that hubs are largely outdated and have been largely replaced by more efficient devices like switches and routers. Here's a breakdown of what a hub is, its applications, advantages, and disadvantages:

**Applications:**
Hubs were primarily used to connect multiple devices within a small network, such as a home network or a small office network. They served as a central point for connecting computers, printers, and other devices to share resources and communicate. They were also used in educational environments and small-scale setups.

**Advantages:**
1. **Simplicity:** Hubs are simple devices that require minimal configuration. They automatically forward incoming data to all connected devices.
2. **Low Cost:** Hubs are usually cheaper than more advanced networking devices like switches or routers.
3. **Basic Connectivity:** Hubs can provide basic network connectivity for simple setups where advanced features aren't required.

**Disadvantages:**
1. **Inefficient Data Forwarding:** Hubs operate at the physical layer of the OSI model, meaning they broadcast incoming data to all connected devices. This creates unnecessary traffic and can lead to network congestion.
2. **Limited Bandwidth Sharing:** Since all devices connected to a hub share the same bandwidth, the overall network performance can degrade as more devices communicate simultaneously.
3. **Security Concerns:** Hubs do not provide any form of data filtering or security features. Any data sent over the network is visible to all connected devices, making it less secure than modern alternatives.
4. **Collision Domains:** In a hub-based network, all devices share the same collision domain. This means that if two devices transmit data simultaneously, a collision occurs, resulting in data retransmission and decreased efficiency.

Given the limitations of hubs, they have largely fallen out of use in favor of more sophisticated networking devices:

1. **Switches:** Switches are more advanced devices that operate at the data link layer (Layer 2) of the OSI model. They selectively forward data to the appropriate device based on MAC addresses, improving network efficiency and reducing collisions.
2. **Routers:** Routers operate at the network layer (Layer 3) and provide functionalities like IP address assignment, routing data between different networks, and implementing security features.

In summary, hubs were simple and inexpensive networking devices used to connect multiple devices in a LAN, but their inefficiencies and lack of advanced features have led to their obsolescence in modern networking setups. Switches and routers are now the preferred choices for creating efficient and secure networks.

#HUB OUTPUT
![hub output](https://github.com/DeepikaA2004/Computer-Networks/assets/110418508/4cc916f5-4f23-43e7-8fab-2d4cc875b3c7)

# SWITCH 
A switch is a networking device that operates at the data link layer (Layer 2) of the OSI model. It is designed to connect multiple devices within a local area network (LAN) and intelligently forward data only to the specific device it is intended for, rather than broadcasting it to all devices like a hub. This results in improved network efficiency and reduced congestion. Here's a breakdown of what a switch is, its applications, advantages, and disadvantages in computer networks:

**Applications:**
Switches are commonly used in various networking environments, ranging from home networks to large enterprise setups. Some common applications include:

1. **LAN Connectivity:** Switches are used to connect computers, printers, servers, and other devices within a LAN, allowing them to communicate efficiently.
2. **Data Center Networks:** In data centers, switches are used to create high-speed, low-latency networks to support the communication between numerous servers and storage systems.
3. **Enterprise Networks:** Large organizations use switches to build complex networks that connect different departments, branches, and devices while ensuring efficient data transmission.
4. **Voice and Video Streaming:** Switches are crucial for delivering quality voice and video streaming services by prioritizing and managing network traffic.

**Advantages:**
1. **Efficient Data Forwarding:** Switches use MAC addresses to forward data only to the intended recipient, reducing unnecessary network traffic and improving overall network efficiency.
2. **Reduced Network Congestion:** By forwarding data only to the relevant port, switches prevent network congestion that can occur with hubs or simple devices.
3. **Segmentation:** Switches can segment the network into separate collision domains, isolating network traffic and reducing the likelihood of data collisions.
4. **Enhanced Security:** Switches provide a level of security by isolating devices from one another. Devices on different ports cannot directly communicate unless network policies allow it.
5. **Higher Bandwidth:** Each port on a switch typically has its own dedicated bandwidth, allowing devices to communicate at their full speed without sharing bandwidth with other devices.

**Disadvantages:**
1. **Cost:** Switches are generally more expensive than hubs due to their advanced features and capabilities.
2. **Complexity:** While they offer greater efficiency, switches can be more complex to manage and configure compared to basic networking devices like hubs.
3. **Limited Broadcast Domain:** While switches greatly reduce unnecessary broadcasts, there can still be situations where broadcast traffic affects network performance.
4. **Single Point of Failure:** If a switch fails, all devices connected to it may lose connectivity, emphasizing the need for redundancy and backup solutions.

In summary, switches have become a fundamental component of modern computer networks due to their ability to intelligently manage network traffic, improve efficiency, and provide enhanced security. While they are more expensive and require some configuration compared to simpler devices like hubs, their advantages far outweigh their disadvantages in most networking scenarios.

# SWITCH OUTPUT
![Switch output](https://github.com/DeepikaA2004/Computer-Networks/assets/110418508/11c8a83c-7f03-43de-9453-df946d721f4d)

# ROUTER
A router is a networking device that operates at the network layer (Layer 3) of the OSI model. It is used to connect different networks together, such as local area networks (LANs) or wide area networks (WANs), and is responsible for directing data packets between these networks. Routers make intelligent routing decisions based on IP addresses, allowing data to be transmitted efficiently across different networks. Here's a breakdown of what a router is, its applications, advantages, and disadvantages in computer networks:

**Applications:**
Routers play a crucial role in connecting and managing network traffic between different networks. Some common applications include:

1. **Internet Connectivity:** Routers are used to connect home or business networks to the internet, enabling access to online resources and services.
2. **Network Segmentation:** Routers can segment large networks into smaller subnets, improving performance and security by controlling the flow of traffic.
3. **Virtual Private Networks (VPNs):** Routers can establish secure connections over public networks, allowing remote users or branch offices to access the main network securely.
4. **Interconnecting LANs:** In larger organizations, routers are used to connect multiple LANs across different locations, creating a wide area network (WAN).
5. **Quality of Service (QoS) Management:** Routers can prioritize certain types of network traffic, ensuring that critical applications like voice or video streaming receive sufficient bandwidth.
6. **Network Security:** Routers often include firewall features that help protect the network from unauthorized access and malicious attacks.

**Advantages:**
1. **Interconnects Networks:** Routers allow different networks with different addressing schemes to communicate, enabling global connectivity.
2. **Efficient Data Routing:** Routers use IP addresses to make intelligent routing decisions, directing data packets along the most optimal paths to reach their destination.
3. **Network Isolation:** Routers create separation between different networks, improving security by controlling which devices can communicate with each other.
4. **Scalability:** Routers can handle a large number of connections and network segments, making them suitable for both small and large-scale networks.
5. **Load Balancing:** Some advanced routers can distribute network traffic across multiple paths, preventing congestion on a single route.

**Disadvantages:**
1. **Complex Configuration:** Routers often require more complex setup and configuration compared to simpler networking devices like switches or hubs.
2. **Cost:** Routers can be more expensive than other networking devices due to their advanced routing capabilities and features.
3. **Single Point of Failure:** If a router fails, it can lead to network disruptions and loss of connectivity for devices relying on that router.
4. **Latency:** In complex network setups, routing decisions may introduce some latency, although this is usually negligible in well-designed networks.

In summary, routers are essential components in modern computer networks, enabling the interconnection of different networks and facilitating efficient data routing. Their ability to manage network traffic, provide security features, and create logical network segments makes them integral to the functioning of the Internet and various network environments.

# SWITCH -ROUTER- SWITCH

![switch-router-switch output](https://github.com/DeepikaA2004/Computer-Networks/assets/110418508/336a5c8c-35e2-4437-b268-52f461b6151d)
