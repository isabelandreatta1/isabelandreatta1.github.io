<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<h1>
    Important Terminology for Networks
</h1>

<h3>Different types of networks</h3>
<p>Order from smallest to largest access</p>
<p>1. PAN: personal area network (personal level, wireless technolog or wire connection, transfer small files e.g. music and files)</p>
<p>2. LAN: local area network, group of devices in same building or close proximity, most common is ethernet lan using a switch</p>
<p>3. WLAN: wireless lan, at least two devices that use wireless connection to create a LAN (wifi router)</p>
<p>4. CAN: Campus area network, joins 2 LANS together within limited area (e.g. university w different departments)</p>
<p>5. MAN: Metropolitan Area network, connected thru high speed connection like fiber optic network, shared data within city</p>
<p>6. SAN: storage Area network, high speed network, provides access to a lot of data, uses switches, disk arrays, servers, not affected by network traffic (or bottlenecks) cause they're not in LAN, they're cut off</p>
<p>7. WAN: Wide area network, largest type, country/continent/global, internet is example</p>

<h3>Differences between Modem and Router</h3>
<p> - Modem brings internet to home/business, maintains connection to internet service provider, computer only reads digital signals, while internet uses only analog signals, moden converts between the two (modulates and demodulates)</p>
<p> - Word Modem = modulator and demodulator </p>
<p> - Router comes in after modem, diff types of routers but do same thing, routers pass internet connection to all devices, common example is router with multiple switch so you can connect many devices at once, and wireless access point. Technically dont need router bc you can just connect one device to modem. </p>
<p> - Different types of modems: cable (colaxial cable e.g. television) and DSL (thru phone line), internet modems are usually a hybrid</p>
<p> - Most routers have integrated switch, you only need switch if you need more wire connections</p>

<h3>Firewalls</h3>
<p> - Prevents unathorised access from private network (safety barrier)</p>
<p> - Especially important to large organisation with data servers</p>
<p> - Stops harmful activity before</p>
<p> - filters access control point, based on certain rules (admin decides)</p>
<p> - allows or denies permissions</p>
<p> - E.g. based on IP address, domain name, protocols, programs, ports, key words</p>
<p> - Host-based firewall, firewall that is installed on computer/device, protects that one device only (can come with comp default or can download from third party)</p>
<p> - Network firewall, mix of hardware and software, protects entire network</p>
<p> - can be stand alone firewall (used for big cooperations), can be integrated within router, or can have cloud firewall</p>

<h3>Differences between a hub, switch and router</h3>
<p>Hub: connects devices to internal network (accepts ethernet) , does not filter and is not considered intelligent, can only know whether device is connected, all devices can see information because hub can not differentiate where to send packet (data is copied to all ports)</p>
    <p style="text-indent: 40px"> - Only physical connection</p>
    <p style="text-indent: 40px"> - uneccessary traffic (wasting badnwidth) and also insecure</p>
<p> Switch - similar to hub but is intelligent, learns physical addresses of devices (mac addresses) and can send packets to intended port</p>
<p> Switch and hub used to exchange data on own network, can't access any other data because can't read IP addresses
<p>Router - routes and forwards data from one network to another, network checks IP address and if its for its address, then recieved, if else, sends to another. it is the gateway for a network.</p>
<p>TLDR: Hubs and switches create networks, routers connect networks</p>

<h3>Network Topologies</h3>
<p> Topologies - layout of how networks communicate with diff devices</p>
<p>
    <b>Wired Topologies</b>
    <p>1. Star Topology</p>
    <p style="text-indent: 40px"> - All devices connected through central wiring point (e..g hub or switch), all data passes can </p>
    <p style="text-indent: 40px"> - PROS: if comp fails or connection fails, then other cmputers not affected. CON: if hub or switch fails, all computers on center point affect (single pint of failure, all network goes down)/<p>
    <p>2. Ring Topolgy</p>
    <p style="text-indent: 40px"> - All devices connect tot each other thru close ring (each has two neighbours)<p/>
    <p style="text-indent: 40px"> - very old and rarely used<p/>
    <p style="text-indent: 40px"> - PROS: easy to install and easy to trouble shoot CON: if there is one single cable break, then whole network goes down<p/>
    <p>3. Bus Topology<p/>
    <p style="text-indent: 40px"> - very old and rarely used<p/>
    <p style="text-indent: 40px"> - each computer is connected to device or back bone (colaxial backbone)<p/>
    <p style="text-indent: 40px"> - each computer connect to colacial backbone thru BNC connectors (T connectors)<p/>
    <p style="text-indent: 40px"> - PROS: cheap and easy to implement CON: every cable terminate on both ends, no open connections including ends, if a computer is removed or terminator loose, cable opens and data bounces back, and then data flow disrupted<p/>
    <p>4.Mesh</p>
    <p style="text-indent: 40px"> - each computer is connected to other computers<p/>
    <p style="text-indent: 40px"> - PROS: high redundancy level CONS: expensive cause of how many cables need (not used for LAN or small networks, e.g. of mesh is internet)<p/>
    <b>Wired Topologies</b>
    <p>5. Infrastructure</p>
    <p style="text-indent: 40px"> - combination of wire and wireless<p/>
    <p style="text-indent: 40px"> - similar to star (have physical wires connected to switch, but also have WAN (wireless access point) connected to cable and then devices can connect to WAN, can have multitple WANS)<p/>
    <p>6. Ad Hoc </p>
    <p style="text-indent: 40px"> -very simple </p>
    <p style="text-indent: 40px"> - no need of physical infrastructure </p>
    <p style="text-indent: 40px"> - each device responsible for security</p>
    <p style="text-indent: 40px"> - all devices wirelessly connect to each other without using centralised device</p>
    <p style="text-indent: 40px"> -PROS: easy and fast to share files without need of wireless network</p>
    <p>7. Wireless Mesh<p/>
    <p style="text-indent: 40px"> - similar to mesh but exception that they are wirelessly connected</p>
    <p style="text-indent: 40px"> - e.g. modem ??? switch ??? multiple Wireless access point</p>
    <p style="text-indent: 40px"> - PRO: very redundant</p>
    <h3> IP Addresses</h3>
    <p style="text-indent: 40px"> - identifier for a device on a network</p>
    <p style="text-indent: 40px"> - consists of two parts: network address and host address</p>
    <p style="text-indent: 40px"> - Two types: IPv 4. and IP v. 6</p>
    <p style="text-indent: 80px"> - IPv4 is 32 bit written as four numberss seperated by period</p>
    <p style="text-indent: 80px"> - each number is called an octet or 8 binary bits</p>
    <p style="text-indent: 80px"> - range from 0-255</p>
    <p style="text-indent: 80px"> - creates over 4 billion diff addresses</p>
    <p style="text-indent: 80px"> - computers and networks only understand addresses in binary format</p>
    <p style="text-indent: 40px"> - IP v v6 next generation, diff is alphabetic and 128 hexadecimal address</p>
    <p style="text-indent: 40px"> - 340 undecillion diff ip addresses</p>
    <h3>Traceroute</h3>
    <p> - command line utilitiy</p>
    <p> - shows route data packet takes</p>
    <p> - trace route is just a tool to find the route that a packet goes from sender to reciever</p>
    <p> - with traceroute, you can find problems like bottle necks or if curious abt paths</p>
    <p> - trace route tells more info than ping</p>
    <p> - pings final destination and every route on its way + time for each router in mls + ip address of each router + domain name if available</p>
    <p> - trying to find consistent round trip times (consistent and slight gradual increase)</p>
    <p> - 3 data packets sent so it can isolate issues</p>
    <p> - trace route also tells us number of hops to network</p>
    <p> - final destination trace route is approx same time as ping</p>
    <p> - ping only displays time of final destination</p>

<p/>


