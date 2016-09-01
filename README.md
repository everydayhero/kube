# kube
Easily get up and running with a Kubernetes cluster by installing tools and providing scripts to make things easier to work with.

## Getting started
The easiest way to get started is to simply run `bin/bootstrap`. This assumes you have [Homebrew](http://brew.sh/) installed.

### Working with an existing cluster
To set up the configuration for accessing a Kubernetes cluster make sure you have permission to access the S3 bucket for the environment.
When that is done simply run `bin/kubetool <environment> init`. This will configure kubectl on your machine.

