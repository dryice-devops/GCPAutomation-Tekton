![logo](https://github.com/michaelawyu/tekton-examples/blob/master/getting-started/images/logo.png?raw=true)

Tekton is a Google-developed open-source framework for creating continuous
integration and deployment (CI/CD) systems. With Tekton, you may build,
test, and deploy code across a variety of environments in an easy,
quick, and standardized way.

Tekton is Kubernetes-native and works well with widely-adopted CI/CD solutions,
such as [Jenkins](https://jenkins.io/)/[Jenkins X](https://jenkins-x.io/),
[Skaffold](https://skaffold.dev/), and [Knative](https://knative.dev/).
It is flexible, and supports many advanced CI/CD patterns, including
rolling, blue/green, and canary deployment.

This playground features a single-node Kubernetes cluster with Tekton installed,
so that you can experiment, explore, and learn about Tekton as you see fit.
The following components are available:

* Tekton pipelines
* Tekton triggers
* Tekton dashboard
* Tekton CLI

Additionally, the Kubernetes cluster includes:

* A Persistent Volume for running Tekton
* Volumes for mounting the Docker socket and storage from the
playground environment into your Tekton pipelines
