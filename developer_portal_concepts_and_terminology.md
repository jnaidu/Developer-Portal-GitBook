# Developer Portal Concepts and Terminology

## Company

A company is either a partner or a customer that is using the Developer Portal Solution Center to administer their solutions on the platform.  A company is represented by a top-level organization in the Platform Identity Realm.  Companies must be invited to join the platform, and during registration, their top-level organizations and initial user account are created.

## Solution

Solutions are a way of logically grouping related development and administrative efforts together under a single concept.  A solution is always associated with a contract, which defines the scope of platform resources that will be made available to it.  Once a company has created a solution, they can begin creating solution instances, which will contain the applications and other platform resources dedicated to it.  A single solution can have any number of solution instances, and is only limited by what is defined in the contract.  A solution also has artifact repositories, and a set of releases, which are associated to it.

## Solution Instance

Solution instances, or just instances as they are more commonly referred to, provide a grouping of platform resources that are intended to run together.  Many people think of instances as application environments, as they contain everything needed for an instance of the solution to run, and are generally dedicated to a specific purpose such as development, QA, staging or production.  Each instance has a portal and identity realm dedicated to it, and an instance type which identifies if that instance will act in a development, pre-production, or production capacity.  Instances contain runtime nodes, and are the target of deployments for releases.

## Runtime Node

A runtime node is a running copy of an application.  At this time, they are limited to the Covisint portal, which means that each runtime node is a running portal.  For development instances, there is only one runtime node per instance.  For pre-production and production instances though, there will be multiple runtime nodes to provide load balancing and fault tolerance for the instance.  Each runtime node within an instance will always run the exact same copy of the application.

## Artifact

The term artifact refers to those items which a developer creates that can be deployed to an instance.  For now, these are limited to portlets and themes, which can be deployed to a Covisint portal.  Artifacts can be uploaded into an external artifact repository that is owned by company.  From there, each artifact can be used in any number of releases.

## Release

Releases are bundles of artifacts that are to be deployed to an instance together.  To prevent issues with knowing what is actually deployed, once a release is created, it is immutable.  A release can be used across any number of instances.
