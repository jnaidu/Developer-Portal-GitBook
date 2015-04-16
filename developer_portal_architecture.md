## Covisint Developer Architecture

Covisint Developer is the provisioning and configuration engine of the Covisint Platform. It provides a foundation for developers to build highly scalable and robust applications.

Application developers can use the Covisint Developer Solution Center UI to perform the following tasks:
* Manage users, roles, and access to the Solution Center
* Create/Delete application runtimes
* Orchestrate application deployments

The UX development can be done using the Covisint Portal Framework based on Liferay. Developers can write/deploy JSR compliant portlets.
The PaaS layer comprises two sets of services: Identity Services and Messaging Services.

Identity Services encompasses three components:

* ID Authenticator - Validates, verifies, and authenticates a user's identity
    * ID/Password
    * Two-Factor
    * Risk-based Authentication
    * Policy Enforcement
* ID Provision - Manages, and authorizes user accounts for access to appropriate digital resources.
    * Password Management
    * Provisioning
    * Profile Management
    * Authorization Management
    * Role Management
    * Workflow Engine
* ID Broker - Manages and configures federations
    * Security Token Service
    * Federation Protocols
    * Token Translation and Attribute Mapping

With Messaging services, you can integrate and aggregate complex information and data to achieve a dynamic, automated business workflow environment. The key features of the messaging services are:
* Ability to create communication channel
* Use XSLT transformation
* Pre-built custom processes

Figure 1. Covisint Developer Architecture

![](Developer_Portal_Architecture.png)
