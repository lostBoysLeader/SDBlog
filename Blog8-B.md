<html>
<style> div{ width: 800; word-wrap: break-word; } div.a{ text-align: center; }
	</style>
<head>
</head>
<body>	
	<h1>Blog 8-B</h1>
	<h2>Internet Control Message Protocol</h2>
<div>
<p>
	&#x2003; &#x2003; Internet Control Message Protocol or ICMP is one of the most simple, integral and useful protocols used. It's integrated 
	into almost every communication overt the internet. It mainly conveys metadata about a transmission between two points. Ping and Traceroute
	are two examples the use of ICMP. It differs from UDP and TCP in that it isn't designed to transmit data but simply information about how 
	data gets from point A to point B. Depending on the type of ICMP it can do different things. Time To Live or TTL can be a response as Type 
	11 with code 0. An echo request, or ping, is Type 8 Code 0. It's echo reply to a ping is Type 0 with Code 0. So it has up to 256 Types with 
	different Codes to convey different information about data packets. It even has a checksum to verify packet integrity. ICMP can be a quick 
	help when it comes to verifying basic communication with a remote server.

<br>
<br>
	<div class=a>
	<img src="https://www.cloudflare.com/img/learning/ddos/ping-of-death-ddos-attack/attack-mitigation.png">
	
	</div>
<br>
<br>
	&#x2003; &#x2003; However, ICMP can be taken advantage of. An IPV4 ping packet is usually 56 or 64 bytes but can technically be as large as 65535 bytes.
	 The "Ping of death" overloads a ping packet. In turn, this creates a buffer overflow on the receiving end through packet fragmentation. The fragmentation
	comes from the fact that incoming frames that are very large are broken down into sections. This fragmentation offeset then can create a packet size larger than
	65535 bytes. This can crash the system and allow an attack or injection of malware. This is an example of Denial of Service using ICMP. ICMP can also be taken
	a advantage of using ICMP tunnels. ICMP tunneling is a covert connection by injecting arbitrary code into the data of an ICMP packet. It can be used circumvent 
	firewalls or even paid wifi services. This is acheived by sending requests by ICMP rather than by TCP or UDP. ICMP attacks can easily be thwarted by denying
	ICMP requests. ICMP requests are not needed for most general traffic so can be ignored for all outward facing network devices. 
<br>
<br>
	
	
</p>

<a href="https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol">ICMP</a></a>
<a href="https://en.wikipedia.org/wiki/Ping_of_death">Ping of death</a></a>
<a href="https://en.wikipedia.org/wiki/ICMP_tunnel">ICMP Tunnel</a></a>
<br>
</div>
</body>
</html>