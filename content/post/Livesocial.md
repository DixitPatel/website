+++
banner = ""
categories = ['Kafka','Websockets']
date = "2017-09-21"
description = ""
images = []
menu = ""
tags = []
title = "Websockets with Apache Kafka"
+++

I spent a considerable amount of time earlier, trying to fit together a basic solution using Spring Websockets and Kafka. Understanding each of these technologies individually is probably very straight-forward but using them in the Spring world might take you some time to figure out.  I'm hoping some tips here would save you time and get started quickly for whatever application you are building.
<br><br>
Firstly, here are some good resources (and probably only) to go through to understand basics of using Apache Kafka. 
1. <a href="https://kafka.apache.org/quickstart">Official Apache Kafka page.</a> and Tim Berglund's short <a href="https://kafka.apache.org/documentation/streams/">videos </a> on Kafka Streams.
2. <a href="http://shop.oreilly.com/product/0636920044123.do">Kafka: The Definitive Guide.</a>. (Tip : Use the 10-day free trial if you can't afford subscription to Safari Books Online like me!)

<br><br>
As for Websockets: go through this blog article, <a href="http://blog.teamtreehouse.com/an-introduction-to-websockets">  An Introduction to WebSockets</a>, from treehouse.
<br>
I used these technologies for an application I <a href="https://github.com/DixitPatel/livesocial">built</a> that allows users to subscribe to topics and get real-time alerts and events happening around them. Going through the code-base might give you an idea on how to use Websockets with Kafka in Spring. This is very much a work in progress and I hope to add more features to the project as well as to this doc in near future. 
