# Meetup Links:

* http://www.meetup.com/big-o-london/events/229961549/
* https://skillsmatter.com/meetups/7848-functional-reactive-programming-and-cassandra-internals

# FRP == OOP - Hans Jacob Hoeglund (@hanshogl) 

The concept of (Functional) Reactive Programming is enjoying increasing popularity in user interface and front-end development. These techniques emerged out of the functional programming community in the early 2000s and have roots in dataflow languages, denotational semantics and temporal logic.

However FRP as originally described has achieved a reputation of being difficult to implement, while the mainstream approach to interactive applications is still dominated by the OOP/MVC paradigm. The purpose of this talk is to demonstrate that it is possible to use FRP in practical application development, and that the approaches taken in FRP and OOP may not be so different after all.

What does a user interface mean?Is it possible to write interactive applications in a functional style?How do you reconfigure state propagation while the system is running?How is state being stored/propagated in a large-scale FRP system?Are FRP and OOP more related than we think?Applications of FRP (forms, games, visuals, music)

This talk will not require any particular knowledge of FRP, though a passing familarity with functional programming in JavaScript or Haskell may be helpful.

For a recap about the history/taxonomy of FRP you may want to watch Evan Czaplicki's talk here:https://www.youtube.com/watch?v=Agu6jipKfYw

Bio: Developer, musician, professionally curious. Particularly interested in functional programming, data mining, music, visuals and digital art. Software engineer at Beautiful Destinations.



# Deep-dive into user defined functions in Apache Cassandra - Robert Stupp (@snazy)

Since Apache Cassandra 2.2 users are able to run their own, custom functions and aggregates. From an implementation’s point of view, it is straight-forward to just compile and run code on a single machine. But there are a lot of things to consider when executing code in a distributed shared-nothing database. This talk will cover the difficulties of building the UDF implementation covering some internals and will also present current and possibly upcoming features of UDFs and UDAs in Cassandra.

Bio: Robert is working as a Solutions Architect at DataStax and is also a Committer to Apache Cassandra. Before joining DataStax he worked with his customers to architect and build distributed systems using Cassandra and has a long experience in building distributed backend systems mostly using Java as the preferred language of choice.