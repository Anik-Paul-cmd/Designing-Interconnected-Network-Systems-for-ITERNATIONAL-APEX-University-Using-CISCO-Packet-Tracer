# Designing-Interconnected-Network-Systems-for-ITERNATIONAL-APEX-University-Using-CISCO-Packet-Tracer

Introduction:

Technology has reached its highest peak of development, especially in making life easier for people. Well implemented technology is faster than human in processing calculation and is more accurate. Technology has become an important concept in our life. It assists in connecting communities together. Obviously, people have started to use technology in every field of life including education, health, the military, etc. The computer network represents a component, especially on how it enhances the functional performance in different fields and organizations. Most of the university’s computer network perform so many functions, such as connecting students with the university, faculty, lab, library and the many other controls. For this reason, computer networks play a vital role in the education area by providing efficient communications for the university environment. However, the design of computer networks differs from one university to another. This is as a result of many factors which determine the differences. 
In our project, our task is to create a complete model of the complex network by discovering the interconnectivity of the systems and sub networks, which will reflect the ITERNATIONAL APEX University’s structure and facilities. We have used CISCO Packet Tracer as a simulation tool in our project.

Objectives:
The main goal of this project is to present a Local Area Network model design suitable for a University by discovering the interconnectivity of the systems and sub-networks. Many universities are searching for ways to integrate networks that have security, backup, and other features available in a university network. The universities are faced with challenges in designing a network that is equal in the standards used by developed countries. The main problem they face deals with a profound budget deficit. This project will help these universities to design a network that employs low-cost solutions without unacceptable compromises in security or quality.
The qualities that reflects the characteristics of an effective and efficient University Network are
1.	Capacity: This is the ability of the network to withstand intense pressure from utilization. Most times, the networks are mainly crowded by many users that the network capacity could not handle. It is very important to design a network in such a way to handle many users without failure. This network is designed for as a sample so that it can be increased as needed later on. If more users access the network, it will be able to scale.

2.	Reliability: Reliability refers to the ability of the computer network’s hardware and software component to consistently perform according to its specifications. This project’s network will be highly reliable in performance because its components will be chosen from Cisco company, a major and well-regarded manufacturer. This is because there are many powerful devices are used in filtering data entering into the network. If any issue happens to the data, there is a way of restoring the data from backup servers. 

3.	Constraints: There is also some constraints that are given to be remembered with caution while designing the network. It was told to configure DHCP server and Web Server (HTTP) and also to follow IPV4 Addressing. The DHCP configuration should automatically assign IPV4 address to any host from the assigned IPV4 address block of the design.
Component for This Project:
1.	PC 
2.	Laptop
3.	DHCP Server 
4.	DNS Server 
5.	HTTP Server 
6.	Switch 
7.	Router
8.	Wireless Router 

Connection Setup:
The network is divided into subnets and all the subnets are connected through router and all routers are interconnected to each other. All the servers are in specific subnets. Each classroom lab, library, employee’s pc, staff’s pc has own subnets. All the IP of pc are provided through one DHCP server. The figure below shows the connection setup of all devices.

Design of the Network:
![image](https://github.com/Anik-Paul-cmd/Designing-Interconnected-Network-Systems-for-ITERNATIONAL-APEX-University-Using-CISCO-Packet-Tracer/assets/57853726/6fdc461c-1d88-4e47-89e1-50941c606997)
The network that we designed maintaining those several criteria looks like this. There is are routers through which the other sub-networks are connected like server, classroom, Labs, Library, Employee and other administrative and academic wings. On top of that university runs a number of complex networked systems to support several business processes like admissions, results, eTender, advising and so on. For simplicity only 5 host has been taken in each of the subnets and 1 host with server for test. If more hosts are needed that can also be concluded with the existing system by switches. There is also a Access point wireless to provide Wi-Fi connection to the students of the university.

Implementation and Functionality:
•	Network and Subnetwork: we used class B type IP address, that is 160.15.0.0 and we used 4 bit for subnet so subnet mask is 255.255.240.0 So each subnet can have 212 hosts. First subnet of network is 160.15.16.0 where all the servers are connected.
•	Personal Computers: Each personal computer is connected to a switch. Each computer needs a IP address which is provided automatically by the DHCP Server. Using HTTP and DNS server we can browse in university website.


<img width="282" alt="image" src="https://github.com/Anik-Paul-cmd/Designing-Interconnected-Network-Systems-for-ITERNATIONAL-APEX-University-Using-CISCO-Packet-Tracer/assets/57853726/eca4cab3-5f71-40db-9b77-99e6ac81722c">


<img width="408" alt="image" src="https://github.com/Anik-Paul-cmd/Designing-Interconnected-Network-Systems-for-ITERNATIONAL-APEX-University-Using-CISCO-Packet-Tracer/assets/57853726/56ebd18c-3aeb-47a4-9681-6de390130a87">

•	Laptops: Laptops and wireless device are for students and which are connected by the wireless router and IP addresses are distributed by that wireless router.


<img width="275" alt="image" src="https://github.com/Anik-Paul-cmd/Designing-Interconnected-Network-Systems-for-ITERNATIONAL-APEX-University-Using-CISCO-Packet-Tracer/assets/57853726/3be9c268-49ce-49d4-810f-71b29b3f4d6c">



•	 Switches: Switches are devices used on the network to transmit and receive data from one device to another or to many devices depending on the message intended. Switches are connected to multiple host server or routers. Switches also perform functions from the Data Link Layer.
•	Routers: Routers are connected to each subnets. We used 3 routers which are interconnected to each other, to expand the subnets routers are connected to switches. To configure routers there are two option CLI command and config to type and save all the necessary terms(IPs, tables, routes). We mostly used config option and few command which we cant configure in config. 
![image](https://github.com/Anik-Paul-cmd/Designing-Interconnected-Network-Systems-for-ITERNATIONAL-APEX-University-Using-CISCO-Packet-Tracer/assets/57853726/1f0fed88-4957-49d1-b99c-3eef000c11b9)
•	Wireless Routers: This is use to provide wireless network. Which is connected to a subnet by switch. Internet is configured by DHCP and LAN is configured statics. This LAN provide wireless devises a unique subnets IP address. 












