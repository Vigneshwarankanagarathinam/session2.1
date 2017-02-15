Session 2: Hadoop Framework Description

HDFS 
•	It is an acronym of Hadoop Distributed File System.
•	It is designed to store very large data sets reliably, and to stream those data sets at high bandwidth to user applications.
•	In a large cluster, thousands of servers both host directly attached storage and execute user application tasks.
•	HDFS also makes applications available to parallel processing.

Hadoop cluster 
•	It is a special type of computational cluster designed specifically for storing and analyzing huge amounts of unstructured data in a distributed computing environment.
•	They are known for boosting the speed of data analysis applications.
•	 They are also highly resistant to failure because each piece of data is copied onto other cluster nodes, which ensures that the data is not lost if one node fails.
•	The three types of node groups in a Hadoop deployment are master nodes, worker nodes, and client nodes.

HDFS blocks 
•	Hadoop distributed file system also stores the data in terms of blocks. 
•	However the block size in HDFS is very large. 
•	The default size of HDFS block is 64MB. 
•	The files are split into 64MB blocks and then stored into the Hadoop file system. 
•	The Hadoop application is responsible for distributing the data blocks across multiple nodes. 
•	In the preceding figure, that block size is 128MB.
