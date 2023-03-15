
The following section contains the new features, enhancements, and changes released in February 2023:

| Change/Feature |Description|
|---|---|
|**Pipeline COE**|[Pipeline COE](#pipeline-coe) provides commonly used runner images and is available for use by tenants in the SHIP-HATS Templates. 
|**Portal Enhancements**|<ul><li>**GitLab:** You can now view up to 3 Subgroups/projects and up to 3 levels of depth within each Subgroup/project. If you want to view all Subgroups/projects and all levels, you can do via the GitLab tool.</li><li>**FOD:** You can now rename FOD app and release</li><li>**SonarQube:** You can now refresh SonarQube token.</li><li>**Profile Information:** You can now view project-based information in the **Profile** section.  </li></ul>
|**Security Patching and Update**| <ul><li>Jira</li><li>SonarQube</li></ul>|  
|**Version Upgrade**|For latest supported version of various tools, refer to the [Supported Tools and Versions](https://docs.developer.tech.gov.sg/docs/ship-hats-tools/tools-overview?id=supported-tools-and-versions).|

### Pipeline COE

[Pipeline COE](https://sgts.GitLab-dedicated.com/innersource/projects/sgts-pipelinecoe)* provides commonly used runner images and is available for use by tenants in the SHIP-HATS Templates.
 
#### Key features
- Integration of container scanning in build pipeline to ensure all images in CR are scanned
- Curated by deprecating versions with security vulnerabilities with regular clean ups and scans
- Up to date & patched base images
 

#### Action required
When tenants require an image to define for runners to use, they should look at the available ones in Pipeline COE:

- Use the latest release (i.e. v.1.0.6) of SHIP-HATS Templates available
- Use the latest release (i.e. v1.0.1) of SHIP-HATS Compliance available
- Update pipelines, which use the deprecating pipelinecoe, to use Official Pipeline COE
- If you do not find an image as per your requirement, please raise a service request to SHIP-HATS support
- Refer to [SHIP-HATS Pipeline COE documentation](https://docs.developer.tech.gov.sg/docs/ship-hats-getting-started/pipeline-coe) and [GitLab Pipeline COE documentation](https://Gitlab-org.Gitlab.io/professional-services-automation/pipelinecoe/pipeline-templates/#/).  
 
*Pipeline COE is a GitLab project that aims to build and store images that all logged in users on SHIP-HATS GitLab Dedicated can use. It is an internal project (as opposed to private project), where all logged in users are able to view, raise MRs, and run pipelines on non-protected branches.

<!--

|**Jira - multiple project support** |You can now add more than one project for Jira. For more information, refer to [Manage applications](https://docs.developer.tech.gov.sg/docs/ship-hats-portal/manage-applications) documentation.|
|**FOD Release Management**|You can now add and remove FOD releases via the SHIP-HATS portal. For more information, refer to [Manage releases](https://docs.developer.tech.gov.sg/docs/ship-hats-portal/manage-releases) documentation. |
-->