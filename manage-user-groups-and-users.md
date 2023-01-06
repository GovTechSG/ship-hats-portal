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
- Fortify on Demand
- Jira
- Nexus IQ
- SonarQube

### To manage user groups for your project tool or app


1. From the side menu, click **Projects** to view all the projects in this subscription account.  
    
    >**Tip:** If needed, [Switch account](manage-account).

1. Click the project that you want to update.
    
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.

1. Click the tool for which you want to manage/add user groups, and then click **Manage**.
    The **Manage Tool** window appears.

    >**Note:** If you want to manage user groups for FOD, select **Manage Users** tab.

1. From the **Select function** dropdown list, select **Manage/add user group**. 

    |Available Tools|Steps|
    |---|---|
    | **Confluence** |Provide value in the **User Group** field, and then select the required permissions. 
    | **Jira** |Provide value in the **User Group** field, and then select the required roles. 
    |**Fortify on Demand** |Select **Manage user access** or **Manage user role** as required.  <br>- If you want to **Manage user access**, select values in the **User(s)** field.  <br>- If you want to **Manage user role**, select values in the **User** and **Role** fields.|   
    | **Nexus IQ**| Provide value in the **User Group** field, and then select the required roles. 
    | **SonarQube**| Provide values in the **App Name** and **User Group** fields, and then select the required permissions.<br> The **Browse** permission is selected by default along with any other permission. 
    
1. Click **Update**.

    The permissions or roles are updated in the portal as well as respective tools. Any permissions assigned via portal will override the previously assigned permissions in NexusIQ at the app level.

    >**Note:** Any permissions assigned via portal will override the previously assigned permissions in NexusIQ at the app level.



## Manage users within a Project Tool

As a Subscription Admin or a Project Admin, you can manage users within a project tool or app. 

You can manage users for the following tools:
- Confluence
- JIRA
- Fortify on Demand
- Nexus IQ


### To manage users for your project tool or app


1. From the side menu, click **Projects** to view all the projects in this subscription account.  
    >**Tip:** If needed, [Switch account](manage-account).

1. Click the project that you want to update.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.

1. Click the tool for which you want to manage/add users.
1. Click **Manage**, and then click **Manage/add users**.

    The **Manage Tool** window appears. 
    
    >**Note:**  If you want to manage user groups for FOD, select **Manage Users** tab.   
    > - If you want to **Manage user access**, select values in the **User(s)** field.  
    > - If you want to **Manage user role**, select values in the **User** and **Role** fields. You can click **Role glossary** to learn more about roles. 
    
1. Change as required, and then click **Update**.   
    or   
    Follow the on-screen instructions.



## Remove user groups from a project tool

As a Subscription Admin or a Project Admin, you can remove permissions and roles within a project tool or app for the following tools:
- Confluence
- Jira
- Fortify on Demand
- Nexus IQ
- SonarQube

### To remove user groups for your project tool or app


1. From the side menu, click **Projects** to view all the projects in this subscription account.  
    >**Tip:** If needed, [Switch account](manage-account).

1. Click the required project.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
    
1. Click the tool for which you want to remove user groups.
1. Click **Manage**, and then click **Manage/add users**.

    The **Manage Tool** window appears. 
    
    >**Note:** If you want to manage user groups for FOD, select **Manage Users** tab.   
    > - If you want to **Manage user access**, select values in the **User(s)** field.  
    > - If you want to **Manage user role**, select values in the **User** and **Role** fields. You can click **Role glossary** to learn more about roles. 
    
1. In the **App Name** and **User Group** fields, select the App and user group for which you want to update permissions or roles.  This step is not applicable for FOD.
1. Next to the permissions or roles that you want to remove, clear the check box. This step is not applicable for FOD.
1. Click **Update**.  

    The permissions or roles are updated.

### Related topics

- [Manage users](manage-users)
- [Manage user groups](manage-user-groups)