# How to setup a wireless network in Windows - 


## Required Equipments - 

**Broadband Internet connection and modem** -



*  A broadband Internet connection is a high-speed Internet connection.
* Digital Subscriber Line (DSL) and cable are two of the most common broadband connections. 
* You can get a broadband connection by contacting an Internet service provider (ISP).
* Typically, ISPs that provide DSL are telephone companies and ISPs that provide cable are cable TV companies. 
* ISPs frequently offer broadband modems. Some ISPs also offer combination modem/wireless routers.

**Wireless router** -



*  A router sends info between your network and the Internet. It is a new gen of router to replace the wired router. Wireless router is a combination of router, switch and WiFi access point in a box, there are three functions combine together so wireless router become very common in now days. Wired router is becoming less and less common and now mostly users would choose wireless router because it is convenience for smart phone, laptop and any device can connect with wireless. 
* With a wireless router, you can connect PCs to your network using radio signals instead of wires. 
* There are several different kinds of wireless network technologies, which include 802.11a, 802.11b, 802.11g, 802.11n, 802.11ac, and 802.11ax. 

**PCI Adapter** - 



* PCIe is short for “**peripheral component interconnect express**” and it's primarily used as a standardized interface for motherboard components including graphics, memory, and storage.

**Access Point** - 



* The access point is a device that links a wireless network to a wired LAN to connect to the internet. An access point can be a standalone hardware device or a computer with a wireless network adapter and appropriate software

**Wireless network adapter -**



*  A wireless network adapter is a device that connects your PC to a wireless network. 
* To connect your portable or desktop PC to your wireless network, the PC must have a wireless network adapter. 
* Most laptops and tablets—and some desktop PCs—come with a wireless network adapter already installed.

To know if your device has a network adapter - 



1. Select start and search for “device manager” and select Device Manager.
2. Click on the arrow next to “network adapters” .
3. Look for a network adapter that might have **wireless** in the name.


## Securing your wireless network -



* **Change the default user name and password - **Most router manufacturers have a default user name and password on the router and a default network name (also known as the SSID). Someone could use this info to access your router without you knowing it. To help avoid that, change the default user name and password for your router.
* **Set up a security key (password) for your network** - Wireless networks have a network security key to help protect them from unauthorized access. Wi-Fi Protected Access 3 (WPA3) security is recomended if your router and PC supports it Some routers support Wi-Fi Protected Setup (WPS). If your router supports WPS and it’s connected to the network, follow these steps to set up a network security key -
* In Windows 7 or Windows 8.1, select **Start**, start typing **Network and Sharing Center**, and then choose it in the list.
* In Windows 10, select **Start **, then select **Settings **> **Network & Internet**  > **Status** > **Network and Sharing Center**.
* In Windows 11, select **Start**, type** control panel**, then select** Control Panel** > **Network and Internet** > **Network and Sharing Center**. 
* Select **Set up a new connection or network**.
* Select **Set up a new network**, then choose **Next**.

### Ping -

This command is used to test connectivity between two nodes. Ping use ICMP (Internet Control Message Protocol) to communicate to other devices. You can ping host name or ip address using below command. 

example: ping 201.54.100.1 or ping www.google.com


## How to run a ping network test?

#### For Windows 10 and 11 go to Search in the taskbar and - 



1. Type “cmd” to bring up the Command Prompt.
2. Open the Command Prompt.
3. Type “ping” in the black box and hit the space bar.
4. Type the IP address you’d like to ping (e.g., 192.XXX.X.X).
5. Review the ping results displayed.

#### For Macs, follow the same cadence by opening Network Utility and inputting the hostname or IP address you’d like to ping.

#### For Linux, open Terminal. You can also use the traceroute command to review the different IP addresses your request routes through. To do this, simply:



1. Open Terminal.
2. Type “traceroute” followed by the IP address or URL you wish to trace.
3. Hit Enter and review the results.

DHCP **- Dynamic Host Configuration Protocol** (DHCP) is a client/server protocol that automatically provides an Internet Protocol (IP) host with its IP address and other related configuration information such as the subnet mask and default gateway.

#Hostname - 
Gives the host name of the computer you are logged into. 

### Traceroute - 
Traceroute is a network troubleshooting utility which shows number of hops taken to reach destination also determine packets traveling path. Example: 



* Windows - tracert google.com
* Linux - traceroute google.com

### Netstat -

Netstat (Network Statistic) command displays interfaces, connection information, routing example: netstat

Execute it with the following options and write the output:

netstat –t

netstat –s –t 

netstat -i 

### Whoami -

The whoami command writes the user name (i.e., login name) of the owner of the current login session to standard output.

### Tcpdump - 

Tcpdump prints out a description of the contents of packets on a network interface that match the boolean expression; the description is preceded by a time stamp, printed, by default, as hours, minutes, seconds, and fractions of a second since midnight. 

Example (Linux) - tcpdump 

Sample output - 


```
arp who-has 128.3.254.6 tell 128.3.254.68 arp reply 128.3.254.6 is-at 02:07:01:00:01:c4
```


### Wireshark - 

![image](https://user-images.githubusercontent.com/74425589/199260311-3a68c064-a8bf-4994-8538-6de1027cfeb1.png)


Wireshark is a free and open source packet analyzer. It is also a protocol analyzer tool which captures network traffic and analyzes it. It is used for network troubleshooting, analysis, software and communications protocol development, and education. Originally named Ethereal, the project was renamed Wireshark in May 2006 .


### Purpose of wireshark - 



*  network administrators use it to troubleshoot network problems
* network security engineers use it to examine security problems 
* developers use it to debug protocol implementations 
* people use it to learn network protocol internals

## Assignment - 



1. Find the IP address of the network you are connected to.
2. Find which security is RVU wifi network using? (WEP, WAP/WAP2/WAP3)
3. Ping RVU website.
4. Check the hostname of your device.
5. Find details of any 5 computers 

<table>
  <tr>
   <td>
MAC Address
   </td>
   <td>IP Address
   </td>
   <td>LAN Speed
   </td>
   <td>Host Name
   </td>
   <td>Default Mask
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>




6. Does the network used in RVU have a DHCP server?
7. If yes, what is the address of the server, if no write “NA”.
8. Are the IP addresses assigned to the computers statically or dynamically? 
9. What are the types of cables used in the computers in lab to provide internet connection.
10. What is the IP address of the router / gateway of the internet used in your home/hostel? 
11. Capture and view network traffic using wireshark.
12. View the detailed contents of the following packets in hexadecimal. i. Ethernet ii. IP iii. TCP iv. ARP
13. Use the TCP dump command.
14. Ping the local host using `ping 0`
15.  Try using gping in your terminal ( [https://github.com/orf/gping](https://github.com/orf/gping) )
