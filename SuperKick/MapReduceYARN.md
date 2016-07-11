
Marks: 1.00
 Not flagged
What are the main components of ResourceManager with YARN?  (Select TWO).

Choose at least one answer.
	a. Scheduler	
	b. JobTracker	
	c. DataManager	
	d. HDFS	
	e. ApplicationManager	
Next

----------------------------------------------------

2
Marks: 1.00
 Not flagged
Which of the following statements is true?

Choose one answer.
	a. Both MapReduce and YARN can scale to any size cluster.	
	b. The NodeManager in Hadoop 2 replaces the TaskTracker in Hadoop 1.	
	c. YARN requires a minimum of two nodes (one master, one slave) to run	
	d. The NameNode in Hadoop 2 is fully fault-tolerant, whereas in Hadoop 1 it was a single point of failure.

---------------------------------------------------

3
Marks: 1.00
 Not flagged
Which of the following is true about MapReduce?

Choose one answer.
	a. MapReduce programs must be written in Java.	
	b. Output from the Map phase is replicated.	
	c. The programmer must write the Map code, the Shuffle code, and the Reduce code.	
	d. Compression of input files is optional.

-------------------------------------------------


4.
4
Marks: 1.00
 Not flagged
Input data to MapReduce is record oriented and splits (blocks) of data contain the same number of full records.

Answer: True False

----------------------------------------------

5
Marks: 1.00
 Not flagged
Which of the following statements is true?  (Select ONE)

Choose one answer.
	a. You can set the number of Mappers	
	b. You can set the number of Reducers	
	c. You can set the number of Mappers and the number of Reducers.	
	d. The number of Combiners is the same as the number of Reducers.	
	e. The Shuffle phase is optional.

----------------------------------------------

6
Marks: 1.00
 Not flagged
Which statement is true about MapReduce use of replication in HDFS?

Choose one answer.
	a. Multiple copies of each record are kept on each node.	
	b. Speculative execution is normally performed on all copies of each “split.”	
	c. Each DataNode uses RAID to store its data.	
	d. Only one copy of each replicated block is processed by MapReduce in normal operation.

-----------------------------------------------

7

7
Marks: 1.00
 Not flagged
The command `classpath hadoop` provides the CLASSPATH needed for compiling Java programs written for MapReduce / YARN.

Answer: True False

--------------------------------------------------

8
Marks: 1.00
 Not flagged
Which of the following is the correct sequence of MapReduce flow?

Choose one answer.
	a. Map —> Combine —> Reduce	
	b. Combine —> Reduce —> Map	
	c. Map —> Reduce —> Combine	
	d. Reduce —> Combine —> Map


-----------------------------------------------------

9
9
Marks: 1.00
 Not flagged
Which statement is true about the Reduce phase of MapReduce?

Choose one answer.
	a. Each Reduce task processes all the data for one key only.	
	b. Data arrives from the Shuffle phase already sorted by key.	
	c. The Reducer phase sums up the values associated with each key.	
	d. Output (results) are sent to the client program

-------------------------------------------

10

10
Marks: 1.00
 Not flagged
Which of the following can be used to control the number of part files in a MapReduce program output directory?

Choose one answer.
	a. Number of Mappers	
	b. Number of Reducers	
	c. Counter	
	d. Shuffle parameters

-------------------------------------------
11
Marks: 1.00
 Not flagged
What will an Hadoop job do if you try to run it with an output directory that is already present?

Choose one answer.
	a. It will not run.	
	b. It will create another directory to store the output.	
	c. It will erase all files in that directory before running.	
	d. New files will be created, but with a different suffix.

---------------------------------------------
12
Marks: 1.00
 Not flagged
Which statement is true about YARN?

Choose one answer.
	a. Each job has an ApplicationManager that obtains Container IDs from the NodeManager.	
	b. There is one JobTracker in the cluster.	
	c. MapReduce jobs written in Java for MRv1 never require recompilation.	
	d. Containers are used instead of slots with MRv1 and can be used with either Map or Reduce tasks with MRv2.

---------------------------------------------

13


13
Marks: 1.00
 Not flagged
With YARN, long-running jobs acquire and retain fixed-size containers before execution starts?

Answer: True False

---------------------------------------

14
Marks: 1.00
 Not flagged
On which file system (FS) is the output of a Mapper task stored?

Choose one answer.
	a. HDFS, but it is not replicated.	
	b. HDFS, and it is replicated 3 times.	
	c. Linux FS, but it is not replicated.	
	d. Linux FS, and it is replicated 3 times



15
Marks: 1.00
 Not flagged
Which of the following operations cannot use Reducer as Combiner also?

Choose one answer.
	a. Minimum	
	b. Maximum	
	c. Count	
	d. Average

