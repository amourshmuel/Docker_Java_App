## My journey: Dockerized Java on Apache Mesos Container cluster on Azure. ##

To the post [click](https://blogs.microsoft.co.il/amourshmuel/2016/08/26/my-journey-dockerized-java-on-apache-mesos-container-cluster-on-azure/)

I want to start this journey from the basic. Although I’m pretty sure that [Docker](https://en.wikipedia.org/wiki/Docker_(software)) software solution are known knowledge, the all pack should cover it all.

So, what we talking about it to take an exiting solution provided by [Docker Hub](https://hub.docker.com/) and second solution provided by [Apache Mesos](http://mesos.apache.org/) and set it on a 3rd IaaS cluster solution stored on [Azure](https://azure.microsoft.com/en-us/). The main idea is to do it well and not step on each other toes.

### The project ###

![Solution architecture](https://github.com/amourshmuel/Docker_Java_App/blob/master/solution_diagtram.png?raw=true)

he project will contain the next layers:

1. The Azure Cluster which contains the Mesos cluster. This part will be an IaaS solution on the cloud.
2. The Apache Mesos cluster the management application that we will use to interact with the installed Docker.
3. The Docker (java application) that will run above the Mesos container.

Let’s start from the top – let’s setup a Docker.

1. [My journey : Dockerized Java on Apache Mesos Container cluster on Azure – Setup a Docker (Part I)](http://blogs.microsoft.co.il/amourshmuel/2016/08/26/my-journey-dockerized-java-on-apache-mesos-container-cluster-on-azure-setup-a-docker/).
2. [My journey: Dockerized Java on Apache Mesos Container cluster on Azure – Setup a Docker (Part II).](http://blogs.microsoft.co.il/amourshmuel/2016/09/01/my-journey-dockerized-java-on-apache-mesos-container-cluster-on-azure-setup-a-docker-part-ii/).
3. [My journey: Dockerized Java on Apache Mesos Container cluster on Azure – Setup Mesus cluster on Azure](https://blogs.microsoft.co.il/amourshmuel/2016/09/02/my-journey-dockerized-java-on-apache-mesos-container-cluster-on-azure-setup-mesus-cluster-on-azure/).
