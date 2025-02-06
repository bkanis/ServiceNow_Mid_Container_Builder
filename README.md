# Automated Mid-Server Build

## For automated Build :
1.  Install "Mid-Server AutoBuild" application from this Repo on the desired instance.
    - Setup a Basic Auth Credential in Servicenow using your git user name and [api key](https://repo.kanis.dev/user/settings/applications).
        - Only needs Repo Read/Write.
    - Pull this repo with Developer Studio.
    - Apply remote changes.
2.  Navigate to Mid-Server AutoBuild > Create Credentials
    - Create a credentials record with your git user name and [api key](https://repo.kanis.dev/user/settings/applications). 
    - Note the *Name* of the credential record for later. 
3.  Navigate to Mid-Server AutoBuild > Properties
    - Set the correct repo URL
    - Set Name of Basic auth Credential to Same as named in Step 2.
# TODO
- Some sort of build now button

## To build Manually from Repo:
- Create Tag from instance mid.version system property.
- https://<instance>.service-now.com/sys_properties_list.do?sysparm_query=name%3Dmid.version&sysparm_view=
(e.g. washingtondc-12-20-2023__patch1-02-28-2024_03-09-2024_0815)