Phantom
=======

Phantom is a high performance proxy for accessing distributed services. It is an RPC system with support for different 
transports and protocols. Phantom is inspired by Twitter Finagle clients and builds on the capabilities of technologies like 
Netty, Unix Domain Sockets, Netflix Hystrix and Spring. Phantom proxies have been used to serve several hundred million 
API calls in production deployments at Flipkart.

## Releases

| Release | Date | Description |
|:------------|:----------------|:------------|
| Version 2.0.1-hystrix-1.5.3             | Sept 2016      |    Bumped Hystrix Version to 1.5.3
| Version 2.0.1             | Jul 2016      |    Bug fix in shutdown sequence, zipkin span collector
| Version 2.0.0             | May 2016      |    Upgrade to Trooper 2.0.0
| Version 1.4.4             | Mar 2016      |    Bug fixes in Thrift proxy, API interface generalization
| Version 1.4.3             | Dec 2015      |    Bug fixes in TCPNettyServer, Distributed tracing
| Version 1.4.2             | Nov 2015      |    Upgrade to Spring 4.x, Http proxy, Task interface

## Changelog

Changelog can be viewed in CHANGELOG.md file (https://github.com/Flipkart/phantom/blob/master/CHANGELOG.md)

## Why Phantom
Phantom is the "ghost who walks" - an entity whose presence can be felt (in a good way) but its existence need not be acknowledged.
The Service Proxies fit this analogy well and therefore earned the moniker "Phantom". Motivation for creating Phantom and design overview 
is described in this [Proxies for resilience and fault tolerance in SOA](http://tech-blog.flipkart.net/2013/07/proxies-for-resilience-and-fault-tolerance-in-distributed-soa) blog post.

## Phantom Consoles
![Monitor](https://github.com/Flipkart/phantom/raw/master/docs/Service%20Proxy.png)

![Admin Console](https://github.com/Flipkart/phantom/raw/master/docs/Phantom%20http%20config.png)

## Getting Started
The [Getting Started](https://github.com/Flipkart/phantom/wiki/Getting-started-and-Examples) page has "5 minute" examples to help you start using Phantom proxies.

## Documentation and Examples
Phantom project modules that start with "sample" - for e.g. sample-http-proxy, sample-task-proxy are example proxy implementations.
Documentation is continuously being added to the Wiki page of Phantom (https://github.com/Flipkart/phantom/wiki)

## Getting help
For discussion, help regarding usage, or receiving important announcements, subscribe to the Phantom users mailing list: http://groups.google.com/group/phantom-users

## License
Phantom is licensed under : The Apache Software License, Version 2.0. Here is a copy of the license (http://www.apache.org/licenses/LICENSE-2.0.txt)

## Core contributors
* Regunath B ([@regunathb](http://twitter.com/RegunathB))
* Devashish Shankar ([@devashishshankar](https://github.com/devashishshankar))
* Kartik B Ukhalkar ([@kartikssj](https://github.com/kartikssj))
* Arya Ketan ([@aryaKetan](https://github.com/aryaKetan))
* Amanpreet Singh ([@aman_high](https://github.com/aman_high))

