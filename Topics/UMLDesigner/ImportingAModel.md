### Context
 * MacOS Mojave (10.4.5)

### First steps
 * Dowload the installer from the [Download page](http://www.umldesigner.org/download/)
   ```bash
   $ wget https://s3-eu-west-1.amazonaws.com/obeo-umldesigner-releases/9.0.0/bundles/UMLDesigner-macosx.cocoa.x86_64.zip
   ```
 * Dowload some UML model e.g. the [CityGML 3.0](https://github.com/opengeospatial/CityGML-3.0CM/blob/master/Conceptual%20Model/CityGML_3.0_Consolidated_Draft.eap)
 
We then follow the [Importing an UML model tutorial](http://www.umldesigner.org/tutorials/tuto-import-model.html)
 * first switch to the modeling perspectiv
 * then "Create the project"
   - Note: after providing a project name (say `MyImportTest`), if you mistakenly hit the Finish button (instead of the tutorial indicated Next button) then UMLDesigner will freeze eventually constraining you to ["force quit"](https://support.apple.com/en-us/HT201276) (kill) the application.
     If, later on, you try to create a project with the same name (`MyImportTest` in this example) then you will be prevented from doing so with a message of the form `A project with that name already exists in the workspace.` 
