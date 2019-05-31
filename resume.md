# Sachin Shukla

**Email:** ss_india2001@yahoo.co.in \
**Phone:** 9535536087

## Summary
Experience in building large, scalable, secured, distributed systems in Advertising, Ecommerce, Social area. Working as platform architect/engineer for last 13 years. Successfully built several products from scratch. Worked on diverse application architectures 
* Web services (Restful, RMI) 
* Nosql Databases (HBase, Dynamodb) 
* Relational Databases (MySql, Oracle) 
* Queues (RabbitMq, Kafka, ActiveMQ) 
* Streaming solutions (Storm) 
* Big Data (Hive)

Familiar with several programming languages - Java, Python, C#.

## Project Experience
### AWS Search Services
#### Domain Lifecycle Re-architecture (Aug 2017 - ) 
* Architect for designing the AWS Elasticsearch cluster provisioning at scale. Cluster provisioning and management platform serves thousands of AWS/ES clusters. The cluster creation, configuration changes, version upgrades are orchestrated by this system. It ensures cluster availability and prevents data loss, across these mutations. It is also used for component deployment in the running cluster. It provides blue/green, in-place, rolling deployment support. 
* Lead development of several other features related to security, encryption at rest/transit, master election support.
* Lead the initiative of moving the AWS Elasticsearch release process to Continuous integration and deployment. 

##### Technologies
Java, Dynamodb, Elasticsearch, AWS/SWF workflow, Python

#### Amazon Retail - AmazonNow (Mar 2017 - Aug 2017)
Architect for the AmazonNow team. Worked on database migration from Oracle to Sable and Dynamodb. 

##### Technologies
Java, Dynamodb, Sable

### Flipkart (Feb, 2014 - Mar, 2016)
#### Ads: Auction based Pricing (Feb 2016 - )
Designed and lead the adoption of Second Price auction mechanism for Flipkart product listing Ads. I socialised the auction based pricing with the Flipkart senior management. Provided the design along with the roadmap for building the keyword feature in the system. Worked with different teams Campaign management, Reporting, Ranking to identify the impact. Prepared design covering all the components. Identified key success metric sand design for providing bid suggestions. Designed the data pipeline to aggregate the auctions data

##### Technologies
Couchbase, Dropwizard, RxJava, MySQL, Hive, MapReduce, Jdbi

#### Ads: Full Funnel Attribution Pipeline
Attribution compares the uplift in the activities done by the users exposed to the campaign to the un- exposed users. The advertisers use the uplifts to measure the effectiveness of their campaigns. Designed and implemented a pipeline on the Flipkart Data Platform (FDP), to compute the uplift for search, browse, purchase and product page views. 

Interfaced with several teams to make the data available for computation. Designed and implemented the pipeline on Hive.

##### Technologies
Hive, Azkaban

#### Ads: Pricing Service (Feb, 2014 - Sep, 2015)
Designed a low latency, scalable and fault-tolerant price management system for managing and serving the click rates for all the listing ads. The serving system operated at extremely low latency under 10ms with average load of 1000 QPS and peak load of 15000 QPS.
The system overlays the Flipkart product category tree with the price points. It allows operations to set the price for the categories. The system resulted in growing the revenue by 3 folds.
* Conceptualised the solution and the architecture
* Introduced the smart client design for extreme low latency. Design multiple caching layers.
* Introduced in-memory MySql for testing
* Mentored junior team members.

##### Technologies
Couchbase, Dropwizard, RxJava, MySQL.

### Microsoft Adcenter (Jun, 2013 - Feb, 2015)
#### Campaign Product Management (Mar, 2014 - Feb, 2015)
Worked on the advertising location (product) management component of the Microsoft advertising platform. Implemented the programmatic direct apis for the products. Implemented the apis and sql server backend. Migrated from on-premise to Azure based implementation.

##### Technologies
 C#, .Net, Azure Caching, Azure Data Table, Azure Blob Store, SQL Server

#### Audience Insights Portal (Jul, 2013 - Mar, 2014)
Implemented the audience insights portal, for displaying the Unique Users across the devices, demographic segments, audience targeting segments. Designed the system with Restful api layer, Reporting UI and sqlserver based pre-aggregations of data.

##### Technologies
C#, .Net, Azure Caching, Azure Data Table, SQL Server

### Yahoo (Dec, 2009 - Jun, 2013)
#### Trending URL Extraction Pipeline (Jan, 2013 - Jun, 2013)
The processing pipeline was created to ingest tweets from the Twitter Firehose, and extract the trending URLs using Storm and Kafka based pipeline.

##### Technologies
Storm, Kafka

### UGC Cloud (Dec, 2009 - Dec, 2013)
#### Development of a new platform for storage of user generated content like ratings, reviews, comments, blogs and message boards. The system also provides features like access control, metrics, scalability and fault tolerance. The apis are exposed as Restful webservices. An in-house distributed hash table is used for data storage. The system handled read at 4000 QPS and write at 100 QPS. Scaled the offline processing component using ActiveMQ.
* Designed and lead the development of ratings and reviews interface
* Architected and lead the development of the datamigration framework for the platform
* Developed many cross-functional features for request tracking and system profiling
* Provide guidance for all java related architecture and issues

##### Technologies
Spring, Jersey, Tomcat, Jackson-json, Nosql datastore, ActiveMQ

### HeadStrong India (Dec, 2004 - Nov, 2009)
Worked over various projects for clients

#### FINRA Oats Reporting Platform (Aug, 2009 - Nov, 2009)
Design and development of a multi-user batch platform for reporting orders from client OMS systems to FINRA. The orders are provided to the job as FIX messages dumped in a file. The job generates an audit trail of the messages for identification and conversion to FINRA Oats format. It also performs validation and repairing of data. System has a web front end for viewing and correction of records.

##### Technologies
Spring, Spring batch, hibernate, junit, jmock, JMX, Oracle 10g, Sqlldr, Quickfixj, Tomcat.

#### Poker - Parameter Service (Jan, 2008 - Jul, 2009)
Development and support of a global, scalable, fault-tolerant and highly available platform for storing parameters required for derivatives processing (volatility, rates etc). The UBS in-house RMI based RTTP engine was used as a framework to provide a distributed cloud for storing the parameters. All the poker services were run as separate processes managed by RTTP infrastructure. Poker provided a feature to setup rules to derive from parent to child parameters and validations. The clients could connect using an RMI based client library or a REST api exposed via an http service. 

##### Technologies
RMI, Spring, hibernate, junit, jmock, FIT, JMX, Oracle 9i

#### Derivates Trade Blotter (Apr, 2007 - Jan, 2008)
Development and maintenance of a sales blotter for entering derivative trades for the institutional clients and generating RTF term sheets. It was a spring MVC and hibernate based web application with oracle 9i as backend. Front end was designed using dojo. Term sheet templates were implemented using RTF template.

##### Technologies
Spring MVC, dojo, hibernate, Apache, Tomcat, Jcifs, RTFtemplate

#### FX Options (Feb, 2006 - Jan, 2007)
Prototype of an infrastructure for auto pricing the quotes and deals from Bloomberg and spreadsheet clients. System was hosted on Cameron FIX server and logically divided into various components for handling Fix protocol to system pojo conversion, market data retrieval, pricing, post trade processing and swing based GUI for monitoring and manual intervention – which were wired using in-memory enterprise message bus architecture.

##### Technologies
Java, FIX, Cameron, Swing, Tibco Rendezvous, Spring

#### FX Trader Console Development (May, 2005 - Feb, 2006)


 
