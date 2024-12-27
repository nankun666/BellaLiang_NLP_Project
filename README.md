# Overview

In this project, I configured and provisioned a Spark cluster on **AWS EMR (Elastic Map Reduce)**, connecting it to a Jupyter Notebook to leverage transformations and actions using **PySpark**. The goal was to perform basic data analysis by running a series of queries (in Python with the **DataFrame API** or **Spark SQL**) and solve several questions related to the IMDB dataset.



### **Setup Instructions**

##### 1. **Create and Configure Spark Cluster**

- Launch an **AWS EMR** cluster with Spark installed.
- Configure the necessary permissions and attach appropriate IAM policies.

##### 2. **Set Up Notebook Environment**

- Access **AWS Studio** and launch a workspace.
- Connect the EMR cluster to the notebook environment to enable **PySpark** for data processing and analysis.

##### 3. **Access Data**

- Load the IMDB dataset from a publicly available **AWS S3 bucket** into the cluster for analysis.

  

### Data Source

The IMDB data is read from a publicly available **AWS S3 bucket**.



### Analysis using pySpark

##### Part I: Installation and Initial Setup

In this part, I load the dataset into a **PySpark DataFrame** and import the necessary dependencies, such as **pandas** and **matplotlib**, for data manipulation and visualization.

##### Part II: Analyzing Movie Genres

Here, I denormalize the genre information associated with each movie title, then perform basic analysis on the resulting data.

##### Part III: Analyzing Job Categories

In this section, I identify the most common job categories in the dataset and visualize the distribution of these categories.

##### Part IV: Answering Rating and Info Queries

Finally, I answer several specific queries related to movie ratings and other related information based on the IMDB dataset.