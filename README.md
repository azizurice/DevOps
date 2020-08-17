# DevOps Tools

## Docker

### Run docker as non-root user in Linux
      Run the following commands to add user in the docker group:
      $ sudo groupadd docker
      $ sudo usermod -aG docker $USER
      $ newgrp docker

      That's it.
      $ docker version


## Jenkins

## Ansible

## Terraform

## Kubernetes
<blockquote>

### VirtualBox
   [Add virtualbox repositor and install following this link](https://computingforgeeks.com/how-to-install-latest-virtualbox-on-ubuntu-debian/)
 B
### Minikube
   [Install Minikube following this link](https://phoenixnap.com/kb/install-minikube-on-ubuntu)

### kubectl
   [Install kubectl on Linux following this link](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

</blockquote>

Few other important servers:

## Kafka
[Install Apache Kafka on Ubuntu 20.04 LTS](https://www.fosstechnix.com/how-to-install-apache-kafka-on-ubuntu-20-04-lts/)

[How to install and run Kafka on your machine](https://www.sohamkamani.com/blog/2017/11/22/how-to-install-and-run-kafka/)

[Microservices, Event-Driven Architecture and Kafka](https://dzone.com/articles/microservices-event-driven-architecture-and-kafka)

## ELK Stack


## HAProxy
 [HAProxy](https://www.haproxy.com/) is a free, very fast and reliable solution offering high availability, load balancing, and proxying for TCP and HTTP-based applications. Please see the following link:
 [Load Balancing using HAProxy](https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts)
 [How to use HAProxy for Loadbalancing](https://www.linode.com/docs/uptime/loadbalancing/how-to-use-haproxy-for-load-balancing/)


 ## Database Management Systems:  
 <hr/>

## MySQL
[MySQL](https://www.mysql.com/) is an open-source relational database management system.

## MongoDB
[MongoDB](https://www.mongodb.com/) is a cross-platform document-oriented NoSQL database program. MongoDB uses JSON-like documents with optional schemas.

 [Install MongoDB on Ubuntu 20.04](https://linuxhint.com/install_mongodb_ubuntu_20_04/) in an easy way. It may not install up-to-date version. To install the latest comunity edition on your preferred platform using your preferred package manager, please follow the link below:
 [Install MongoDB Community Edition](https://docs.mongodb.com/manual/administration/install-community/)



 ## Testing Tools:  
 <hr/>

 ### SonarQube
 [SonarQube](https://www.sonarqube.org/) is an open-source platform for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities.

 ### PMD
 [PMD](https://pmd.github.io/) is a static source code analyzer for finding common programming flaws like unused variables, empty catch blocks, unnecessary object creation, and so forth. PMD includes built-in rule sets and supports the ability to write custom rules.

 ### Checkstyle
 [Checkstyle](https://github.com/checkstyle/checkstyle) is a static code analysis tool for checking if Java source code complies with coding rules. This tool is fully configurable to your preferences such as [Sun Code Conventions](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html) or [Google Java Style](https://checkstyle.sourceforge.io/reports/google-java-style.html).

 ### FindBugs
 [FindBugs](http://findbugs.sourceforge.net/) specifically looks for bugs in Java Code; it covers for [over 400 different bugs](http://findbugs.sourceforge.net/bugDescriptions.html).

 ### Codacy
 [Codacy](https://www.codacy.com/) is an automated code analysis/quality tool
 
 ### Gatling
 [Gatling](https://gatling.io/) is an open-source load- and performance-testing framework.
 
 #### [Install Gatling on Ubuntu](https://www.blazemeter.com/blog/how-to-install-gatling-on-ubuntu)
 Download latest stable version from the following link:
 wget(https://repo1.maven.org/maven2/io/gatling/highcharts/gatling-charts-highcharts-bundle/3.3.1/gatling-charts-highcharts-bundle-3.3.1-bundle.zip)
