Neo4j Puppet Module
===================

Automates installing Neo4j on an EC2 Linux system, optionally creating the EC2 machine also.

About
-----

This module will install Neo4j, and its dependencies (e.g. a JVM).  It's designed to run on a server and expose the REST
API over the network.

Features
--------

* Installs Neo4j community from stable Debian packages
* Choose OpenJDK or Oracle JVM
* Daily cold backup to an Amazon EBS volume (defaults to /dev/xvdj)
* Will generate EC2 machine, EBS volume, static IP, etc. from [CloudFormation](/CLOUDFORMATION.md)

Usage
-----

* Aquire a fresh Ubuntu machine, virtual, cloud or metal
* Execute a shell
* wget https://raw.github.com/neo4j-contrib/neo4j-puppet/master/go
* chmod +x go
* sudo ./go


License
-------
This Puppet module is licensed under the Affero GPL.
If you use the Oracle JVM you must read and accept the terms of the [Oracle end user license agreement](http://www.oracle.com/technetwork/java/javase/terms/license/index.html)
Oracle and Java are registered trademarks of Oracle and/or its affiliates. Other names may be trademarks of their respective owners.


Support
-------

Please log tickets and issues at the [Github project](https://github.com/neo4j-contrib/neo4j-puppet).
