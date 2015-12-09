# wfs_service_info
Angular app used to query WFS endpoints

***
*You will need to have node installed in order to run the application*

####Running####
1. Navigate to the root of the project
2. ```npm install```
3. You will need a web server to run the application: ```http-server ```
4. Enter a test WFS URL (endpoint): ```http://demo.boundlessgeo.com/geoserver/wfs```
6. Click the "Get Info" button.  This will conduct a *GetCapabilities* on the WFS
7. Select an item from the Feature Type list.  This will conduct a *DescribeFeature* and a *GetFeature* on the WFS

Optional:

1. You can pass a CQL filter to the WFS by using the CQL Filter input
``` Ex: STATE_NAME='Indiana' ```
2. You can also change the amount of features returned by using the "Max Features" input
