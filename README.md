# database-observability-toolkit

This Github project should help you to make your database service observable for you and for your users.

This page is currently in WIP (Work In Progress)

## The USE method

The USE method was intriduced by Brendan Gregg.

Utilization:
Saturation:
Errors:

Great example when applied to resources like host CPU & Memory, or caches.

## The RED method
The RED method was introduced byt Tom Wilkie.
It's a subset of “The Four Golden Signals” that’s focused on micro-service architectures and which includes these metrics:

    Rate: the number of requests our service is serving per second;
    Error: the number of failed requests per second;
    Duration: the amount of time it takes to process a request;
    
## The CASE method
The CASE method was introduced by Cory Watson.

Context-heavy:
Actionable: 
Symptom based:
Evaluated:

## The seven golden signals

The seven golden signals was introduced by Baron Schwartz.

CELT + USE method aka the seven golden signals

    Concurrency: number of simultaneous requests
    Error rate
    Latency: reponsonse time
    Throughput: query per seconds (QPS)

## TODO

- Complete this page with links.
- Complete the log and metrics part
- Add screenshots
