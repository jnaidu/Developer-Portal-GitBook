## Managing Instances
An individual with the Solution Center Solution Administrator role will be able to manage all the instances across a particular solution. An Instance Administrator will be able to manage a particular instance.

### Runtime Node

A runtime node is a running copy of an application.  At this time, they are limited to the Covisint portal, which means that each runtime node is a running portal.  For development instances, there is only one runtime node per instance.  For pre-production and production instances though, there will be multiple runtime nodes to provide load balancing and fault tolerance for the instance.  Each runtime node within an instance will always run the exact same copy of the application.

### Artifact

The term artifact refers to those items which a developer creates that can be deployed to an instance.  For now, these are limited to portlets and themes, which can be deployed to a Covisint portal.  Artifacts can be uploaded into an external artifact repository that is owned by company.  From there, each artifact can be used in any number of releases.

### Release

Releases are bundles of artifacts that are to be deployed to an instance together.  To prevent issues with knowing what is actually deployed, once a release is created, it is immutable.  A release can be used across any number of instances.
