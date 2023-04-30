### 2.3.Accessing Files through File Manager #

Your University of Rochester cPanel includes a File Manager that allows you to interact directly with the files stored in your web hosting account. This can be useful if you want to upload software that cannot be automatically installed via the Web Applications section of your cPanel, if you need to change the name or permissions of a file or group or files, or if you want to edit a plain text file. To access your files via the File Manager, use these steps:

1.  Login to sites.haverford.edu with your Haverford username and password.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/login.png)
2.  Once logged in, you’ll be on the homepage of your cPanel. The easiest way to navigate your cPanel is by utilizing the search bar in the top right panel. Search **File Manager**. When you press enter, you will be automatically redirected to the File Manager.  You can also find the File Manager icon under the **Files** section.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.37-PM.png)
3.  On the left side of the “File Manager” window, you’ll see a navigation menu containing the file structure of your web hosting account. More information about the contents of these files and folders can be found in the [File Structures and the File Manager](http://www.stateu.org/docs/uncategorized/file-structures-and-the-file-manager/) documentation article.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.39-PM.png)
4.  In the navigation menu, choose the **public\_html** directory. This will take you directly to the folder that contains the files associated with your website(s). You’ll notice your current location (the public\_html folder) is bolded and highlighted in this menu. Click the \[+\] (expand) icon next to a folder to see what subfolders it contains, or click on the name of the folder to view all of its contents in the file browser on the right side of the page. You can also navigate through the folders in your account by double-clicking on them in the menu on the left side of your file manager.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.44-PM.png)
5.  To select an item, click once on its icon in the file browser. You can also use the “Select All” button above the file browser, or your computer’s keyboard shortcuts (Shift, Command, Control, etc), to select multiple items from this list.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.47-PM.png)
6.  Depending on what you have selected, different options will be available to you in the action menu across the top of your file manager. For example, if you have selected a folder, you can **rename** it or **Change Permissions** on it.  
    ![screen shot of file manager tools](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/2.4-e-file-manager-tools.gif)
7.  If you know exactly what location you want to skip to within your web hosting account, you can type it into the box directly above the navigation menu and click **Go**.![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.51-PM.png)
8.  Alternatively, if you know the exact name of the file or folder you are looking for, but not its location, you can use the **Search** box to find it.![screen shot to find file by name](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/2.4-f-file-manager-search.gif)

[comment]: # (feedback link here)

### 2.4.File Structures and the File Manager #

Web hosting is, at its basic core, files and folders on a computer that is connected to the internet and setup to distribute them. How that computer (typically a server) is set up to do that is covered more in [LAMP Environments](http://stateu.org/docs/uncategorized/lamp-environments/ "https://digitalscholar.rochester.edu/support/general/lamp-environments") but this article will explain the idea of the file structure and how it relates to what you view on your domain.

When you signed up for your domain, a web hosting account was created. Although you typically will interact mostly with the web interface to create subdomains, install applications, and other common tasks, you might occasionally also need to work directly with the files in your account. The **File Manager** in your [cPanel](http://stateu.org/docs/uncategorized/introduction-to-cpanel/ "https://digitalscholar.rochester.edu/support/cpanel/introduction-to-cpanel") is one way to see these files. You can also create an FTP account in cPanel and use an FTP program to interact with these files (FTP stands for File Transfer Protocol, and it’s a way of using a desktop client to transfer files to and from your Web server space).

Let’s take a look at the **File Manager** built into your cPanel to get a better understanding of the file structure that makes up your website(s).

1.  Login to cPanel with your Haverford username and password.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/login.png)
2.  On the homepage of your control panel, you’ll have all the various tools listed. You can easily find the File Manager by using the search tool in the upper righthand corner and typing File Manager. You can also find its icon under **Files**.![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.37-PM.png)
3.  You are now sent to the File Manager and can navigate the folder structure there.

![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-12.44-PM.png)

You’ll notice when the File Manager opens up that this looks very much like a folder on your computer. There are a few folders in it as well as files, and you can navigate down into those folders and see what’s inside of them. At the top level of the File Manager, you also have the option of interacting with files and folders you select by moving them around or removing them. There is a larger article all about how to use the file manager at [Accessing Your Files through the File Manager](http://stateu.org/docs/uncategorized/accessing-your-files-through-the-file-manager/ "https://digitalscholar.rochester.edu/support/cpanel/accessing-your-files-through-the-file-manager") so we won’t talk much about how the interface works here. Instead, we’ll cover what those folders and files actually mean and how they relate to what someone sees when they visit your website.

By default, you have a variety of folders at the root of your web space (the first screen you see when you open up the file manager). Some of them are created automatically to store information about the panel and setup of certain sites. These folders are things like access-logs, etc, ssl, and tmp. You can safely ignore most of those folders because they don’t correspond to actual websites. Let’s look at which folders do and how it all works.

Your main domain will correspond with a folder called **public\_html**. Whatever files and folders are inside of this folder are available on that main domain. If you installed WordPress here you’ll likely see a lot of WordPress-related files within it (which were probably helpfully put there by the automated installer). Let’s say we uploaded an image called mypicture.jpg directly into the public\_html folder. That image would now be available at yourdomain.com/mypicture.jpg. The slash after your domain implies “this file is inside this folder”. But what if we had a folder inside the public\_html folder? How does that appear? This is typically called a subfolder so let’s put a folder in public\_html called “images” and put our image, mypicture.jpg, inside of that folder. What would you type in a browser to get to that file now? The location would be mydomain.com/images/mypicture.jpg. So subfolders are also indicated by a forward slash after a domain.

**What about subdomains?** You can have completely separate sites called subdomains that appear as nameofsubdomain.yourdomain.com. But where are they in the file structure? When you create a subdomain, cPanel will ask you to give the subdomain directory a name. If I had a subdomain called photos.mydomain.com for example, I might want to name the folder “photos” (by default your control panel will call the folder by the name of the subdomain). Folders for subdomains are located inside the public\_html folder. So when you go to the File Manager and navigate to public_\__html, you’ll see folders listed for all of your subdomains and once you navigate inside one of those folders, you’ll see files and folders specifically for that subdomain that appear on the web at that subdomain’s address.

File Manager in cPanel is great to view these files and folders, but it can be limiting if you want to upload an entire folder of information to your website. If you find yourself wanting to do more with the files and folders on your web space you may want to consider using File Transfer Protocol (FTP). FTP will allow you to upload and download files to and from your File Manager (i.e. your website) in bulk. For information on using FTP, click [here](http://www.stateu.org/docs/uncategorized/setting-up-ftp/).

[comment]: # (feedback link here)