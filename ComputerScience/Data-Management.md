# Data Management

#### Developer Interface
- To create user-friendly features e.g. forms
- To create output reports
- To create interactive features e.g. buttons

#### Query processor
- To create SQL queries
- To search for data that meets set criteria





#### Why web application uses server-side scripting \[3\]
- All data is held on the server
- The client doesn't have access to all the data,
- ... which keep the data more secure
- Customers can be identified when they log in,
- ... from a database of usernames and passwords

## Database

#### Database terms
`Table`/`Relation`: all the data about one entity
`Record`/`Tuple`: the data in one row of a table
`Attribute`: a column or field in a table

#### Features of a rational database \[4\]
Max 3 from each group

- Multiple tables are linked together
- ..., which eliminates data redundancy
- ... and increase data consistency
- data need only to be updated once
- ... and associated data will be automatically updated
- ..., which make it easier to maintain the data


- Allows concurrent access to the data
- ... by the use of record locking


- Complex queries can be more easily written


#### Normalization

##### 1NF
- No repeating groups

##### 2NF
- No partial dependencies

##### 3NF
- No non-key(transitive) dependencies


When explaining why is not in 3NF, say also `...` is dependent on `...` which is not the primary key.


