---
layout: post
title: "Resolving mongo error"
date: 2016-04-26
excerpt: "server crash in mongo"

---


**While working on mongodb, most of the times I came through an error while starting the server by using the command:**
           
           ./mongod


**The error was:**
   
![Unclean shutdown detected](//lailashaikh.github.io/assets/img/MongoError1.PNG)

After researching on internet I came with the reason and solution of it:

**Reason**
111111111Its because you did not the shutdown the server properly, therefore it got crashed

**Solution**
The most easiest way to repair is to look for the lockfile which would have been created resultantly, manually delete it. 
and you are done!!!

![Unclean shutdown detected](//lailashaikh.github.io/assets/img/lockFile.PNG)


