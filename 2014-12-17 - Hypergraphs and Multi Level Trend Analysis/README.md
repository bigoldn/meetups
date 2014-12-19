Meetup Links
- https://www.skillsmatter.com/meetups/6850-the-london-big-o-december-meetup
- http://www.meetup.com/big-o-london/events/218973469/

* Hypergraphs - Rajeshwar Bisht 
A hypergraph is a generalisation of a graph in which an edge can connect any number of vertices. This talk will describe hypergraphs and hypergraph partitioning along with its applications.

Bio: Rajeshwar Singh Bisht is software engineer at iDirect, where he works on database optimization and as a C++ developer.

* TrendCalculus - creating a proper data science method for studying trends that doesn¿t rely on eyeballs.

TrendCalculus is an ongoing R&D project to build a workable data science library for advanced time series analysis using MTA (Multi-Scale Trend Analysis). MTA (http://arxiv.org/pdf/physics/0305013.pdf) was developed by Ilya Zaliapin, Andrei Gabrielov, and Vladimir Keilis-Borok and published in 2003. 

Their methods show great promise - but have languished. This is due to the high compute cost of creating the needed underlying data structures using PLA (piecewise linear approximation) which is too slow to be effective as they envisioned it.

TrendCalculus delivers an alternative approach to PLA: it is a fast, multi-scale, Trend Reversal Detection method that works on a single pass of streamed data, in O(n) time, which should enable to the MTA analysis methods to become workable in practice. It is implemented in LuaJit.

Bio: Andrew Morgan is the CEO of ByteSumo, a data science consultancy in London. 
He is a long-time Data Scientist and Enterprise Data Architect who seeks better methods for understanding population dynamics.
