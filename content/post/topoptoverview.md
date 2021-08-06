---
title: "Topology optimization software overview"
date: 2021-08-06T07:52:30+02:00
draft: false
---

It looks like every engineering software package can do Topology optimization these days. Here is my experience...

..* Every self respecting engineer software package has a Topology optimization module these days, but don't be surprised if find out that they all give you different results for the same problem. Why? Because these software tools are just being developed and there are a lot of parameters to tune which influences the result. So basically, there is no standard jet.

..* There are different 'approaches' to Topology optimization. The density based topology optimization method is mostly used and easiest for beginners.

..* There are two paths you can take: 1) use off-the-shelf (commercial) engineering software or 2) use open-source software code. Let's look at which path is best for you...

### Commercial vs. open-source software
If you want to start with Topology optimization, let me give you an idea which choice you have to make first. The commercial engineering software packages all have Topology optimization capability. Off-course these cost money, but maybe you can get a free trail or pay per use. From experience I can tell that it takes a while to understand it well enough to get reasonable results, so give yourself some time. To good thing is that if you can't do any programming, for the commercial software you don't need to and than this is probably your best choice. On the other hand, not all the newest features are available in the commercial packages, which are on the open-source codes.

So if you know a bit of programming, one of the open-source codes is probably something for you. These codes are mostly developed by academics and are therefore usually having features which do not exist in commercial software. And it is for free. 

### Commercial software: standard names and next generation
Standard names: Abaqus, Ansys, NX, Solidworks, Inventor or fusion360

These are 'traditional' CAD programs in the sense that the represent the geometry of the object as NURBS-Based solid representation. This is very was very helpful, but the geometries are getting more and more organic and sophisticated. Therefore, a surface representation to represent the geometry of the object is increasingly used. These are what I call the next generation software tools: nTopology and Parameters. These use Implicit Modeling which is gives speed advantages and increase flexibility.

### Open-source TO codes an overview
Looking at the open-source codes we can subdivide per programming language or capabilities.

#### Matlab (which is not open-source)

#### Python

#### C++/PETSc

#### Julia

### Latest trends in TO

..* Larger

..* AI