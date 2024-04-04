# Pyspark_data_analysis

PySpark is the collaboration of Apache Spark and Python.

Apache Spark is an open-source cluster-computing framework, built around speed, ease of use, and streaming analytics whereas Python is a general-purpose, high-level programming language. It provides a wide range of libraries and is majorly used for Machine Learning and Real-Time Streaming Analytics.

In other words, it is a Python API for Spark that lets you harness the simplicity of Python and the power of Apache Spark in order to tame Big Data. 

Installation guide for windows - 

https://medium.com/@naomi.fridman/install-pyspark-to-run-on-jupyter-notebook-on-windows-4ec2009de21f
https://changhsinlee.com/install-pyspark-windows-jupyter/

-------------------------------------------------------------------------------------------------------------------------------------



Apache Spark is an excellent framework for wrangling, analyzing and modeling on structured and unstructured data at scale server logs are a very common data source in enterprises and often contain a gold mine of actionable insights and information. 
Log data comes from many sources in an enterprise, such as the web, client and compute servers, applications, user-generated content, flat files. They can be used for monitoring servers, improving business and customer intelligence, building recommendation systems, fraud detection, and much more.



log file structure [ remotehost  rfc931  authuser  [date]  "request" status bytes ]

remotehost--Remote hostname (or IP number if DNS hostname is not available or if DNSLookup is off).

rfc931--    The remote logname of the user if at all it is present.

authuser--	The username of the remote user after authentication by the HTTP server.

[date] -- 	Date and time of the request.

"request"--	The request, exactly as it came from the browser or client.

status	--    The HTTP status code the server sent back to the client.

bytes	--    The number of bytes (Content-Length) transferred to the client.



