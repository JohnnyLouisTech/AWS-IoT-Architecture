# AWS-IoT-Architecture
Computing As a Service 

<img width="317" alt="IoT Design" src="https://github.com/JohnnyLouisTech/AWS-IoT-Architecture/assets/29494723/ada2c108-abc7-4a3a-825b-0db4d757fd9d">




Computing as a Service

•	They are three errors that are represented in this diagram. These are the LANs, there are online connections, and no firewall showing.

•	First error is that there’s one LAN for the whole design with other components. We also have one single-line connection that connects the WAP and the Router/Modem. The network needs to have a well-configured firewall for all of the IoT devices to be secured in cases of an attack. With this, we’ll be able to see what type of data is coming and leaving the network. We’ll also have a chance to stop an attack before it enters our systems.

•	If this design needs to be redesigned, it would require everything to be redesigned to be successful. But as stated in the next question, the whole system can be functional without redesigning of the current issues.

•	This system will not have other problems operating besides being vulnerable to attackers. If the issues are addressed, they’ll be more secure. The LAN is fully operational and secured, however, it can be more secure if addressed. The firewall and the online connections are working but if addressed can be more secure from vulnerabilities in the network

•	One of the best solutions is to have two different LANs. We could install and configure a new router to the current modem. This will provide extra layers to the network.  

•	For the single-line connections, we could have another ethernet cable connect the routers and the WAPs. We could also add a switch for redundancy and installation between the WAPs, routers, and two other WAPs pet each switch. In the end, we’ll have separate LANs, and two routers, with each double-linked connected to the WAPs. We’ll also install the firewalls on the routers to successfully monitor the traffic on the LANs

•	Since we’ll be installing and configuring firewalls on the network, this will provide confidentiality and integrity for the data against attackers


o	The LANs would also provide the network with great confidentiality and integrity after separating more access points from the network

o	The network redundancy, we have set up, like the connections will be beneficial for the network systems and devices. It will provide data security and availability throughout the whole network. This will be eliminating other points of failure as they arise. We’ll also have a chance not to have our hardware taken down from the network.
