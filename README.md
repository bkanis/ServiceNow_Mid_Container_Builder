# Automated Mid-Server Build

## For automated Build :
- Install "Mid-Server AutoBuild" application from this Repo on the desired instance.
- Navigate to the "mid.version" system property and update the Descript to "build_now" to start immediately.
- Builds will be created as instance is upgraded and system property changes.
##TODO
- Property page
- Change endpoint
- Some sort of build now button

## To build Manually from Repo:
- Create Tag from instance mid.version system property.
- https://<instance>.service-now.com/sys_properties_list.do?sysparm_query=name%3Dmid.version&sysparm_view=
(e.g. washingtondc-12-20-2023__patch1-02-28-2024_03-09-2024_0815)