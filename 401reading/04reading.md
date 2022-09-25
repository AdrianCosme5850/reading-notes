# Data Modeling  

## nosql vs sql  

1. Sql databases are the best fit for complex query intensive environments, because sql has a standard for performing complex queries.  
2. NoSql databases are better for hierarchical storage because of the key value pair association.  
3. Sql are vertically scalable meaing to decrease search time you need more powerful computing ability. Nosql needs less information in each database to increase its speed.  

## sql modeling techniques  

1. One to many refers to records in one table being refered to by many records in another. These are related by having the many in another table have a foreign key that is equal to the main id in the one table.  
2. It may be important to define your native keys and foreign keys beforehand.  
3. A primary key refers to where a record is located in its own table. A foreign key is a reference from one record in a table to another.  

## sql vs nosql  

1. Parameters are defined across all of the records, whereas in nosql the keys are unique to each object.  
2. Data must be formatted to fit into each table schema in your sql database.  
3. One to one means that an item in our database is related strictly to one other iem in another table. One to many means that one item is related to many in another database. Many to many is that several items in one table to be related to many in another table.  

