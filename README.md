# family
HBase is an open-source, distributed, non-relational database management system (DBMS) that runs on top of the Hadoop Distributed File System (HDFS). It is modeled after Google's Bigtable, and is designed to store and manage large amounts of structured data across many commodity servers.

HBase is typically used in big data applications where data is constantly changing and needs to be processed quickly. It is commonly used for real-time access to data, such as for online transaction processing (OLTP), analytics, and search. HBase is horizontally scalable, meaning it can easily handle large amounts of data by adding more servers to a cluster.

In this family table there are three columns named Details, Relatives and Account info containing three rows basically 


![image](https://user-images.githubusercontent.com/123818960/225751703-4b4ef514-2823-4508-b610-e1338935c8e7.png)


I updated the values of row no 01 by changing their account details.In the second row I inserted the father info in the relatives details column using put keyword column using put keyword, Then I updated the values of row no 01 by changing their account details. finally I deleted the last row's account
details that they have dropped earlier using delete keyword.

![image](https://user-images.githubusercontent.com/123818960/225751816-0f582064-96a5-49bf-9903-d113de96e276.png)


To make the above operation I used the following keywords:
     put- put keyword is used to insert and update the values of the student in the table 
     scan- scan keyword is used to display the entities of the table we have created
     get-  get keyword is used to read the values of the table
     delete- delete keyword is used to delete the value as well as the table
     
     
Pictorial representation of CRUD operation in family database are attached in the Issues file(3 files)
     In conclusion, column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.     



