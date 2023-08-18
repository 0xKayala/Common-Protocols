# Common-Protocols
<hr/>
<p>Internet protocols are standardized rules and guidelines defined in RFCs that specify how devices on a network should communicate with each other. They ensure that devices on a network can exchange information consistently and reliably, regardless of the hardware and software used. For devices to communicate on a network, they need to be connected through a communication channel, such as a wired or wireless connection. The devices then exchange information using a set of standardized protocols that define the format and structure of the data being transmitted. The two main types of connections used on networks are <a href="https://en.wikipedia.org/wiki/Transmission_Control_Protocol">Transmission Control Protocol</a> (<code>TCP</code>) and <a href="https://en.wikipedia.org/wiki/User_Datagram_Protocol">User Datagram Protocol</a> (<code>UDP</code>).</p>
<p>We need to deal with and know the different and most used protocols. As we have already learned, these protocols are the basis of all communication between our devices and computers in the networks. We have compiled below many of these protocols that we will be dealing with throughout the modules. The better we understand them, the more effectively we can work with them.</p>
<hr/>
## Transmission Control Protocol
<p><code>TCP</code> is a <code>connection-oriented</code> protocol that establishes a virtual connection between two devices before transmitting data by using a <a href="https://en.wikipedia.org/wiki/Transmission_Control_Protocol#Connection_establishment">Three-Way-Handshake</a>. This connection is maintained until the data transfer is complete, and the devices can continue to send data back and forth as long as the connection is active.</p>
<p>For example, When we enter a URL into our web browser, the browser sends an HTTP request to the server hosting the website using <code>TCP</code>. The server responds by sending the HTML code for the website back to the browser using <code>TCP</code>. The browser then uses this code to render the website on our screen. This process relies on a <code>TCP</code> connection being established between the browser and the web server and maintained until the data transfer is complete. As a result, <code>TCP</code> is reliable but slower than UDP because it requires additional overhead for establishing and maintaining the connection.</p>
<table>
<thead>
<tr>
<th><strong>Protocol</strong></th>
<th><strong>Acronym</strong></th>
<th><strong>Port</strong></th>
<th><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>Telnet</td>
<td><code>Telnet</code></td>
<td><code>23</code></td>
<td>Remote login service</td>
</tr>
<tr>
<td>Secure Shell</td>
<td><code>SSH</code></td>
<td><code>22</code></td>
<td>Secure remote login service</td>
</tr>
<tr>
<td>Simple Network Management Protocol</td>
<td><code>SNMP</code></td>
<td><code>161-162</code></td>
<td>Manage network devices</td>
</tr>
<tr>
<td>Hyper Text Transfer Protocol</td>
<td><code>HTTP</code></td>
<td><code>80</code></td>
<td>Used to transfer webpages</td>
</tr>
<tr>
<td>Hyper Text Transfer Protocol Secure</td>
<td><code>HTTPS</code></td>
<td><code>443</code></td>
<td>Used to transfer secure webpages</td>
</tr>
<tr>
<td>Domain Name System</td>
<td><code>DNS</code></td>
<td><code>53</code></td>
<td>Lookup domain names</td>
</tr>
<tr>
<td>File Transfer Protocol</td>
<td><code>FTP</code></td>
<td><code>20-21</code></td>
<td>Used to transfer files</td>
</tr>
<tr>
<td>Trivial File Transfer Protocol</td>
<td><code>TFTP</code></td>
<td><code>69</code></td>
<td>Used to transfer files</td>
</tr>
<tr>
<td>Network Time Protocol</td>
<td><code>NTP</code></td>
<td><code>123</code></td>
<td>Synchronize computer clocks</td>
</tr>
<tr>
<td>Simple Mail Transfer Protocol</td>
<td><code>SMTP</code></td>
<td><code>25</code></td>
<td>Used for email transfer</td>
</tr>
<tr>
<td>Post Office Protocol</td>
<td><code>POP3</code></td>
<td><code>110</code></td>
<td>Used to retrieve emails</td>
</tr>
<tr>
<td>Internet Message Access Protocol</td>
<td><code>IMAP</code></td>
<td><code>143</code></td>
<td>Used to access emails</td>
</tr>
<tr>
<td>Server Message Block</td>
<td><code>SMB</code></td>
<td><code>445</code></td>
<td>Used to transfer files</td>
</tr>
<tr>
<td>Network File System</td>
<td><code>NFS</code></td>
<td><code>111</code>, <code>2049</code></td>
<td>Used to mount remote systems</td>
</tr>
<tr>
<td>Bootstrap Protocol</td>
<td><code>BOOTP</code></td>
<td><code>67</code>, <code>68</code></td>
<td>Used to bootstrap computers</td>
</tr>
<tr>
<td>Kerberos</td>
<td><code>Kerberos</code></td>
<td><code>88</code></td>
<td>Used for authentication and authorization</td>
</tr>
<tr>
<td>Lightweight Directory Access Protocol</td>
<td><code>LDAP</code></td>
<td><code>389</code></td>
<td>Used for directory services</td>
</tr>
<tr>
<td>Remote Authentication Dial-In User Service</td>
<td><code>RADIUS</code></td>
<td><code>1812</code>, <code>1813</code></td>
<td>Used for authentication and authorization</td>
</tr>
<tr>
<td>Dynamic Host Configuration Protocol</td>
<td><code>DHCP</code></td>
<td><code>67</code>, <code>68</code></td>
<td>Used to configure IP addresses</td>
</tr>
<tr>
<td>Remote Desktop Protocol</td>
<td><code>RDP</code></td>
<td><code>3389</code></td>
<td>Used for remote desktop access</td>
</tr>
<tr>
<td>Network News Transfer Protocol</td>
<td><code>NNTP</code></td>
<td><code>119</code></td>
<td>Used to access newsgroups</td>
</tr>
<tr>
<td>Remote Procedure Call</td>
<td><code>RPC</code></td>
<td><code>135</code>, <code>137-139</code></td>
<td>Used to call remote procedures</td>
</tr>
<tr>
<td>Identification Protocol</td>
<td><code>Ident</code></td>
<td><code>113</code></td>
<td>Used to identify user processes</td>
</tr>
<tr>
<td>Internet Control Message Protocol</td>
<td><code>ICMP</code></td>
<td><code>0-255</code></td>
<td>Used to troubleshoot network issues</td>
</tr>
<tr>
<td>Internet Group Management Protocol</td>
<td><code>IGMP</code></td>
<td><code>0-255</code></td>
<td>Used for multicasting</td>
</tr>
<tr>
<td>Oracle DB (Default/Alternative) Listener</td>
<td><code>oracle-tns</code></td>
<td><code>1521</code>/<code>1526</code></td>
<td>The Oracle database default/alternative listener is a service that runs on the database host and receives requests from Oracle clients.</td>
</tr>
<tr>
<td>Ingres Lock</td>
<td><code>ingreslock</code></td>
<td><code>1524</code></td>
<td>Ingres database is commonly used for large commercial applications and as a backdoor that can execute commands remotely via RPC.</td>
</tr>
<tr>
<td>Squid Web Proxy</td>
<td><code>http-proxy</code></td>
<td><code>3128</code></td>
<td>Squid web proxy is a caching and forwarding HTTP web proxy used to speed up a web server by caching repeated requests.</td>
</tr>
<tr>
<td>Secure Copy Protocol</td>
<td><code>SCP</code></td>
<td><code>22</code></td>
<td>Securely copy files between systems</td>
</tr>
<tr>
<td>Session Initiation Protocol</td>
<td><code>SIP</code></td>
<td><code>5060</code></td>
<td>Used for VoIP sessions</td>
</tr>
<tr>
<td>Simple Object Access Protocol</td>
<td><code>SOAP</code></td>
<td><code>80</code>, <code>443</code></td>
<td>Used for web services</td>
</tr>
<tr>
<td>Secure Socket Layer</td>
<td><code>SSL</code></td>
<td><code>443</code></td>
<td>Securely transfer files</td>
</tr>
<tr>
<td>TCP Wrappers</td>
<td><code>TCPW</code></td>
<td><code>113</code></td>
<td>Used for access control</td>
</tr>
<tr>
<td>Network Time Protocol</td>
<td><code>NTP</code></td>
<td><code>123</code></td>
<td>Synchronize computer clocks</td>
</tr>
<tr>
<td>Internet Security Association and Key Management Protocol</td>
<td><code>ISAKMP</code></td>
<td><code>500</code></td>
<td>Used for VPN connections</td>
</tr>
<tr>
<td>Microsoft SQL Server</td>
<td><code>ms-sql-s</code></td>
<td><code>1433</code></td>
<td>Used for client connections to the Microsoft SQL Server.</td>
</tr>
<tr>
<td>Kerberized Internet Negotiation of Keys</td>
<td><code>KINK</code></td>
<td><code>892</code></td>
<td>Used for authentication and authorization</td>
</tr>
<tr>
<td>Open Shortest Path First</td>
<td><code>OSPF</code></td>
<td><code>520</code></td>
<td>Used for routing</td>
</tr>
<tr>
<td>Point-to-Point Tunneling Protocol</td>
<td><code>PPTP</code></td>
<td><code>1723</code></td>
<td>Is used to create VPNs</td>
</tr>
<tr>
<td>Remote Execution</td>
<td><code>REXEC</code></td>
<td><code>512</code></td>
<td>This protocol is used to execute commands on remote computers and send the output of commands back to the local computer.</td>
</tr>
<tr>
<td>Remote Login</td>
<td><code>RLOGIN</code></td>
<td><code>513</code></td>
<td>This protocol starts an interactive shell session on a remote computer.</td>
</tr>
<tr>
<td>X Window System</td>
<td><code>X11</code></td>
<td><code>6000</code></td>
<td>It is a computer software system and network protocol that provides a graphical user interface (GUI) for networked computers.</td>
</tr>
<tr>
<td>Relational Database Management System</td>
<td><code>DB2</code></td>
<td><code>50000</code></td>
<td>RDBMS is designed to store, retrieve and manage data in a structured format for enterprise applications such as financial systems, customer relationship management (CRM) systems.</td>
</tr>
</tbody>
</table>
<hr/>
## User Datagram Protocol
<p>On the other hand, <code>UDP</code> is a <code>connectionless</code> protocol, which means it does not establish a virtual connection before transmitting data. Instead, it sends the data packets to the destination without checking to see if they were received.</p>
<p>For example, when we stream or watch a video on a platform like YouTube, the video data is transmitted to our device using <code>UDP</code>. This is because the video can tolerate some data loss, and the transmission speed is more important than the reliability. If a few packets of video data are lost along the way, it will not significantly impact the overall quality of the video. This makes <code>UDP</code> faster than TCP but less reliable because there is no guarantee that the packets will reach their destination.</p>
<table>
<thead>
<tr>
<th><strong>Protocol</strong></th>
<th><strong>Acronym</strong></th>
<th><strong>Port</strong></th>
<th><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>Domain Name System</td>
<td><code>DNS</code></td>
<td><code>53</code></td>
<td>It is a protocol to resolve domain names to IP addresses.</td>
</tr>
<tr>
<td>Trivial File Transfer Protocol</td>
<td><code>TFTP</code></td>
<td><code>69</code></td>
<td>It is used to transfer files between systems.</td>
</tr>
<tr>
<td>Network Time Protocol</td>
<td><code>NTP</code></td>
<td><code>123</code></td>
<td>It synchronizes computer clocks in a network.</td>
</tr>
<tr>
<td>Simple Network Management Protocol</td>
<td><code>SNMP</code></td>
<td><code>161</code></td>
<td>It monitors and manages network devices remotely.</td>
</tr>
<tr>
<td>Routing Information Protocol</td>
<td><code>RIP</code></td>
<td><code>520</code></td>
<td>It is used to exchange routing information between routers.</td>
</tr>
<tr>
<td>Internet Key Exchange</td>
<td><code>IKE</code></td>
<td><code>500</code></td>
<td>Internet Key Exchange</td>
</tr>
<tr>
<td>Bootstrap Protocol</td>
<td><code>BOOTP</code></td>
<td><code>68</code></td>
<td>It is used to bootstrap hosts in a network.</td>
</tr>
<tr>
<td>Dynamic Host Configuration Protocol</td>
<td><code>DHCP</code></td>
<td><code>67</code></td>
<td>It is used to assign IP addresses to devices in a network dynamically.</td>
</tr>
<tr>
<td>Telnet</td>
<td><code>TELNET</code></td>
<td><code>23</code></td>
<td>It is a text-based remote access communication protocol.</td>
</tr>
<tr>
<td>MySQL</td>
<td><code>MySQL</code></td>
<td><code>3306</code></td>
<td>It is an open-source database management system.</td>
</tr>
<tr>
<td>Terminal Server</td>
<td><code>TS</code></td>
<td><code>3389</code></td>
<td>It is a remote access protocol used for Microsoft Windows Terminal Services by default.</td>
</tr>
<tr>
<td>NetBIOS Name</td>
<td><code>netbios-ns</code></td>
<td><code>137</code></td>
<td>It is used in Windows operating systems to resolve NetBIOS names to IP addresses on a LAN.</td>
</tr>
<tr>
<td>Microsoft SQL Server</td>
<td><code>ms-sql-m</code></td>
<td><code>1434</code></td>
<td>Used for the Microsoft SQL Server Browser service.</td>
</tr>
<tr>
<td>Universal Plug and Play</td>
<td><code>UPnP</code></td>
<td><code>1900</code></td>
<td>It is a protocol for devices to discover each other on the network and communicate.</td>
</tr>
<tr>
<td>PostgreSQL</td>
<td><code>PGSQL</code></td>
<td><code>5432</code></td>
<td>It is an object-relational database management system.</td>
</tr>
<tr>
<td>Virtual Network Computing</td>
<td><code>VNC</code></td>
<td><code>5900</code></td>
<td>It is a graphical desktop sharing system.</td>
</tr>
<tr>
<td>X Window System</td>
<td><code>X11</code></td>
<td><code>6000-6063</code></td>
<td>It is a computer software system and network protocol that provides GUI on Unix-like systems.</td>
</tr>
<tr>
<td>Syslog</td>
<td><code>SYSLOG</code></td>
<td><code>514</code></td>
<td>It is a standard protocol to collect and store log messages on a computer system.</td>
</tr>
<tr>
<td>Internet Relay Chat</td>
<td><code>IRC</code></td>
<td><code>194</code></td>
<td>It is a real-time Internet text messaging (chat) or synchronous communication protocol.</td>
</tr>
<tr>
<td>OpenPGP</td>
<td><code>OpenPGP</code></td>
<td><code>11371</code></td>
<td>It is a protocol for encrypting and signing data and communications.</td>
</tr>
<tr>
<td>Internet Protocol Security</td>
<td><code>IPsec</code></td>
<td><code>500</code></td>
<td>IPsec is also a protocol that provides secure, encrypted communication. It is commonly used in VPNs to create a secure tunnel between two devices.</td>
</tr>
<tr>
<td>Internet Key Exchange</td>
<td><code>IKE</code></td>
<td><code>11371</code></td>
<td>It is a protocol for encrypting and signing data and communications.</td>
</tr>
<tr>
<td>X Display Manager Control Protocol</td>
<td><code>XDMCP</code></td>
<td><code>177</code></td>
<td>XDMCP is a network protocol that allows a user to remotely log in to a computer running the X11.</td>
</tr>
</tbody>
</table>
<hr/>
## ICMP
<p><a href="https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol">Internet Control Message Protocol</a> (<code>ICMP</code>) is a protocol used by devices to communicate with each other on the Internet for various purposes, including error reporting and status information. It sends requests and messages between devices, which can be used to report errors or provide status information.</p>
<h4>ICMP Requests</h4>
<p>A request is a message sent by one device to another to request information or perform a specific action. An example of a request in ICMP is the <code>ping</code> request, which tests the connectivity between two devices. When one device sends a ping request to another, the second device responds with a <code>ping reply</code> message.</p>
<h4>ICMP Messages</h4>
<p>A message in ICMP can be either a request or a reply. In addition to ping requests and responses, ICMP supports other types of messages, such as error messages, <code>destination unreachable</code>, and <code>time exceeded</code> messages. These messages are used to communicate various types of information and errors between devices on the network.</p>
<p>For example, if a device tries to send a packet to another device and the packet cannot be delivered, the device can use ICMP to send an error message back to the sender. ICMP has two different versions:</p>
<ul>
<li>
<code>ICMPv4</code>: For IPv4 only</li>
<li>
<code>ICMPv6</code>: For IPv6 only</li>
</ul>
<p>ICMPv4 is the original version of <code>ICMP</code>, developed for use with IPv4. It is still widely used and is the most common version of ICMP. On the other hand, ICMPv6 was developed for IPv6. It includes additional functionality and is designed to address some of the limitations of ICMPv4.</p>
<table>
<thead>
<tr>
<th><strong>Request Type</strong></th>
<th><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>Echo Request</code></td>
<td>This message tests whether a device is reachable on the network. When a device sends an echo request, it expects to receive an echo reply message. For example, the tools <code>tracert</code> (Windows) or <code>traceroute</code> (Linux) always send ICMP echo requests.</td>
</tr>
<tr>
<td><code>Timestamp Request</code></td>
<td>This message determines the time on a remote device.</td>
</tr>
<tr>
<td><code>Address Mask Request</code></td>
<td>This message is used to request the subnet mask of a device.</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th><strong>Message Type</strong></th>
<th><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>Echo reply</code></td>
<td>This message is sent in response to an echo request message.</td>
</tr>
<tr>
<td><code>Destination unreachable</code></td>
<td>This message is sent when a device cannot deliver a packet to its destination.</td>
</tr>
<tr>
<td><code>Redirect</code></td>
<td>A router sends this message to inform a device that it should send its packets to a different router.</td>
</tr>
<tr>
<td><code> time exceeded</code></td>
<td>This message is sent when a packet has taken too long to reach its destination.</td>
</tr>
<tr>
<td><code>Parameter problem</code></td>
<td>This message is sent when there is a problem with a packet's header.</td>
</tr>
<tr>
<td><code>Source quench</code></td>
<td>This message is sent when a device receives packets too quickly and cannot keep up. It is used to slow down the flow of packets.</td>
</tr>
</tbody>
</table>
<p>Another crucial part of ICMP for us is the <a href="https://en.wikipedia.org/wiki/Time_to_live">Time-To-Live</a> (<code>TTL</code>) field in the ICMP packet header that limits the packet's lifetime as it travels through the network. It prevents packets from circulating indefinitely on the network in the event of routing loops. Each time a packet passes through a router, the router decrements the <code>TTL value by 1</code>. When the TTL value reaches <code>0</code>, the router discards the packet and sends an ICMP <code>Time Exceeded</code> message back to the sender.</p>
<p>We can also use <code>TTL</code> to determine the number of hops a packet has taken and the approximate distance to the destination. For example, if a packet has a <code>TTL</code> of 10 and takes 5 hops to reach its destination, it can be inferred that the destination is approximately 5 hops away. For example, if we see a ping with the <code>TTL</code> value of <code>122</code>, it could mean that we are dealing with a Windows system (<code>TTL 128</code> by default) that is 6 hops away.</p>
<p>However, it is also possible to guess the operating system based on the default <code>TTL</code> value used by the device. Each operating system typically has a default <code>TTL</code> value when sending packets. This value is set in the packet's header and is decremented by 1 each time the packet passes through a router. Therefore, examining a device's default <code>TTL</code> value makes it possible to infer which operating system the device is using. For example: Windows systems (<code>2000/XP/2003/Vista/10</code>) typically have a default <code>TTL</code> value of 128, while macOS and Linux systems typically have a default <code>TTL</code> value of 64 and Solaris' default <code>TTL</code> value of 255. However, it is important to note that the user can change these values, so they should be independent of a definitive way to determine a device's operating system.</p>
<hr/>
## VoIP
<p><a href="https://www.fcc.gov/general/voice-over-internet-protocol-voip">Voice over Internet Protocol</a> (<code>VoIP</code>) is a method of transmitting voice and multimedia communications. For example, it allows us to make phone calls using a broadband internet connection instead of a traditional phone line, like Skype, Whatsapp, Google Hangouts, Slack, Zoom, and others.</p>
<p>The most common VoIP ports are <code>TCP/5060</code> and <code>TCP/5061</code>, which are used for the <a href="https://en.wikipedia.org/wiki/Session_Initiation_Protocol">Session Initiation Protocol</a> (SIP). However, the port <code>TCP/1720</code> may also be used by some VoIP systems for the <a href="https://en.wikipedia.org/wiki/H.323">H.323 protocol</a>, a set of standards for multimedia communication over packet-based networks. Still, SIP is more widely used than H.323 in VoIP systems.</p>
<p>Nevertheless, SIP is a signaling protocol for initiating, maintaining, modifying, and terminating real-time sessions involving video, voice, messaging, and other communications applications and services between two or more endpoints on the Internet. Therefore, it uses requests and methods between the endpoints. The most common SIP requests and methods are:</p>
<table>
<thead>
<tr>
<th><strong>Method</strong></th>
<th><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>INVITE</code></td>
<td>Initiates a session or invites another endpoint to participate.</td>
</tr>
<tr>
<td><code>ACK</code></td>
<td>Confirms the receipt of an INVITE request.</td>
</tr>
<tr>
<td><code>BYE</code></td>
<td>Terminate a session.</td>
</tr>
<tr>
<td><code>CANCEL</code></td>
<td>Cancels a pending INVITE request.</td>
</tr>
<tr>
<td><code>REGISTER</code></td>
<td>Registers a SIP user agent (UA) with a SIP server.</td>
</tr>
<tr>
<td><code>OPTIONS</code></td>
<td>Requests information about the capabilities of a SIP server or user agent, such as the types of media it supports.</td>
</tr>
</tbody>
</table>
<h4>Information Disclosure</h4>
<p>However, SIP allows us to enumerate existing users for potential attacks. This can be done for various purposes, such as determining a user's availability, finding out information about the user's capabilities or services, or performing brute-force attacks on user accounts later on.</p>
<p>One of the possible ways to enumerate users is the SIP <code>OPTIONS</code> request. It is a method used to request information about the capabilities of a SIP server or user agents, such as the types of media it supports, the codecs it can decode, and other details. The <code>OPTIONS</code> request can probe a SIP server or user agent for information or test its connectivity and availability.</p>
<p>During our analysis, it is possible to discover a <code>SEPxxxx.cnf</code> file, where <code>xxxx</code> is a unique identifier, is a configuration file used by Cisco Unified Communications Manager, formerly known as Cisco CallManager, to define the settings and parameters for a Cisco Unified IP Phone. The file specifies the phone model, firmware version, network settings, and other details.</p>
