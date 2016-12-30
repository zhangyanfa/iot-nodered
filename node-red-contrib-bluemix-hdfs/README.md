bluemixhdfs
========================
This is a Node-RED node meant for connecting to the Big Data on IBM Bluemix.
This Node-RED node can be used only within the IBM Bluemix environment. This node requires a bound Analytics for Apache Hadoop service to work.  
Within the Bluemix environment, the node specifically assumes that /user/biblumix as the home location.   
Also, append the forward slash for any operation.  

In case there is no bound Analytics for Apache Hadoop, then the node will warn about its inability to connect to the HDFS system and will not work.  


Install
-------
Install from [npm](http://npmjs.org)
```
npm install node-red-contrib-bluemix-hdfs
```

Usage
-------

**HDFS Out Node**

The HDFS Out node can be used to 

1. Create File
2. Append to File and 
3. Delete File

  
**HDFS In Out Node**

The HDFS In Out node can be used to 

1. Read the file contents
