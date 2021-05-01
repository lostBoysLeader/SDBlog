<html>
<style> div{ width: 800; word-wrap: break-word; } div.a{ text-align: center; }
	</style>
<head>
</head>
<body>	
	<h1>Blog 9-B</h1>
	<h2>Intrusion Detections and Prevention Systems (IDPS)</h2>
<div>
<p>
	&#x2003; &#x2003; Intrusion Detection and Prevention Systems do two things. They detect attacks and/or prevent them. 
	Intrusion Detection Systems can act indpendently of prevention systems, however prevention systems are dependent on 
	some detection system to initiate a response to an attack.  They work in tandem with a firewall, they do not replace 
	firewalls. Some of the most common  IDPS software used is OSSEC, Snort, Suricata and Security Onion and all are open 
	source. Unlike firewalls, IDS systems more advanced techniques than simple traffic rules to determine whether or not 
	traffic is malicious or not. They can use signature-based detection to recognize known malware. They also use 
	anomaly-based detection that uses machine  learning. There are several other detection methods depending on the IDS software. 
	An IDS system does have an intended flaw. They only alert that something is happening. They do not attempt to do anything 
	about it. IDS's can either be placed in front of an entire network called NIDS or on every individual host called HIDS. 
	NIDS can be placed in many or single point on a network. They can track individual subnets or all network traffic. 
	If implemented incorrectly the IDS can miss internal attacks. HIDS are placed on ever individual host. It's great that it 
	can detect anything coming in and out of every node but can be a problem with a requirement for powerful hardware to 
	maintain the IDS processing and normal node functions simultaneously. There are several ways to avoid IDS's as well. 
	Packet fragmentation, Fireawll attacks and Addresss spoofing are some examples.
<br>
<br>
	<div class=a>
	<img src="https://www.juniper.net/assets/img/misc/diagram-what-is-idp-ips.png">
	
	</div>
<br>
<br>
	&#x2003; &#x2003;  Intrusion Prevention Systems rely on a detection system. They are synonymous with IDPS's for this reason. Without 
	knowing an attack is occuring it isn't possible to the prevent the attack. IDS systems aren't placed "in line" with network
	traffic. That is IDS systems passively are simply watching traffic pass by. IDPS or IPS systems must "open the door" to traffic
	so that it can continue on its way into, out of, and/or through the network (depending on network positioning). Just like IDS's,
	IDPS's can be positioned within networks or on hosts for different effects. They can also be placed infront of firewalls. This
	would be done to clear out unwated traffic coming from the internet. Unlike IDS's, IDPS's can alsu be used to correct network errors, 
	defragment package streams, and mitigate TCP sequencing. They can also clean up unwanted network and transport layer options.
	Overall, these systems are integral to any well defended network (especially commercial networks). There is also little
	reason to not have them since there a plethora of different open sources to choose from.
<br>
<br>
	
	
</p>

<a href="https://en.wikipedia.org/wiki/Intrusion_detection_system">IDS</a>
<br>
</div>
</body>
</html>