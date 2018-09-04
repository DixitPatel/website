+++
banner = ""
categories = ['distributed-systems','golang']
date = "2018-07-06"
description = ""
images = []
menu = ""
tags = []
title = "Distributed Stack"
+++
I ocassionally find myself taking some time out and diving into some of the content from this very interesting collection of fairly in-depth and well-written articles, <a href="https://breakingsmart.com/en/season-1/">Software is eating the world </a>, exploring, in some sense, the interplay between *modern* technology and human life post tech hysteria of the early 2000's. 
<br><br>
Here's my favorite from the intro :
    <blockquote>
        *People change, then forget that they changed, and act as though they always behaved a certain way and could never change again. Because of this, unexpected changes in human behavior are often dismissed as regressive rather than as potentially intelligent adaptations*
    </blockquote>

It's very exciting to read about the variety and complexity of today's software requirements and the abundant opportunity available to innovate across academic disciplines through quality software realizations. Programming languages are the bread and butter of the software world. Exploring a bit in that realm, I learned a few things about Go programming language and implemented a <a href="https://github.com/DixitPatel/Distributed_Stack">Distributed Fault-tolerant stack. </a> 
<br><br>
Most modern large-scale applications are distributed in nature and are designed around high-availability. A fundamental principle underlying such systems is that failure is inevitable. Having fault-tolerance built-in, essentially helps to mitigate the effects of such failures, which can be very critical depending on nature of the application. In the event of a failure of one or more underlying computer systems, we need a way to have the entire state of the application reach a consistent state before it can continue to operate.
The faster the application is able to recover from such failures, the lesser the chance of affecting the end-user, which often becomes a deciding factor as far as usability is concerned. 
<br><br>
I am using a distributed consensus algorithm called Raft that provides such a mechanism. The algorithm is easier to understand as compared to it's ancient counter-part Paxos.The example I implement is adapted from <a href="https://github.com/coreos/etcd">Etcd</a>, a popular distributed key-value store that also uses Raft algorithm to implement fault-tolerance.
