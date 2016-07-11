Spark Fundamentals II - (BD097EN)

1
Marks: 1.00
 Not flagged
Which operation should you use to map the values in a pair RDD without affecting the keys and/or partitions?

Choose one answer.
	A. mapValues	
	B. map	
	C. You cannot map a pair RDD without affecting the keys and/or partitions	
	D. Either map or mapValues
----------------------------------------------------------------------

2
Marks: 1.00
 Not flagged
With the MEMORY_ONLY storage level, what happens when an RDD can’t fit in memory?

Choose one answer.
	A. Spark will throw an OOM error	
	B. Some of the partitions will be not be cached	
	C. Some of the partitions will be spilled to disk	
	D. Spark will automatically change the storage level to MEMORY_AND_DISK	
	E. None of the options is correct

-------------------------------------------------------------------------
3
True or false: Adding a key to an RDD will automatically repartition it so the keys are co-located

Choose one answer.
	A. False	
	B. True	

Next

4
Marks: 1.00
 Not flagged
What is the result of this code?

val pairs = sc.parallelize(List(("a", 1), ("a", 5), ("b", 6), ("b", 3), ("c", 2)))

val results = pairs.reduceByKey((a, b) => {

a > b match {

case true => a

case false => b

}

}).collectAsMap()

 

Choose one answer.
	A. (“a” -> 5, “b “ -> 6, “c” -> 2)	
	B. (5, 6, 2)	
	C. (“a” -> 6, “b “ -> 9, “c” -> 2)	
	D. None of the options is correct

5
Marks: 1.00
 Not flagged
How can you reference an external class in a closure without serializing it?

Choose one answer.
	A. define it as @transient	
	B. define it as lazy	
	C. Both A and B	
	D. None of the above

---------------------------------------------------------------

6
Marks: 1.00
 Not flagged
What does the following code do?

val text = sc.textFile(“SomeText.txt”)

val counts = text.flatMap(_.split(" ")).map((_, 1)).reduceByKey(_ + _).collectAsMap()

 



Choose one answer.
	A. Maps every word in the document to the number of times it occurs	
	B. Counts the number of distinct words in the document	
	C. Counts the total number of words in the document	
	D. None of the options is correct

------------------------------------------------------------------

7

Marks: 1.00
 Not flagged
What defines a stage boundary?

Choose one answer.
	A. Shuffle dependency	
	B. Action	
	C. Transformation	
	D. Repartition

------------------------------------------------------------------

8
Marks: 1.00
 Not flagged
What does RDD stand for?

Choose one answer.
	A. Resilient Distributed Dataset	
	B. Reusable Data Directory	
	C. Reusable Distributed Dataset	
	D. None of the options is correct


9
Marks: 1.00
 Not flagged
True or False: You can execute asynchronous actions with the default FIFO scheduler.

Choose one answer.
	A. True	
	B. False

-----------------------------------------------------

10
Marks: 1.00
 Not flagged
Which of the following web-based notebook is built around Jupyter and iPython?

Choose one answer.
	A. Zeppelin	
	B. Spark Notebook	
	C. DataBricks Cloud	
	D. Data Scientist Workbench

----------------------------------------------------
11

11
Marks: 1.00
 Not flagged
How can you reduce the amount of memory used by persisted RDDs?

Choose one answer.
	A. Using Kryo serialization instead of Java	
	B. Enabling compression	
	C. Using primitive types instead of Java/Scala collections and nested classes	
	D. All of the above	
	E. None of the above

12
12
Marks: 1.00
 Not flagged
How can you view the lineage of an RDD?

Choose one answer.
	A. toDebugString()	
	B. printGraph()	
	C. printHistory()	
	D. showLineage()
-------------------------------------------------

13
Marks: 1.00
 Not flagged
True or False: Coalesce can reduce the number of partitions without causing a shuffle

Choose one answer.
	A. True	
	B. False

--------------------------------------------------------

14
Marks: 1.00
 Not flagged
In the event of a failure, how can Spark recover a lost partition?

Choose one answer.
	A. Find the last good state in RDD lineage and recompute every task.	
	B. Restart from the root RDD.	
	C. Find the last good state in RDD lineage and recompute the lost partition.	
	D. Spark’s fail-safes ensure failures don’t occur	
	E. None of the options is correct

------------------------------------------------------

15
Marks: 1.00
 Not flagged
True or False: A pool can have its own scheduler.

Choose one answer.
	A. True	
	B. False

-------------------------------------------------

16
16
Marks: 1.00
 Not flagged
Which operation has the highest chance to cause out-of-memory errors if the dataset is really large?

Choose one answer.
	A. groupByKey	
	B. map	
	C. reduceByKey	
	D. countByValue

----------------------------------------------------

17
Marks: 1.00
 Not flagged
Which of the following IDE fully supports SBT?

Choose one answer.
	A. Eclipse	
	B. IntelliJ	
	C. Nothing, use SBT for full support	
	D. Both A & B

---------------------------------------------------

18
Marks: 1.00
 Not flagged
What is speculative execution?

Choose one answer.
	A. Spark identifies slow running tasks and restarts them	
	B. Spark dynamically allocates more resources to large tasks	
	C. Spark looks for tasks it expects to be short and runs them first	
	D. None of the options is correct

---------------------------------------------

19

19
Marks: 1.00
 Not flagged
Which point in an RDD lineage is the best to persist?

Choose one answer.
	A. The root RDD	
	B. After outputting to disk	
	C. After a lot of transformations (filtering, joining, etc.) for downstream computations	
	D. Before a reduceByKey operation	
	E. None of the above

-----------------------------------------------

20
Marks: 1.00
 Not flagged
Which of the following statements about broadcast variables is true?

Choose one answer.
	A. They are shared between workers via peer-to-peer protocol	
	B. They can eliminate shuffles	
	C. They are read-only	
	D. All of the above	
	E. None of the above
