# Visualizing Distributed Systems with Statemaps
https://opsummitna18.sched.com/event/HfG2/visualizing-distributed-systems-with-statemaps-bryan-cantrill-joyent

## Presentor 
Bryan Cantrill - @BryanContrill

## Slides
https://www.slideshare.net/bcantrill/visualizing-systems-with-statemaps

## Notes
Out tech stacks are so complex and deep in levels that we can't comprehend or understand the state of it.

Issues at the top of the stack are easy to fix.  (Software vs hardware)
Issues near the bottom of the stack cause greater impact.  

Observability is Debugging.

Pillars of Observability
* Logging
* Metrics
* Tracing

GNU Plot[http://www.gnuplot.info/](http://www.gnuplot.info/)  Need to learn how to use it.

CPU bottlenecks easy to understand.  Bigger issue is when system aren't doing work.  How to interrogate a system what it *should* be doing?

Flame Graph
Heat Map
Statemap

Walks through using statemap visualation.  (Hint it isn't CPU that's the bottle neck)

You have to wire your system to track when the state changes.  Then you have to wire the system to emit the state changes across all the processes.  Then you can start seeing correlations.  With the right visualation the issue becomes human viewable.  Trick is to automate the part for Human Eyes.

Statemap Code [https://github.com/joyent/statemap](https://github.com/joyent/statemap)
