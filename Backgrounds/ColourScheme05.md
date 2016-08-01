09/06/2016 17:56:48	Manoj Pandey	manojpandey1996@gmail.com	Student	"I am currently a rising Computer Science junior, studying in New Delhi (IN). I am also a part of Stanford's Crowd Research Collective (HCI dept at Stanford University) and interning at SquadRun, this summer. 
I am very passionate about learning programming and making others learn too. A keen FOSS enthusiast, I've interests in Data Science, Machine Learning and general concepts in AI, Human Computer Interaction and a strong knack in Design !

Recently, I organized my college's first hackathon: Hack@MSIT. I have been frequently giving a lot of open talks in his college, since I joined the college from first semester, on competitive programming, python programming, general web development, version control systems and open source tools/libraries."	I've used Python a lot, for several years	Speaker at PyDelhi Conference 2016	http://manojpandey.me , http://twitter.com/manojpandey96	Python Data Science	An Introduction to web scraping using Python	Data Science	"In 21st century, the amount of data around us is growing at a tremendous pace. Everybody wants to do something with the available data. The only problem is that the available data is not present in a form directly to use most of the time.

This is why Data Mining and web scraping techniques are helpful to gather huge chunks of data in which further analytics could be done. My talk will focus on ways in which that data could be fetched using Python programming and even a novice programmer can get started. I'll also talk on the ethics of data scraping from the internet and common gotchas and warts (Do's and Dont's) :)

Want to learn how to scrape the web (and / or organized data sets and APIs) for content? This talk will give you the building blocks (and code) to begin your own scraping adventures. We will review basic data scraping, API usage, form submission as well as how to scrape pesky bits like Javascript-usage for DOM manipulation."	Beginner	An introduction into a niche area of Python or a niche library/technology.	30 Mins		I'll use a macbook pro, HDMI-VGA adapter									
11/06/2016 22:16:07	Sergii Khomenko	khomenko@brainscode.com	Data Scientist	"Data scientist at one of the biggest fashion communities, STYLIGHT. Data analysis and visualisation hobbyist, working on problems not only in working time, but in free time for fun and personal data visualisations.

Speaker at different conferences: Berlin Buzzwords 2014, ApacheCon Europe 2014, Puppet Camp London 2015, Munich Developer Camp, Berlin Buzzwords 2015, Tableau Conference on Tour - Berlin 2015, Budapest BI forum 2015, CrunchConf 2015, FOSDEM 2016, PyData Amsterdam 2016

Founder and speaker at Munich Golang User Group, Munich Tableau User Group
Speaker at Munich UseR Group, Munich Search User Group, Munich Quantified Self Meetup, Munich Datageeks, AWS User Group "	I've used Python a lot, for several years	PyData Amsterdam 2016	https://twitter.com/lc0d3r	Python Data Science	From Data Science to Production - deploy, scale, enjoy!	Data Science, Data Engineering and a bit of operations in order to scale it	"Data Science is quite a young field. One of the definitions of Data Scientist: Person who is better at statistics than any software engineer and better at software engineering than any statistician. Hence, it's quite important to talk not only about best practices of feature generation and not overfitting but also about more of software engineering topics.

The talk is based on our experience of Data Science developments at Stylight, an international fashion e-commerce company, that operates in 15 countries worldwide. We refer to our Data Applications written in R and Python, Scala; but  the content is not limited to mentioned languages and applicable others.

The talk consists three main parts. A first part introduces best practices of development. How to structure your development, make deployment easy and reproducible, how to make Continuous Integration and commit triggered deployments. The second part covers production deployment to AWS stack, in particular focusing on concepts of immutable infrastructure and infrastructure as code. The last part about using serverless architecture for data applications. We introduce an example of our outlier detection system, that automatically scales based on such approach."	Beginner	An introduction into a commonly used third-party technology. (good for beginners), An insight into the Python ecosystem. (good for everyone)	45 - 50 Mins											
13/06/2016 11:06:47	David Charles	dave@cobe.io	CTO	Engineer for over 30 years, CTO with huge enthusiasm for science, technology and engineering. Mad about monitoring and what we can do to make it better.	I've used Python a lot, for several years	"This would be the first time I have given a talk at a major conference but I regularly deliver talks at tech meet-ups.  I currently have talk submissions for EP2016 and PyConUK 2016.  As CTO at Cobe.io, a significant part of my job is delivering talks to prospective customers, clients and investors.

Some blog articles I've written:
https://cobe.io/blog/authors/dave-charles/

Tech Tran Network video:
http://www.thettn.tv/headlines/a-brief-history-of-monitoring-david-charles.aspx"	https://cobe.io  @cobecto	Promoting a new project/product/framework	Managing Kubernetes from Python using Kube	Kubernetes containerised infrastructure management using Python	"#Proposal

## Subtitle
Manage Kubernetes with Python using the open source, pythononic API wrapper we developed called Kube

## Duration
30 minutes.

## Description
Kubernetes is the Google Borg inspired control plane for Docker containers that everyone is talking about.  It has a great API but needs a load of HTTP client code and JSON processing to use it from Python.  This talk introduces Kube, a Python wrapper around the Kubernetes API that enables you to manage your Kubernetes cluster in a pythonic way while avoiding any Kubernetes API peculiarities.

## Audience
Programmers and operations folk who are interested in interacting with the Kubernetes API using Python, whether it's to help create a software defined infrastructure, monitor the behaviour of their cluster or just for fun.

## Level
Intermediate

## Prerequisites
A reasonable handle of Python, iterators, context managers etc; understanding of Kubernetes concepts and the need to manage K8s programmatically.

## Objectives
Attendees will learn about the key concepts in getting resource information out of their Kubernetes cluster using Kube; how to create, view, update and destroy resources and how to respond to 'watch' events that signify that a resource's state has changed.

## Detailed Abstract
Docker has had a transformative influence on the way we deploy software and Kubernetes, the Google Borg inspired control plane for Docker-container-hosting-clusters, is gaining similar momentum.  Being able to easily interact with this technology from Python will become an increasingly important capability in many organisations.

In this talk I'll discuss what the motivations behind writing Kube were, provide a quick recap of Kubernetes, it's role and key concepts.  We'll then dive into Kube using the Python interactive interpreter, from getting connected to the API to some simple viewing and label update operations. Finally I'll discuss more advanced resource management activities like Kube's 'watch' API capability, creating resources and the Cluster proxy attribute for when you really need to get to the raw Kubernetes API.

## Outline
1. Setting the scene (3 minutes)
    * We are writing a monitoring SaaS product
    * We assessed the various IaaS and PaaS offerings available,
      chose GCP and GKE.
    * Needed to be able to interact with K8s programmatically for
      provisioning.
    * Also wanted to dog food, monitor our own deployment.

1. Aren't there other Python kubernetes wrappers? (2 minutes)
    * There are, at the time there were less.
    * List some and their strengths.
    * We really needed decent WATCH API support though.

1. Kubernetes concepts quick recap (5 minutes)
    * Refresher of main Kubernetes concepts.

1. Dive into Kube in the Python interactive interpreter (10 minutes)

    * Quickly outline prerequisites, pip-installation and how K8s clients
    should run inside or outside K8s itself, using ``kubectl proxy``:

        $ kubectl proxy
        Starting to serve on localhost:8001

    * The entry point - a Cluster instance:

        >>> import kube
        >>> cluster = kube.Cluster()

        - or...
        >>> cluster = kube.Cluster(url='http://localhost:8080/api')

        - or...
        >>> with kube.Cluster() as cluster:
        ...     cluster.nodes
        ...
        <NodeView>

    * Discuss Views and Items - two important Kube concepts:

        >>> cluster.nodes
        <NodeView>
        >>> cluster.replicasets
        <ReplicaSetView>
        >>> cluster.namespaces
        <NamespaceView>

    * Get a resource item - if you know what it is:

        >>> rs = cluster.replicasets.fetch('tiauth-v1', namespace='default')
        >>> rs
        <ReplicaSetItem tiauth-v1 namespace=default>

    * Good news, the view attributes are iterators!

        >>> [rs for rs in cluster.replicasets]
        [<ReplicaSetItem tiauth-v1 namespace=default>, ...]

    * Lets get one and poke around

        >>> rs = [rs for rs in cluster.replicasets][0]
        >>> rs
        <ReplicaSetItem tiauth-v1 namespace=default>

    * The meta data attribute:

        >>> rs.meta
        <kube._meta.ObjectMeta object at 0x7f6c7f9f4668>
        >>> rs.meta.name
        'auth-v1'
        >>> rs.meta.namespace
        'default'
        >>> rs.meta.labels
        <Labels ""stream=staging,svc=tiauth,portal=all,mylabel=value,v=v1"">

    * Discuss resource versions in K8s

        >>> rs.meta.version
        655487
        >>> print([node.meta.version for node in cluster.nodes])
        ['6434482', '6434483', '6434481']
        >>> # A bit later
        ...
        >>> print([node.meta.version for node in cluster.nodes])
        ['6434485', '6434486', '6434484']

    * Labels - get, set and delete.
        - What are labels? Labels are key/value pairs that are attached to
          resource objects. Identifying attributes that are meaningful
          Can be used to select subsets of objects for operations.

        - So we have a replicaset, look at its labels
        >>> rs.meta.labels
        <Labels ""svc=auth,stream=staging,portal=all,v=v1"">

        - It's a dict-like object
        >>> rs.meta.labels['svc']
        'auth'

        - Which is immutable
        >>> rs.meta.labels['svc'] = 'foobar'
        Traceback (most recent call last):
          File ""<stdin>"", line 1, in <module>
        TypeError: 'ResourceLabels' object does not support item assignment

        - You can add a label like this
        >>> rs.meta.labels.set('mylabel','foo')
        <ReplicaSetItem tiauth-v1 namespace=default>

        - The latest version of the resource item is returned for any update
          operation, this is important!  Look at rs...
        >>> rs.meta.labels
        <Labels svc=tiauth,stream=staging,portal=all,v=v1"">

        - So always get the latest version of a resource...
        >>> rs = rs.meta.labels.set('mylabel','foo2')
        >>> rs.meta.labels
        <Labels ""mylabel=foo2,svc=tiauth,stream=staging,portal=all,v=v1"">

        - Update is same
        >>> rs = rs.meta.labels.set('mylabel','foo3')
        >>> rs.meta.labels
        <Labels ""mylabel=foo3,svc=tiauth,stream=staging,portal=all,v=v1"">

        - Delete label
        >>> rs = rs.meta.labels.delete('mylabel')
        >>> rs.meta.labels
        <Labels ""svc=tiauth,portal=all,v=v1,stream=staging"">

1. More Kube features (5 minutes)
    * Creating and deleting resources
    * Using Kube's Watch API support
    * Resource View Filters
    * The cluster proxy attribute for when you need to get at the actual API

1. Q&A (5 minutes)
"	Intermediate	An introduction into a niche area of Python or a niche library/technology.	30 Mins		Macbook									
13/06/2016 12:20:04	David Charles	dave@cobe.io	CTO	Engineer for over 30 years, CTO with huge enthusiasm for science, technology and engineering. Mad about monitoring and what we can do to make it better.	I've used Python a lot, for several years	"This would be the first time I have given a talk at a major conference but I regularly deliver talks at tech meet-ups.  I currently have talk submissions for EP2016 and PyConUK 2016.  As CTO at Cobe.io, a significant part of my job is delivering talks to prospective customers, clients and investors.

Some blog articles I've written:
https://cobe.io/blog/authors/dave-charles/

Tech Tran Network video:
http://www.thettn.tv/headlines/a-brief-history-of-monitoring-david-charles.aspx"	https://cobe.io @cobecto	Promoting a new project/product/framework	Managing Kubernetes from Python using Kube	Kubernetes containerised infrastructure management using Python	"#Proposal

## Subtitle
Manage Kubernetes with Python using the open source, pythononic API wrapper we developed called Kube.

## Duration
30 minutes.

## Description
Kubernetes is the Google Borg inspired control plane for Docker containers that everyone is talking about.  It has a great API but needs a load of HTTP client code and JSON processing to use it from Python.  This talk introduces Kube, a Python wrapper around the Kubernetes API that enables you to manage your Kubernetes cluster in a pythonic way while avoiding any Kubernetes API peculiarities.

## Audience
Anyone interested in interacting with the Kubernetes API using Python, whether it's to help create a software defined infrastructure, monitor the behaviour of their cluster or just for fun.

## Level
Intermediate

## Prerequisites
A reasonable handle of Python, iterators, context managers etc; understanding of Kubernetes concepts and the need to manage K8s programmatically.

## Objectives
Attendees will learn about the key concepts in getting resource information out of their Kubernetes cluster using Kube; how to create, view, update and destroy resources and how to respond to 'watch' events that signify that a resource's state has changed.

## Detailed Abstract
Docker has had a transformative influence on the way we deploy software and Kubernetes, the Google Borg inspired control plane for Docker-container-hosting-clusters, is gaining similar momentum.  Being able to easily interact with this technology from Python will become an increasingly important capability in many organisations.

In this talk I'll discuss what the motivations behind writing Kube were, provide a quick recap of Kubernetes, it's role and key concepts.  We'll then dive into Kube using the Python interactive interpreter, from getting connected to the API to some simple viewing and label update operations. Finally I'll discuss more advanced resource management activities like Kube's 'watch' API capability, creating resources and the Cluster proxy attribute for when you really need to get to the raw Kubernetes API.

## Outline
1. Setting the scene (3 minutes)
    * We are writing a monitoring SaaS product
    * We assessed the various IaaS and PaaS offerings available,
      chose GCP and GKE.
    * Needed to be able to interact with K8s programmatically for
      provisioning.
    * Also wanted to dog food, monitor our own deployment.

1. Aren't there other Python kubernetes wrappers? (2 minutes)
    * There are, at the time there were less.
    * List some and their strengths.
    * We really needed decent WATCH API support though.

1. Kubernetes concepts quick recap (5 minutes)
    * Refresher of main Kubernetes concepts.

1. Dive into Kube in the Python interactive interpreter (10 minutes)

    * Quickly outline prerequisites, pip-installation and how K8s clients
    should run inside or outside K8s itself, using ``kubectl proxy``:

        $ kubectl proxy
        Starting to serve on localhost:8001

    * The entry point - a Cluster instance:

        >>> import kube
        >>> cluster = kube.Cluster()

        - or...
        >>> cluster = kube.Cluster(url='http://localhost:8080/api')

        - or...
        >>> with kube.Cluster() as cluster:
        ...     cluster.nodes
        ...
        <NodeView>

    * Discuss Views and Items - two important Kube concepts:

        >>> cluster.nodes
        <NodeView>
        >>> cluster.replicasets
        <ReplicaSetView>
        >>> cluster.namespaces
        <NamespaceView>

    * Get a resource item - if you know what it is:

        >>> rs = cluster.replicasets.fetch('tiauth-v1', namespace='default')
        >>> rs
        <ReplicaSetItem tiauth-v1 namespace=default>

    * Good news, the view attributes are iterators!

        >>> [rs for rs in cluster.replicasets]
        [<ReplicaSetItem tiauth-v1 namespace=default>, ...]

    * Lets get one and poke around

        >>> rs = [rs for rs in cluster.replicasets][0]
        >>> rs
        <ReplicaSetItem tiauth-v1 namespace=default>

    * The meta data attribute:

        >>> rs.meta
        <kube._meta.ObjectMeta object at 0x7f6c7f9f4668>
        >>> rs.meta.name
        'auth-v1'
        >>> rs.meta.namespace
        'default'
        >>> rs.meta.labels
        <Labels ""stream=staging,svc=tiauth,portal=all,mylabel=value,v=v1"">

    * Discuss resource versions in K8s

        >>> rs.meta.version
        655487
        >>> print([node.meta.version for node in cluster.nodes])
        ['6434482', '6434483', '6434481']
        >>> # A bit later
        ...
        >>> print([node.meta.version for node in cluster.nodes])
        ['6434485', '6434486', '6434484']

    * Labels - get, set and delete.
        - What are labels? Labels are key/value pairs that are attached to
          resource objects. Identifying attributes that are meaningful
          Can be used to select subsets of objects for operations.

        - So we have a replicaset, look at its labels
        >>> rs.meta.labels
        <Labels ""svc=auth,stream=staging,portal=all,v=v1"">

        - It's a dict-like object
        >>> rs.meta.labels['svc']
        'auth'

        - Which is immutable
        >>> rs.meta.labels['svc'] = 'foobar'
        Traceback (most recent call last):
          File ""<stdin>"", line 1, in <module>
        TypeError: 'ResourceLabels' object does not support item assignment

        - You can add a label like this
        >>> rs.meta.labels.set('mylabel','foo')
        <ReplicaSetItem tiauth-v1 namespace=default>

        - The latest version of the resource item is returned for any update
          operation, this is important!  Look at rs...
        >>> rs.meta.labels
        <Labels svc=tiauth,stream=staging,portal=all,v=v1"">

        - So always get the latest version of a resource...
        >>> rs = rs.meta.labels.set('mylabel','foo2')
        >>> rs.meta.labels
        <Labels ""mylabel=foo2,svc=tiauth,stream=staging,portal=all,v=v1"">

        - Update is same
        >>> rs = rs.meta.labels.set('mylabel','foo3')
        >>> rs.meta.labels
        <Labels ""mylabel=foo3,svc=tiauth,stream=staging,portal=all,v=v1"">

        - Delete label
        >>> rs = rs.meta.labels.delete('mylabel')
        >>> rs.meta.labels
        <Labels ""svc=tiauth,portal=all,v=v1,stream=staging"">

1. More Kube features (5 minutes)
    * Creating and deleting resources
    * Using Kube's Watch API support
    * Resource View Filters
    * The cluster proxy attribute for when you need to get at the actual API

1. Q&A (5 minutes)
"	Intermediate	An introduction into a niche area of Python or a niche library/technology.	30 Mins		Macbook									
16/06/2016 07:35:55	Alessandro Molina	alessandro.molina@gmail.com	Software Engineer at Crunch.IO & CTO at AXANT.it	Python Developer since 2009, TurboGears2 Core Developer, Beaker Maintainer, Contributor to MING MongoDB ODM, ToscaWidgets2 and FormEncode.	I've used Python a lot, for several years	Spoke at more than 16 Python events: http://lanyrd.com/profile/__amol__/past/	http://twitter.com/__amol__	Promoting a new project/product/framework	Kajiki, the fast and validated Template Engine your were looking for	Web Apps	"Being dissatisfied with some of the constraints and complex usage of Genshi, the TurboGears2 team started working on an alternative that could solve Genshi speed issues, complex inheritance system and be backward compatible with genshi templates. This is what lead to the creation of the Kajiki template engine.

The talk will cover: 
- Comparison on the major template engines available in python to showcase what's special in Kajiki (validated, xml based) what was special in Genshi (also lazy evaluated)
- What's a validated template engine and why it's good to have one.
- How Kajiki works, showcase kajiki syntax, it's performances and how to use it in any python project.
- Why Kajiki is fast, code generation applied and how to write a code generation template engine like Kajiki and Jinja2 (showcase a simple 50 lines of code template engine that uses code generation)."	Intermediate	An introduction into a commonly used third-party technology. (good for beginners), A detailed look at a niche library/technology.	45 - 50 Mins											
