# CS443-Project
Photo editor and uploader with GPS android application
For running the app 
• Start MySql and create a database named pilla then load all the tables from db.zip.
• Load server code from JSP JAVA.zip to eclipse and then run any file as server from web content folder(right click -> run as server) with tomcat so you can check jsp pages are running
• load android program from Android.zip in android studio
• your java server and android emulator or device should be on same network
• Get your pc’s IP address(go to command prompt - run ipconfig command then take IPV4 address) and you have to put that in your android code
• In android code in Android studio change IP address in file  "Project chovatiya/hinali/myapplication/global/AppUrl.java" AS
public static String mainLink = "http://192.168.0.101:8080/WebService/"; at here.
• we can run the application from Android studio to emulator or device.
