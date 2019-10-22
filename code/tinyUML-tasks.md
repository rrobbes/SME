# Tasks for TinyUML

To build tinyUML, simply use ant: `ant run`, or use the relevant option in your IDE. The build file is `build.xml`. 

### Class counter

Implement a class counter on the status bar of the application. The counter should update whenever new UML classes are added or deleted from the diagram.

### Check connections

In TinyUML, it is impossible to make an "interitance" connection when one of the elements is a Note. However, it is perfectly possible to make a Package inherit from a Class, or a Class from a Component. Make it so that these connections are not allowed anymore.

### Remove empty methods

When a UML class has methods, it is possible to delete the entire method signature of a method, which cause the appliation to display a blank method instead of removing the empty line. Make it so that blank lines are automatically removed.

