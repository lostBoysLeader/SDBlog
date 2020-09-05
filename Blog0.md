<html>
	<head>
	</head>
	<body>	
		<h1>Blog 0</h1>
		<h2>Port Hopping</h2>
	<div>
	<p>
	Port hopping is an active defense against denial of service attacks and could work against nmapping subsequently. I came 
	across it while thinking about my past time in the military using frequency jumping to secure communications on radios. It 
	works approximately like port knocking. However, the actual listening port of the service is changed at pre-determined 
	intervals rather than "knocking" on closed ports. This would mean the sending and receiving systems would need to have access 
	to an algorithm that would change the listening port at regular intervals. It seems to have been used to some extent in VPNs 
	to as a way to stay ahead of those who would block users' communication with a specific website. While PKI is widely used to 
	communicate securely across the internet this could just be one more layer of security in case PKI was somehow bypassed or 
	decrypted. I have read a few research papers (because thats the only information there is) but none of them speak of it what 
	real world scenario it would be useful. 
	</p>
	<p>
	I have seen a few initial issues with this concept. One problem would be having to stop and start services in order to change 
	their listening port. This means TCP traffic would see repetitive packets due to loss of packets in the times that the service 
	is stopping and starting. So, I would assume the best use of this concept would be the same as my inspiration to research this 
	topic, human communication. That is why I think this would be better to secure UDP traffic like VoIP.
	</p>
	</div>
	</body>
</html>
