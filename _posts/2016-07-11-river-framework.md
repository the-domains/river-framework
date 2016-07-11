---
description: OBJECT-DOCUMENT MAPPER FOR NOSQL DATABASES
dateModified: '2016-07-11T18:41:49.901Z'
datePublished: '2016-07-11T18:43:58.130Z'
title: River Framework
author: []
isBasedOnUrl: >-
  https://the-grid-user-content.s3-us-west-2.amazonaws.com/eece4b09-93b8-400a-8e9b-04105ea4cc24.png
starred: false
sourcePath: _posts/2016-07-11-river-framework.md
inFeed: true
hasPage: false
inNav: false
_type: MediaObject

---
# River Framework
![](https://imgflo.herokuapp.com/graph/vahj1ThiexotieMo/14bd7122c00343fe1918f3d220ebe77b/croprotate.png?cropheight=120&cropwidth=864&degrees=0&input=https%3A%2F%2Fthe-grid-user-content.s3-us-west-2.amazonaws.com%2Feece4b09-93b8-400a-8e9b-04105ea4cc24.png&x=17&y=10)

**OBJECT-DOCUMENT MAPPER FOR NOSQL DATABASES**

**A single interface for different NoSQL databases, written in Java**

Its design is oriented to provide one coding style for different NoSQL databases.  
That's the main goal of this project.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/976c2c9b-eeb7-447f-866b-f0f47a53f4e0.png)

**At development stage**

This project **is growing, learning** from different databases and proposing a common interface  
for all.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/b6e3e0b1-1c5f-48c8-8fd2-f783135625c2.png)

**The current version**

* Supports **IBM Notes** and it's **stable**
* Has **Couchbase Lite** in development
* That's all so far but it's not finished yet. This is just the beginning :-)
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/a9fb13dd-c3f7-4a2c-a92f-74198f6b2a28.png)

**What is next?**

* Support **Couchbase Lite**
* Support **MongoDB**
* Support **Neo4J**
* Support **Couchbase**
* Support **CouchDB**
* Support graphs for document relationship
* Support transactions
* Support a query language (SQL++)

**How does the code look?**

So far, the Java code written with this ODM looks like this:
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/f06107d3-b9e5-4ba6-a600-6f11a64cc7af.png)

**Learn more**

### **Getting Started**

It requires Java JDK 1.6+, IBM Notes 8.5+, and the River Framework. Please, follow the instructions from this [link][0].

### **Demos as Maven Projects**

If you're feeling daring, you can download demos for Eclipse from this [GitHub repo][1].

### **The Project**

If you want to know about current features, next versions, binaries, Maven artifacts, known issues and the changelog, you will find them at its [GitHub repo][2]

### **Documentation**

Guides and javadoc files will be written along September and Octuber of this year.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/5b8be2cb-d4ce-41bb-b3b5-2343274b6e86.jpg)

**About the project**

Over the last decade, I have been working as an IBM Notes workflow application Developer. But after developing similar applications over and over at my job, five years ago, I took the initiative to develop an Application Framework (Workflow + ODM) in LotusScript, the native IBM Notes programming language.

It was really useful and fun to work on!

Anyway, in November 2014, I started to design and write a new one in Java in my spare time, at home. The design is different from the previous one in LotusScript, since it will consider not only IBM Notes, but important NoSQL databases like MongoDB, Neo4J, CouchDB and Couchbase. So, I am incorporating all the features that I would like to have. In this project I'm focusing only in the ODM part. I hope to write the Workflow part in the near future, when the River Framework goals have been achieved.

I expected this work to be useful for you. I'll be looking forward to hear your ideas, comments or questions at [mario.sotil@gmail.com][3]

One big hug and thank you for your interest.

[0]: https://github.com/mariosotil/river-framework-documentation/blob/master/getting-started.md
[1]: https://github.com/mariosotil/river-framework-demo
[2]: https://github.com/mariosotil/river-framework
[3]: mailto:mario.sotil@gmail.com