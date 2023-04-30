


### 4.5.Mediawiki #

MediaWiki is an open-source publishing platform that can be used for creating a collaborative document repository. It’s the software that drives the [Wikipedia](https://wikipedia.com/ "http://wikipedia.com") website.

You can learn how to use this application at the official [MediaWiki Help Pages](https://www.mediawiki.org/wiki/Help:Contents). This support documentation wiki will show you how to manage all aspects of your wiki, including customizing its appearance, editing content, and changing user settings.

[comment]: # (feedback link here)

### 4.5.1.Installing Mediawiki #

1.  To get started you’ll need to login to your control panel ([https://digitalscholar.rochester.edu/dashboard](https://digitalscholar.rochester.edu/dashboard "https://digitalscholar.rochester.edu/dashboard")) using your University of Rochester username and password.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/login.png)
    
2.  Once logged in you’ll be at the homepage of your control panel. Navigate the **Applications** section of the cPanel and click **All Applications**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/4.4-all-applications.gif)
3.  Find and select **MediaWiki**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/4.4-all-mediawiki-installer.gif)
4.  The next page gives you more information about the MediaWiki software. To begin the install, click **install this application** in the upper-righthand corner.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/4.4-MediaWiki-installatron-window.gif)
5.  On the next page, the installer will ask for some information about this install. The first thing you’ll want to do is decide where to install it. If you’re wanting to install MediaWiki on your main (the root) domain, you can leave the directory area empty. If you created a subdomain, you can select it from the drop-down menu. You also have the option of installing MediaWiki in a subfolder by typing in the folder name in the **Directory** field. Click [here](http://sites.haverford.edu/docs/uncategorized/subdomains-vs-subdirectories/) for more information about subdomains and subfolders.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-03-at-1.07-PM.png)  
    (By default the installer will automatically backup your MediaWiki website and update it anytime a new version comes out. While we recommend you keep this option, it is possible to only do minor updates, or turn them off completely. The installer will also create a database for you automatically, but if you’ve already created one for this website you can choose **Let me manage the database settings** and enter the details.)
6.  Finally, you’ll need to create an initial username and password for the MediaWiki install. Enter those credentials in the **Settings** section and click **Install**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/Screen-Shot-2018-04-03-at-1.09.23-PM.png)
7.  The installer will take just a few moments to install MediaWiki and a progress bar will keep you updated. When it is complete you will see a link to your new MediaWiki site as well as a link to the back-end administrative section for your MediaWiki site.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-03-at-1.16-PM.png)

Congratulations, you have now completed the installation of MediaWiki! You can now start to create collaborative documents on your own domain.

[comment]: # (feedback link here)

### 4.5.2.Managing Permissions #

The default Mediawiki installed has been customized to make it a bit harder for spammers to overwhelm wikis with illegitimate content and comments. This is done by modifying the **LocalSettings.php** file (a file that is included in every install in which it is possible to provide configurations details).

By default, Mediawiki allows anonymous users to create pages and edit pages in the wiki. The modifications change this in the following ways:

*   Anonymous users cannot edit existing pages
    
*   Anonymous users cannot create pages
    
*   Registered users must click the confirmation link in the registration email in order to edit or create pages
    

This approach should drastically reduce unsolicited content and comments on Mediawiki installations. One further step that administrator might take is to turn registration off after a predetermined amount of time. Users must create accounts by this date; after that, the settings are changed so that registrations are no longer open.

To add this setting, you must edit **LocalSettings.php** in your Mediawiki install:

1.  Login to cPanel and browse to your [File Manager](http://stateu.org/docs/uncategorized/accessing-your-files-through-the-file-manager/ "https://digitalscholar.rochester.edu/support/cpanel/accessing-your-files-through-the-file-manager").  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.37-PM.png)
2.  In the File Manager, browse to the folder within **public\_html** that contains your Mediawiki install. If you installed the wiki at the root of your domain, you won’t need to go any further than public\_html. If you installed the wiki in a subdomain or subdirectory, you’ll need to find the directory that is associated with that space.
3.  Locate **LocalSettings.php.** Once selecting the file, click **download** in the top menu bar to download the file as a backup before proceeding. Then click **Edit** in the top menu bar to edit the file.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-03-at-1.21-PM.png)
4.   Confirm that you want to edit the file.  
    ![Confirm that you want to edit the file](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.4-MediaWiki-files-confirm-edit.gif)
5.  Browse to the bottom of the document, and locate the custom settings that were added during the Mediawiki install and the following line:

$wgGroupPermissions\['\*'\]\['createaccount'\] = false;

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-03-at-1.30-PM.png)

[comment]: # (feedback link here)
