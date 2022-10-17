# Manage user groups & users

**Topics**

- [Manage user groups within a project tool](#manage-user-groups-within-a-project-tool)
- [Manage user within a project tool](#manage-users-within-a-project-tool)
- [Remove user groups from a project tool](#remove-user-groups-from-a-project-tool)



## Manage user groups within a project tool

As a Subscription Admin or a Project Admin, you can manage following within a project tool or app:  
- User groups
- Permissions or Roles  

You can manage user groups and permissions/roles for the following tools:
- Confluence
- Jira
- Nexus IQ
- SonarQube

### To manage user groups for your project tool or app


1. From the side menu, click **Projects** > **All Projects** to view all the projects in this subscription account. If needed, refer to [Switch account](manage-account).
1. Click the project that you want to update.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
1. Click the tool for which you want to manage/add user groups, and then click **Manage**.
    The **Manage Tool** window appears. 
1. From the **Select function** dropdown list, select **Manage/add user group**. 

    - **Confluence:** Provide value in the **User Group** field, and then select the required permissions. To know more about the permissions, refer to the Confluence documentation.

    - **Jira:** Provide value in the **User Group** field, and then select the required roles. To know more about the roles, refer to the Jira documentation.

    - **Nexus IQ:** Provide value in the **User Group** field, and then select the required roles. To know more about the roles, click the **Roles** dropdown list.
    
    - **SonarQube:** Provide values in the **App Name** and **User Group** fields, and then select the required permissions. The **Browse** permission is selected by default along with any other permission. To know more about the permissions, click the **Permissions** dropdown list.
    
1. Click **Update**.
    The permissions or roles are updated in the portal as well as respective tools. Any permissions assigned via portal will override the previously assigned permissions in NexusIQ at the app level.

    >**Note:** Any permissions assigned via portal will override the previously assigned permissions in NexusIQ at the app level.



## Manage users within a Project Tool

As a Subscription Admin or a Project Admin, you can manage users within a project tool or app. 

You can manage users for the following tools:
- Confluence
- JIRA
- Nexus IQ


### To manage users for your project tool or app


1. From the side menu, click **Projects** > **All Projects** to view all the projects in this subscription account. If needed, refer to [Switch account](manage-account).
1. Click the project that you want to update.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
1. Click the tool for which you want to manage/add users, and then click **Manage**.
    The **Manage Tool** window appears. 


    Follow the steps in table for your tool.

    |Available Tools|Steps|
    |---|---|
    |GitLab|ol><li>Click the **Manage/add user access** drop-down list.</li><li>Click Application name in the **App Name** drop-down list.</li><li> Click**User** drop-down list, and select a user.</li><li>Select the role that you want to assign to the user.</li><li>Click **Update**.</li><ol>|
    |Jira|<ol><li>Click the **Manage/add user** drop-down list, and follow the on-screen instructions.</li><ol>|
    |Confluence|<ol><li>Click the **Manage/add user** drop-down list, and follow the on-screen instructions.</li><ol>|
    |Fortify on Demand|<ol><li>Click the **Manage/add user access** drop-down list, and follow the on-screen instructions.</li><ol>|
    |Nexus IQ|<ol><li>Click the **Manage/add user** drop-down list.</li><li>Select the **User** drop-down list, and select a user.</li><li>Select the role that you want to assign to the user.</li><li>Click **Update**.</li><ol>|
    |SonarQube|<ol><li>Click the **Manage/add user** drop-down list, and follow the on-screen instructions.</li><ol>|

    >**Note:** For the Atlassian apps (Confluence and JIRA), in the **Manage Tool** window, the link to tool or app server, includes the project key that you selected. This enables you to get to the project in the tool or app server directly. 
    >
    ><kbd>![All Projects](./images/portal-projects-manage-users.png  ':size=60%')</kbd>





## Remove user groups from a project tool

As a Subscription Admin or a Project Admin, you can remove permissions and roles within a project tool or app for the following tools:
- Confluence
- Jira
- Nexus IQ
- SonarQube

### To remove user groups for your project tool or app


1. From the side menu, click **Projects** > **All Projects** to view all the projects in this subscription account. If needed, refer to [Switch account](manage-account).
1. Click the required project.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
1. Click the tool for which you want to remove user groups, and then click **Manage**.
    The **Manage Tool** window appears. 
1. In the **Manage Tool** window that appears, from the dropdown, select **Manage/add user group**. 
1. In the **App Name** and **User Group** fields, select the App and user group for which you want to update permissions or roles.  
1. Next to the permissions or roles that you want to remove, clear the check box, and then click **Update**. 
The permissions or roles are updated.
