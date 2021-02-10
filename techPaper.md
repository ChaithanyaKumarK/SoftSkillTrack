# What is NoSQL?
"NoSQL database" refers to "non SQL" or non-relational database. NoSQL database is sometimes called as Not only SQL because it may support SQL like query languages. It is a misconception that the NoSQL database does not store relationship data well rather store data in a format other than relational tables.

NoSQL databases came into the picture in the late 2000s when the cost of storage was reduced. In the initial days complex, difficult-to-manage data models were built only to save storage or to avoid data duplication. 
Now NoSQL removes that barrier and is optimized to give freedom to the developer.

NoSQL can be preferred over SQL because they are highly scalable, superior performance, capable of running a large number of nodes, non-locking concurrency mechanism, schema-less data model, scalable replication and distribution, and high availability.

### Types of NoSQL
>1.Document databases

>2.Key-value databases

>3.Wide-column stores

>4.Graph databases

![Types](https://www.guru99.com/images/1/101818_0537_NoSQLTutori1.png "Diagram of Types")

for detailed explanation of NoSQL types [click here](https://www.digitalocean.com/community/tutorials/a-comparison-of-nosql-database-management-systems-and-models "NoSQL types")

---

## MongoDB 
* It is written in `C++` 
* Its a document type NoSQL
* Its mostly used for JSON document store
* **License:** AGPL (Drivers: Apache)
* Queries are in javascript expressions
* It has a very good performance and lets you have a huge database.
* It is used for dynamic queriers.
* It's mostly used in IoT, real-time analytics, and personalization.

---
## H-Base
* It is written in `Java`
* It's a Wide-column store type NoSQL
* It can handle Billions of rows X millions of columns
* **License:** Apache
* It's based on Google's [Bigtable](https://research.google/pubs/pub27898/)
* Random access performance like in MySQL
* The solution is cost-effective even when the data is scaled to petabytes.
* Used to store genome sequence and matching the same.
* Used application that needs large volume like Tweets, Facebook posts, etc.
* It is mainly used for running online analytics for large datasets.
* User to store online user history for better customer tracking.


---
## Cassandra
* Written in `Java`
* It's a Wide-column store NoSQL.
* Huge datasets
* **License:** Apache
* You can write triggers in Java
* Best in class scalability and query performance 
* High availability and low cost of ownership.
* It's used in fraud detection, IoT.
* Used in recommendation engine and messaging application.
* Used by companies like Twitter and Netflix.

---
## Redis
* Written in `C`
* It is a Key-value NoSQL database.
* It is super fast
* **License:** BSD
* It supports data structures such as strings, hashes, lists, sorted sets with range queries, bit maps, hyper logs, and many more.
* Used for rapidly changing data with foreseeable database size.

---
## Neo4j
* Written in `Java`
* It's a graph-based NoSQL database.
* **License:** GPL
* Standalone, or embedded into Java applications.
* Full ACID conformity.
* Used for graph-style, rich or complex, interconnected data.
* Used in searching routes in public transport links, road maps, social relations, or network topologies.

---
## Conclusion


NoSQL provides many advantages in dealing with Big Data Storage, querying, and processing. It is also suitable for high volume state changes per second with many simultaneous distributed users. The cost of data replication will be at a low cost while optimizing system resources.


Each type of NoSQL is designed with a particular scenario in mind, and there would be technical reasons for how each kind of database should be organized. Each database in NoSQL has different speeds and availability, developers have to choose between NoSQL carefully according to their specific needs in the terms of scalability, costs, consistency, performance, security, and other respective areas.
 
 ---
 ## Sources
 * NoSQL explained - [mongodb.com](https://www.mongodb.com/nosql-explained "mongodb.com")
 * Introduction to NoSQL - [geeksforgeeks.org](https://www.geeksforgeeks.org/introduction-to-nosql/)
 * Comparision of NoSQl databases - [kkovacs.eu](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis)
 * Types of NoSQL Databases - [guru99.com](https://www.guru99.com/nosql-tutorial.html)
 * Comparison and Classiﬁcation of NoSQL Databases for Big Data - [researchgate.net](https://www.researchgate.net/publication/278963532_Comparison_and_Classification_of_NoSQL_Databases_for_Big_Data)
 *   Top 5 NoSQL Databases Programmers Should Learn in 2021 - [javarevisited.blogspot.com](https://javarevisited.blogspot.com/2019/03/top-5-nosql-database-web-developers-should-learn.html#axzz6lonWqaqm)
 * A Comparison of NoSQL Database Management Systems and Models - [digitalocean.com](https://www.digitalocean.com/community/tutorials/a-comparison-of-nosql-database-management-systems-and-models#key-value-databases)
 * Cassandra vs MongoDB vs HBase | Difference Between Popular NoSQL Databases | Edureka - [youtube.com](https://youtu.be/QlqylUeqeis)