## Create an Instance
Solution instances, or just instances as they are more commonly referred to, provide a grouping of platform resources that are intended to run together.  Many people think of instances as application environments, as they contain everything needed for an instance of the solution to run, and are generally dedicated to a specific purpose such as development, QA, staging or production.  Each instance has a portal and identity realm dedicated to it, and an instance type which identifies if that instance will act in a development, pre-production, or production capacity.  Instances contain runtime nodes, and are the target of deployments for releases. You'll be able to create multiple instances for a solution.

### Who can perform this function?
* Solution Center Administrator
* Solution Center Company Administrator
* Solution Center Solution Administrator

### Steps
1. On the left panel of the **Solutions Center**, click **Solutions**. A list of all the solutions that have access to the solution center will be displayed.
2. Select your solution by clicking on the solution name.
3. Click the **Instances** tab. A list of all the instances for your solution will be displayed if you have added any instances before.
4. Click **Add Instance**.
5. Provide a friendly instance name in the field **Instance Name**.
6. Provide an instance description in the field **Instance Description**.
6. Pick an instance type from the available configuration options. You have the ability to create multiple development and pre-production instances, however, you can only create one production instance.
7. Provide an instance alias name in the field **Alias**.
8. You can either create a new realm or choose from existing realms. If you choose an existing realm, the instance portal, identity APIs, ID Provision, and ID Broker will be configured to run against your selected realm.
9. Enter a password for the exchange operator role for your new instance. This role will be responsible for managing company level membership for the platform. The primary function of the role is to allow the operators to invite new companies to join the platform, and to grant other types of roles, such as the CIS Service Administrator.
8. Click the **Add Instance** button.
9. The instance creation does the following background work to set up the instance:
    1. Create Realm
    2. Create Portal
10. Once your instance has been successfully provisioned, note down the instance details for your reference.The admin login Id is always “SOLUTION ALIAS-INSTANCE ALIAS_ADMIN”. This is the SEED ACCOUNT for this solution instance.
11. Click the **View Instance Settings* button to view instance details.
