
<h1>IPSEC-Configuration Lab </h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this lab, we will build a secure network configuration using a Palo Alto firewall, FortiGate firewall, and Layer 3 switching. We will establish a VPN connection between the Palo Alto and FortiGate firewalls, enable NAT for specific traffic, and control internet access.


Step 1: Palo Alto to FortiGate VPN Connection
Configure a VPN connection between the Palo Alto and FortiGate firewalls to create a secure tunnel for traffic.
Ensure that PC3 can ping PC1 through the established VPN tunnel.
Ensure that PC3 can ping R1, R2, and R3 using the FortiGate outside interface as the source.

Step 2: Adding PC4 and Configuring SW2
Add PC4 to the network and assign it the IP address 192.168.4.4.
Configure SW2 as a Layer 3 switch to enable routing capabilities.

Step 3: Testing PC4 and Internet Access Control
Test PC4 by ensuring it can ping PC3 and the FortiGate firewall.
Implement access control to allow only the 192.168.4.0/24 network to access the internet.
Ensure that PC4 can access the internet and ping R2 and R3.
Restrict PC3 from having internet access.
Verify that PC3 can still ping R2 and R3.

<br />

<h2>Languages and Utilities Used</h2>

- <b>Palo Alto Firewall </b>
- <b> Fortinet Firewall </b> 
  
<h2>Environments Used </h2>

- <b>Eve ng</b> (21H2)
- <b>VM workstation </b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
IPSEC: <br/>
<img src="https://i.imgur.com/4sG6xLa.png" height="80%" width="80%" alt="IPSEC"/>
<br />
<br />

