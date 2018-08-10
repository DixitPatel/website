+++
banner = ""
categories = ['distributed-systems','golang']
date = "2018-07-06"
description = ""
images = []
menu = ""
tags = []
title = "Distributed Fault-Tolerant Stack"
+++
It's very exciting to read about all the variety and complexity of today's software requirements and the abundant opportunity available to innovate across academic disciplines through good software. Programming languages are the bread and butter of the software world. Exploring a bit, I learned a few things about Go programming language and implemented a <a href="https://github.com/DixitPatel/Distributed_Stack">Distributed Fault-tolerant stack. </a> <br><br>
Most modern large-scale applications are distributed in nature and are designed around high-availability. A fundamental principle underlying such systems is that failure is inevitable. Having fault-tolerance built-in, essentially helps to mitigate the effects of such failures, which can be very critical depending on nature of the application. In the event of a failure of one or more underlying computer systems, we need a way to have the entire state of the application reach a consistent state before it can continue to operate.
The faster the application is able to recover from such failures, the lesser the chance of affecting the end-user, which often becomes a deciding factor as far as usability is concerned. 
<br><br>
I am using a distributed consensus algorithm called Raft that provides such a mechanism. The algorithm is easier to understand as compared to it's ancient counter-part Paxos.
The example I implement is adapted from <a href="https://github.com/coreos/etcd">Etcd</a>, a popular distributed key-value store that also uses Raft algorithm to implement fault-tolerance.
