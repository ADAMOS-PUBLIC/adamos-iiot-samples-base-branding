# ADAMOS Base Branding

This is the ADAMOS base branding. You can use it as a starting point when developing your own branding.

## How to use the branding

Please refer to the Web developer's guide  for information on how to build and deploy branding plugins: https://docs.adamos.com/guides/web/introduction/

After installing npm and c8y please run the following commands from within then `ADAMOS_CORE` folder:

* `c8y install`  // This will install required dependencies
* `c8y build:plugin branding` // This will build the branding

Now you can upload the branding:

* Go to your tenant, open the Admnistration application and select Own Applications.
* Select _Add application_ / _Clone exsiting application_ / _Cockpit_ / _Clone_
* Edit the newly cloned Cockpit app
* Select the _Plugins_ tab
* Upload the newly created zip-file and open the Cockpit app to see your changes
* If required repeat the steps for the Administration and Device Management application
