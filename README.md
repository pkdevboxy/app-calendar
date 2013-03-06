app-calendar
========

A sample application showing how to make RESTful calls to your Document Services Platform (DSP). This app is installed automatically when you create a new DSP. It can be updated or deleted from the Applications tab in the admin app.

calendar.dfpkg - A zip archive containing everything needed to run the app. The system uses this file to create the calendar app at startup. This file can also be imported directly into the Applications section of the admin app.  Importing a package file always creates a new app.  

src - The directory for all source files required for the application.  Normally this will include all HTML, JavaScript, and CSS.

src.zip - A zip archive of the src directory.  You can import this file from the Applications section of the admin app to update just the source code for your app.

data.json - Sample table rows to be created when importing the app as a package file. This file is optional.

description.json - Application properties to be used for creating a new application when importing the app as a package file.

schema.json - Application schema to be created when importing the app as a package file. This file is optional.
