15/07/2016 15:55:41	Michael McKerns	mmckerns@uqfoundation.org	Computational Scientist	Mike has been a research scientist at Caltech since 2002, and is co-founder of the UQ Foundation, a non-profit for the advancement of predictive science. Mike is the author several python packages, including mystic (highly-constrained non-convex optimization and uncertainty quantification), pathos (parallel graph management and execution in heterogeneous computing), and dill (serialize all of python). His software is the backbone of several research projects on risk analysis and predictive science, and is leveraged by packages in machine learning and parallel computing. He has over fifteen years of teaching experience, has given hundreds of conference and workshop presentations, and has taught over fifty week-long Python training classes in the past four years.	I've used Python a lot, for several years	I have given hundreds of conference and workshop presentations. At PyConIE, I have presented at least one talk or workshop each of the past two years.	https://github.com/mmckerns	Parallel computing in Python	Scalable Hierarchical Parallel Computing	efficiency, parallel computing	"This tutorial is targeted at the intermediate-to-advanced Python user who wants to extend Python into hierarchical parallel computing. The tutorial will provide hands-on examples and essential performance tips every developer should know for writing effective parallel Python. The result will be a clear sense of possibilities and best practices using Python in simple parallel computing environments.

Many of the examples you often find on parallel Python focus on the mechanics of getting the parallel infrastructure working with your code, and not on actually building good portable parallel Python. This tutorial is intended to be a broad introduction to writing high-performance parallel Python that is well suited to both the beginner and the veteran developer. Parallel efficiency starts with the speed of the target code itself, so we will start with how to evolve code from for-loops to Python looping constructs and vector programming. We will also discuss tools and techniques to optimize your code for speed and memory performance.

The tutorial will overview working with the common parallel communication technologies (threading and multiprocessing) and introduce the use of parallel programming models such as blocking and non-blocking pipes, asynchronous and iterative conditional maps, and map-reduce. We will discuss strategies for extending parallel workflow to utilize hierarchical and heterogeneous computing, distributed parallel computing, and job schedulers.

At the end of the tutorial, participants should be able to write simple parallel Python scripts, make use of effective parallel programming techniques, and have a framework in place to leverage the power of Python in parallel computing environments.

OUTLINE:
~~ parallel programming ~~ 
* vector programming vs looping constructs
* timing, profiling, and code optimization
* coding for speed and portability
* scalability with asynchronous computing
* Exercise(s)
~~ multiprocessing and threads ~~ 
* point to point communication
* blocking and non-blocking (iterative, unordered, and asynchronous) communication
* task pools and collective communication
* issues: serialization, working in __main__
* Exercise(s)
~~ distributed parallel computing ~~
* point to point communication
* blocking and non-blocking (iterative, unordered, and asynchronous) communication
* task pools and collective communication
* issues: serialization and heterogeneity
* issues: failure detection and reporting
* Exercise(s)
~~ hierarchical workflow ~~
* workflow management
* server-client computing
* cluster schedulers
* ssh-tunneling
* Exercise(s)

PREREQUISITES:
This tutorial will assume attendees have basic knowledge of python and numpy. The tutorial will require python, numpy, and pathos to be installed. All packages can be installed under Anaconda or Canopy, with setuptools or pip, and may also be installed with Linux or Macintosh package managers.

PRELIMINARY MATERIALS and DOCUMENTATION:
An earlier version of the tutorial is available at: http://www.pyvideo.org/video/1345/efficient-parallel-python-for-high-performance-co while a preliminary version of the tutorial is at https://github.com/mmckerns/tuthpc."	Intermediate	An introduction into a niche area of Python or a niche library/technology.	120 Mins	No	laptop, projector									
15/07/2016 16:02:10	Michael McKerns	mmckerns@uqfoundation.org	Computational Scientist	Mike has been a research scientist at Caltech since 2002, and is co-founder of the UQ Foundation, a non-profit for the advancement of predictive science. Mike is the author several python packages, including mystic (highly-constrained non-convex optimization and uncertainty quantification), pathos (parallel graph management and execution in heterogeneous computing), and dill (serialize all of python). His software is the backbone of several research projects on risk analysis and predictive science, and is leveraged by packages in machine learning and parallel computing. He has over fifteen years of teaching experience, has given hundreds of conference and workshop presentations, and has taught over fifty week-long Python training classes in the past four years.	I've used Python a lot, for several years	I have given hundreds of conference and workshop presentations. At PyConIE, I have presented at least one talk or workshop each of the past two years.	https://github.com/mmckerns	Parallel computing in Python	Shared-Memory High-Performance Parallel Computing 	Parallel computing in Python	"This tutorial is targeted at the intermediate-to-advanced Python user who wants to extend Python into high-performance computing. The tutorial will provide hands-on examples and essential performance tips every developer should know for writing effective parallel Python. The result will be a clear sense of possibilities and best practices using Python in HPC environments.

Many of the examples you often find on parallel Python focus on the mechanics of getting the parallel infrastructure working with your code, and not on actually building good portable parallel Python. This tutorial is intended to be a broad introduction to writing high-performance parallel Python that is well suited to both the beginner and the veteran developer. Parallel efficiency starts with the speed of the target code itself, so we discuss tools and techniques to optimize your code for speed and memory performance. We will then compare code in for-loops versus Python looping constructs and vector programming.

The tutorial will overview working with the common parallel communication technologies (threading, multiprocessing, MPI) and introduce the use of parallel programming models such as blocking and non-blocking pipes, and locks and asynchronous communication. We will discuss strategies for extending parallel workflow to utilize common communication patterns for shared memory constructs. We then return our focus to the speeding up our target code by leveraging parallelism within compiled code using cython.

At the end of the tutorial, participants should be able to write simple parallel Python scripts, make use of parallel programming techniques, and have a framework in place to leverage the power of Python in high-performance computing.

OUTLINE:
~~ parallel programming ~~ 
* vector programming vs looping constructs
* timing, profiling, and code optimization
* coding for speed and portability
* skirting the GIL (ctypes and shared memory)
* Exercise(s)
~~ multiprocessing and threading ~~ 
* pipes and queues, locks and synchronization
* blocking and non-blocking communication
* shared memory and shared objects
* issues: thread-locking and collisions
* Exercise(s)
~~ mpi4py ~~ 
* pipes and queues, locks and synchronization
* blocking and non-blocking communication
* shared memory and shared objects
* issues: MPI and python imports, resource allocation 
* Exercise(s)
~~ cython~~ 
* building extension modules 
* adding type declarations
* leveraging external functions, structures, and classes
* accessing native parallelism (numpy and nogil)
* Exercise(s)

PREREQUISITES:
This tutorial will assume attendees have basic knowledge of python and numpy. The tutorial will require python, numpy, mpi4py, and cython to be installed. All packages can be installed under Anaconda or Canopy, with setuptools or pip, and may also be installed with Linux or Macintosh package managers.

PRELIMINARY MATERIALS and DOCUMENTATION:
An earlier version of the tutorial is available at: http://www.pyvideo.org/video/1345/efficient-parallel-python-for-high-performance-co while a preliminary version of the tutorial is at https://github.com/mmckerns/tuthpc."	Advanced	An introduction into a niche area of Python or a niche library/technology.	120 Mins	No	laptop, projector									
15/07/2016 16:12:45	davide poggiali	poggiali.davide@gmail.com	PhD student	"Last year PhD student in Neuroscience in Padua, Italy.  
I got my Degree in Mathematics in 2012 with thesis on medical image reconstruction, then I decided to study Neuroimaging, with focus on MRI and PET/MRI of patients with Multiple Sclerosis, Alzheimer's  Disease, Brain Tumor and other neurological disorders.
As an enthusiastic python user, I write my own code any time it's possible to have complete control over the computation of neurological biomarkes."	I've used Python a lot, just recently	I never did	http://dpoggiali.altervista.org/	Python Data Science	Data Analysis in MRI and PET/MRI Neuroimaging	Neuroimaging in python	Since the introduction of new hybrid systems as PET/MRI and due to the constant increase of MRI sequences, neuroimaging datasets are growing constantly. Nowadays a Neurological research study has to be considered a big data problem. In this talk I will introduce from scratch some of the most common algorithms for computing neuroimaging biomarkers and give some ideas about efficiency increasing. Some examples in python will be given.	Intermediate	An introduction into a niche area of Python or a niche library/technology.	30 Mins	In the morning it would be better	my Macbook									
15/07/2016 16:23:33	Michael McKerns	mmckerns@uqfoundation.org	Computational Scientist	Mike has been a research scientist at Caltech since 2002, and is co-founder of the UQ Foundation, a non-profit for the advancement of predictive science. Mike is the author several python packages, including mystic (highly-constrained non-convex optimization and uncertainty quantification), pathos (parallel graph management and execution in heterogeneous computing), and dill (serialize all of python). His software is the backbone of several research projects on risk analysis and predictive science, and is leveraged by packages in machine learning and parallel computing. He has over fifteen years of teaching experience, has given hundreds of conference and workshop presentations, and has taught over fifty week-long Python training classes in the past four years.	I've used Python a lot, for several years	I have given hundreds of conference and workshop presentations. At PyConIE, I have presented at least one talk or workshop each of the past two years.	https://github.com/mmckerns	Python Data Science	New Tools for Constrained Nonlinear Optimizations and Kernel Transformations	numerical optimization, data science, and parallel computing	"Highly-constrained, large-dimensional, and nonlinear optimizations are found at the root of most of today’s forefront problems in risk, operations research, materials design, and other predictive sciences. This tutorial will introduce modern tools for solving optimization problems -- beginning with traditional methods, and extending to solving high-dimensional non-convex optimization problems with highly nonlinear constraints. We will start by introducing the cost function, and it’s use in local and global optimization. We will then address how to monitor and diagnose your optimization convergence and results, tune your optimizer, and utilize compound termination conditions. This tutorial will discuss building and applying box constraints, penalty functions, and symbolic constraints. We will then demonstrate methods to efficiently reduce search space through the use of robust optimization constraints.  Real-world inverse problems can be expensive, thus we will show how to enable your optimization to seamlessly leverage parallel computing. This tutorial will cover using asynchronous computing for results caching and archiving, dynamic real-time optimization, and dimensional reduction. Next we will discuss new hyper-optimization methods that leverage parallel computing to perform fast global optimizations and n-dimensional global searches. We will then learn how to apply statistical and probabilistic constraints, and put that knowledge into use in solving applications of global optimization in statistical and data sciences.

The audience need not be an expert in optimization, but should have interest in solving hard real-world optimization problems.  We will begin with a walk through some introductory optimizations, learning how to build confidence in understanding your results. By the end of the tutorial, participants will have working knowledge of how to use modern constrained optimization tools, how to enable their solvers to leverage high-performance parallel computing, and how to utilize legacy data and surrogate models in statistical and predictive modeling.

OUTLINE:
~~ introduction to optimization ~~
* the cost function
* local and global optimization
* monitoring and diagnosing convergence and optimization results
* solver tuning and compound termination conditions
* Exercise(s)
~~ penalty functions and constraints ~~ 
* box constraints
* applying penalty functions
* reducing search space with constraints
* applying symbolic constraints
* Exercise(s)
~~ solver efficiency ~~
* leveraging parallel and asynchronous computing
* ensemble search
* surrogate construction
* dimensional reduction
* Exercise(s)
~~ statistical and probabilistic constraints~~
* sampling statistics
* sampling distributions
* statistical constraints
* information constraints from legacy data
* optimization with unknown probability distributions
* Exercise(s)
~~ design under uncertainty ~~
* the cost metric
* sensitivity analysis 
* experimental design
* calculating likelihood and probability
* Exercise(s)

PREREQUISITES:
This tutorial will assume attendees have basic knowledge of python and numpy, and is intended for scientific developers who are interested in utilizing optimization to solve real-world problems in statistical and data sciences. The tutorial will require python, numpy, and mystic to be installed, and optionally installs of matplotlib, scipy, and pathos. All packages can be installed under Anaconda or Canopy, or with setuptools or pip.

PRELIMINARY MATERIALS and DOCUMENTATION:
Sample exercises are available at https://github.com/uqfoundation/mystic and https://github.com/uqfoundation/pathos/examples2. A preliminary version of the tutorial is available at: https://github.com/mmckerns/tutmom."	Intermediate	An introduction into a niche area of Python or a niche library/technology.	120 Mins	No	laptop, projector									
15/07/2016 21:46:02	Niall O'Connor	zechs.marquie@gmail.com	Software Developer (team lead) Bank of America	A familiar face at Irish tech events. Has previously given talks and workshops on TDD, BDD, Linked Data and python in general.	I've used Python a lot, for several years	Yep. See bio.	@nialloc1978	General Python or Python based Frameworks	Introduction to Python, Spark & Hadoop	Introducing participants to the use of python, spark and hadoop for large datasets	"Using python to interact with the spark data engine on the hadoop platform.
 
·         What is hadoop.

·         What is spark.

·         What is pyspark.

·         Using pyspark to work with data on HDFS

·         Using pyspark to parallelize computation on a hadoop cluster.

·         Limitations of spark and hadoop.

 
A workshop for python programmers to get familiar with hadoop and spark.  It is assumed you can code and run a python module, that you understand basic data structures.  It is assumed you have hadoop and spark installed."	Intermediate	An introduction into a niche area of Python or a niche library/technology.	4 hours/half day	Saturday Afternoon	Laptop									
17/07/2016 17:54:32	Leonid Vasilyev	vsleonid@gmail.com	SRE	Joined Dropbox as SRE in Dublin a year ago. Working on Dropbox's physical data center and AWS EC2 infrastructure automation. Before worked in AWS for 2.5 years. I'm programming in Python for 8 years now.	I've used Python a lot, for several years	No	https://twitter.com/chingun	General Python or Python based Frameworks	Building Hermetic Python Packages with Bazel @ Dropbox	Shipping Python code in production	"Historically, Dropbox used Encap as a packaging system to deploy custom Python packages to production servers. This approach has a number of issues and limitations. Early this year we started transition to custom build system based on Google's recently open sourced project – Bazel. I'd like to share our experience of building ecosystem around  Bazel and workflow we use to build and package our code that is scalable and robust. 

Draft of Agenda:
Background: [~10 mins]
- Encap intro
- Workflow with encap
- Issues with encap
Migration to Bazel:[~20 mins]
- Bazel intro
- Hermetic packages
- Managing Pypi/C dependencies
- Workflow with Bazel
- Wins/Issues with Bazel
- Future work"	Intermediate	An introduction into a commonly used third-party technology. (good for beginners), A detailed look at a niche library/technology., An insight into the Python ecosystem. (good for everyone)	30 Mins		MacBook Pro/Keynote slides + iterm2  demo									
17/07/2016 21:57:55	Ronan Hayes	ronan.hayes@teamaol.com	Automation Engineer	Automation Engineer on the AOL Adtech team	I've used Python on-and-off over several years	No	www.linkedin.com/in/batmansdad	General Python or Python based Frameworks	Lazy Automation : Get your code to do your job	Automation with sprinkles of introspection and bigdata	"“I choose a lazy person to do a hard job. Because a lazy person will find an easy way to do it.”

In the AOL Adtech team we have some creative/easy ways to test our systems. This workshop will showcase two key points:

1. How to get your code to generate your unit and integration tests
2. How to get your customers to generate even more tests

The workshop will go into detail on:

1. Modelling your interfaces and data
2. Using introspection and JINJA2 to generate tests
3 . Using the Elastic stack to monitor and collect data
4. Leveraging data to generate more test cases.

The workshop will assume a beginner level of python and introduce each library and technology . The net result is a very simple and easy step by step guide to getting your code to do your job."	Beginner	An introduction into some commonly used parts of Python. (good for beginners), An introduction into a commonly used third-party technology. (good for beginners), An introduction into a niche area of Python or a niche library/technology., A detailed look at a niche library/technology.	45 - 50 Mins	No	Laptop, projector, websites									
18/07/2016 14:01:47	Mick Cooney	mickcooney@gmail.com	Quantitative Analysis	Same as my other submission (which I forgot to save)	I've used Python on-and-off over several years	I speak a lot at Dublin R, and have given presentations at a bunch of other meetups, but never for Python Ireland.	@kaybenleroll	General Data Science	Introduction to Survival Analysis	data science	"Survival analysis, and time to event modelling in general, is a well established field in areas such as medical statistics and a few other places but has never really made the jump over to machine learning.

In this talk I will talk about the basic of survival analysis and show how to implement various survival models in both R and Python. I will discuss some of the pitfalls and gotchas, and will show its use in areas such as churn analysis."	Intermediate	An introduction into a niche area of Python or a niche library/technology., A detailed look at a niche library/technology.	45 - 50 Mins	I'm good for any configuration / duration or timeslot that works	Laptop									
18/07/2016 23:44:35	Humberto Corona	hcorona@gmail.com	Data Scienctist	I am a Data Scientist at Zalando, previously Insight UCD. My research interests are recommender systems, and machine learning applied to music. 	I've used Python a lot, just recently	no	http://hcorona.github.io , https://www.linkedin.com/in/humberto-corona-86394328	General Data Science	sharing knowledge in the python ecosystem 	data science, jupyter, github, research	Data Scientists (or researchers) often do many early-stage prototyping and run many experiments before finding the optimal solution for the problem they are trying to solve. However, sometimes, a lot of the knowledge gained in the process stays with the person. In this proposed talk, I would like to introduce how to produce, share and ensure the reproducibility of experiments using jupyter notebooks and github. This is a series of lessons Iearned while being a research student (where open-sourcing the code and data used to generate papers is very important) and more recently, working in a new team in Zalando, where we have experimented with different ways to share and review the data science tasks, as well as the knowledge generated from those tasks. 	Beginner	An insight into the Python ecosystem. (good for everyone), An insight into our community. (good for everyone)	between 15 and 30 mins	no	laptop + internet 									
