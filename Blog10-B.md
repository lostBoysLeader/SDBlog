<html>
<style> div{ width: 800; word-wrap: break-word; } div.a{ text-align: center; }
	</style>
<head>
</head>
<body>	
	<h1>Blog 10-B</h1>
	<h2>Prometheus</h2>
<p>
	&#x2003; &#x2003; Prometheus is an open source software for system monitoring. It records system events
	and can create alerts based on those events. It records data in time series. This helps show data change over time
	where events are time stamped to facilitate change over time. It is written in Go and openly available on 
	GitHub. While it does record data in real time it doesn't show real time graphs. It needs to be working 
	with Grafana to create live feeds of visual data on a system. It uses its own query language called PromQL. 
	The data is stored in format unique to Prometheus ".tsdb." It can work with a variety of software tools 
	including Docker, HAProxy, and JMX. 
	
<br>
	<div class=a>
	<img src="https://miro.medium.com/max/560/1*wWz5vwHcBeTATvBFKGqRkA.png">
	
	</div>
<br>
<br>
	&#x2003; &#x2003; To create alerts Prometheus must communicate with AlertManager. It also needs Node Exporter
	to scrape a variety of system metrics that Prometheus can then analyze. AlertManager is 
	what handles sending alerts to system managers via e-mail, slack or other intermediaries. AlertManager
	is managed by .yml configuration file to communicate outwards towards its managers. So, in short,
	Node Exporter pulls system information, then Prometheus scans and stores the information. Finally,
	if Prometheus detects that an alert rule has been fulfilled it sends the alert to AlertManager, which
	then sends an alert to the remote contact point that it has been told to.
<br>
<br>
	
	
</p>

<a href="https://en.wikipedia.org/wiki/Prometheus_(software)">Wikipedia</a>
<br>
<a href="https://prometheus.io/">Prometheus</a>
<br>
<a href="https://medium.com/devops-dudes/prometheus-alerting-with-alertmanager-e1bbba8e6a8e">AlertManager</a>
<br>
<a href="https://prometheus.io/docs/guides/node-exporter/">Node Exporter</a>
<br>
</div>
</body>
</html>