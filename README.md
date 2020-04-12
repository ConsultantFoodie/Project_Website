# Analysis of CPU Usage and Performance Scaling for Container Networks
With containers being the chosen way of deplloying applications over various different environments, it will be useful to determine if the process of container networking is scalable, and if so, to what extent.

## Aim:
The aim of this project is to analyse how the performance of a network scales in three scenarios using three cases for each of them.
The three scenarios will be running applications on an end-host without any overlay networks, running applications on a virtual network, and running applications in containers on the overlay network. The cases to be tested are examining a single flow between end-hosts, examining multiple flows, and examining transfer of small data packets.

## Experimental Tasks:
I will be recreating the experiment done by **Lei, Suo, Lu, and Rao** in their paper [**Tackling Parallelization Challenges of Kernel Network Stack for Container Overlay Networks**](https://www.usenix.org/system/files/hotcloud19-paper-lei.pdf)
This will be done to analyse whether the same bottlenecks are observed and confirm the causes of the bottlenecks in order to come up with ways to improve modern systems in order to tackle these challenges.
If the same outcomes are observed, we can start working on improving the existing issues, otherwise it will be useful to find out whether these challenges are subject to some conditions and how to avoid them.
