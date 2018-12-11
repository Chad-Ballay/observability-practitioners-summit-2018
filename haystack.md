# Finding the needle in a Haystack
https://opsummitna18.sched.com/event/HhCP/finding-the-needle-in-a-haystack-shreya-sharma-expedia-inc-jeff-baker-expedia-inc

## Presentor
Shreya Sharma https://twitter.com/shreyas17802199
Jeff Baker https://github.com/jeffbakerexpedia

## Notes
Define what's the haystack and what's the needle you are looking for.

[Haystack](https://expediadotcom.github.io/haystack/)

Single request makes calls to multiple services.  Harder to diagnosis across multiple systems.

Google paper about [Dapper](https://ai.google/research/pubs/pub36356)
Trace ID - ID that gets tagged for a single request that represents atomic action.
Span ID - This is that tags a unique service action in a resource.  Think PID in unix.
Parent Span ID - How the heirachy is defined.  Think paren PID in unix.

After Dapper came out everyone made their own implementation
Twitter - Zipkin
Expedia - Haystack
Uber - Jaeger

Archeticture of HayStack
https://expediadotcom.github.io/haystack/docs/about/architecture.html

