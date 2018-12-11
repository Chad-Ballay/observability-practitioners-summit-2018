# Myth of the Server's Very Bad Day
https://opsummitna18.sched.com/event/HfGP/diamond-sponsor-talk-myth-of-the-servers-very-bad-day-daniela-miao-lightstep

## Presenter
Daniela Miao - https://github.com/danielamiao

## Notes
Personification of servers.  Bad day to describe server behavior that has no known cause.

RCA and actually understanding what it is your system is doing.

Visualation magic.  Seriously, I'm going to need to learn how to display data.

Server cluster starts having performance issues.
* Throw more hardware.
* Rollback code changes when issue presented.
* Optimize cache.

Historical example
1. List out critical path.  
1. Database call shows up.  
1. CPU shows being bound.  
1. Turns out they were tearing down the whole connection for each query.  (TLS handshake was the cpu hog).
1. Code changes on the system was further researched and ruled out.
1. Started to look out at the client side.
1. Turns out a bad client was able to reveal a bad design due to how it was failing.

Actually track down what you think is the cause and have data to show what is the issue.  Don't assume you know what is the cause since it'll waste time.  Also address issues when you notice people personifying tempermental processes.  Human hack that tells us we have a system issue work investigating.
