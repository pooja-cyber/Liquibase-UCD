# Liquibase plug-in for IBM UrbanCode Deploy [![Build Status](https://travis-ci.org/IBM-UrbanCode/Liquibase-UCD.svg?branch=master)](https://travis-ci.org/IBM-UrbanCode/Liquibase-UCD)
---
Note: This is not the plug-in distributable! This is the source code. To find the installable plug-in, go to the plug-in page on the [IBM UrbanCode Plug-ins microsite](https://developer.ibm.com/urbancode/plugins).

### License
This plug-in is protected under the [Eclipse Public 1.0 License](http://www.eclipse.org/legal/epl-v10.html)

### Overview
Liquibase is open source command line tool that run database deployment and rollbacks. It supports all major database types: DB2, Oracle, MSSQL, MySQL, PostgreSQL, Sybase, Informix, etc. Liquibase uses database change log files to run all db commands (same strategy that DBUpgrader is using). Change logs can be described in many different formats. I usually prefer XMLs or SQLs.  You can read about all Liquibase functionality here http://www.liquibase.org/. This plug-in enables you to utilize Liquibase's cli tool through IBM UrbanCode Deploy.

### Documentation
View the /doc folder for a details on the Liquibase plug-in's steps.

### Support
This plug-in is an open source project supported by the IBM UrbanCode Development Community. Installable plug-ins are available in the releases tab. Create a GitHub Issue or Pull Request for minor requests and bug fixes. Plug-ins built externally or modified with custom code are supported on a best-effort-basis using GitHub Issues.

### Locally Build the Plug-in
This open source plug-in uses Gradle as its build tool. [Install the latest version of Gradle](https://gradle.org/install) to build the plug-in locally. Build the plug-in by running the `gradle` command in the plug-in's root directory. The plug-in distributable will be placed under the `build/distributions` folder.
