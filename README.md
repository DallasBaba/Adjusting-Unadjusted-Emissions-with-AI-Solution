In this project, we leverage a dataset obtained from the **Environmental Protection Agency** (EPA) via their website. 

The dataset, named egrid2022_data, contains valuable information related to energy generation, emissions, and power plants.

Our focus lies on a specific subset of this data, including the tables labeled as **UNT22, GEN22, PLNT22, and US22**. These tables serve as the foundation for creating a **view** named “**Unadjusted Emissions**”. 

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

**4- Notebook Integration**:
We open a notebook environment and connect it to the **lakehouse**.
This connection allows us to access the data and perform exploratory analysis using tools like **Spark SQL, R, or Python**.

By following this approach, we aim to create an efficient and scalable solution for monitoring emissions data. 
The “**Unadjusted Emissions**” view, provided by the data administrator, will be our starting point for insightful analyses and actionable insights.
