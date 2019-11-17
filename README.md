Severe Weather Data Inventory Dataset



Map Reduce:

a) The dataset was loaded in the amazon S3 bucket.
b) The jar file implementation was done in eclipse using java with mapper , driver and reducer classes
c) The EMR cluster was created with Custom jar and ec2 instances including the arguments in the step events
d) Once the EMR cluster is created,it starts running with the completed Custom JAR.\
e) The output files will be created in the folder located in S3 bucket.

The screenshots of the output files and some of the output files is uploaded here.


Spark:

a)In Spark Implementation,the EMR cluster is created with a key pair.
b) Once the Cluster starts running,the Amazon master node is connect with the SSH using the putty.
c)Using the host name id and the created key pair,the hadoop session is established.
d) Once the session is started,you can establish spark session using python.
e)The data files is loaded from the S3 bucket using Spark dataframes and SparkSQL queries were used to  implement our problem statements.


HIVE:
a)In Hive Implementation,the EMR cluster is created with a key pair.
b) Once the Cluster starts running,the Amazon master node is connect with the SSH using the putty.
c)Using the host name id and the created key pair,the hadoop session is established.
d) Once the session is started,you can establish spark session using hive command.
e)And databases and external tables were created and some queries were implemented . 


