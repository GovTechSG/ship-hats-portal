# Manage User Groups

Using the user groups, as an SA or a PA, you can:
- Group multiple users together
- Assign tool's permissions to a group
- Assign same permissions or roles to all users in a group

**Topics**

- [Create user groups](#create-user-groups)
- [Access user groups](#access-user-groups)
- [Add users to user groups](#add-users-to-user-groups)
- [Remove user groups](#remove-user-groups)
- [Remove users from user groups](#remove-users-from-user-groups)

## Create user groups

As an SA/PA, you can create user groups based on quota specified for your projects based on your subscription.  

### To create a user group
1. From the side menu, click **Users** > **All User Groups**. 

   ![User groups](./images/user-groups-view.png)

1. Click **Create Group**.  

   The **Create New User Group** window appears.  

   >**Note:** If you have consumed the quota available for user groups, the **Create Group** button is disabled. If you want to continue to add user groups beyond the available quota limit, [create a service request](https://jira.ship.gov.sg/servicedesk/customer/portal/11).

   ![Create group](./images/user-groups-create.png)

1. Enter values in the following fields:     
   |Field|Description|
   |---|---|
   **Group Name**|Enter name for the group. Make sure that the group name meets the following criteria: <ul><li>Group name must be alphanumeric</li><li>Group name must be less than 40 characters</li><li>Group name can contain only `-` and `_` special characters</li></ul>|
   |**Group Description**|Enter description for the group. You can add up to 250 characters.|
   **Group Members**|Select users to be added to the group from the drop-down list. You can select active users in the current subscription only. Though inactive (suspended) users will also appear in the list, you cannot add them as group members.|

1. Click **Create Group**.  

   The user group is created and appears under the **Group Name** column on the **All User Groups** screen. 

   ![Create group](./images/all-user-groups.png)

## Access user groups

### To access user groups

1. From the side menu, click **Users** > **All User Groups**.  

   The **All User Groups** window appears, displaying all the user groups listed under the **Group Name** column.  
   
   At the top, you can view the quota consumed/quota available. For example, `1/5 groups created` indicates that you have created 1 out of the 5 group quota that is available based on the number of projects your subscription can create.

   ![User groups](./images/all-user-groups.png)

## Add users to user group

### To add users to a user group

1. From the side menu, click **Users** > **All User Groups**.
1. Next to the user group to which you want to add a new user, under **Actions**, select **Manage**.   

   ![Actions](./images/user-group-actions.png)

1. In **Add users**, select additional users, and then click **Add**.  

   >**Note:** Users will appear here only if they were added in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/).

   ![add users](./images/user-groups-add-users.png)

   The newly added user appears under the **Name** column.

## Remove users from user groups

### To remove a user from a user group
1. From the side menu, click **Users** > **All User Groups**.
1. Next to the user group from which you want to remove a user, under **Actions**, select **Manage**.

   ![Manage](./images/user-group-actions.png)

1. Next to the user that you want to remove, click **Remove**.  

   ![remove user](./images/user-group-users.png)

   A pop-up appears indicating that the selected user will lose all the permissions assigned to the user group.  

   ![Remove](./images/user-group-user-remove.png)

1. Click **Proceed**.  
   The user is removed.


## Remove user groups

### To remove a user group
1. From the side menu, click **Users** > **All User Groups**.
1. Next to the user group to which you want to add a new user, under **Actions**, select **Remove group**.  

   ![Actions](./images/user-group-actions.png)

   A **Remove User Group** pop-up message appears indicating that the users in this user group will lose all permissions assigned to it.  

   ![Remove user group](./images/user-group-remove.png)

1. Click **Proceed**.  
   The user group is removed. 

### Related Topics
- [Manage users](manage-users)
- [Manage user groups & users](manage-user-groups-and-users)