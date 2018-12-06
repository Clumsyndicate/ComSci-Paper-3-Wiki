# Weighted Round Robin (WRR)

## WRR Simplied


## How WRR works
* Each packet flow or connection has its own packet queue in a network interface controller. 
* It is the simplest approximation of generalized processor sharing (GPS). 
* GPS serves infinitesimal amounts of data from each nonempty queue
* WRR serves a number of packets for each nonempty queue. The number of packets served is in proportion to the assigned weight and in inverse proportion to the size of the packets.
