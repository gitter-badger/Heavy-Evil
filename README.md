# Heavy-Evil
Application/Web Forum/MMORPG Template


SDK's currently used in project development.

JOGL 2.3,
MySQL,
Spring 4.4,
JRE and JDK 1.8 System Library(Java SE 8),
JSoup1.8.3,
Maven 3+

  You're going to need to install the JDK's and use Maven SDK exclusively via the command line using cd terminal or linux command prompt calls to increase performance later in the development process. You only need to add the external jar files and create an Images folder within the project for your image sources. You can use any image but you will have to update the file name within the code.  

  The project is an open source game template for Java developers who want to build a fully functional OpenGL based application or game that will eventually be connected to a forum using Java Servlets and JSP(refer to the webpage). Portable to DirectX, and with some work and an XBOX One or PS4 development kit, it can be used to create console games as many are based in OpenGL, with the addition of many mainstream graphics programs. I plan to also incorporate Microsofts Kinect technology, the Hololens when it's development kit becomes available on the market outside of it's early development phases as well as the ALICE Bot most likely using node.js api. 

Major Updates:

-Removed Maven from project. I would identify it as a rogue virus. To remove it, right click on the project and then Maven-->Disable Maven nature, then you will need to edit in your Build Path, go to the sources tab and remove the target output folders, renaming the output folder to Heavy Evil/bin and hit okay. Then you will be allowed to delete the target folder, which reduplicates itself after delete and cannot be deleted from within the system. An incorrect build will corrupt all of your files. 
