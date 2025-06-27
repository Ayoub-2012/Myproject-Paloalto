# Myproject-Paloalto
This project sets up a complex network topology using Palo Alto firewalls for securing and managing traffic between different network segments. The topology includes three Palo Alto firewalls (PaloAlto1, PaloAlto2, PaloAlto3) connected via a central router (R1). Each firewall is associated with a distinct Virtual Private Cloud (VPC), namely VPC1, VPC2, and VPC3, and is connected to an external network (Net1, Net2, Net3) for management.

Routing between these elements is handled by the OSPF protocol, ensuring efficient communication between the various subnets. To secure inter-firewall exchanges, three IPSec tunnels have been configured, ensuring secure and encrypted connections between each pair of firewalls.

IP addresses and interfaces are carefully configured to allow optimal traffic management and ensure connectivity between the different components of the network. This project is designed to simulate a secure and adaptable network environment, ideal for testing advanced security configurations and routing scenarios in a multi-site context.
