
The following section contains the new features, enhancements, and changes released in March 2023:

| Change/Feature |Description|
|---|---|
|**SHIP-HATS Portal Enhancements**|<ul><li>**Left Navigation:** You can now view **Projects without system** under **Workspace**. </li><li>**Fortify on Demand:** You can now [renew FOD token](https://docs.developer.tech.gov.sg/docs/ship-hats-portal/manage-tokens) and [remove FOD app](https://docs.developer.tech.gov.sg/docs/ship-hats-portal/manage-applications).</li><li>**Unsubscribed tools:** If you are a SHIP-HATS 1.0 user and want to remove the tools that you have not subscribed in TechBiz, you can [use the SHIP-HATS Portal](https://docs.developer.tech.gov.sg/docs/ship-hats-portal/manage-tools) to remove the **Unsubscribed tools**.  </li><li>**Workspace UX:** The Workspace UX has been enhanced to display Systems and Projects in a tabular format. You can choose to view the projects list in a Card view or Table view.</li></ul>
|**Extended Code Analysis (XCA)**|[Extended Code Analysis (XCA)](#extended-code-analysis-xca) has been integrated with SHIP-HATS 2.0 GitLab Dedicated platform. 
|**Security Patching and Update**| <ul><li>Confluence</li><li>Jira</li><li>Nexus IQ</li><li>Nexus Repo</li><li>SonarQube</li></ul>|  
|**Version Upgrade**|For latest supported version of various tools, refer to the [Tools > Supported Tools and Versions](https://docs.developer.tech.gov.sg/docs/ship-hats-tools/tools-overview?id=supported-tools-and-versions).|

### Extended Code Analysis (XCA)

In line with the CSG advisory sent earlier, [Extended Code Analysis (XCA)](https://www.developer.tech.gov.sg/products/categories/cybersecurity/xca/overview.html) has been integrated with SHIP-HATS 2.0’s GitLab Dedicated Platform.  XCA is an augmented security testing tool that help users detect source code vulnerabilities that are common across the government.

From 10 Mar 2023, XCA will be enabled by default on all pipelines. Since XCA is added as a required pipeline configuration in SHIP-HATS 2.0 GitLab, no configuration action is required from tenants (refer to [SHIP-HATS documentation](https://docs.developer.tech.gov.sg/docs/ship-hats-getting-started/ship-hats-tools) for more details). To review the XCA findings, refer to the Vulnerability Report (**GitLab** > **Security & Compliance** > **Vulnerability Report**) in GitLab.  

<!--
|**SHIP-HATS Portal Enhancements**|<ul><li>**Left Navigation:** You can now view **Projects without system** under **Workspace**.</li><li>**FOD:** </li><li>**Unsubscribed tools:** If you are a SHIP-HATS 1.0 user and want to remove the tools that you have not subscribed in TechBiz, you can [use the SHIP-HATS Portal](https://docs.developer.tech.gov.sg/docs/ship-hats-portal/manage-tools) to remove the **Unsubscribed tools**.  </li></ul>

-->