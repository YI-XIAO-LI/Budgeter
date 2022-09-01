Please use your Eclipse workspace for PA2 grading.

Open Eclipse -> File -> Open Projects from File System -> Select archive file -> Browse the zip we sumbit and only import the final project. If you are using the workspace for PA2 grading, this should be working. 

However, if it doesn't work for some reason, create a new server based on your tomcat server, right click on the created server, then go to Show in -> System Explorer, and the server directory will open. Unzip our submission zip manually, go into the server folder in that unzipped folder, and copy the "Tomcat v9.0 Server at localhost-config" folder into your server folder in the new workspace.

If there are still errors, right click the project -> Properties -> Java Build Path -> Double click Server Runtime -> Choose the runtime and finish. If the first line of jsp files give errors showing that "The superclass "javax.servlet.http.HttpServlet" was not found on the Java Build Path", please make sure that you are using the jdk-14.0.2. Go to Properties -> Java Build Path -> Libraries -> JRE System Library -> Edit... -> Choose Workspace default JRE (jdk-14.0.2). And the errors should go away.

You can now start to use the Budgeter!

Note: Although the sql script is provided, you are not able to use it and there should be no need to use it, since we keep our database on cloud. This file only aims to show you the basic structure of our database. You may ignore it.