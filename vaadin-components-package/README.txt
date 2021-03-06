

This is the Grid demo project for Vaadin X .

- Assuming you have installed maven, compile and package it just running:
$ mvn clean package

- Run it in development mode (superdev):
$ mvn gwt:run
and point your browser to http://127.0.0.1:8888/index.html

- Import and run in Eclipse:

 The archetype generates a project ready to be used in eclipse, 
 but before importing it you have to install the following plugins:

    * Google plugin for eclipse (Available in marketplace)
    * Sonatype Maven plugin (Normally installed by default with Eclipse)

 Then you can import the project in your eclipse workspace:

    * File -> Import -> Maven -> Existing Maven Projects

 Finally you should be able to run the project in development mode and to run the gwt test unit.

    * Right click on the project -> Run as -> Web Application
    * Right click on the test class -> Run as -> GWT JUnit Test 

- If you prefer maven to generate your eclipse files you could run either:

$ mvn eclipse:m2eclipse  (if you like to use m2eclipse)
$ mvn eclipse:eclipse    (to use the project without m2eclipse)

 Then you can import the project in eclipse in the normal way

   * File -> Import -> General -> Existing Projects into Workspace

- In the folder eclipse there are a couple of launchers you can use in eclipse to launch 
  GWT dev and superdev modes.
