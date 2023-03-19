# museum-ticket-register
HBase is a column-oriented non-relational database management system that runs on top of Hadoop Distributed File System (HDFS). HBase provides a fault-tolerant way of storing sparse data sets, which are common in many big data use cases. It is well suited for real-time data processing or random read/write access to large volumes of data.
This schema includes three tables:

             1)vis_details 
             2)mus_details
             3)sta_details

The vis_details table stores information about visitors details, including its unique
             1)name
             2)age
             3)date
             
The mus_details table stores information about museum details, including its unique
             1)name
             2)location
             3)time
             
The sta_details table stores information about staff details, including its unique
             1)name
             2)id
             3)age
             4)salary
             
In this family table there are three columns named vis_details, mus_details and sta_details info containing three rows basically
  ![WhatsApp Image 2023-03-18 at 10 22 33 PM](https://user-images.githubusercontent.com/124859919/226159012-5c1f3751-c19a-4b7e-975f-0341df66a5f4.jpeg)
  
  
I updated the values of row no 01 by changing their vis_details.In the second row I inserted the time info in the mus_details column using put keyword column using put keyword, Then I updated the values of row no 01 by changing their  vis_details. Finally I deleted the last row's  sta_details that they have dropped earlier using delete keyword.
![WhatsApp Image 2023-03-18 at 10 22 33 PM](https://user-images.githubusercontent.com/124859919/226159130-b5f764e0-b41c-471e-8345-f66dcccda888.jpeg)
Pictorial representation of CRUD operation in family database are attached in the Issues file(3 files) In conclusion, column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.
