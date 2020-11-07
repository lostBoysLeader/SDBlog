<html>
	<head>
		<style>
			div{
			width: 800;
			word-wrap: break-word;
			}
		</style>
	</head>
	<body>	
		<h1>Blog 9</h1>
		<h2>Salt (Cryptography)</h2>
	<div>
	<p>
		&#x2003; &#x2003; Salt is a pretty simple concept to understand.
		It's a way of hashing a password. According to Wikipedia, a salt 
		is a just a password with random data thrown in. This "random data"
		is then paired with the password and hashed using SHA-256. Using a
		hash to helps to secure the password further because it cannot be
		decrypted. Instead the salt data is paired with password. then Hashed
		using SHA256. This creates a string value. Further attempts to login
		using the associated user name will always be hashed an then compared
		to the salt. While this is a secure means of storing and authenticating
		passwords there are certain precautions that must be used concurently.
	<br>
	<br>
		&#x2003; &#x2003; Brute force attacks and dictionary are common
		password hacking attempts. They both involve repeated attempts to
		try to find the password to potential victim accounts. Salts severely
		slow them since adding random data makes the password longer and therefor
		more difficult to crack using a reapeated attempt system. 
		Rainbow tables are one way hashed passwords are "hacked".
		It has a glaring weakness, long and/or complex salts(<a href="https://en.wikipedia.org/wiki/Rainbow_table">Rainbow Tables</a>).
		This means that if a salt is being used, then it should certainly be long (more than 8 characters)
		and use all forms of alphanumeric characters. A salt can also be static.
		That doesn't mean they should be. A static salt uses the exact same salt
		for all passwords that are hashed. This obvoiusly creates a common weakness
		for all passwords stored for any account on the system. Additionally,
		web applications that don't store passwords with a salt are vulnerable
		to SQL injections. Salts are an extremely useful tool for securing
		client information but also must be implemented effectively to 
		secure data that clients entrust to any company & website.
		
	</p>
	
	<a href="https://en.wikipedia.org/wiki/Salt_(cryptography)">Wikipedia</a>
	<br>
	<a href="https://en.wikipedia.org/wiki/Rainbow_table">Rainbow Tables</a>
	</div>
	</body>
</html>
