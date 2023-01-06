# Manage tokens

**Topics**

- [Retrieve token](#retrieve-token)
- [Renew token](#renew-token)


## Retrieve token

You can retrieve token for the following project tools:  

- Fortify on Demand (FOD)
- Nexus IQ
- pCloudy Device Farm & HATS Browser Farm
- Prisma Cloud
- SonarQube


### To retrieve token

1. From the side menu, click **Projects** to view all the projects in this subscription account.  

    >**Tip:** If needed, [Switch account](manage-account).

1. Click the required project.

    > **Note:** Alternatively, click three dots for more options, and then click **Manage Project**.

1. Click the tool for which you want to retrieve the token, and then click **Manage**.

    The **Manage Tool** window appears.

    > **Note:**
    >- To view the token value for FOD or Nexus IQ, click the eye icon next to **CI Token**.
    >- To retrieve the token for FOD or Nexus IQ, click the copy icon next to **CI Token**.

1. In the **Manage Tool** window that appears, from the dropdown, select **Token & Key for pipeline**.

1. If requested, select the app name/key.

    The token appears under the **Token/Decoded Token ID** field. You can also view expiry date below the token.
    
1. Click the **Copy** button next to the token to copy the token.

## Renew Token

You can renew token for the following tools:
- Fortify on Demand
- SonarQube
- NexusIQ

### To renew an expired token


1. From the side menu, click **Projects** to view all the projects in this subscription account. 

    >**Tip:** If needed, [Switch account](manage-account).

1. Click the required project.

    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
    
1. Click the tool for which you want to renew the token, and then click **Manage**.

    The **Manage Tool** window appears.

    > **Note:** If you are trying to renew the token for NexusIQ, in the **Token** tab, click **Refresh Token**.

1. Click the drop-down arrow, and then choose **Token**. The option may vary based on tool selected.

1. Click **Renew Token**.

1. Refresh the page to get the new token.


<!--
# Manage releases

**Topics**

- [Add release](#add-release)
- [Delete release](#delete-release)

## Add release

This feature is applicable only for FOD.

### To add a release in FOD

1. From the side menu, click **Projects** > **All Projects** to view all the projects in this subscription account. If needed, refer to [Switch account](manage-account).
1. Click the required project.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
1. Click Fortify on Demand, and then click **Release**.

1. Click **New Release**.  
    The **Add New Release** window appears.
1. Enter a unique value in the **Release Name** field, and then select **Add**.  
    >**Note:** You can only use `a-z`, `A-Z`, `0-9`, `(`, `)`, `.`, `-`, and `_` characters for a release name.

    The newly added **Release Name** and **Release ID** appear in the list.


## Delete release

  There must be at least one release version in FOD, the system does not allow you to delete if there is just a single release version.

### To delete a release in FOD

1. From the side menu, click **Projects** > **All Projects** to view all the projects in this subscription account. If needed, refer to [Switch account](manage-account).
1. Click the required project.
    > **Note:** Alternately, click three dots for more options, and then click **Manage Project**.
1. Click Fortify on Demand, and then click **Release**.
1. Click the delete icon corresponding to the release version to be deleted.
    The **Remove FOD Release** window appears.
1. Type *REMOVE* to confirm, and click *Proceed**.
  The release version is deleted from here as well as from the Fortify **Releases** list.
>**Note**: You can reuse the name of the deleted version only after 72 hours.
-->