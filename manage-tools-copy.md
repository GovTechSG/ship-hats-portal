# Manage tools and applications

# Manage tools

**Topics**

- [Add project tools](#add-project-tools)
- [Create project tool with customised project key](#create-project-tool-with-customised-project-key)
- [Remove project tools](#remove-project-tools)

# Manage applications

**Topics**

- [Add applications to a project tool](#add-applications-to-a-project-tool)
- [Remove applications from a project tool](#remove-applications-from-a-project-tool)

# Manage user groups & users

**Topics**

- [Manage user groups within a project tool](#manage-user-groups-within-a-project-tool)
- [Manage user within a project tool](#manage-users-within-a-project-tool)
- [Remove user groups from a project tool](#remove-user-groups-from-a-project-tool)

# Manage tokens

**Topics**

- [Retrieve token](#retrieve-token)
- [Renew token](#renew-token)


## Add project tools

SA or PA can add the required project tools as explained below. You can add tools under the **Subscribed Tools** section based on the tools quota allotted for your subscription type. 


### To add project tools

1. From the side menu, click **Projects** > **All Projects** to view all the projects in this subscription account. If needed, refer to [Switch account](manage-account).
1. Locate the project to which you want to add a tool, and then click the project.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
1. Locate the tool that you want to add, click **Create**, and follow the specific steps in table for the tool that you want to add.

    |Available Tools|Steps|
    |---|---|
    |GitLab|Make sure that at least 1 Project Admin has a GitLab account and is added to the TechPass group.<ol><li>Click the **Tool Type** > **Select Tool** drop-down list, and select **GitLab**.</li><li>In the **GitLab Group Name**, enter the group name.</li> <ol> |
    |Jira|<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list, and select **Jira**.</li><ol>|
    |Confluence|<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list, and select **Confluence**.</li><ol>|
    |Nexus IQ|<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list.</li><li> Enter values in the **Application Name** and **Application ID** fields.</li><ol>|
    |Nexus Repo|<ol><li>Click **Add**.</li><li>Submit a [service request](https://jira.ship.gov.sg/servicedesk/customer/portal/11/) to add this tool.</li><ol>|
    |pCloudy|<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list, and select **pCloudy Device Farm & HATS Browser Farm**.</li><ol>|
    |Prisma Cloud|<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list, and then select **Container Image Scanner**.</li><li>In the **Scanner type** field, select **Prisma Cloud**</li><li>In the **App Name** field, enter the required value. </li><ol>|
    |SonarQube - Community Edition|Make sure that you have logged in to [SonarQube](https://sonar.hats.stack.gov.sg/sonar) at least once.<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list.</li><li>In the **App Name** field, enter the required value.</li><ol>|
    |SonarQube - Developer Edition|Make sure that you have logged in to [SonarQube](https://sonar1.hats.stack.gov.sg/sonar) at least once.<ol><li>Click **Add**.</li><li>Click the **Select Tool** drop-down list.</li><li>In the **App Name** field, enter the required value.</li><ol>|
    |Fortify on Demand| <ol><li>Click the **Select Tool** drop-down list.</li><li> Provide values in the **App Name** field.</li><ol>|
    |Fortify On-Prem|<ol><li>Click the **Select Tool** drop-down list.</li><li> Provide values in the **App Name** field.</li><ol>|

    >**Note:** After you reach the quota, the respective tool name(s) will be disabled in the **Select Tool** drop-down list. If you still want to add these tools, send an email to [enquiries_ENP@tech.gov.sg](enquiries_ENP@tech.gov.sg).    
1. Click **Add**.   
    
    The selected project tool and application is added.


## Create project tool with customised project key
Subscription Admin (SA) and Project Admin (PA) can customise the project keys when adding app tools on SHIP-HATS. This is currently applicable for Jira and Confluence.  

### To customise project key 

1. Go to **Projects** > **All Projects**.
1. Identify your project, and then click the project.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.

1. Locate the tool that you want to add, click **Create** > **Add** > **Customise Project Key**. 
<!--
1. Choose the required tool.

    ![Add new Development tool](./images/add-new-dev-tool.png)

1.  Select **Customise Project Key**.

    ![customise](./images/customise.png)
-->

1. In the **Project Key** field, enter the required project key. A project key can include 2-10 characters, consisting of uppercase letters A-Z and numbers from 0-9. First character must be an alphabet. 

<!--    ![add](./images/addnewkey.png)-->
1. Click **Add**. 


## Add applications to a project tool

By default, when you add a project tool, an application is added. However, you can add additional applications to the following tools:
- Prisma Cloud
- Fortify On-Prem
- Fortify on Demand
- Nexus IQ
- SonarQube - Community Edition
- SonarQube - Developer Edition


### To add an application to a project tool
1. Go to **Projects** > **All Projects**.

    <kbd>![All Projects](./images/portal-projects-all-projects.png)</kbd>

1. Navigate to your project, and then click **Manage**.
1. Go to the required tab, and then click **Add another** under the project tool to which you want to add another application.  
    The **Add new tool** window appears. 
1. Provide values in the available fields, and then click **Add**.    
    The new application is added.



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

1. Go to **Projects** > **All Projects**.

    <!--<kbd>![All Projects](./images/portal-projects-all-projects.png)</kbd>-->

1. Navigate to your project, and then click **Manage** on the project tool for which you want to manage/add user groups. 

1. In the **Manage Tool** window that appears, from the dropdown, select **Manage/add user group**. 

    - **Confluence:** Provide value in the **User Group** field, and then select the required permissions.

        <kbd>![Manage tool](confluence-manage-user-group.png) ':size=60%')</kbd>
    - **Jira:** Provide value in the **User Group** field, and then select the required roles.

        <kbd>![Manage tool](jira-manage-user-group.png) ':size=60%')</kbd>
    - **Nexus IQ:** Provide value in the **User Group** field, and then select the required roles.
        
        <kbd>![Manage Tool](./images/nexus-iq-manage-user-group.png  ':size=60%')</kbd> 
    - **SonarQube:** Provide values in the **App Name** and **User Group** fields, and then select the required permissions. The **Browse** permission is selected by default along with any other permission.

        <kbd>![Manage Tool](./images/sonarqube-manage-user-group.png ':size=60%')
    
1. Click **Update**.
    The permissions or roles are updated in the portal as well as respective tools. Any permissions assigned via portal will override the previously assigned permissions in NexusIQ at the app level.

## Manage users within a Project Tool

As a Subscription Admin or a Project Admin, you can manage users within a project tool or app. You can manage users for the following tools:
- Confluence
- JIRA
- Nexus IQ

### To manage users for your project tool or app

1. Go to **Projects** > **All Projects**.

    <kbd>![All Projects](./images/portal-projects-all-projects.png)</kbd>

1. Navigate to your project, and then select **Manage**.
1. Go to the required tab, and then click **Manage** on the project tool whose users you want to manage. The **Manage Tool** window appears. 

    Follow the steps in table for the tool that you want to add.

    |Available Tools|Steps|
    |---|---|
    |Jira|<ol><li>Click the **Manage/add user** drop-down list, and follow the on-screen instructions.</li><ol>|
    |Confluence|<ol><li>Click the **Manage/add user** drop-down list, and follow the on-screen instructions.</li><ol>|
    |Nexus IQ|<ol><li>Click the **Manage/add user** drop-down list.</li><li>Select the **User** drop-down list, and select a user.</li><li>Select the role that you want to assign to the user.</li><li>Click **Update**.</li><ol>|
    |SonarQube|<ol><li>Click the **Manage/add user** drop-down list, and follow the on-screen instructions.</li><ol>|

    >**Note:** For the Atlassian apps (Confluence and JIRA), in the **Manage Tool** window, the link to tool or app server, includes the project key that you selected. This enables you to get to the project in the tool or app server directly. 
    >
    ><kbd>![All Projects](./images/portal-projects-manage-users.png  ':size=60%')</kbd>


## Retrieve token 

You can retrieve token for the following project tools:  

- Fortify SCA & WebInspect 
- Container Image Scanner
- Nexus IQ
- pCloudy Device Farm & HATS Browser Farm
- SonarQube

### To retrieve token
1. Go to **Projects** > **All Projects**.

    <!--<kbd>![All Projects](./images/portal-projects-all-projects.png)</kbd>-->

1. Navigate to your project, and then click **Manage** on the project tool for which you want to retrieve the token. 
1. In the **Manage Tool** window that appears, from the dropdown, select **Token for bamboo pipeline**. 
1. If requested, select the app name.
    The token appears under the **Token/Decoded Token ID** field. 
1. Click the **Copy** button next to the token to copy the token.

## Renew Token

You can renew token for the following tools:
- Fortify SCA & WebInspect
- SonarQube

### To renew an expired token

1. From the side menu, click  **Projects**  >  **All Projects**  to view all the projects in this subscription account. If needed, refer to [**Switch account**](https://docs.developer.tech.gov.sg/docs/ship-hats-documentation/#/manage-account?id=switch-account).
2. Find the project, and then click  **Manage**.
3. Click **QA &amp; Security**.

4. Click **Manage**. 
    
    The **Manage Tool** pane is displayed.

5. Click the drop-down arrow, and then choose **Token**. The option may vary based on tool selected.

6. Click **Renew Token**.

    <kbd>![Renew Token](./images/renew-token.png ':size=75%')</kbd>
    A message appears, indicating that the token renewal is in progress. 

    <kbd>![Renew Token In Progress](./images/renew-token-inprogress.png ':size=75%')</kbd>

1. Refresh the page to get the new token. 



## Remove user groups from a project tool

As a Subscription Admin or a Project Admin, you can remove permissions and roles within a project tool or app for the following tools:
- Confluence
- Jira
- Nexus IQ
- SonarQube

### To remove user groups for your project tool or app

1. Go to **Projects** > **All Projects**.

    <kbd>![All Projects](./images/portal-projects-all-projects.png)</kbd>

1. Navigate to your project, and then click **Manage** on the project tool for which you want to manage/add user groups. 
1. In the **Manage Tool** window that appears, from the dropdown, select **Manage/add user group**. 
1. In the **App Name** and **User Group** fields, select the App and user group for which you want to update permissions or roles.  
1. Next to the permissions or roles that you want to remove, clear the check box, and then click **Update**. 
The permissions or roles are updated.



## Remove project tools

As a Subscription Admin or a Project Admin, you can remove a tool or an app when it is not required. You can remove the following tools: 
- Confluence
- Fortify SCA & WebInspect
- Jira
- Nexus IQ
- SonarQube


### To remove a project tool

1. Go to **Projects** > **All Projects**.
1. Navigate to the project whose tool you want to remove, and then click **Manage**.
1. On the tool that want to remove, click **Manage**.  
    The **Manage Tool** window appears.
1. From the dropdown, select **Remove App**. 
    **Select App to Remove:** appears, displaying a list of apps. 

    ![removetool](./images/removetool.png)

1. Next to the app that want to remove, click **Remove**.  
    The **Remove** window appears.

    ![remove](./images/confirmremove.png)
1. Enter the requested information, and then click **Proceed**.  

    ![proceed](./images/proceed.png)
    The selected app is removed. If this the last app for the tool, the project tool is also removed. 





## Remove applications from a project tool

You can remove app from the following project tools:
- Confluence
- Container Image Scanner
- Fortify SCA & WebInspect
- Jira
- Nexus IQ
- SonarQube

### To remove an app

1. Go to **Projects** > **All Projects**.
1. Navigate to your project, and then click **Manage**.
1. On the tool, click **Manage**.  
    The **Manage Tool** window appears.
1. From the dropdown, select **Remove App**. 
    **Select App to Remove:** appears, displaying a list of apps. 

    ![removetool](./images/removetool.png)

1. Next to the app that want to remove, click **Remove**.  
    The **Remove** window appears.

    ![remove](./images/confirmremove.png)
1. Enter the requested information, and then click **Proceed**.  

    ![proceed](./images/proceed.png)
    The selected app is removed. If this the last app for the tool, the project tool is also removed. 
