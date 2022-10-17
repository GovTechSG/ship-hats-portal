# Manage Users

**Topics**

- [View users](#view-users)
- [Generate user report](#generate-user-report)
- [Manage access](#manage-access)
- [Reactivate users](#reactivate-users)
- [Remove users](#remove-users) 


## View users

Subscription Admin (SA) and Project Admin (PA) can view all users associated with a subscription account and their roles in your account.

### To view users

1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).  
   Make sure that you are in the required account. If needed, refer to [Switch account](manage-account).

1. From the side menu, click **Users > All Users**.  
   A list of users appears, along with following details:  
   |Column|Description|
   |---|---|
   **Name**|Indicates the name of the user. <br>If *First Name* and *Last Name* were not provided when creating a new user account, only email address will appear in this column.<br>If a user is a Subscription Admin, it is indicated by the label **Subscr Admin** beside the username.
   **Project Role**|Indicates whether a user is a Project Admin.
   **Quota consumed**|Indicates whether the user is consuming quota from the current subscription. <ul><li>If user is not consuming quota of the subscription, a tag **free user**, appears beside the name. When you hover over the tag, you can view the billing subscription under which the quota is being consumed.</li></ul>   
   **CI**| Indicates whether the user is consuming the CI tools quota from the current subscription. 
   **Sonatype**|Indicates whether the user is consuming Sonatype tools quota from the current subscription.
   **Last Login**|Indicates the date and time when the user logged in the last time. The time indicated is based on data captured until the daily scheduled job runs.
   **Action**|Enables you to [Manage access](#manage-access) and [Remove User](#remove-users).

   <!--<kbd>![all-users-new](./images/all-users-new.png ':size=100%')</kbd>-->

   You can perform following additional functions on this screen:
   - **Sort:** You can sort this list in ascending or descending order by one of the following options:
      - Name
      - Project Role
      - CI
      - Sonatype
      - Quota consumed  
      - Last Login
    - **Search:** You can quickly search for a user by typing the username in the search box.

       <!--<kbd>![search_user](./images/export-csv.png ':size=100%')</kbd>-->
    - **Download:** If you want to download the user list as a .csv file to your local machine, click **Export CSV**. This csv lists the active and removed users along with the approval and removal details. For more details, refer to the [Generate User Report](#generate-user-report) documentation.

## Generate user report
You can generate a report to view all details for the active and removed users.

### To generate a user report
1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).   
   Make sure that you are in the required account. If needed, refer to [Switch account](manage-account).
1. From the side menu, click **Users > All Users**.

   <!--<kbd>![all-users-new](./images/all-users-new.png ':size=100%')</kbd>-->
1. Click **Export CSV**.  
   The CSV report is downloaded to the your machine with the following details:

   |Field|Description|
   |---|---|
   **Username**|Indicates the username for the user
   **Name**|Indicates the full name of the user
   **Email**|Indicates the email address of the user
   **Subscription Admin**|Indicates whether the user is a Subscription Admin. 
   **Project Role**|Indicates whether the user is a Project Admin.
   **Quota consumed**|Indicates whether the user is consuming quota from the current subscription.  
   **CI Quota Consumed**|Indicates whether the user is consuming CI tools quota from the current subscription. 
   **Sonatype Quota Consumed**|Indicates whether the user is consuming Sonatype tools quota from the current subscription. 
   **Last Login**|Indicates the date and time when the user logged in the last time.
   **Status**|Indicates whether the user is active or removed.
   **Approved Date**|Indicates the date when the user was approved.
   **Approved By**|Indicated the name of the SA or PA who approved the user.
   **Removed Date**| Indicates the date when the user was removed.
   **Removed By**|Indicates the name of the SA or PA who removed the user.
   **Removal Reason**|Indicates the reason for removal of a user as entered by the SA or PA

## Manage access

### To manage access for a user

1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).   
   Make sure that you are in the required account. If needed, refer to [Switch account](manage-account).

1. From the side menu, click **Users > All Users**.

   <!--<kbd>![all-users-new](./images/all-users-new.png ':size=100%')</kbd>-->

1. Search for the user whose access you want to manage. 
1. From the **Action** column, click ![3 dots](./images/3_dot.png) corresponding to the user.  
1. Select **Manage Access**, and then select the tools that you want to enable for the user. Following options are available: 
   - **CI tools:** Select this option if the user is required to have access to Jira, Confluence, Bitbucket, Bamboo, pCloudy, SonarQube, Fortify SCA & WebInspect, Fortify on Demand, and Prisma Cloud services.
   - **SonaType tools:** Select this option if the user is required to have access to Nexus IQ and Nexus Repo Scan services.

      ![manage-access](./images/manage-access.png ':size=80%')

1. Click **Proceed**.  
   A confirmation message appears, indicating that the user will receive an email regarding the change. 

   >**Notes:**
   >- You will be able to update access only if the numbers of users align with the approved tools quota for the users.
   >- The Proceed button is enabled only when there is a change to the existing selection.
   >- A PA or SA user will be able to update their own access.
   >- You will not be able to proceed if both the options are cleared.



## Reactivate users

If SHIP-HATS users are inactive for 60 consecutive days, their status changes from **normal user** to **sleeping user**. If the user continues to be inactive, from day 81 onwards an email notification is sent every day to the user until user becomes active (**normal user**) or until it reaches day 90.  

On day 91, if the user is still inactive on SHIP-HATS, user status changes from **sleeping user** to **suspended user**, indicated by a grey avatar.  

<!--<kbd>![profile-legends](./images/profile-legends.png ':size=100%')</kbd>-->

<!--SA and PA can reactivate a suspended user back to their account if required.-->

### To reactivate a user

If you are **a TechPass user**, the SA can raise a service request using the [TechPass Support form](https://form.gov.sg/#!/5f69797d0666cb0011cc59da). It will take 1-3 business days to process the service request.

If you are **not a TechPass user**, the SA or PA can complete the following steps to reactivate a user:

1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).  
   Make sure that you are in the required account. If needed, refer to [Switch account](manage-account).  
1.  From the side menu, click **Users > All Users**.  
1. Search for the user to be reactivated and from the **Action** column, click ![3_dot](./images/3_dot.png) corresponding to the user.  

   <!--<kbd>![user_status_2](./images/user_status_2.png ':size=100%')</kbd><br />-->
   
   > **Tip:** Refer to [Viewing users](#view-users) to know how to search for users  
1. Choose **Reactivate User**. User, SAs and the requestor will be notified through an email about the reactivation.  

   >**Notes:**
   >- Though the reactivated user can log in using the existing credentials, we recommend reactivated users to reset their password. The email sent to the reactivated users includes the link to reset their password.  
   >- After a user has been reactivated, an email notification about this reactivation is sent to the requestor and the SAs.

## Remove users

We recommend Subscription Admin (SA) and Project Admin (PA) to periodically review the named users in their account, consumed user quota and remove users who are no longer required.

>**Notes:**
>- You can remove a user who does not have the Project Admin or Subscription Admin roles in the subscription account.
>- You can remove a user that is added to the billing subscription (quota consumed) only.
>- You can remove a user from a subscription if the user is not consuming quota from the current subscription (labeled as **free user**). However, you cannot remove a user consuming quota from current subscription if the user is also included in another subscription.
>- You cannot remove a user from a billing subscription (quota consumed) if the user is also added to another subscription (quota not consumed and labeled as **free user**). 

### To remove a user

1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).   
Make sure that you are in the required account. If needed, refer to [Switch account](manage-account).
1. From the side menu, click **Users > All Users**.
1. Search for the user to be removed and from the **Action** column, click ![3_dot](./images/3_dot.png) corresponding to the user.
   >**Tip:** Refer to [View users](#view-users) to know how to search for users and to sort by **Quota Consumed**.

   <!--<kbd>![remove_user](./images/remove-users-2.png ':size=100%')</kbd>-->

1. Choose **Remove User**.

### Related Topics
- [Manage user groups](manage-user-groups)
- [Manage user groups & users](manage-user-groups-and-users) 