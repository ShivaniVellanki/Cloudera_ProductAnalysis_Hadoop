# Cloudera_ProductAnalysis_Hadoop
Analysis of an organization purchasing patterns using Apache Hadoop, moving data to HDFS without disrupting current systems.

I worked on a project focused on analyzing customer purchasing patterns for a company, using Apache Hadoop to handle their extensive transaction data. The aim was to discover which products their customers preferred to buy, a task traditionally handled by database systems. However, the sheer volume and complexity of data required a more scalable and cost-effective solution. By employing Apache Hadoop, known for its ability to process big data efficiently, I could analyze transaction data on a much larger scale. This involved transferring the existing data into Hadoop's Distributed File System (HDFS) without altering the company's ongoing reports or analysis frameworks. The challenge was to ensure that the data transfer did not disrupt any existing processes while still allowing for the enhanced analytical capabilities that Hadoop provides.

The GitHub repository related to this project contains just the documentation (.doc) detailing the research and findings of this endeavor. These files outline the entire process, from initializing the Cloudera Virtual Machine and running Sqoop ingest queries for data migration from RDBMS to HDFS, to performing MapReduce operations and analyzing the results using Hue. This detailed documentation serves as a comprehensive guide for leveraging big data analytics in product analysis, specifically highlighting how to maintain data integrity during transfer and how to utilize Hadoop for complex data analysis. This work not only provided DataCo with deeper insights into their customers' preferences but also demonstrated the practical application of big data analytics in uncovering valuable business intelligence.


