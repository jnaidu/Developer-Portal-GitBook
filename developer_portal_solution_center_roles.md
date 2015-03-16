# Developer Portal Solution Center Roles

The Solution Center is an application within the Developer Portal that provides administrative control over the platform.  The application is used by both Covisint and external companies that are developing on the platform. It has self-service administrative functions for most of the concepts mentioned in this section.

The Developer Portal Solution Center has its own set of associated roles, and when a user is granted a role, they gain access to specific features for that application.

# Solution Center Administrator Role
Solution Center Administrators are the highest level administrators in the Solution Center. They can manage the entire platform, and for most installations, this role will be limited to Covisint personnel. Solution Center Administrators can access the features of all subsequent roles. The first Solution Center Administrator will need to be added manually to the system.

# Solution Center Company Administrator Role
Solution Center Company Administrators represent the top-level administrators at a partner or customer that will be using the Solution Center.  They are primarily focused on creating solutions, and inviting other users to join the company.  This role is automatically tied to the company associated with the user.  Company Administrators can access features of all subsequent roles, but only on solutions and instances that are owned by their company.

# Solution Center Solution Administrator Role
Solution Center Solution Administrators are those individuals within a company that have been given ownership over a solution.  They are primarily focused on tasks such as managing instances and releases for a solution.  This role must be granted to a user for each solution on which they need ownership.  Solution Administrators can access features of all subsequent roles, but only on solutions they own. They have complete read access to everything in their company, but no ability to change solutions for which they don't have ownerships.

# Solution Center Instance Administrator Role
Solution Center Instance Administrators are those individuals within a company that have been given ownership over a solution instance.  They are primarily focused on tasks such as assigning developers and deploying releases to an instance.  This role must be granted to a user for each instance on which the need ownership.  Instance Administrators can access features of all subsequent roles, but only on instances they own.

# Solution Center Instance Developer Role
Solution Center Instance Developers are those individuals within a company that have been given development rights on a solution instance.  They are primarily focused on tasks such as deploying to development instances and restarting portal runtime nodes.  This role must be granted to a user for each instance on which they need access.

# Solution Center User Role
A Solution Center User is the most basic role in the Solution Center.  It should automatically be applied to any user that has been granted the service package for the Solution Center.  Those with the Solution Center User role have complete read access to everything in their company, but no ability to change anything.
