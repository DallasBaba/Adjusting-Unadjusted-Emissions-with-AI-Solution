In this project, we leverage a dataset obtained from the **Environmental Protection Agency** (EPA) via their website. 

The dataset, named egrid2022_data, contains valuable information related to energy generation, emissions, and power plants.

Our focus lies on a specific subset of this data, including the tables labeled as **UNT22, GEN22, PLNT22, and US22**. These tables serve as the foundation for creating a **view** named “**Unadjusted Emissions**”. 

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/ba7d029e-d232-4d5d-b8d1-ad31af53b01b) 

However, in real-world scenarios access to the main tables will be restricted by database administrators due to  sensitive information and government policies. The primary objective of this project is to establish a real-world scenarios with data engineering process for developing a Monitoring Tracker.   Here’s our step-by-step approach:
 
**1- Workspace and Data Warehouse Creation**:

We begin by setting up a workspace where all project-related activities will take place.
Next, we create a robust data warehouse capable of storing large volumes of data. This warehouse will serve as the central repository for our dataset.

**2- Data Loading and Transformation**:
Using gen2 (presumably a data loading tool), we load the relevant data into our data warehouse.
We ensure that the data is properly transformed and organized for efficient querying and analysis.

**3- Pipeline Setup**:

To facilitate seamless data movement, we establish a pipeline connecting the data warehouse to a **lakehouse** (a hybrid storage system combining data lake and data warehouse features).
The pipeline ensures that updates to the warehouse are reflected in the **lakehouse**.
![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/f56d4d00-f8d2-468b-8531-ab150d983356)

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/ed4031f0-45f8-4784-9b1c-397af8be83a7)

**4- Notebook Integration**:

We open a notebook environment and connect it to the **lakehouse**.
This connection allows us to access the data and perform exploratory analysis using tools like **Spark SQL, R, or Python**.
By following this approach, we aim to create an efficient and scalable solution for monitoring emissions data. 
The “**Unadjusted Emissions**” view, provided by the data administrator, this is our starting point for analyses and actionable insights.

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/d3c4b350-850b-4ddc-877c-13784d0833e7)

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/054266d0-3ae7-4f92-b9c9-dcaa1d62d1ee)

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/bad36871-1d13-4ad3-83e8-dbba3a4374cb)

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/1c5e5170-cf9d-499e-ba87-94bd35bfe98e)
 
 ![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/22dbf6ae-44f6-4ef1-ba72-5c7172682dd1)

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/99fd0d0b-14ad-4561-b825-cb8555c8dd9c)

![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/a3b36b29-6487-44c9-b638-37d32cd27c4f)

 ![image](https://github.com/DallasBaba/Adjusting-Unadjusted-Emissions-with-AI-Solution/assets/104704361/3fe8ff4b-972d-4d85-b2b3-57b3c10e0f31)
