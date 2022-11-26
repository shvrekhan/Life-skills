# NoSQL
A NoSQL database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases.

The data structures used by NoSQL databases (e.g. key–value pair, wide column, graph, or document) are different from those used by default in relational databases, making some operations faster in NoSQL. The particular suitability of a given NoSQL database depends on the problem it must solve. Sometimes the data structures used by NoSQL databases are also viewed as "more flexible" than relational database tables.

# Types of NoSQL databases
NoSQL databases (aka "not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model.
- Key/Value store 
- Document database
- Column oriented database
- Graph database 

# When to use NoSQL
- NoSQL are good fit for the rapid agile devlopment, NoSQL allows developer to in control of the structure of data.
- Gives a upper hand to handelling the semi-structured and the un-structured data.
- To handel the de-centerlised NoSQL is very effective and effecnt.
- NoSQL is designed to handel the situation like hardware fail to minimise the down time.

# Key/Value store
 ## How key value database work?
Key-value databases use compact, efficient index structures to be able to quickly and reliably locate a value by its key, making them ideal for systems that need to be able to find and retrieve data in constant time. Redis, for instance, is a key-value database that is optimized for tracking relatively simple data structures (primitive types, lists, heaps, and maps) in a persistent database. 

## features of a key-value database
- Retrieving a value (if there is one) stored and associated with a given key.
- Deleting the value (if there is one) stored and associated with a given key.
- Setting, updating, and replacing the value (if there is one) associated with a given key.
 
## When to use key-value database
 - Real time random data access, e.g., user session attributes in an online application such as gaming or finance.
 - Caching mechanism for frequently accessed data or configuration based on keys.
 - Application is designed on simple key-based queries.

# Document databse
## How document database work
A document database is a type of nonrelational database that is designed to store and query data as JSON-like documents. Document databases make it easier for developers to store and query data in a database by using the same document-model format they use in their application code. The flexible, semistructured, and hierarchical nature of documents and document databases allows them to evolve with applications’ needs. The document model works well with use cases such as catalogs, user profiles, and content management systems where each document is unique and evolves over time.

## Feature of document database
- Document Type Model
- Flexible Schema
- Distributed and Resilient
- Manageable Query Language

## When to use document database
- These data models are very much used in creating various video streaming platforms, blogs, and similar services Because each is stored as a single document and the database here is much easier to maintain as the service evolves over time.
- These are very much useful in making book databases because as we know this data model lets us nest.
- When it comes to storing and reading catalog files these data models are very much used because it has a fast reading ability if incase Catalogs have thousands of attributes stored.

# Column oriented database
## How column orientd database work
column-store databases do exactly what is advertised on the tin: namely, that instead of organizing information into rows, it does so in columns. This essentially makes them function the same way that tables work in relational databases. Of course, since this is a NoSQL database, this data model makes them much more flexible.

## Feature of column database
- Since a majority of the information is stored in a column, aggregation queries are quite fast, which is important for projects that require large amounts of queries in a small amount of time.
- Scalability is excellent with column-store databases. They can be expanded nearly infinitely, and are often spread across large clusters of machines, even numbering in thousands.
- Load times are similarly excellent, as you can easily load a billion-row table in a few seconds. That means you can load and query nearly instantly.

# Graph Database
We live in a connected world, and understanding most domains requires processing rich sets of connections to understand what’s really happening. Often, we find that the connections between items are as important as the items themselves.

## How graph database work
Graphs and graph databases provide graph models to represent relationships in data. They allow users to perform “traversal queries” based on connections and apply graph algorithms to find patterns, paths, communities, influencers, single points of failure, and other relationships, which enable more efficient analysis at scale against massive amounts of data. 

## When to use graph database
- Fraud detection
- Recommendation engines
- Navigate deep hierarchies,
- Find hidden connections between distant items





# Refrences
- https://learning-notes.kovacevic.dev/databases/nosql/nosql/
- https://www.geeksforgeeks.org/document-databases-in-nosql/
- https://www.mongodb.com/document-databases
- https://aws.amazon.com/nosql/document/
- https://neo4j.com/developer/graph-database/
- https://aws.amazon.com/nosql/graph/
