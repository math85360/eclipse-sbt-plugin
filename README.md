This project is built using Eclipse Tycho (https://www.eclipse.org/tycho/) and requires at least maven 3.0 (http://maven.apache.org/download.html) to be built via CLI. 
Simply run :

    mvn clean package


Steps to install in eclipse.

* Install sbt in windows/unix
* Install scala-ide plugin in eclipse
* Install sbteclipse https://github.com/typesafehub/sbteclipse  Now sbt eclipse should work from command prompt/shell

This plugin hooks into eclipse and developer can run it from eclipse itself.

* Install new software and with update site or newly build update.zip from this source code
* Edit "Sbt" in preferences page.

Now "sbt eclipse" is invoked automatically to listening to any changes in conf files and will refresh eclipse.
Also you can run any sbt commands from eclipse.

