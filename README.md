# memcached-PoC

memcached Proof of Concept Amplification via spoofed source UDP packets. 

Repo includes source code for PoC and approximately 17,000 AMP hosts within included AMP file. 



Usage: [Destination IP] [port] [reflection file] [threads] [pps limiter, -1 for no limit] [time]




memcached.c - Source code :: Source code based on other popular versions for NTP, DNS, SSDP, etc.


memecache-amp-03-05-2018-rd.list :: List of memcached servers as of 03-05-2018

Compile:
gcc memcached.c -o memecached -pthread


----------------------------------------------------------------------------------------


*Educational and/or testing purposes only. 

*Use of these tools against an unauthorized party may be unethtical, rude, and even illegal in some countries.  

