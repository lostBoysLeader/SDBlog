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
		<h1>Blog 5</h1>
		<h2>SQL vs NoSQL</h2>
	<div>
	<p>
		At this point I have had quite a bit of experience with SQL databases
		and retrieval calls to them. NoSQL is a term I've heard many times
		but have yet to experience interaction with. The main difference
		is how the data is stored in these different type systems. A SQL
		Database stores data in a tables while NoSQL is usually structured
		in JSON or XML. SQL has been the dominant way to store data for a long time.
		However, NoSQL has been around for decades as well but hasn't been needed.
		Today, Big Data demands NoSQL. NoSQL gives the ability to store information
		across nodes The differences can go into the weeds but are based
		upon CAP Theorem. C=Consistency, A=Availability, P=Partition Tolerance. 
		The image below is a pictoral representation between these three
		basic possible needs of any database. This creates three possible
		Database Management types: CA,CP, & AP. None are perfect hence all
		have drawbacks. SQL DBMSs tend to exist in CA while NoSQL domainates
		the other two types, CP & AP. So, the real question is, Which one is best 
		this particular situation?
	<br>
	
	<img src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/607361/CausfGVcU2tskB-TR5b8CMm8Keg/medium_media_httpfarm5static_mevIk.png"
	
	<br>
		There isn't much to learn about AJAX. For the most part COMP 484
		gave me enough info and to be able to make AJAX calls. It makes a call
		to the server and assigns the returned data to a tag. Instead of 
		the server having to resend the entire HTML page with the updated
		information. AJAX also cleanly
		uses jQuery to make its calls as well to the host server. For those 
		that are familiar with computer programming, JSON isn't difficult to 
		understand either. JSON is simply a standarization. This is needed
		so web server hosts can call data from its database and always expect
		the data to be returned in the same format so that a single call can
		be made and always expect the data to be returned in the exact same
		format without further code to do catch case scenarios. JSON sends data
		as and array of arrays. Where the overall array has sub-arrays of  data
		pairs. According to w3schools.com JSON can pull only parts of a document and parse
		only the parts you need of the document, while XML requires the whole 
		document be pulled and then parsed. Overall, from what I've read
		from w3schools and other places online this will simply be a "getting
		used to how to do it" rather than "spending hours trying to figure
		out how this works and is implemented"!
		
	</p>
	
	<a href="https://blog.nahurst.com/visual-guide-to-nosql-systems">Nathan Hurst's Blog</a>
	<br>
	<a href="https://www.digitalocean.com/community/tutorials/a-comparison-of-nosql-database-management-systems-and-models">Digital Ocean</a>
	
	</div>
	</body>
</html>
