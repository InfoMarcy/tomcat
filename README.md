https://www.dev2qa.com/how-to-install-tomcat-in-macos/

1. Install Apache Tomcat In MacOS Steps.

Then run below command to make the .sh file executable.
sh-3.2# cd /Users/desarrolladorios1/tomcat

sh-3.2# sudo chmod +x ./bin/*.sh

Now all the .sh file in tomcat bin directory is executable, you can run ls -al command to see that.
now run ./bin/startup.sh to start tomcat. When you see below message, it means tomcat has been started successfully.
sh-3.2# ./bin/startup.sh 

Now open a web browser, input http://localhost:8080/ in the url address input box. Click enter then you can see below web page.
