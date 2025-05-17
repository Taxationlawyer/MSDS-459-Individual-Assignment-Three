## Part One, Structured Querying 

SQL (Structured Query Language) has decades of proven reliability. The schema language structure type of storage is precisely defined and leaves very little room for error, if any. It is a science (as opposed to art). For that reason (and probably other reasons), SQL works very well in a completely controlled environment, specifically for querying the data within the schema language structure. Good luck using this system to store and query incredibly large amounts of data that comprises in good part of natural language, however. It will not work. Against that backdrop, there are robust systems available that leverage the best of SQL and are robust in processing natural language. Chapter 12 (of the book entitled “Knowledge Graphs) covers 3 keys aspects: (1) SPARQL, (2) NoSQL, and (3) hyperplanes and tuples. 

(1) SPARQL works by using a graph query pattern. That means that it uses a triple pattern for querying (subject, predicate, and object). One example of how SPARQL combines the best of both worlds (schema language structure and natural language processing) is the use of “[t]riple (vertical) table stores.” These setups consist of tables (tabular data setup) that contain, as columns, the triples (subject, predicate, and object). 

(2) Another method that is more robust than SPARQL, when dealing with highly unstructured data, is NoSQL. With NoSQL, the data can be structured as documents. Moreover, NoSQL is useful for graphs, because the “entity relationships are easy to map.” 

(3) Still another method for dealing with data is to use hypernodes and hypergraphs. This is where the rubber hits the road. Chapter 12 starts the discussion by stating that some of the methods are a combination of natural language processing and machine learning. To that end, hypernodes are tuples—that is mentioned in Chapter 12. And the hypernodes (the tuples) are represented on a hypergraph—also, described as a hyperplane. This appears to be a support vector machine (“SVM”) algorithm. In SVMs, data are represented as tuples on a hyperplane. These tuples are representations of large amounts of information. 

In conclusion, Chapter 12 is a very good discussion of alternative methods to the SQL practices. The alternative methods are more robust because they can deal with natural language processing and are more efficient and faster than traditional schema language structures. And, most importantly, these methods work with knowledge graph tasks. 

**Reference**

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. 2021. Knowledge Graphs: Fundamentals, Techniques, and Applications. Cambridge, MA: MIT Press. [ISBN-13: 978-0262045094]
