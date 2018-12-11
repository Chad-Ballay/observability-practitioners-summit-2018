# Latency SLOs Done Right
https://opsummitna18.sched.com/event/Hh6J/latency-slos-done-right-fred-moyer-circonus

## Presentor
Fred Moyer @phredmoyer

## Slides
https://schd.ws/hosted_files/opsummitna18/d3/SLOs%20Done%20Right%20-%20OPS%20KubeCon.pdf

##Notes
99th percentile

Everyone should have documented SLOs.

Stop averaging your data.  It hides the extremes and that's where we should focus.

#### SLO Refresher  
Intro video
https://www.youtube.com/watch?v=tEylFyxbDLE

* [SRE book](https://landing.google.com/sre/sre-book/toc/index.html)
* Seeking SRE
* The Site Reliability Workbook

#### A Common Mistake  
Averaging Percentiles
Just unintelligantly grabbing metrics isn't a way to reach the goal.

#### Computing SLOs with log data  
Example around pulling the data out of logs.  Computationally expensive but is extremely accurate.

#### Computing SLOs by counting requests  
Example on load balancer data.  Cheap to calculate.

#### Computing SLOs with histograms  
Example on how you break the data down into bins for a histogram.  

