# RIST: Robust Internet Speed Test System for End Users
### Introduction
Web-based speed test systems (STSes) such as SpeedTest.net
are extremely popular among Interent users. In this paper,
we conduct to our knowledge a first comprehensive study of
commercial STSes. Using a global-scale testbed consisting
of 108 VMs deployed in 20 countries, we conduct in-depth
characterizations of popular STSes, and find their reported
speed is oftentimes inconsistent and inaccurate.We also carefully
reverse-engineer their speed test logic, whose many
design decisions are found to be ad-hoc and non-adaptive.
Motivated by the above observations, we design and implement
RIST, a new STS solution that innovates web-based
STS through several new techniques including big data analytics,
intellignet sampling, and careful network resource
management. Real-world testing results demonstrate that
RIST significantly outperforms existing STSes in terms of
test accuracy and consistency under the same server pool
size. On the other hand, using only 30 test servers, RIST
achieves similar performance compared to the production
system of SpeedTest that employs about 8,000 test servers
when evaluated using 108 geographically distributed clients.
<br/>
### Client Side of RIST System We Built

|STS|Implementation|
|------|------|
|RIST|[https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-RIST/](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-RIST/)|

### Client Sides of Other Systems We Implemented

|STS|Website|Our Implementation|
|------|------|------|
|Speedof.me|[https://speedof.me](https://speedof.me/)|[https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-Speedof.me/](https://github.com/RISTSystem/RISTsystem.github.io/tree/master/client-Speedof.me/)|
|BandwidthPlace.com|[https://www.bandwidthplace.com](https://www.bandwidthplace.com/)|[https://github.com/RISTSystem/RISTsystem.github.io/tree/master/client-BandwidthPlace](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-BandwidthPlace/)|
|SourceForge SpeedTest|[https://sourceforge.net/speedtest](https://sourceforge.net/speedtest/)|[https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-SourceForge/](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-SourceForge/)|
|Fast.com|[https://fast.com](https://fast.com)|[https://github.com/RISTSystem/RISTsystem.github.io/tree/master/client-Fast.com/](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-Fast.com/)|
|SpeedTest.net|[https://speedtest.net](https://speedtest.net)|[https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-SpeedTest.net/](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-SpeedTest.net/)|
|Xfinity|[http://speedtest.xfinity.com/](http://speedtest.xfinity.com/)|[https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-XFinity/](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/client-XFinity/)|

### Server Side of All the Systems

|STS|Server Implementation|
|------|------|
|All Systems|[https://github.com/RISTSystem/RISTSystem.github.io/tree/master/serverScripts/](https://github.com/RISTSystem/RISTSystem.github.io/tree/master/serverScripts/)|


