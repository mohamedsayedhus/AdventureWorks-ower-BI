# AdventureWorks-Power-BI

# We're all striving to improve the performance of the queries 
We're working to make it easier for you to navigate the data freely and extract the planned insights effortlessly. This is exactly what the Star Schema Structure is designed to do. ✔️

# In this project 
all the sales data was initially combined in a single table, which isn't the best approach because it results in a large file size, consumes more memory, and increases redundancy—not good for performance.
##
One of the advantages of the Star Schema is that it helps you separate data into different Dimensions, allowing you to remove duplicates efficiently. If you don't have a Primary Key (PK) or you do but it's not numerical, you can use Power Query Editor to add an Index. After that, you can merge queries and let the index detect the relationships from the master query. This will significantly improve performance. Additionally, it will reduce redundancy, which decreases the file size.

##
Furthermore, setting up relationships between tables becomes easier, as you'll have a Fact Table surrounded by clearly defined Dimension Tables, making data extraction more efficient and straightforward.


![Screenshot 2024-10-12 160209](https://github.com/user-attachments/assets/df21d7db-38fd-4685-a914-45579566ed5f)

![Screenshot 2024-10-12 162028](https://github.com/user-attachments/assets/253e190f-7f61-4ebb-926d-55225f05b79e)
