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

**Address Allocations**
**Table 1: IP Address Allocation Table
Table**

**Recommended Hardware**:

The network design contains following hardwares connected to the network.  
	Routers: The network design consist of two routers such as R1 and R2 which connects four packet-switched sub network to manage traffic in the network. The router receives and sends packets in the network of manufacturing company. 
	Switches: The network contains three switches such as switch 0, switch 1 and switch 2 that connects laptops, computers and other devices in the network. 
	Access Point: The Wi-Fi signal to the particular area in the subnets of office and factory building will be projected using access point which also connects router and switch. 
	Servers: Web server, email server, DHCP and monitor server are included in the network for effective communication (Hassan & Mondol, 2015).

**4.2 Cloud Services**
**4.2.1 Pricing for Cloud Services**:

The cost of cloud services are estimated in two different cloud service providers such as AWS and Microsoft Azure.

1.	**Amazon Web Server**:
    
Web server - $150 / month = $1800 / year 
Database Server - $100/ month = $1200 / year
Monitoring – Free 
Backup Server - $ 120/ month = $1440 / year
The total annual cost would be $ 4,440. 
2.	**Azure** :

Web hosting – $31.39 / month = $ 376.68 / year
Database Server - $2,635 / year
Backup Server - $ 200 / month =$ 4,800 / year
The total annual cost would be $7,811.68 (wp.nyu.edu, 2023)
.

**4.2.2 Backup Strategies** 
**Comparison of Backup Strategies** 
The company decided to keep confidential and sensitive information on local servers for ensuring security of those information. But backup of confidential information can be stored on cloud services only if the information is encrypted before sending to the cloud. The company focusing on three approaches such as 
1.	Local backup 
2.	Storing backup on cloud after information was encrypted before sending to cloud 
3.	Storing backup at cloud without encryption.
4.	
**Local Backup**:

In local back, the manufacturing company stores sensitive files into the local server which provides advantages and disadvantages as follows.

Table

**Cloud Backup with Encryption**:

 The backup files are encrypted before sending to the cloud in this approach
 Table

 **Cloud Backup without Encryption**:

 The files are not encrypted before sending to the cloud in this approach. 

  Table

  **Different approaches to Backup University Work**:
  
When working in a group project, it is necessary to back up the files of assessments for which various tools and approaches will be used. 
1.	**External Devices (Hard Disk / USB)**:
   
The university files and group project files can be stored in external physical storage devices like hard disk and USB drive. These type of storage are easy and highly convenient for backup. But the main thing to consider is the data may overflow the internal storage. These solutions are highly cost effective way of backing up the files.  
3.	**Google Drive:**:

The important university files will be imported to the Google drive which is an effective way of securing university files. The Google drive provides easy recovery of files as well as easy retrieval of files from anywhere and any device. If the data was lost, it can be easily recovered. The university files will be securely stored in world-class data centers. It provides higher level security because data is encrypted during transit and at-rest. 
4.	**Personal Cloud Server**: 

A personal cloud server efficiently stores personal files as well as university files in an effective way. Using shared network drives or network-attached storage, the personal cloud servers enables to upload the files as well as download the files over internet. These cloud storage are different from conventional cloud servers because the personal cloud server allows the users to own and manage the data. Personal cloud server would be the best option for storing university files because it is highly scalable, provides better performance, secured and easily configured based on user needs (Tozzi, 2023). 

4.3 **Security**:

4.3.1 **Cyber Security Risk Assessment**:

The risk assessment has been conducted for the network design. The network designed for manufacturing company consist of following assets

Table

Table

The vulnerability assessment has been conducted for the identified assets present in the network of manufacturing company. For each asset specific vulnerability and threat has been identified. The vulnerability assessment also provides impact and likelihood of occurrence of each vulnerabilities. Based on likelihood and impact each threats are ranked (Sánchez-García & Mejía, 2023)
.

4.3.2	**Recommended Security Controls**:

Based on NIST cyber security framework, unauthorized access thread on the data asset such as customer data, financial statements and engineering designs can be protected by implementing role based access control as it provides strong authentication. This ensures that the employees and other users to the network gets only necessary level of access to the sensitive information of a company. This mechanism significantly reduces the risk of unauthorized access by restricting access to sensitive and confidential information of manufacturing company (Hutchins, 2015). 

Based on ACSC essential eight framework, malware that affects desktop, laptop and mobile phones connected to the network can be addressed using below strategies, 
1.	Application control can be implemented which will prevent from unapproved and malicious program running on the desktop computers and other personal devices. 
2.	Patch application can be implemented which will significantly eliminate extreme vulnerabilities in the personal devices connected to the network. 
3.	Automated dynamic analysis of website and email will help to block suspicious behavior identified in the network such as network traffic and configuration changes. 
4.	User application hardening which includes configuring the web browsers to block unwanted ads and disabling unnecessary features (Hinge‬, 2023).
   
To protect against Denial of service attack that exploit network traffic and affects router capabilities, software based application firewall can be implemented. This strategy will significantly deny the network traffic. Intrusion detection and prevention system can be implemented in the network to successfully identify the network traffic and DoS attacks in real-time. To detect and protect functions in the NIST cyber security framework focuses on intrusion detection to successfully mitigate DoS attack by limiting the network traffic to the router. 

Spoofing attack can be effectively mitigated through Network Access Control Solution. Following capabilities of NAC solution can be utilized for avoiding spoofing attack and other vulnerabilities in the switch. 

	Enforcing policies for different scenarios to separate the modules or subnets in the network. 
	Profiling and visibility 
	Guest network access should be managed which include gust authentication, and guest management portal. 
	Enforcing security policies that successfully blocks and isolates noncompliant switches. 

Web application firewall can be implemented to prevent from SQL injection on server. When designing a network, a secure coding should be followed. This comes under protect function of NIST framework. The network administrator must enforce least privileges to the network which will protect against SQL injection attack (Ahmad, et al., 2010).  
To mitigate the VLAN hopping attack based on NIST cyber security framework, following steps can be followed. 

	Configuring the access point on the following modes such as dynamic desirable or, trunk or dynamic auto should be avoided. 
	The access ports should be manually configured and it is necessary to disable DTP on access ports 
	If an interface is not in use, then it need to be switched down. 

The double tagging also leads to VLAN hopping which can be prevented by keeping the native VLAN of trunk ports in the network different from user VLAN. Following these strategies VLAN hopping can be significantly mitigated and protected (Alshar’’e, 2023)

5 **Project Management** 
5.1	**Project Plan** 
A detailed project plan for network design project of small manufacturing company have been presented in the Gantt chart below.

  Table

The project will be implemented under five phases such as initiation, planning design and implementation. Testing and closure. The total duration of the project is 60 days. The network design project starts by 04-09-2023 and finishes off by 24-11-2023. All the tasks mentioned under each phases will be completed as scheduled (MEARDON, 2023).

**Communication Plan**:

Table

Diagram

The draft network diagram developed has been presented in figure 5. The network diagram shows the current network design developed by incorporating necessary subnets for sales, customer support, administration and engineering. Necessary servers such as web server, monitor server, email server and DHCP server have been connected to the network. VLAN has been used to connect multiple devices on the LAN to the network to ensure successful function of each subnets. IP address allocation shows that the devices on each subnet can be easily scaled.

5.3	**Project Reflection**:

The network design project was carried out as a group project with the two team members. The responsibilities of network design has been equally shared among the team members. Initially we have gathered enough information about the project requirement and the given case. Then the activities that need to be carried out to successfully complete the project have been estimated based on each activities or milestones, the responsibilities of a team members have been shared. Even though the each team members are responsible for carrying out different activities, we both worked together in all the phases of network design to ensure that the project meets all the requirements.

**What Went Well?**:

During the project, the team building and collaboration was successfully carried out. The team meetings are planned and executed effectively which helps to track the project progress successfully. For every month as well as every week, team meetings have been carried out to review the project progress and necessary changes. During the meeting, the ideas were brainstormed and presented. Effective decision making was carried out as a team. 
Learning in-depth networking concepts were another thing went well during the project. Before starting this project, I have limited knowledge about networking components and design. The project helped me to gain more knowledge about the network design for small manufacturing company. I have shared my knowledge with the team member and listed to the idea of a team member to successfully design a network. From the risk assessment, I have gained knowledge regarding various attacks and vulnerabilities of the network. The overall experience of network design project was amazing and it will be applied in future for designing a complex network (Farrah, 2012). 

**Issues Encountered**:

The main challenge I have encountered during the project was working with Cisco software. Since I do not have experience in working with Cisco packet tracer for network design, I struggled to work on the project during initial days. But I have referred to online videos and materials to gain information which helped me to successfully work with Cisco packet tracer tool.  I have also faced issues with IP address allocation due to limited knowledge. Later I have enhanced my knowledge by collaborating with the team member which helped me to successfully allocate IP addresses to the subnets.

**Recommendation**:

I will use task prioritization approach in future to successfully prioritize each tasks. This will solve the burden of completing the most important tasks within estimated timeframe and avoids project delays. Regular team reflection and feedback will be made to identify the areas of improvements in future. This will significantly improve the knowledge of each team member (Farrah, 2012).  


**References**
Ahmad, K., Shekhar, J. & Yadav, K., 2010. A Potential Solution to Mitigate SQL Injection Attack. VSRD Technical & Non-Technical Journal, 1(2), pp. 1 - 9.
Alshar’’e, M., 2023. Cyber Security Framework Selection: Comparision Of Nist And Iso27001. Applied Computing Journal , 3(1), pp. 1 - 11.
Farrah, M. A. A., 2012. Reflective Journal Writing as an Effective Technique in the Writing Process. An-Najah University Journal for Research - B (Humanities), 26(4), pp. 1 - 24.
Hassan, A. & Mondol, R., 2015. Computer network design of a company — A simplistic way. 2015 International Conference on Advanced Computing and Communication Systems (ICACCS), pp. 1 - 11.
Hinge‬, A., 2023. ACSC Essential 8 Cybersecurity Strategies, Maturity Levels, and Best Practices. [Online] 
Available at: https://blog.qualys.com/vulnerabilities-threat-research/2023/03/21/acsc-essential-8-cybersecurity-strategies-maturity-levels-and-best-practices
[Accessed 14 September 2023].
Huitao, W. & Ruopeng, Y., 2019. Research on IP Address Allocation of Tactical Communication Network. Journal of Physics: Conference Series, 1187(042105), pp. 1 - 8.
Hutchins, M. J., 2015. Framework for Identifying Cybersecurity Risks in Manufacturing. Procedia Manufacturing, Volume 1, pp. 1 - 17.
Kochovski, A., 2022. The Risks and Benefits of Cloud Storage in 2023. [Online] 
Available at: https://www.cloudwards.net/the-risks-and-benefits-of-cloud-storage/
[Accessed 13 September 2023].
MEARDON, E., 2023. What are Gantt charts?. [Online] 
Available at: What are Gantt charts?
[Accessed 14 September 2023].
Navsariwala, M., 2023. What is Localized vs. Remote Backup?. [Online] 
Available at: https://www.servermania.com/kb/articles/localized-vs-remote
[Accessed 26 September 2023].
Sánchez-García, I. D. & Mejía, J., 2023. Cybersecurity Risk Assessment: A Systematic Mapping Review, Proposal, and Validation. Applied Science , 13(395), pp. 1 - 29.
Tozzi, C., 2023. How to Build a Personal Cloud Server for Private File Storage at Home. [Online] 
Available at: https://www.itprotoday.com/cloud-storage/how-build-personal-cloud-server-private-file-storage-home
[Accessed 14 September 2023].
wp.nyu.edu, 2023. Ultimate Guide To Azure Costs For 2022. [Online] 
Available at: https://wp.nyu.edu/dispatch/ultimate-guide-to-azure-costs-for-2022/
[Accessed 14 September 2023].









