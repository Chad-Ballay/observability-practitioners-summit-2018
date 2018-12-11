# NanoLog: A Nanosecond Scale Logging System
https://opsummitna18.sched.com/event/HfGb/nanolog-a-nanosecond-scale-logging-system-stephen-yang-stanford-university

## Presentor
Stephen Yang - https://platformlab.stanford.edu/student-stephen-yang.php

## Slides
https://schd.ws/hosted_files/opsummitna18/2f/NanoLog-Observability.pdf

## Notes
Order of magnitude faster logging for c++.

https://github.com/PlatformLab/NanoLog

Breaks down to the bare metal level why is logging expensive.

1. Why do we make the log human readable format at runtime?
1. Lots of formatting is known at compile time.
1. Strip out that static info and 129 byte message can be shrunk to 16 byte message.

At compile time log statements get rewritten to pit out only dynamic info.  A data dictionary is written out as well.  Now your app is only sending the dynamic data that it has to at runtime.  If we need to view the data we have to inflate the info using the dicitionary.(His slide has a better representation of this for hello world.)

Unstructured logging is the devil.
