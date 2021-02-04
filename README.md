# Northwind SAPUI5 Web App #

A small test app that uses the public OData service, SAPUI5, and SAPUI5 design guidelines.

### SAPUI5 ###

* Requires a license to SAP. Use openUI5 otherwise

### Chrome Note ###

Since the northwind OData service is served over HTTP, Chrome will not allow sites hosted over HTTPS to load the data.

* Run chrome in a separate user profile with --web-security-disabled command

### Contribution guidelines ###

* Stay within SAPUI5 Fiori design guidelines
* Use XML views only
* Use SAPUI5 components only
* Use OData only
* Use publicly available data only

### To learn about SAPUI5/openUI5 ###

* https://sapui5.hana.ondemand.com/
* https://openui5.hana.ondemand.com/

# JM Info: 04.02.2021

# UI5 Tooling
* https://sap.github.io/ui5-tooling/

# In your project
* npm init
* npm install --save-dev @ui5/cli
* npm install ui5-middleware-simpleproxy --save-dev
* ui5 init
* Check ui5.yaml, package.json -> ui5-middleware-simpleproxy
* Proxy in manifest.json in "dataSources" eintragen
* ui2 serve -h2




