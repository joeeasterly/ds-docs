### 5.When You Leave #

There are a few reasons that could lead you to consider exporting your website content from University of Rochester. Perhaps you’re leaving the University, or maybe you’re just wanting to use your data on another hosting environment. Whatever the case, you have a couple options for how you want to handle this:

If you are leaving the college, you can migrate your webspace from University of Rochester to our hosting provider, Reclaim Hosting, for a discounted price. Detailed instructions can be found [here](http://www.stateu.org/docs/uncategorized/migrate-to-reclaim-hosting/).

If you would like to move to a third party service, you’ll want to capture a backup of your site. From there you’ll be able to import this backup into a handful of other web hosting services. You can find instructions on taking a backup [here](http://www.stateu.org/docs/uncategorized/export-your-domain/).

[comment]: # (feedback link here)

### 5.1.Migrate to Reclaim Hosting #

#### Step One: Signing up for an Account

The first step will be to sign up for an account at Reclaim Hosting. [This link](https://portal.reclaimhosting.com/cart.php?a=add&pid=2) will take you directly to their Student/Individual Hosting plan option.

\-If you already have a Top-Level domain (i.e. yourdomain.com) choose the _I will use my existing domain and update my nameservers_ option.

\-If your current website content exists on a subdomain (i.e. yourdomain.digitalscholar.rochester.edu), select the _Register a New Domain_ option.

\-Enter a new top-level domain name

Complete the sign-up process/pay invoice. If you’d like to take advantage of a 10% discount, enter the promo code **reclaim4edu**.

#### Step Two: Let Reclaim Hosting Know

Send a support request to **[\[email protected\]](/cdn-cgi/l/email-protection)** with the following message:

> Hello Reclaim Hosting Support,  
> I am graduating from (your school) and I would like to migrate my account, (your domain), to Reclaim Hosting. Please let me know if you need anything else from me.  
> Best,  
> (Your Name)

A member of Reclaim Hosting support will respond & help you get your account migrated within 24 hrs.

[comment]: # (feedback link here)

### 5.2.Export your domain #

To export your domain, we will create a backup of both the files in your domain and the databases that your domain draws from.  First, click on the ‘Manage Your Account’ menu at the top of your screen and select ‘Migration Information.

1.  To get started you’ll need to login to your control panel ([https://digitalscholar.rochester.edu/dashboard](https://digitalscholar.rochester.edu/dashboard "https://digitalscholar.rochester.edu/dashboard")) using your University of Rochester username and password.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/login.png)
2.  Once you’re logged in, you’ll see the cPanel interface.  Now click on the **Manage Your Account** menu at the top of your screen and select **Migration Information**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/Screen-Shot-2018-04-03-at-11.35.24-AM.png)
3.  To create a backup of your files and databases, simply click the button labeled **Add Backup**. The system will take a moment to create a backup. When it is complete, you will see the new backup appear below the button. You can click on this backup to download the file.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-03-at-1.52-PM.png)

[comment]: # (feedback link here)

### 5.3.Unlock your domain #

This article only if you own your own top-level domain. If you have been using the free subdomain option with digitalscholar.rochester.edu through University of Rochester, this does **not** apply to you.

Similarly, if you’re [migrating your content to Reclaim Hosting](http://www.stateu.org/docs/uncategorized/migrate-to-reclaim-hosting/), this article does **not** apply to you.

Transferring a domain you already own is not too much different from registering a new domain, except the transfer process requires an **EPP code**, or an agreement code between your old registrar and your new registrar that allows the release of your domain. Your new registrar will have information on how to transfer in a domain. When you start that process, you will be prompted to enter your EPP code.

**How to find your EPP Code**:

1.  To get started you’ll need to login to your control panel ([https://digitalscholar.rochester.edu/dashboard](https://digitalscholar.rochester.edu/dashboard "https://digitalscholar.rochester.edu/dashboard")) using your Haverford username and password.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/login.png)
2.  Once you’re logged in, you’ll see the cPanel interface.  Now click on the **Manage Your Account** menu at the top of your screen and select **Migration Information**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/Screen-Shot-2018-04-03-at-11.35.24-AM.png)

3\. Click the **Lock** button to unlock your University of Rochester account.

4\. Click **Get Code**. Once that’s done, the system will send you an email with your EPP code.

At this stage, here are a few items to note:

*   You’ll receive a series of emails from both your old and new registrars asking you to authorize the transfer. Please act on _every_ email you receive in a timely fashion– even if the emails look like duplicates.
*   If you do not authorize the transfer in a timely fashion, the domain transfer will expire and you will need to start over.
*   The domain must be older than 60 days.
*   The domain must have no other transfers in the last 60 days.
*   The domain transfer process can take up to a week, depending on how fast your registrars work.
*   Once the domain transfer completes, you’ll receive a notification.

[comment]: # (feedback link here)

### 5.4.Export from WordPress #

If you are using your WordPress, you can also get an export of your posts, pages, comments, custom fields, categories, and tags.

The WordPress export is great for grabbing the content of your WordPress site so that you can import it into another WordPress host, such as WordPress.com or WordPress.org.

> Note: Exports do not include plug-ins, or other site customizations.

Exporting
---------

1.  From the **Dashboard** navigate to _Tools>Export_The screenshot below shows how to export all of your posts, pages, comments, custom fields, terms, navigation menus, and custom posts. However, you can also export just certain posts, pages, or media. **![The export page within WordPress](http://sites.haverford.edu/docs/wp-content/uploads/2017/12/wordpress-export.png)**

This export process generates an XML file of your blog’s content. WordPress calls this an  eXtended RSS or WXR file.

**Note:** This will ONLY export your **posts, pages, comments, categories, and tags**; uploads and images _may_ need to be manually transferred to the new blog. If possible, do not delete your blog until after media files have successfully been imported into the new blog.

Importing
---------

Once you have exported your posts, pages, etc., you can import them into your new WordPress site.

1.  Login to your new WordPress.com or self-hosted WordPress site and go to the Dashboard.  From there navigate to _Tools>Import_ and click on the link to “_Run Importer_“**  
    ![Screenshot showing where to find the WordPress Importer](http://sites.haverford.edu/docs/wp-content/uploads/2017/12/worpress_run_importer.gif)**
2.   Next you will see a screen that prompts you to upload the WXR (.xml) file you generated through the export process. Browse to your exported WordPress archive and then click the “_Upload file and import_” button.  
    ![Upload file and import](http://sites.haverford.edu/docs/wp-content/uploads/2017/12/worpress_import1.gif)
3.  Choose and upload your file.  You will then be prompted to assign an author to the posts that you are importing.  You can use this function to assign one author to all posts, or you can manually set the author for each post in the posts menu. Unless you have a space limit, you will also want to select the option to “download and import file attachments” before clicking the “_Submit_” button.  
    ![Select desired import options and click the ](http://sites.haverford.edu/docs/wp-content/uploads/2017/12/worpress_import2.gif)
4.  When your import is complete, you will see a confirmation screen.  
    ![Confirmation screen](http://sites.haverford.edu/docs/wp-content/uploads/2017/12/worpress_import3.gif)

Your exported content is now added to your site. If you had posts on your site prior to importing, those posts are still available.

Because the export did not include themes or plug-ins, you will need to reinstall those separately from the export/import process.

[comment]: # (feedback link here)