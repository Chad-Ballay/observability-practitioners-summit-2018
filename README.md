# Observabilty Practioners Summit
https://events.linuxfoundation.org/events/kubecon-cloudnativecon-north-america-2018/observability-practitioners-summit-2018-speaker-guide/

## Schedule
https://opsummitna18.sched.com/

## Dime Store Tour (No specific order just references)
* https://twitter.com/mipsytipsy/status/1044845574128893954
* https://www.honeycomb.io/resources/guide-achieving-observability/
* https://medium.com/@copyconstruct/monitoring-and-observability-8417d1952e1c
* https://thenewstack.io/monitoring-and-observability-whats-the-difference-and-why-does-it-matter/
* https://www.reddit.com/r/dataisbeautiful/
* https://content.pivotal.io/blog/the-3-stages-to-observability-for-modern-apps

## Talking point idea list
http://bit.ly/ops-ideas

## Follow up links
https://twitter.com/tedsuo?lang=en

## Twitter Hashtag
https://twitter.com/hashtag/ObservabilitySummit

## Presentations
* [Who Monitors the Monitors](who_monitors_the_monitors.md)
* [System Comprehension and Root Cause Analysis with Distributed Tracing](distributed_tracing_RCA_system_comprehension.md) 
* [Visualizing Distributed Systems with Statemaps](visualizing_statemaps.md)
* [Logging What Matters: The Pythia Just-in-Time Instrumentation Framework](pythia.md)
* [Myth of the Server's Very Bad Day](myth_bad_day.md)
* [NanoLog: A Nanosecond Scale Logging System](nanolog.md)
* [How to Query Millions of Time Series Efficiently](query_million.md)
* [OpenCensus](opencensus.md)
* [Latency SLOs Done Right](latency_SLO.md)
* [Finding the needle in a Haystack](haystack.md)

## Topic of interest
#### 1. Black box monitoring.  
> I've got oodles and oodles of prehistoric dinosaur apps.  These apps are key due to 
> business logic that isn't well documented.  Wiring up these items would be a high risk /
> low reward.  What do I do?  Just monitor the inputs and outputs of the peremiter of these? 
> Reset my threshold lower for what I need to wire up?

#### 2. Much of the example graphs are pretty as well as succient on what they speaker is trying to convey.  
> Is it that they have perfected the correct graphs for their tech stacks or is it that we 
> are only seeing the curated graph they want to share.  How much signal and how much noise 
> do they have behind the curtain.

#### 3. Single panes.
> Right now we have some data in Meduse, some in Dynatrace, some in Appdynamics, etc, etc...  There is no way to link these.  Do we burn it all down or do we start double tracking some metrics in different systems.  (Cheaper to store or cheaper to ETL?)

## Tools
* [Mermaid](https://github.com/knsv/mermaid) programattically generate flow chars.
* [GNU Plot](http://www.gnuplot.info/) programattically generate graphs.