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
		&#x2003; &#x2003; At this point I have had quite a bit of experience with SQL databases
		and retrieval calls to them. NoSQL is a term I've heard many times
		but have yet to experience interaction with or even learn about. The main difference
		is how the data is stored in these different type systems. A SQL
		Database stores data in a tables while NoSQL is usually structured
		in JSON, XML or even as a graphs. SQL has been the dominant way to store data for a long time.
		However, NoSQL has been around for decades as well but hasn't been needed.
		Today, Big Data demands NoSQL. NoSQL gives the ability to store information
		across partitions. Partitioning can help a system by organizing data in
		a way that basically chops up the data so an entire table doesn't have to be
		traversed to find the data per the query. The differences go further into the weeds but are based
		upon CAP Theorem, pictured below. C=Consistency, A=Availability, P=Partition Tolerance. 
		The image below is a pictoral representation between these three
		basic possible needs of any database. This creates three possible
		Database Management types: CA,CP, & AP. SQL DBMSs tend to exist in CA while NoSQL domainates
		the other two types, CP & AP. Each has the strengths of the
		letters they represent in the triangle but always have the weakness of the
		other letter not named. None are perfect hence all have drawbacks. So, the 
		real question is, Which one is best  this particular situation?
	<br>
	<br>
	<img src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/607361/CausfGVcU2tskB-TR5b8CMm8Keg/medium_media_httpfarm5static_mevIk.png" alt="CAP Triangle">
	<br>
	<br>
		&#x2003; &#x2003; NoSQL thrives on the BASE model. Basically Available, Soft state,
		Eventual consistenty. Availability means the data is always available. Soft state
		refers to the schema that is bound to change based on data stored. Eventual consistency
		states that once the database stops getting input it can create consistency
		across storage nodes through verification. The main focus of NoSQL is
		the ability to adventageously partition tables. It also gives the database
		the ability to scale across many nodes. NoSQL DBMSstends grow horizonatally across
		nodes to distribute demand while SQL DBMSs tends to grow vertically.
		The verticallity is simply that more data is stored on a single system which, with enough
		data to sort through creates slower responses in high demand situations.
		So, if demand and amount of data or manageable on single system them
		SQL should be fine,e.g. internal retrieval systems for a company. If
		there is high demand then distributed DBMSs speed up traffic in a highly
		demanded system, e.g. Netflix or Amazon. So certainly SQL still has a lot
		of benefit to it NoSQL simply has a different advantages. Youtube still
		uses MySQL and it runs fine and very rarely goes down. So the question remains,
		What kind of data will your database hold and what do you need your DBMS to do?
		
	</p>
	
	<a href="https://blog.nahurst.com/visual-guide-to-nosql-systems">Nathan Hurst's Blog</a>
	<br>
	<a href="https://www.digitalocean.com/community/tutorials/a-comparison-of-nosql-database-management-systems-and-models">Digital Ocean</a>
	<br>
	<a href="https://www.sql.kiwi/2012/09/why-doesn-t-partition-elimination-work.html">SQL kiwi</a>
	</div>
	</body>
</html>
