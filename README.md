# MongoDB
>>MongoDB step by step

The attached document outlines the MongoDB CRUD (Create, Read, Update, Delete) steps


>>MongoDB_Joins_html (1)

The document shows the following:

1. import the required libraries
2. Creating a dbase (**Hospitallist**), collection (**Hospital**) and inserting multiple records
 ![image](https://user-images.githubusercontent.com/52436599/112549812-c5509180-8d94-11eb-8d4d-a6a3ae2ad345.png)
3. Creating another collection (**Doctors**) and inserting multiple records
![image](https://user-images.githubusercontent.com/52436599/112549957-ff219800-8d94-11eb-9351-cfa76a5f5e20.png)

4. Creating a view of from the created collections (join is on the HospitalId column) using **$lookup**
![image](https://user-images.githubusercontent.com/52436599/112550094-342dea80-8d95-11eb-9c46-97b86dbffe6d.png)

5. using HTML table to display the output of Doctors collection and that of Hospital collection separately
![image](https://user-images.githubusercontent.com/52436599/112550199-60e20200-8d95-11eb-8dd2-6516858a572b.png)
