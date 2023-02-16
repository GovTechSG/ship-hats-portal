# SHIP-HATS to GitLab

## Access SHIP-HATS Portal

### To access the SHIP-HATS portal

1. Go to the [SHIP-HATS portal](https://portal.ship.gov.sg/).
1. Click **Login with TechPass**.

1. If you are a **new user**:
    1. Enter your **Enter your TechPass details**, and then click **Next**.  
        You will be redirected to the GCC log-in page. 
    1. Enter your TechPass email address along with the verification code from the Authenticator app, and then click sign in. 

    5. Read through the **TechPass** Terms of Use, and then click **Accept**.

    6. Read through the **TechPass MDM** Terms of Use, and then click **Accept**.
1. If you are an **existing user**, select your TechPass account.  
1. Under your name, select **Switch account**, and then select the account that you created in TechBiz.  

    You have successfully linked your TechPass to SHIP-HATS. You can directly log in using TechPass for future access.  

    The **Overview** page appears, providing the dashboard view of the subscription account. 

    <kbd>![Dashboard](./images/dashboard.png)</kbd>    

## Verify Users and System (s)

Subscription Admin (SA) and Project Admin (PA) can view all users associated with a subscription account and their roles in their account if the users were added in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/).

### To view users

1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).  

   > **Tip:** Make sure that you are in the required account. 

1. From the side menu, click **Users > All Users**.  

   A list of users appears, along with following details:

   >**Note:** Users will appear here only if they were added in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/).

   ![View all users](./images/users-all.png)

   |Column|Description|
   |---|---|
   **Name**|Indicates the name of the user. <br>If *First Name* and *Last Name* were not provided when creating a new user account, only email address will appear in this column.<br>If a user is a Subscription Admin, it is indicated by the label **Subscr Admin** beside the username.
   **Project Role**|Indicates whether a user is a Project Admin.
   **GitLab**|Indicates whether the user is consuming GitLab tools quota from the current subscription. The quota consumed/quota available is indicated at the top of the screen. For example, *5 / 8 GitLab quota consumed.* 
   **Jira/Confluence**| Indicates whether the user is consuming the Jira/Confluence tools quota from the current subscription. The quota consumed/quota available is indicated at the top of the screen. For example, *1 / 3 Jira/Confluence quota consumed.*
   **Sonatype**|Indicates whether the user is consuming Sonatype tools quota from the current subscription. The quota consumed/quota available is indicated at the top of the screen. For example, *1 / 1 Sonatype quota consumed.*
   **Last Login**|Indicates the date and time when the user logged in the last time. The time indicated is based on data captured until the daily scheduled job runs.


## Create Project

Subscription Admin (SA) can create new projects in SHIP-HATS.

### To create a new project

1. From the side menu, click **Workspace**.
    
    The **Systems** screen appears, displaying all the systems added to your subscription.

    ![view systems](./images/view-systems.png)

1. Select the System to which you want to add a project. 

    The **Projects** screen appears, displaying all the previously added projects. 

    ![all projects](./images/view-projects.png)

1. Click **Create Project**.  

    ![create project](./images/create-new-project.png)

1. Provide information in the following fields:

    |Field|Description|
    |---|---|
    |**Project Name**| Specify name of the project. Your agency name is prefixed to the project name automatically. 
    |**Project Description**| Specify details of the project. 
    |**Project Admin 1**| Select Project Admin from the drop-down list. Users will appear here only if they were added in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/).<!--If you want to invite new users, click **Invite here**. If *First Name* and *Last Name* were not provided when creating a new user account, email address will appear in the drop-down list.-->
    |**Project Admin 2**| This is an optional field. Select a second Project Admin from the drop-down list. Users will appear here only if they were added in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/).<!--If *First Name* and *Last Name* were not provided when creating a new user account, email address will appear in the drop-down list.--> 
1. Click **Create Project**.  
    
    A message appears, indicating **Project Created Successfully**. The created project appears on the **Projects** screen.

    ![Projects](./images/projects-all.png)


## Assign Project Admins

Subscription Admins can add Project Admins using the SHIP-HATS portal. When creating a project in an account, it is mandatory to specify at least one Project Admin. SAs can add additional PAs anytime in the future.  

### To add a project admin


1. From the side menu, click **Workspace**.

    > **Tip:** 

    The **Systems** screen appears, displaying all the systems added to your subscription.

    ![view systems](./images/view-systems.png)

1. Select the System. 

    The **Projects** screen appears, displaying all the previously added projects. 

    ![all projects](./images/projects-all.png)

1. Locate the project for which you want to add a Project Admin, and then click three dots for more options.

    ![more options](./images/projects.png)

1. Click **Manage Admins** > **Add New**.  

    ![manage admins](./images/project-admins.png)

1. In the **Select Admin** drop down list, select the required user.

    >**Note:** Users will appear here only if they were added in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/). <!--If *First Name* and *Last Name* were not provided when creating a new user account, email address will appear in the drop-down list.-->

    ![select admins](./images/project-admins-add.png)

1. Click **Add** to add this user as a project admin.  
   
   After a user is successfully added, an email notification will be sent to the requesting SA with copy sent to other SA and the newly added PA.


## Add GitLab

SA or PA can add the tools (GitLab and add-ons) under the **Subscribed Tools** section based on the tools subscribed in the [TechBiz portal](https://portal.techbiz.suite.gov.sg/).  

### To add tools

1. From the side menu, click **Workspace**.
    
    The **Systems** screen appears, displaying all the systems added to your subscription.

    ![view systems](./images/view-systems.png)

1. Select the System for which you want to view projects. 

    The **Projects** screen appears, displaying all the previously added projects. 

    ![all projects](./images/projects-all.png)

1. Locate the project to which you want to add a tool, and then click the project.

    **Project Description** screen appears, displaying the **Subscribed Tools** that the SA added in the TechBiz portal. You can also view **Not Subscribed Tools** that SA can subscribe via the TechBiz portal.

    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.

    ![Project description](./images/project-description.png)

1. Locate the tool that you want to add, click **Create**, and follow the specific steps in table for the tool that you want to add.

    |Available Tools (Base)|Steps|
    |---|---|
    |**GitLab**|Make sure that at least 1 Project Admin has a GitLab account and is added to the TechPass group. Provide value in the **GitLab Group Name** field. <!--<br>If you cannot find your system in the drop-down list, follow the steps to [Declare a DGP System](declare-dgp-systems).--> <br><br>![Add GitLab](./images/tool-gitlab-add-new.png)
    |**Nexus IQ**|Provide values in the **Application Name** and **Application ID** fields.|
    |**Nexus Repo**|Submit a [service request](https://jira.ship.gov.sg/servicedesk/customer/portal/11/) to add this tool.
    |**pCloudy**|The **Add New pCloudy Application** popup appears, displaying the allowed number of parallel shared mobile device tests.|

    |Available Tools (Add-ons)|Steps|
    |---|---|
    |**Confluence**|Make sure that you have subscribed to this product via the TechBiz portal for it to be listed in **Subscribed Tools**. Provide value in the **Project Name** field. <br><br>![](./images/tool-confluence-add-new.png)
    |**Fortify on Demand**| Make sure that you have subscribed to this product via the TechBiz portal for it to be listed in **Subscribed Tools**. Provide value in the **Application Name** and **Release name** fields.<br>**Release name** is an optional field.<br><br> ![](./images/tool-fod-add-new.png)   
    |**Jira**|Make sure that you have subscribed to this product via the TechBiz portal for it to be listed in **Subscribed Tools**. Provide value in the **Project Name** field.<br><br>![](./images/tool-jira-add-new.png)
    |**Prisma Cloud**|Make sure that you have subscribed to this product via the TechBiz portal for it to be listed in **Subscribed Tools**. Provide value in the **App name** field.|
    |**SonarQube**|Make sure that you have subscribed to this product via the TechBiz portal for it to be listed in **Subscribed Tools**. Make sure that you have logged in to [SonarQube Community Edition](https://sonar.hats.stack.gov.sg/sonar) or [SonarQube Developer Edition](https://sonar1.hats.stack.gov.sg/sonar) at least once. provide values in the **Application Type** and **App Name** fields.<br><br>![](./images/tool-sonarqube-add-new.png)

    >**Note:** After you reach the quota, the respective tool name(s) will be disabled in the **Select Tool** drop-down list. If you still want to add these tools, send an email to [enquiries_ENP@tech.gov.sg](enquiries_ENP@tech.gov.sg).    

1. Click **Add**.   
    
    The selected project tool (GitLab in our example) is added.

    ![GitLab added](./images/gitlab-added.png)    

## Verify User Mapping

### To verify user mapping

1. In the [SHIP-HATS portal](https://portal.ship.gov.sg/), click GitLab group.

    ![GitLab added](./images/gitlab-added.png)    

1. In the GitLab tool, click **Subgroup information** > **Members**.

    ![GitLab members](./images/gitlab-members.png ':size=50%')

    The **Group members** screen appears. 

    ![GitLab Group Members](./images/gitlab-group-members.png)

1. Verify that all your users added in the selected Group appear. 

    If you want to **add additional users**:

    1. Click **Invite Members**.

    ![Invite Members](./images/gitlab-invite-members.png ':size=80%')

    1. Provide values in the **Username or email address** and **Select a role** fields, and then click **Invite**. 

## Set up SSH keys

In GitLab, each developer must [Use SSH keys to communicate with GitLab](https://docs.gitlab.com/ee/user/ssh.html).

## Set up GPG keys	

In GitLab, each developer must [Sign commits with GPG](https://docs.gitlab.com/ee/user/project/repository/gpg_signed_commits/).
