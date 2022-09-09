# visualize data from a system activity report (SAR) file

SAR collects system metrics useful for long-duration profiling in linux.
Overview: https://www.thegeekstuff.com/2011/03/sar-examples/

Sources of bottlenecks are
* CPU 
  * count
  * speed per core
* memory
  * capacity
  * speed
* storage
  * capacity
  * speed
* network
  * capacity
  * latency

To use SAR to identify bottlenecks, 
* is any metric approaching full utilization (e.g., 100% of capacity)?

