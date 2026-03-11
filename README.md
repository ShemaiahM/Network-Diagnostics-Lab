# Network-Diagnostics-Lab

**Author:** Shemaiah M
**Date:** March 2026

## Objective: Demonstrate basic network diagnostic skills using the Windows Command Line (CLI) to verify local IP configuration and external connectivity.

## Steps Performed

##1. Local IP discovery.
**Command:** 'ipconfig' then press enter
**Observation:** Used to identify the **IPv4 Address** under the **Wireless LAN adapter Wi-Fi** section.
**Outcome:** Successfully identified my machine's unique identifier on the local network.

##2. Connectivity Tesing(ICMP)
**Command:** 'ping google.com'
**Observation:** This sent 4 packets, to Google's servers, to simply test Google's servers & test communication latency and packet loss.
**Outcome:** Received 4 successful replies "Reply from". This confirms that my **Network Interface Card (NIC)**, router, and ISP are successfully communicating with the wider internet.

##3. The Route Tracing
**Command:** `tracert google.com`
**Observation:** Tracked the path of the data packets (the "hops") across the internet.
**Outcome:** The data took **13 hops** to reach the destination server. This visualization helps identify where potential delays or bottlenecks occur in a network path. The data took 13 hops(passing through to 13 different routers) to connect to Google's destinations server. 


## My Skills Demonstrated
* Command Line Interface (CLI) usage (windows)
* Network Diagnostics & Troubleshooting
* Understanding of ICMP (Internet Control Message Protocol)
* Knowledge of Hops and Routing paths

