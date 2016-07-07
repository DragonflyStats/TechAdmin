                                                            1
#### Question 1
If I want to write a SQL query over a DataFrame, I have to call the following method first:

Choose one answer.
	a. map	
	b. write	
	c. registerTempTable	
	d. persist	
	e. None of the answers are correct

------------------------------------------------------------------------

#### Question 2

If I have a dataframe "person" with a field "age", which of the following expressions can never be used to reference that field?

Choose one answer.
	a. person("age")	
	b. person($"age")	
	c. $"age"	
	d. "age"	
	e. All answers are valid      

------------------------------------------------------------------------

#### Question 3

The Spark Web Console is used to:

Choose one answer.
	a. Submit Spark jobs	
	b. Edit Spark code	
	c. Monitor running Spark jobs	
	d. Examined data produced by Spark jobs	
	e. Integrate Spark with third-party tools

---------------------------------------------------------------------------

#### Question 4

Action methods have one or more of the following characteristics:

Choose one answer.
	a. Eager (immediate) evaluation	
	b. Must be the first methods in a sequence of methods	
	c. Do not support type inference	
	d. Return a new RDD	
	e. All answers are correct
---------------------------------------------------------------------------

#### Question 5

The sequence of transformation and action method calls:

Choose one answer.
	a. Forms a directed, acyclic graph	
	b. Is decomposed into stages	
	c. Is run in parallel for each data partition	
	d. Starts with some data and returns or outputs new data	
	e. All of the answers are correct

------------------------------------------------------------------------

#### Question 6 

Shuffling is used to:

Choose one answer.
	a. Move tasks to the appropriate nodes in a cluster	
	b. Sort data when that's requested	
	c. Move data between stages	
	d. Design where partitions are written to disk	
------------------------------------------------------------------------

#### Question 7

Which one of the following kinds of joins is not supported?

Choose one answer.
	a. Inner join	
	b. Left outer join	
	c. Right outer join	
	d. Left semijoin	
	e. All are supported
	e. All answers are correct

------------------------------------------------------------------------

#### Question 8 .
DataFrames support the following operations:

Choose one answer.
	a. reduce	
	b. group by	
	c. non-equi joins	
	d. delete	
	e. All answers are correct


------------------------------------------------------------------------

#### Question 9

Transformation methods have one or more of the following characteristics:

Choose one answer.
	a. Eager (immediate) evaluation	
	b. Lazy (delayed) evaluation	
	c. Their results are cached in memory	
	d. One and only one record is output for each input record	
	e. None of the answers are correct

------------------------------------------------------------------------

#### Question 10

The RDD flatMap method does what?

Choose one answer.
	a. Reads a data source	
	b. Transforms each input record to a new output record	
	c. Transform each input record to zero or more output records	
	d. Combines all records into a value	
	e. None of the answers are correct

------------------------------------------------------------------------

#### Question 11

In Hive, an external table has the property:

Choose one answer.
	a. It is visible to all users of Hive	
	b. It's schema is defined elsewhere	
	c. It's format is defined elsewhere	
	d. It's data is not managed by Hive	
	e. All of the answers are correct

------------------------------------------------------------------------

#### Question 12


In Spark Streaming, a DStream is:

Choose one answer.
	a. A collection of DataFrames	
	b. A connector to a socket	
	c. A sequence of RDDs	
	d. A fixed-sized batch of incoming data	
	e. None of the answers are correct

-----------------------------------------------------------

#### Question 13

DataFrames have one or more of the following characteristics:

Choose one answer.
	a. Support Hive integration	
	b. Handle data when its structure is known and consistent	
	c. Excellent runtime performance	
	d. Support for SQL queries	
	e. All answers are correct

---------------------------------------------------------

#### Question 14

Broadcast variables are used for what?

Choose one answer.
	a. Print messages to the Spark web console	
	b. Send metrics to a monitoring tool	
	c. Share read-only data with all tasks in an efficient way	
	d. To send all RDD data to the tasks	
	e. None of the answers are correct

-----------------------------------------------------

#### Question 15

Accumulators are used for what?

Choose one answer.
	a. Collect the results of the Spark job	
	b. Manage streams in Spark Streaming	
	c. Send metrics to a monitoring tool	
	d. Aggregate extra data across all tasks	
	e. All answers are correct

-----------------------------------------------------

#### Question 16

The Inverted Index computes what?

Choose one answer.
	a. The records sorted descending by a key	
	b. A table of contents for a corpus of documents	
	c. The minimum, maximum, and average counts for words in the corpus	
	d. Output records with words as keys and document ids and counts as values	
	e. All of the answers are correct

-----------------------------------------------------

#### Question 17

Which language is not supported by Spark?

Choose one answer.
	a. Java	
	b. Scala	
	c. Python	
	d. C	
	e. SQL

-----------------------------------------------------

#### Question 18

The batch interval:

Choose one answer.
	a. is determined dynamically by Spark	
	b. starts at a user-specified value and adjusts in response to load	
	c. is the number of events to capture per batch	
	d. is the number of seconds to capture data per batch	
	e. is the size of each data "chunk" returned by a DataFrame query

-----------------------------------------------------------------------------

#### Question 19

The DataFrame expression ``"persons.select($"age").where($"age" > 21)"`` returns:

Choose one answer.
	a. A DataFrame	
	b. A RDD	
	c. A ResultSet	
	d. A Scala Vector[Int]	
	e. None of the answers are correct

-----------------------------------------------------------------------------

#### Question 20

What does RDD stand for?

Choose one answer.
	a. REPL Definition and Description	
	b. Resilient Distributed Dataset	
	c. Reader Distribution Defined	
	d. Resilient Documented DataFrame	
	e. Read, Distribute, Delete
