# cloud-compute
Set up and use pandas for off-core compute

## Installation

### Cluster

In order to do meaningful compute, we will need a remote cluster. There are a number of ways to do this, but following current trends we will aim to deploy using `Kubernetes` and for the sake of my sanity, we will throw that at Azure. It is important to note that everything we do should run locally (but then why are we getting off of Pandas?), and *more importantly* should work on any modern cloud compute platform (wherever `Kubernetes` is welcome).

#### Azure
Let's get [AKS](https://docs.microsoft.com/en-us/azure/aks/spark-job) working ...

1. Get a [Docker Hub](https://docs.docker.com/docker-hub/) account!
2. Install the [Azure CLI](https://docs.microsoft.com/en-ca/cli/azure/?view=azure-cli-latest)
3. JDK 8, get it ready
4. Scala Build Tool ([SBT](https://www.scala-sbt.org/1.0/docs/Setup.html))
