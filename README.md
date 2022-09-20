# Data Warehouse vs Data Lake: Pros and Cons

With critical business decisions relying on a large amount of data, the decision to use an enterprise data warehouse strategy or deploy data lake stores is a significant one.

We’ll outline the pros and cons of data lakes and data warehouses, but first, it’s important to understand the key differences between the two as it relates to the type of data being stored, the various sources it can use, and the different approaches to processing data.

## What Is a Data Warehouse?

A data warehouse is a large store of data and a set of processes collected into a database. The primary purpose of a data warehouse is to help organizations with data analytics as part of their business intelligence.

As a central repository, data is used to analyze heterogeneous sources of business data within the database.

- Data is typically subject-oriented, such as supply chain or sales inventory.
- Data typically includes a time-variant, such as a month, day, time, etc.
- Data warehouses can combine data sets from multiple sources, including cloud, relational databases, structured and semi-structured data, and metadata as long as the data structure is consistent.
- Data is persistent and not deleted when new data is added.

## What Is a Data Lake?

A data lake is a highly scalable storage repository that ingests raw data regardless of its format. The data gets cleansed, validated, and processed through streaming pipelines. Data can then be stored in tables for reports, dashboards, or made available to feed other systems downstream, including data warehouses.

- Data often comes from disparate data sources.
- Data can include a mix of structured, semi-structured, and unstructured data formats.
- Data is stored with a flat architecture and can be queried as needed.
- A data lake is an efficient way for companies to collect and store a large amount of data, including raw data, especially when they don’t need to process or analyze it immediately.

# Data Lake vs Data Warehouse: The Pros and Cons

Traditional data warehouses still play an important role in business intelligence, but face challenges from Big Data and the increased demands from data scientists to do deeper data analysis using varied sources, including social media.

Using a data lake allows for the storage of more varied data and lower costs for storage. However, a data lake is more complex when it comes to queries.

Here are the pros and cons companies need to consider when comparing a data warehouse and a data lake.

### Data Warehouse: Pros

A data warehouse stores data from multiple sources in a common format using the Extract, Transform, Load (ETL) process and verifying the integrity of the data. Other advantages of data warehouses include:

- Maturity: If you’re looking for a way to store data, a data warehouse is a well-established and proven way to do so. There are mature tools for data analysis and the SQL server stack is widely available.
- Maintenance: Data warehouses typically perform efficiently with little maintenance. If you do need to work on your warehouses, there are plenty of IT teams with the skill sets needed.
- Performance: Since data warehouses use a schema-on-write process, the common underlying data structure makes it easy for the query engine to sift through data and generate results quickly.
- Usability: Rather than sort through raw data or complex data structures, users find it easy to find what they need.
- Flexibility: Companies can store data in the cloud, such as using an Azure SQL database, or use an on-premises SQL server stack for storage.
- Data Marts: Data marts can provide structure and access to specific environments within a single functional data set. For example, you can create data marts for specific product lines.

### Data Warehouse: Cons

While there are advantages to using a data warehouse for data storage, there are also some disadvantages.

- Storage Costs: One of the downsides of data warehouses is the cost of storage for large volumes of data. Database resources will be more expensive than for a data lake.
- Time: Each business process component must be built to extract value from the data. It can be time-consuming to get data into the data warehouse using an ETL process. For example, if you want to do data analytics on current and historical data, but the source data is not currently in the database, it will have to be processed and added before you can examine it.
- Limited Source Data: Because of storage costs and the need to process data, organizations often limit what data is captured and stored and what data sources are ingested. In most cases, this leads to storing data for known reporting requirements rather than raw data or data you may need in the future.
- The Big Data Challenge: A data warehouse is not built for Big Data analysis. Data warehouses are not optimized for the massive amount of data being collected and its variety. Data scientists may find significant limits during database queries because of what’s not being stored either in the cloud or on-premises.
- Complicated Changeover: If you decide in the future that you want to add different parameters to what data is captured and stored, it can be complicated. Historical data must either be reprocessed or not include the new parameters that you want.
- Potential for Data Distortion: Since data quality relies on pre-load data cleansing, any error in the processing means data will be distorted in perpetuity.

### Data Lake: Pros

Data lakes are more suited for data analysis from diverse sources, especially in cases where the initial cleaning of data is intensive or problematic.

Here are some of the big advantages of a data lake:

- Volume and Variety: A data lake can accommodate the large amount of data that Big Data, artificial intelligence, and machine learning requires. Data lakes can handle the volume, variety, and velocity of data from various sources being ingested in any format. 
- Speed of Ingest: Format is irrelevant during ingest. Rather than schema-on-write, it uses schema-on-read, which means data doesn’t need to be processed for use until it is needed. Data can be written quickly.
- Lower Costs: Relative to a data warehouse, a data lake can be significantly less expensive when it comes to storage costs. This allows companies to collect a wider variety of data, including unstructured data such as rich media, sensor data from the Internet of Things (IoT), email, or social media.
- Greater Accessibility: Data stored in a data lake makes it easy to open copies or subsets of data to be accessed by different users or user groups. Data access can be controlled while companies can provide broader accessibility.
- Advanced Algorithms: Data lakes let companies conduct complex queries and deep learning algorithms to recognize patterns.

### Data Lake: Cons

Depending on your data storage and data analysis needs, data lakes also have some downsides. 

Disadvantages of using a data lake in organizations include:

- Complex On-Premises Deployment: Spinning off a data lake in the cloud is a simple process. Deploying a data lake on-premises can be significantly more complex. On-prem solutions such as Hadoop or Splunk are available, but data lakes are built for the cloud.
- Learning Curve: There is a bit of a learning curve, new tools, and new services with a data lake. This requires either outside help, training, or recruiting team members with data lake skill sets.
- Migration: If you’re already working with a data warehouse, transitioning to a data lake takes some careful planning of your data strategy to manage your data sets. Depending on your infrastructure, this can be a challenge.
- Handling Queries: It’s fast and easy to ingest data, but a data lake is not optimized for queries in the way structured and semi-structured data is in a data warehouse. Using best practices for database queries can help, but data retrieval is not as straightforward as it is with a data warehouse. In a data lake, data is processed after it’s been loaded using the Extract, Load, Transform (ELT) process.
- Governance, semantic consistency, and access controls are required, otherwise, the data lake may turn into a “data swamp” of unusable, raw data.

## Data Lake vs Data Warehouse: Which Option Is Right for You?

- Depending on your business needs and relevant data, data lakes and data warehouses are both viable solutions. Many companies find a hybrid approach that addresses different goals of business intelligence is a smart approach.

- Data warehousing and data lake solutions can store a lot of data. Your data strategy should examine use cases, business processes, and the different approaches needed in your business.

- Which data platform is right for you and your organization? Here are some of the key considerations you will need to take into account, including the type of data you need to capture and the use cases for the data as you define your data strategy.

## Defining Your Data Strategy

When you are defining your data strategy, you should weigh the pros and cons of data warehouses and data lakes. How your organization will approach data set collection, storage, and usage will help you determine the right path to take.

### Here are some of the major questions you need to answer as you define your data strategy:

#### What Types of Data Sets are You Working With?

- 80% of the world’s data will be unstructured by 2025. For many companies, this has already hit critical mass with lots of data, data sets, and data types being unstructured. This forces companies to make decisions. Do you want to collect and store unstructured data in a data lake, then process it when you need it or do you want to process unstructured data and turn it into semi-structured or structured data before storage?

- It gets complex quickly as some data cannot be structured in the way a data warehouse would need to be available for data science queries. For example, the metadata attached to a video or social media post may not fit into neat formats that allow for data analysis without pre-processing. This is where governance products have to evolve and work in tandem with Data Warehouses and Data Lakes to provide Data Scientists insight into what is relevant for them. Ideally, governance products can and should be the entry point for the Data Science community.

#### What Data Are You Working With and How Will it grow in the Future?

- There is a lot of data out there. The amount of data being created, captured, and consumed globally is expected to grow by more than 50% between 2020 and 2022. Any solution you choose to store your data sets must be able to handle the velocity of data growth and consider the costs.

#### What Are Your Data Science Needs?

To gain insights from Big Data and advanced data analytics, your data solution should meet the requirements for AI, machine learning, natural language processing, and deep learning, along with accommodating the variety of data sources that will be ingested.

#### Data Management and Governance Needs?

Both data warehouses and data lakes create challenges for governance and compliance. With a data warehouse, you need to constantly manage and maintain the data that is ingested to make sure it is added with consistent business logic and data model.

Data lakes may be more difficult to govern because of the ability to ingest any data type. Data is less structured and can easily be loaded into a data lake without validation or organizational data standards applied without proactive management.

#### Should you choose Cloud or On-Prem?

There are pros and cons to keeping data on-premises or in the cloud. While you may prefer the security and protection of an on-prem solution, the cloud offers the ability to scale compute capacity to match demand.

#### What Skills and Tools are Required?

While you shouldn’t make foundational decisions about your business based on your current tools and skillsets, you do need to make sure you have what you need to operate efficiently. Examine the current skillsets of your data engineering team and the tools you have. This will help determine what you need to add to effectively implement your data strategy. There should be a good blend of traditional and up/coming tools to attract new talent and transform the talent continuously.

#### Should you build in-house or buy?

A crucial decision will be whether to build or buy. Will you be able to build the solution you need yourself and maintain it or do you need to bring in outside contractors? Consider the opportunity costs. Building this solution yourself takes considerable skillsets, time, and maintenance effort. However, some organizations may choose this route to meet unique requirements that off-the-shelf solutions don’t solve.

