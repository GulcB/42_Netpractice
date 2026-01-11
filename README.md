*This project has been created as part of the 42 curriculum by gbodur.*

# NetPractice

## Description
NetPractice is a general practical exercise designed to introduce the basics of computer networking. The main goal of this project is to configure small-scale networks by solving a series of 10 levels. It requires a solid understanding of how devices communicate, how IP addressing works, and how to manage traffic flow between different subnets.

Throughout the project, I learned to configure IP addresses, connect devices through routers, and understand the critical role of gateways and subnet masks within a network infrastructure.

## Instructions

### Installation and Execution
1. Download the project file from your intra account attached to the subject page.
2. Extract the files into a folder.
3. Open the `index.html` file in a web browser.
	* *Note: It is strongly recommended to use Google Chrome or a Chromium-based browser, as Firefox may have compatibility issues in the subject.*
4.  Enter your 42 intranet login in the interface to start the training.

### How to Use
* **Training:** Adjust the configuration fields (IP, Mask, Routes, Interfaces) for each level until the goals are met.
* **Export:** Once a level is succeeded, click the **"Get my config"** button to download the configuration file for that specific level.
* **Submission:** Repeat the process for all 10 levels.
* **Test Yourself** Use evaluation button to test your knowledge with random levels between 6-10.

### Submission Details
The repository root contains exactly 10 exported configuration files (one for each level) and a README as required by the subject.

## Resources

### Networking Concepts Studied
This project relies on the understanding of the following core concepts:
* **TCP/IP Addressing:** Learned how to assign unique IP addresses to devices to prevent conflicts and ensure proper communication.
* **Subnet Mask:** Used masks to define the "size" of a network, determining which IP addresses belong to the local group and which ones are outside.
* **Default Gateway:** Understood that the gateway acts as the "exit door" for the network; without it, devices cannot reach the internet or other subnets.
* **Routers and Switches:** Grasped the key difference: switches connect devices in the same "room" (network), while routers connect different "rooms" together.
* **OSI Layers:** Gained insights into the OSI model, specifically focusing on **Layer 3 (Network Layer)** where IP addressing and packet routing operate.

### AI Usage
As permitted by the subject, AI tools were used to assist in the learning process:
* **Concept Explanation:** AI was used to clarify the logic behind "Default Routes" (`0.0.0.0/0`) and why they are mandatory for internet access in this project.

### References
* 42 NetPractice Subject PDF
* [Transmission Control Protocol - TCP](https://www.geeksforgeeks.org/computer-networks/what-is-transmission-control-protocol-tcp/)
* [Role of Subnet Mask](https://www.geeksforgeeks.org/computer-networks/role-of-subnet-mask/)
* [TCP/IP Model](https://www.geeksforgeeks.org/computer-networks/tcp-ip-model/)
* [What is OSI Model? - Layers of OSI Model](https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/)
* [Types of Network Topology](https://www.geeksforgeeks.org/computer-networks/types-of-network-topology/)
* [IPv4 Datagram Header](https://www.geeksforgeeks.org/computer-networks/introduction-and-ipv4-datagram-header/)
* [Difference Between IPv4 and IPv6](https://www.geeksforgeeks.org/computer-networks/differences-between-ipv4-and-ipv6/)
* [Public and Private IP addresses](https://www.geeksforgeeks.org/computer-networks/difference-between-private-and-public-ip-addresses/)
* [Introduction To Subnetting](https://www.geeksforgeeks.org/computer-networks/introduction-to-subnetting/)
* [Role of Subnet Mask](https://www.geeksforgeeks.org/computer-networks/role-of-subnet-mask/)

## Acknowledgements
I would like to thank all 42 Istanbul students who shared their knowledge with me during my NetPractice learning process.