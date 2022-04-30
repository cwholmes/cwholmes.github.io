## Projects

### [Elixir DNS Rest Server](https://github.com/cwholmes/elixir-dns-rest-server)

Partial DNS server written in Elixir and packaged in a docker image. Combines
the traditional UCP based DNS queries with a REST implementation, using the Maru
framework, exposing some additional functionality such as updating and deleting
records. This service was crucial for testing workflows reliant on DNS records.

### JFrog Artifactory Kaniko CD

Components required for deploying container images built with Kaniko and JIB, as
an Artifactory build. This allows for improved tracking and the ability to promote
artifacts. These components are primarily used within Jenkins pipelines to allow
for building and pushing images when using Kubernetes Pods as build nodes.
