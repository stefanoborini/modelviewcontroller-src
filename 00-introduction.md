---
title: Introduction
nav_order: 0
---
# Introduction

Model-View-Controller (MVC) is probably the most used architectural solution
for User Interface design and web programming; Introduced first in the
70s, MVC has been progressively adapted into a wide range of
subtypes and variations, so much that the plain term "MVC" without additional
qualifications has lost specificity. As a general interpretation, it is a
rather loose guideline for organizing your code when the data and visualization
parts of your application need to interact while staying as loosely coupled as
possible. How this is accomplished in practice depends on the particular MVC
incarnation.

MVC can be seen as an aggregation of more fundamental design patterns
such as Composite, Mediator and Observer/Notifier. The complexity and variation
in style of MVC arises from all the possible uses and variations of these
independent patterns to satisfy the potentially elaborate requirements of a
GUI. 

The objective of this book is to explore the many variations of MVC,
generally arising from the need to decide “who is responsible for what” 
and “who knows about whom” in the interaction between the User and the
application state. MVC variations assign new and old responsibilities in
different ways, connect or organize protagonists, or add intermediate objects
to gain more flexibility and satisfy peculiar use cases.

This book is structured as follows:

- The first chapter will introduce a basic MVC application through implementation code, 
  with the objective of defining the terms of the MVC vocabulary. The chapter will define 
  the fundamentals of components, roles, and communication patterns.

- the second chapter will introduce MVC variations to address specific UI constraints 
  and practical needs, or to improve development efficiency. 

- The third chapter will expand the concept of MVC to hierarchical MVC schemes.

- The fourth chapter will focus on special techniques that emerge from a 
  complex modern GUI.

- The fifth and final chapter will specifically focus on Web MVC and
  its implementations.


## Acknowledgements and motivations

I started writing this book as an accident. Initially, I wanted to write a
series of blog posts to describe Model View Controller and a few related
patterns.  As I gathered more and more information from the net and my personal
experience, I suddenly found out that the amount and structure of what I wrote
was beyond the scope of a blog, hence the decision to re-label it as a book. I
am happy with the decision, because it gave me freedom to add material I would
not have added otherwise.

This works presents and enriches design solutions, best practices, and
experiments made available by countless blog posts and comments. To these 
authors goes my acknowledgement and gratitude.  Being a work in progress,
there's still a lot to be done. Please be patient, but feel free to send me
feedback, pull requests, and take advantage of the material already present. 

This book is released under GFDL license, and free (gratis), mainly for three 
reasons

 - As stated, most of the material here presented was gathered from the net.
   It was my personal effort to organize this knowledge, but I had
   a lower startup barrier.

 - I already [published a book with a commercial publisher](http://www.amazon.com/Computing-Comparative-Microbial-Genomics-Microbiologists/dp/1849967636), 
   and from my experience and math, I think that if I put a book on the 
   web and accept donations I would probably get more money and feedback than
   going through a publisher.

 - This book is part of my portfolio as a professional in software development
   and design, and I am proud to focus on a personal project to increase my
   competences.

The sources of this book are available as a github repository at the following
URL:

https://github.com/stefanoborini/book-modelviewcontroller

I also have a personal website at http://stefanoborini.com where you can find
more information.
