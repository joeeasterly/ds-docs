
---
chapter: 1.9
---
### 1.9.LAMP Environments #

When you sign up for an account on Stateu.org, you get a personal space our web host. There are a few things you need to know about the Web host that will make it easier to understand what you can do with your new space.

The Web Server
--------------

The Web server is the main computer that is associated with the digitalscholar.rochester.edu hosting account. It is literally a computer that has special software on it that allows it to be accessible via the Web. The files that run your applications, images, video, or any other files you upload into your Web space are stored on this server.

(For comparison’s sake, your desktop or laptop computer, by default, doesn’t allow this; I can’t access files on your computer through a Web browser by default. You _can_ actually install Web server software on your own computer, however, essentially making your files accessible over the Web.)

In order to run properly, a Web server has to have an operating system installed _and_ some kind of Web server software. Our University of Rochester hosting environment runs the `LINUX` operating system and an `APACHE` Web server.

The Database Server
-------------------

In addition to the Web server, there is also an associated database server. This is another computer, but it is configured with software that allows it to host databases. It is also connected to your Web server so that your applications (hosted on the Web server) can retrieve data (from databases hosted on the database server).

Databases come in many varieties. The kind of database you can use for a Web application depends on the kind of software that’s installed on the database server. Our University of Rochester hosting environment runs `MYSQL` databases.

The Programming Language
------------------------

When you install open-source software on your Web account, it’s going to be written in a programming language. Our University of Rochester hosting environment has software installed on it that allows it to understand different programming languages. If you install software that’s written in a language that your Web server doesn’t read, it won’t work.

The Digital Scholar hosting environment can currently interpret `PHP`, `PERL`, and `PYTHON`.

Add it Together: LAMP
---------------------

If you take a look at all the descriptions above, you can determine that we are running what is known as a LAMP server for digitalscholar.rochester.edu:

*   **L**inux (operating system)
    
*   **A**pache (Web server)
    
*   **M**ySQL (database server)
    
*   **P**HP/PERL/PYTHON (programming language)
    

Applications that are written for LAMP environments will, presumably, run on the server. _However_, some applications do require additional extensions or libraries that aren’t included in a LAMP environment by default. The applications you can install via Installatron (in cPanel) should work just fine.

LAMP environments are unique because all components are open-source, meaning Linux, Apache, MySQL, PHP, PERL, and PYTHON are open for anyone to use for free. Anyone can also modify them and redistribute them. As a result, there are lots of online resources for using these systems that have been built by their communities of users. But, also as a result, since you’re not paying for these systems, you can’t just call up a company and ask them to fix a problem.

[comment]: # (feedback link here)