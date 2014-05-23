Meetup Links:
* http://www.meetup.com/big-o-london/events/180209022/ 
* https://skillsmatter.com/meetups/6385-lost-in-space-binary-search-trees-beyond-1d-and-crdts

Blurb:

* Lost in Space: binary search trees beyond dimension one - Jeff Abrahamson (Google) 

BST's are a great general-purpose tool for locating points on the line. In higher dimensions, we have to do more work. In this talk,we'll look at a handful of algorithms that let us search for points,ranges of points, and nearest points, all in higher dimensions -- just like with BST's. We'll also touch on some surprising applications of these algorithms and even have a quick chat about the Curse of Dimensionality. The talk keeps evolving, but it's a safe bet that we'll at least discuss range trees, KD-trees, and higher dimensional Voronoi diagrams. 
Bio: Jeff Abrahamson collects advanced degrees while roaming the globe doing computer science and writing software. He currently hangs his (virtual) hat at Google London, where he is called site reliability engineer.


* CRDTs for Fun and Eventual Profit - Noel Welsh (Myna, @noelwelsh)

CRDTs are a way of handling replicated or distributed data. What is distributed data? It just means data that is copied to many machines. As soon as we have such a distributed system we have to think about what happens when our data changes. We can decide that all machines will be aware of all changes. That is, we can maintain consistency. This is nice because it means we never deal with out-of-date data, but it requires every change to be sent to every machine before it is considered complete. If a machine (or the network) goes down we must refuse updates because we can’t ensure everyone has seen every update, and thus we can’t maintain consistency . 

We can instead prefer availability, meaning we’ll just soldier on if machines go down, but this does mean we will end up with the same piece of data having different values on different machines. In other words our data will become inconsistent. CRDTs allow us to recover a particular type of consistency, called eventual consistency, without a great deal of work. With CRDTs we will be able to merge different copies of our data together without issue, and if we merge all copies together we are guaranteed to arrive at the same value everywhere.
In this talk I'll cover the basics of CRDTs and discuss some applications.

Bio: Noel is a founder of Myna and partner at Underscore. Noel has over fifteen years experience in software architecture and development, and over a decade in machine learning and data mining. Examples of the projects he's been involved with include one of the first commercial products to apply machine learning to the Internet (eventually acquired by Omniture), a BAFTA award winning website, and a custom CMS used daily by thousands of students. 

Noel is an active writer, presenter, and open source contributor. Noel has a PhD in machine learning from the University of Birmingham. 