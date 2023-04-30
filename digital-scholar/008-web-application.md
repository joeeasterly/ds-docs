---
chapter: 1.7
---
### 1.7.What Exactly is a Web Application? #

In the most general terms, a Web application is a piece of software that runs on a Web server. A Web server is a just a specialized computer designed to host Web pages.

Most Web applications are comprised of two components: files and a database. When you install a Web application, you will need to make sure all of the files are copied over into the appropriate location AND that a database (and database user) has been set up to connect to those files. Often, you will have to do some configuration to make sure the application knows how to access the database.

The system we use for University of Rochester uses a special script installer called [Installatron](http://installatron.com/) (in cPanel) that allows you to automatically [install dozens of open source applications](http://www.stateu.org/docs/uncategorized/applications-available-in-installatron/). When you use Installatron, you don’t need to worry about moving files, creating databases, or doing the initial configuration. It’s all taken care of for you.

In order to run on the University of Rochester server, Web applications must be able to run on a LAMP server, which is the particular kind of Web server that we use. Occasionally, a Web application may require additional components or modules that need to be installed on the server.

[comment]: # (feedback link here)