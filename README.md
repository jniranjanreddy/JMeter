# JMeter

## Performance Test Application
## Build using java
## Recording 
```
root@swarm01:/apache-jmeter-5.5/extras# jmeter -n -t Test.jmx -l 'report-1.csv'
Creating summariser <summary>
Created the tree successfully using Test.jmx
Starting standalone test @ 2022 Nov 18 17:34:47 IST (1668773087396)
Waiting for possible Shutdown/StopTestNow/HeapDump/ThreadDump message on port 4445
Warning: Nashorn engine is planned to be removed from a future JDK release
summary =     30 in 00:00:03 =    9.8/s Avg:   238 Min:   106 Max:   349 Err:     2 (6.67%)
Tidying up ...    @ 2022 Nov 18 17:34:51 IST (1668773091288)
... end of run
root@swarm01:/apache-jmeter-5.5/extras#


How to export Display.
export DISPLAY=:0 # This to be tested.


```
