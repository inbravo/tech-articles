#	Multidimensional Scalability Capabilities 

Industry is gradually moving away from the days when operational capabilities were solely in the hands of bunch of operation engineers, who were sitting in front of large screens, keeping an eye on system health, and undesirably waiting for a scalability bottleneck to arise, before applying a predefined remedy.

Twenty four hours constant running processes, which are vertically scalable but only through manual interventions. All time available hardwares, which are horizontally scalable but only with manual efforts. Every operational change to cater larger volume demands, must go through time consuming, capability building cycles.

New age scalability demands a comprehensive yet dynamically scalable model to address all possible grey areas of system architecture. Engineering activities are not just limited to development or quality, it has spread its wings to cover operational activities now.

A multidimensionally scalable dynamic system, is what any large & mid-scale enterprise service provider, seeks these days. Human driven operation management has its own limitations, It needs a perfectly aligned combination of hardware and softwares to make a dynamically scalable system. 

It requires an operation management system, to constantly monitor the existing enviornmental situation, and take timely decisions to serve increasing system load, by spawning additional system capabilities.

[The Art of Scalability](http://theartofscalability.com/) describes a really useful, three dimensional scalability model. The [scale cube](http://microservices.io/articles/scalecube.html) has given us the idea to understand the holistic appraoch to touch base all aspects of system scalability. Three dimensions of scalability are,

-	X-axis scaling consists of running cloned copies of an application, running behind a load balancer. If there are N cloned copies then each copy will handle 1/N of the load.
-   Y-axis scaling splits the application into multiple, subset of services. Each service is responsible for one or more closely related functions. SOLID principles makes relevance here.
-	Z-axis scaling is used to scale data storage mostly. Data is partitioned across several machines on a whole cluster.

There are various scalability capabilities, which are relevant for building a truly scalable system. These 3P (People/Process/Platform) capabilities are described below.

![](https://github.com/inbravo/tech-articles/blob/master/dzone/images/mdsc.png)

Detailed [list](https://github.com/inbravo/tech-articles/blob/master/dzone/docs/mdsc.pdf) of all capabilities. These capabilities are applicable for organizations with self managed operations. The next in series will be scalability capabilities for clouds. 
