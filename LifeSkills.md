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
