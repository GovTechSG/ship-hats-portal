If you are a Subscription Admin (SA), you can off-board your subscription account after the trial period has lapsed or project is coming to an end. 

### Prerequisites
- Take backup of your data.
- Plan to complete the steps at least one week before the off-boarding date.
- Inform your users that they will not have access to tools after the off-boarding date.


### To off-board an account

<!--1. Log in to the [SHIP-HATS portal](https://portal.ship.gov.sg/).--> 

1. Select an expected date to off-board. 

    - For a subscribed account, there is a minimum commitment of 6 months stated in the service sheet. Therefore, you will be allowed to select a date after fulfilling the 6 month period only.
    - If you are on a trial account, you can select a date of your choice to off-board the account.

1. After you have a confirmed date, [create a service request](https://docs.developer.tech.gov.sg/docs/ship-hats-support/raise-service-request) with following details:  

    - In the **Title** field, add the title in the following format: `[REQUEST TO OFF-BOARD] AgencyName - BillingRef - SubscriptionTitle`
    - In the **Description** field, provide the following details: 
        - Expected date to off-board
        - Users list (including SA & PA)
        - Project title & project key for Jira/Confluence/BB/Bamboo
        - Fortify app name
        - SonarQube app name
        - PrismaCloud app name
        - Text box to capture Sonatype app name
        - Master billing crowd/ldap group name  

    You will receive an email confirmation with further details. 

**After you have raised the service request for off-boarding, note the following behavior:**
- When SA or PA logs in to the SHIP-HATS portal, in the **Alerts** section, you will see a termination message.
- Tools cannot be added
- Changing the PA function is disabled 
- User invitations are disabled 
- After the termination date, SA or PA will not be able to view the subscription details for the off-boarded account. However, if SA or PA have other subscription accounts, they will continue to view details for these additional subscriptions accounts.
