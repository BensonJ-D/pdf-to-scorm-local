# PDF to SCORM

This is the source code to https://pdf.to-scorm.com, a tool for the simple packaging of PDF files in a SCORM wrapper.

There is no server side code. No NPM modules. No massive javascript frameworks.

The heavy lifting is done by https://github.com/Stuk/jszip and https://github.com/mozilla/pdf.js

# Fork changes

In order to run the site locally, simply find and open the `index.html` file in your web browser (double clicking should open it by default).
Once open, use the first drop box to load the `package.zip` file - this is required as it contains the necessary SCORM spec the PDF will be injected into.

Once the `package.zip` file is loaded, simply load a PDF as normal.

# Licence

MIT + GPL3 dual licence
