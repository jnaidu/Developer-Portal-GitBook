# Developer Portal Architecture

The AppCloud Developer Portal is the provisioning and configuration engine of the PaaS. It provides a foundation for developers to build highly scalable and robust applications.

Application developers can use the Cloud Foundry command line interface or the browser-based UI to perform the following tasks:
* Manage users, roles, and access to the Solution Center
* Create/Delete application runtimes
* Orchestrate application deployments
* Manage service allocations

The PaaS layer comprises two services: Identity Services and Messaging Services.

Identity Services has the following components:

* ID Authenticator
    * ID/Password
    * 2 Factor
    * Risk-based Authentication
    * Policy Enforcement
* ID Provision
    * Password Management
    * Provisioning
    * Profile Management
    * Authorization Management
    * Role Management
    * Workflow Engine
* ID Broker
    * Security Token Service
    * Federation Protocols
    * Translation and Mapping

With Messaging services, you can integrate and aggregate complex information and data to achieve a dynamic, automated business workflow environment.

![](Developer_Portal_Architecture.png)
