# proxmox for school
short plan on how to use proxmox as a learning tool for students to get started on linux and making virtual machines

# What is proxmox?
Proxmox is an open source debian-based operating system that is used for making multiple virtual machines and containers. It is commonly installed on headless servers and is accessed through a web browser. It is a tool commonly used on enterprise settings, homelabs, and now on education settings! 

Proxmox is a flexible tool that can be used by new and advanced users through its easy-to-use web gui, or through an ssh shell or the built-in terminal that can let you write commands onto the server easily.

# Why proxmox?
Although there are other options and solutions, proxmox is one of the easiest, common, and well documented options which can make it easy for both students and teacher to troubleshoot issues, search up solutions to problems, and configuring the server. System admins are easily able to receive help through online forums, documentations, and even the paid enterprise solutions that can be bought. 


# Getting started
## Type in the ip address of the server

GSAL5: 10.56.67.41:8006
GSACRD: current: 10.56.56.168:8006
todo: give static ip to GSACRD rather than dhcp for consistency

## Login
Teacher: login to root via linux PAM auth

Student: login to specified student account via proxmox VE auth
