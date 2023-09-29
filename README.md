# Preegaya
Group assignment 
**Introduction**:

The study focuses on designing a network for the small manufacturing company with a single factory and office buildings. The cloud services are used as a part of network. The study analyzes various cloud service options and estimate the cost for cloud services. The confidential information in the organization is kept in local servers. Different backup strategies are compared and analyzed based on the scenario. Since the network of manufacturing company is prone to various cyber security risk the study focus on conducting risk assessment to analyze the risks to recommend appropriate security controls. Project management approach is applied on the developing network design project by presenting a detailed project plan, and draft network design. The final part of the study presents a reflective work to state issues faced, experience and recommendation to work for a group projects in future.

**4 Tasks**

**4.1 Network Design** 

**4.1.1 List of Assumptions and Requirements**

**Requirements** 

Based on the scenario given about small manufacturing company, the network design incorporates following requirements. 
1.	Security Camera: IP-based security cameras should be present in the network of manufacturing company both inside and outside of the building for continuous security monitoring. 
2.	IP Subnets: Minimum three different IP subnets are required for the network i.e. separate subnet for factory, security cameras and office. 
3.	Subnet Masks: The subnet masks should be used in the network is either /24 or /16 network masks throughout the company’s network. Other subnet masks are not allowed to use. 
4.	Wired and Wireless Devices: Office and factory buildings contains wired desktop computers as well as wireless devices like laptops, monitoring equipment and phones are connected to the network. 
5.	Printers: Several general purpose printers are connected to the network which includes specialized printers like 3D printers. 
6.	Cloud Services: Cloud services are incorporated into the network of the company for website and email. 
7.	Local Servers: Office building contains local servers for sensitive information such as finances, engineering designs and intellectual property details. 
8.	Security: Security control are mandatory in the design of network for securing the information and network from various attacks. 
9.	Interface: LAN interface or wireless Wi-Fi interface are used in the network (Hassan & Mondol, 2015)


**Assumptions**:

Following assumptions are made during the network design. 
1.	The network design comply with relevant procedure and IP address standards. 
2.	The network design and development can be completed by meeting all the requirements stated. 
3.	Availability of network operation will be continued all the time without any downtime to achieve continuous operation. 
4.	The manufacturing company has fast internet connectivity to access cloud services. 
5.	The network can be scaled in future based on requirements.

**4.1.2 Network Design
Network Diagram**

The network diagram designed for the small manufacturing company has been presented above. The network diagram contains various components required to perform the operations of the company
**Diagram**
The initial network has been designed with two subnets for sales and customer support which has been depicted in figure 1. The initial network design contains two subnets such as sales and customer support. The initial design also incorporates servers such as web server, email server and DHCP server connected to the network of manufacturing company
**Diagram**

Figure 2 shows final network design of the manufacturing company which contains four subnets connected to the internet through router. The departments such as administration, engineering, sales and customer support are considered as separate subnets and each subnet contains laptop, desktop devices and other monitoring devices connected to the switch via access point (Huitao & Ruopeng, 2019)

**Key Design Decisions**:

The network diagram contains four subnets for each departments or operations in the company. The four subnets are for administration, engineering, sales and customer support. The two subnets such as sales and customer support are assigned with the network mask of /16 whereas administration and engineering are assigned with the network mask of /24. These network mask accommodates wired desktop computers and wireless devices connected to the network. 
IP Address Allocation for each subnet has been presented below, 
1.	Engineering: 1.100.24.0 /16
2.	Administration: 1.100.24.0 /16
3.	Customer Support: 64.44.0.0	/16
4.	Sales: 64.43.0.0 /16	
Since the group has two members with the IDs 12217501 and 12227964, the IP address in the network design starts with 01 and 64 i.e. 1.100.24.0 /16, 1.100.24.0 /16, 64.44.0.0	/16 and 64.43.0.0 /16 (Huitao & Ruopeng, 2019). 
Internet has been used for establishing communication in the network. The network contains two routers connected to subnets through switch. Each subnet contains access point which connects the Desktop computers, laptop, monitoring devices to the wired network. The network contains four server such as web server, email server, monitor server and DHCP server. The web server enables to access the internet and Email server facilitates to send and receive emails from the customers. DHCP server automatically fetches IP host based on the IP address along with relevant information such as default gateway and subnet mask. To improve the network performance as well as to establish intercommunication among devices present in each subnets, VLAN has been utilized (Hassan & Mondol, 2015).





