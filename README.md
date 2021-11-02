# sping
Simple network testing tool

Goals:
1. The tool should be cross-platform (at least Linux, Windows, and Mac, Android is optional)
2. The tool should be super fast (that is what the name means - s[uper]ping
3. The tool should consist of a library and command-line utility.
4. The tool shouldn't grab all the CPU/RAM resources, or print at least a warning
5. Doxygen should be used to create a documentation


Architecture:

Library    <---->    Command line tool



Features:
1. TCP,UPD,ICMP packets sending with a specified delay
2. UDP attack
3. TCP SYN attack
5. IP source address spoofing
6. Port scanning
7. Setting type of service field
8. Average ACK receiving time for TCP
9. Average Latency, Standard Deviation, and Percentage of Loss for UDP/ICMP
