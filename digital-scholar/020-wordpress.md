### 4.Popular Applications #

### 4.1.Wordpress #

WordPress is an online, open source blog application. Powering over 30% of the web, WordPress is easily one of the most popular content management systems (CMS) in existence today. WordPress forked from b2/cafelog in 2003, and WordPress MU multiple website functionality has been integrated since 2010. You can read more about the WordPress backstory [here](https://wordpress.org/about/).

[comment]: # (feedback link here)

### 4.1.1.Installing WordPress #

1.  Once logged at [https://digitalscholar.rochester.edu](https://digitalscholar.rochester.edu/ "https://stateu.org") you’ll be at the homepage of your control panel. Scroll down and look under **Web Applications**, then click the **WordPress** button.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-03-30-at-4.05-PM.png)
2.  This page gives you more information about the WordPress software. To begin the install click **Install this Application** in the upper-righthand corner.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/16.png)
3.  On the next page, the installer will ask for some information about this install. The first thing you’ll want to do is decide where to install it. For example, you could install it in a subdomain you have created by selecting it from the drop-down menu. You also have the option of installing WordPress in a subfolder by typing in the folder name in the **Directory** field. [Click here](http://stateu.org/docs/uncategorized/subdomains-vs-subdirectories/) for more information about subdomains.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/Screen-Shot-2018-03-30-at-2.52.33-PM.png)
4.  By default the installer will automatically backup your website and update it anytime a new version comes out. While we recommend you keep this option, it is possible to only do minor updates, or turn them off completely. The installer will also create a database for you automatically, but if you’ve already created one for this website you can choose **Let me manage the database settings** and enter the details. Finally, you’ll need to create an initial username and password for the WordPress install. Enter that information in the final section and click **Install**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/17-1.png)
5.  The installer will take just a few moments to install WordPress and a progress bar will keep you updated. When it is complete, you will see a link to your new WordPress site as well as a link to the backend administrative section for your WordPress site.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/18.png)

Congratulations, you’ve now installed WordPress! Now you can start customizing it with themes, plugins, and more.

[comment]: # (feedback link here)

### 4.1.2.Settings: Title & Tagline #

Now that you have your WordPress installed and running, it’s time to look at some basic settings for your site.

1.  The place that you will access the settings for your site is called the **Dashboard**, and it provides the starting point for accessing all of your sites dials and knobs.![Screenshot of WordPress dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
2.  The setting we will look at here is your blog “title” and “tagline”. It is located in **Settings > General**. Once you’re on the General Settings page, you can give your blog any **title** you want. You can also give your blog a **tagline**, which can be a short description of the blog.

When you change the Blog title and tagline, they will show up at the top of your site. Depending on what theme you use, the title and taglines will show up in various places. In the case of some themes, they might not show up at all depending on whether they allow custom configurations. We won’t worry about that for now.

There are more settings on the General Settings page, such as setting the administrative email account, time zone, date format, etc. Change those to whatever is appropriate for your site and geographical location.

[comment]: # (feedback link here)

### 4.1.3.WordPress Themes #

When it comes to WordPress, customizing the look of your site is simple and straightforward. When you install WordPress, the default (or pre-set) theme is called **Twenty Seventeen** (as of WordPress version 4.8). It is a very customizable theme.

You can find [general information about Twenty Seventeen here](https://wordpress.org/themes/twentyseventeen/ "http://wordpress.org/support/theme/twentyfourteen").

In addition to Twenty Seventeen, you’ll have other themes available to you. (What themes you have depends upon if you did a default WordPress installation, or if you installed a special package.) If Twenty Seventeen doesn’t meet your needs, you can activate another theme on your site or install a completely new one.

Activating Themes
=================

1.  Start at your site’s **Dashboard**.  
    ![Screenshot of WordPress dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
    
2.  Navigate to **Appearance > Themes**.  
    ![screen shot of WordPress theme options](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-h.gif)
3.  You will see thumbnail images representing each of the themes that you currently have available on your site. Simply mouse over any one of them, and click the **Activate** link.  
    ![screen shot of activating different wordpress theme](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-activate-wordpress-theme.gif)

That’s all you need to do to change the look of your site with a new theme.

Installing Themes
=================

If none of the themes that were provided when you installed WordPress are what you’re looking for, you can always search for and install other themes from the WordPress Theme Repository.

1.  Navigate to **Appearance > Themes**.  
    ![screen shot of WordPress theme options](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-h.gif)
2.  Installing new themes is quite simple. You start by going to the **Add New** Button.  
    ![Screen shot of ](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-i.gif)
3.  The initial page is the Search Theme page, and it’s not visually helpful. You can check a few filter boxes to see what comes up, but there is a more visual way. Click the **Featured** link at the top and you’ll get visual (screenshot) examples of other themes you can install. You can also click **Newest** or **Recently Updated**.
4.  Under the thumbnail picture of each theme (when you hover your mouse over the theme) are three choices – **Install**, **Preview**, and **Details & Preview**. Those choices should be pretty self-explanatory so click **Install** to add a new theme to your site.  
    ![](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-j.gif)
5.  After you install the theme, it is still not active on your site. You will need to **Activate** it to use it.  
    ![Activate desired theme by clicking ](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-activate-wordpress-theme.gif)

Once activated, your site will be using the new theme. Visit your site’s homepage to view your new theme.

[comment]: # (feedback link here)

### 4.1.4.Publishing Content #

The primary activity that you’re likely to be doing on your WordPress site is publishing content. The content could be the text you write, pictures you take, videos or audios (which may be hosted on another site), or other media that you’ve found elsewhere on the Web. WordPress makes it very easy to publish media content of all types, whether hosted on your actual Web server or elsewhere.

Posts vs. Pages
---------------

Out of the box, WordPress provides two primary content types for you two work with: posts and pages. If you read blogs or have ever written for a blog before, the concept of a post is probably a bit familiar. **Posts** often are content that appear on your blog in some kind of scheduled way. They usually are presented on your site in reverse-chronological order. Posts might be what you use to share your regular thoughts, reflections, or ideas about a topic. Posts make up a kind of “river” of content that you’re producing as part of your blogging activity.

**Pages** usually correspond to our more traditional concept of what makes up a Web site. Pages are presented outside of the “river” of content that are posts. They are more likely to stand alone and be organized according to a traditional hierarchy. Pages might be content that is less frequently updated or changed.

If you were using WordPress to build a business Web site with a lot of information content, you would probably use Pages. If you added a feature to that site where you started to advertise special events or news, you would probably use Posts.

**A few other things to know about Pages vs Posts:**

*   If you want your content to be accessible to your users via RSS/syndication, you’ll need to use Posts. By default, Pages do not appear in a site’s RSS feed.
    
*   Categories and Tags (which are used in WordPress to help you organize your content) are ONLY available on Posts. Page organization is done by customizing your site’s menus.
    
*   Okay, this get’s a little tricky: WordPress, by default, also creates “Category Pages” and “Tag Pages” that display all the Posts in a category or tag. These are NOT related to the regular Page type.
    

Media
-----

Upon occasion, you may want to include media (images, audio, video) in your site’s posts and pages. There are generally two approaches to handling media in WordPress:

**Uploading**: You can upload the files to your site’s Media Gallery and then link to them in your posts/pages. This works very well for images, and when you take this approach for images you have the added benefit of being able to make use of WordPress’ built-in (albeit rudimentary) editing tools. Also, when you upload images to WordPress, it automatically creates different sizes that you can use, as needed. This approach works less well for audio and video. In order to have your media files actually show up in a “player” (with controls for stopping, pausing, etc.) you’ll need to install a plugin. Otherwise, you’ll only be able to include links to the files. How people view/listen to them will depend a bit on the setup on their own computer and in their own browser. They may, for example, have to download the media file and then open it in another program on their computer.

**Embedding**: You can embed media from other sites easily in WordPress. Embedding an image just means providing a URL to its location elsewhere on the Web. Instead of uploading it to the server, WordPress grabs that image from the external source and displays it on your post/page. However, with this approach, you lose your editing capabilities as well as the resizing feature. Embedding audio and video from external sources becomes easier with every version of WordPress it seems. These days, you can embed video and audio from many external services (YouTube, Vimeo, SoundCloud, complete list here) by simply placing the full URL of the audio/video location on its own line in your post/page. There is [a complete list of supported external services](http://codex.wordpress.org/Embeds#Okay.2C_So_What_Sites_Can_I_Embed_From.3F "http://codex.wordpress.org/Embeds#Okay.2C_So_What_Sites_Can_I_Embed_From.3F"), and you can learn [more about embedding from external sources at the WordPress site](http://codex.wordpress.org/Embeds "http://codex.wordpress.org/Embeds"). Our general advice is to use externally hosted media whenever it makes sense and works. This is _usually_ the case when you need to use audio or video; without plugins, well-presented audio and video in WordPress is tricky. For images, if you need to do basic editing and/or require different sizes of images, upload them to your site. Otherwise, consider referencing them from another location (your Flickr account, for example).

Post Formats
------------

Recent versions of WordPress have built out a new “post format” feature which, if you are using a theme with the feature enabled, will style post formats differently depending on what they are. The formats that are built-in to WordPress (and are available for theme developers to use) are the following:

*   aside – Similar to a Facebook note update.
    
*   gallery – A gallery of images.
    
*   link – A link to another site.
    
*   image – A single image.
    
*   quote – A quotation.
    
*   status – A short status update, similar to a Twitter status update.
    
*   video – A single video.
    
*   audio – An audio file.
    
*   chat – A chat transcript.
    

Those of you familiar with [Tumblr](https://tumblr.com/ "http://tumblr.com/") may recognize this approach to post formats.

For the most part, post formats are designed as a way to **style** a site (and customize styling depending on the kind of content that is being displayed). They have no special functionality, and their use depends entirely upon the theme you are using. Many older themes, for example, do not recognize post formats.

[comment]: # (feedback link here)

### 4.1.5.Reading Settings - Front Page #

WordPress is a very flexible platform for creating full-blown websites, not just blogging sites. This page will show you how to change the “front page” of your website.

As we have said before, WordPress provides two primary content types for you two work with: **posts** and **pages**. Posts, as in blog posts, are a somewhat complex form of a webpage. Each blog post gets published in reverse chronological order, on the front page of a WordPress site. You write a new post, and it gets published at the top of the front page. Pages are a more static form of content. They are additional areas to put information that doesn’t change much. So what if you would like to make the front page of your WordPress site based on a page instead of your blog posts?

1.  Start at the **Dashboard**.![Screen shot of WordPress Dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
2.  Navigate to **Settings > Reading**.![screen shot of WordPress reading settings](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-l.gif)
3.  Normally, the front page displays your latest blog posts. What we want to do instead is select a **Page** from the website. Obviously, this page has to exist before you can select it. Select the “**A static page**” radio button and choose the **About** page from the Front page drop-down menu (an About page was created for you when you installed WordPress). Press the **Save Changes** button and now you will have the “About” page as your Front page. Edit it as you see fit and provide a good welcoming page for your visitors. ![screen shot of Word press reading settings](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-l-2.gif)
4.  But wait. What will happen to your blog posts? Most people will want them as the “dynamic” part of your site. First, create a new **Page.**![screen shot of ](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-add-new-WP-page.gif)
5.  Title it **Blog** (you can title it whatever you want but Blog is common and descriptive). Leave the page blank (don’t type any text in the edit box) and Publish it.![screen shot of adding a new post](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-add-new-WP-post.gif)
6.  Now go back to **Settings > Reading**. Under the **static page** area choose Blog from the **Posts page** drop-down.![select new WP post page](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-select-new-WP-post-page.gif)
7.  Click the **Save Changes** button. Now your “home” page will actually display the About page. You will also have a Blog item in your menu (depending on your theme, you may have to customize your page display to see pages).
8.  If you click on the Blog menu item, you will then see your blog posts. Notice the **/blog** added to the web address.![](http://www.stateu.org/docs/wp-content/uploads/2018/03/4.1-WP-blog-page.png)

[comment]: # (feedback link here)

### 4.1.6.Permalinks #

Part of the popularity of WordPress is how easily it makes a website functional and yet attractive. One of the smaller details that you might want to adjust is how the addresses to your blog posts are structured. **Permalink** is the name given to the address of an individual blog post because they are “permanent links”. For this example, the web address we’ll use for this sample blog is yourdomain.digitalscholar.rochester.edu. The link to the first post, titled “Hello World” may be structured in many ways. The screenshot below shows one way: “http://yourdomain.digitalscholar.rochester.edu/blog/uncategorized/hello-world”.

![](http://www.stateu.org/docs/wp-content/uploads/2018/03/stateu.org_-2.png)

With WordPress, you have many options to form the links to posts, and you can change them to work for your particular content.

1.  To change the permalink structure, start by going to the **Dashboard**.  
    ![Screen shot of WordPress Dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
2.  Next, go to **Settings > Permalinks**. By default, your blog will use a “custom structure” that includes a category select and the name of the blog post.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-9.56-AM.png)
3.  If you are not using categories, or prefer a different look to your blog post addresses, there are several choices under **Common Settings**.  A popular choice is to use the **Post name** choice, which is a bit more informative. So our post titled “Hello World” will have an address of “http://sstrauss.sites.haverford.edu/blog/hello-world”.
4.  If you want to have the date as part of the address, you can choose **Day and name** or **Month and name**. You can also change the structure of category and tag names under the **Optional** section.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-10.00-AM.png)
5.  Finally, when you write a blog post, you have the option of editing the permalink for an individual post. Just click the **Edit** button (underneath the Title field).  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-10.06-AM.png)
6.  Then type in whatever is appropriate (and hasn’t been used yet). Generally, you want to make it as simple and short a word, or words, as makes sense.

[comment]: # (feedback link here)

### 4.1.7.Custom Menus #

1.  Start at your site’s **Dashboard** and choose **Appearance** the **Menus**.![screen shot of appearance menu](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-appearance-menu.gif)
2.  In the Custom Menus interface that appears, type a name for your menu. This can be anything you want. It doesn’t get displayed anywhere; it’s used by WordPress to identify and place your menu. Once you’ve typed the name, click **Create Menu**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/4.1-create-custom-menu.png)
3.  You’ll now be presented with a screen that includes a section titled **Menu Settings**. This is where you’ll indicate where you want your menu to appear in your theme. The number of locations available depends entirely upon the theme you choose. In the example shown below, there are two areas available; we’ve chosen to place the menu in the **Top primary menu** area which we know corresponds to the header menu. You may need to experiment a bit in order to find out where your menu will appear in your theme. You can always change this location later by coming back here and clicking the **Manage Locations** tab.  
    ![custom menu settings](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-custom-menu-settings.gif)
4.  Now that you’ve set up your menu and assigned it to a location, you can begin to add links to it. On the left-hand side of the screen, you’ll see what content is available to add. On the right-hand side of the screen, in the _Menu Structure_ area, you can arrange and organize your links.
5.  By default, you may not see **everything** that is available to you to add to your menu. For example, posts can be added to menus, but they’re not usually displayed by default. To make more content available, click the **Screen Options** tab at the top of your WordPress screen, and then click off the check boxes that correspond to additional content.![custom menu screeen options](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-custom-menu-screeen-options.gif)
6.  To add content to your menu, simply check it off on the left, and click the **Add to Menu** button.![add items to custom menu](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-custom-menu-add-items.gif)
7.  Your new content will appear on the right, and you can drag items in the order you want them to appear. Drag items to the right to indent them under other items. This will usually make them appear as drop-down items in your menu.![](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-custom-menu-items.gif)
8.  You can add custom links to your menu by clicking the **Links** section on the left. In the short form that appears, enter your link’s URL, and a text for the link. Click **Add to Menu** to move it to the left.![Change navigation labels on your custom menu](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-custom-menu-navigation-labels.gif)
9.  Note that you can change the link text of any item you add to your menu. This can be helpful if you have a page with a long title, and you’d like the link to not take up so much space. You can abbreviate the title in the **Navigation Label** section, and that shorter text will become the actual menu link.
10.  When you are done, make sure you click **Save Menu.**

### Other Notes about Menus

When you add a **Category** or **Tag** to a menu, the link will take your readers to an archive of all the posts on your site that use that category or tag. This can be a very useful feature for organizing your content when you’re using posts to share your work.

In addition to assigning Custom Menus to theme areas, there is a default Custom Menu widget that you can put in the sidebar of your site. This is useful for creating smaller, customized navigation for your site.

If you forget to click **Save Menu** after making changes to your menu location or content, you will lose your work!

[comment]: # (feedback link here)

### 4.1.8.Widgets #

Widgets are a more advanced feature of WordPress that allow you even more control over the content on your site. In essence, widgets are small containers of content that can be placed in various areas of your site. Where you can place widgets depends entirely on the theme you are using. Many (most) themes include at least one “sidebar” into which you can place widgets. Some themes include additional “widgetized” areas. The best way to find out what areas are available to you is to go to Appearance > Widgets and take a look at the areas listed on the right. Each widgetized area will appear as a box on the right. In the example shown below, the theme contains three widgetized areas: Primary Sidebar, Content Sidebar, and Footer Widget Area.

![screen shot of widgets](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-widgets.gif)

On the right, you will see a number of widgets available to you. WordPress comes with some default widgets. Other widgets might become available when you have a particular theme activated. Finally, some plugins provide additional widgets to you.

Widgets can present all different kinds of information. The simplest widgets allow you to add text to your site. But you’ll also find widgets with many options that you can set to display dynamic content or to interact with other services. Below is a list of the default widgets available in WordPress.

When you’re ready to start using widgets, all you need to do is drag them from the right-hand side of the Widgets interface into the boxes on the left. WordPress will immediately save them, but you may need to set some options

Default Widgets
---------------

*   Archives: Shows a monthly listing of your posts.
    
    *   Calendar: Shows a calendar view of your posts.
        
    *   Categories: Shows a list of all of the categories on your site.
        
    *   Custom Menu: Shows a custom menu that you’ve set up with WordPress’ Custom Menu interface.
        
    *   Links: Shows your links.
        
    *   Meta: Shows links to your RSS feed and your login.
        
    *   Pages: Shows a menu of all of your pages.
        
    *   Recent Comments: Shows the most recent comments on your posts.
        
    *   Recent Posts: Shows your most recent posts.
        
    *   RSS: Allows you to show content from an RSS feed.
        
    *   Search: Provides your users with a search box.
        
    *   Tag Cloud: Shows a “cloud” of the tags/categories on your site.
        
    *   Text: Shows whatever text you enter.
        
    

[comment]: # (feedback link here)

### 4.1.9.Plugins #

WordPress has a lot of functionality built-in, but occasionally you might find a specific need that isn’t a part of the default software. To accomplish this, WordPress has a plugin architecture where developers can create plugins that add additional functionality to your site. From simple photo galleries to site statistics, to automatic Twitter and Facebook sharing of posts, there is practically a plugin for whatever you need for your blog (over 54,000 at the time of this writing). To start using and installing plugins just follow these simple instructions:

1.  Log in to your WordPress dashboard.
2.  From the left side menu, locate and click **plugins**.![screen shot of plugin menu](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-plugin-menu.gif)
3.  You will be given a list of all your currently installed plugins. From this menu, you are able to activate and disable specified plugins by using either the single plugin options located under each plugin name. Or you may use the bulk action drop down menu to simultaneously activate/disable multiple plugins by checking desired plugins. Additionally, you may also sort through installed plugins using the sorting options above the bulk action menu.
    
     ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-10.13-AM.png)
    
4.  To install a new plugin click **add new** either from the plugin sidebar or the main plugin menu, you will then be redirected to a search engine where you can search using general or specific terms to find plugins. For example, searching “photo gallery” brings up various plugins from different developers.
    
    Once you find your desired plugin to install it hit **install now**, which will automatically install the plugin and prompt you if you would like to activate it now or return to the menu.![find and install desired new plugins](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-plugin-install-new.gif)
    

After installing your plugin be sure to visit the developers’ website if you have any additional questions about how the plugin works, as some plugins may require certain codes or other actions to be used properly.

Some plugins will have their own settings page located under the **settings** or **tools** categories, other plugins will break out their own menu item on the lefthand side of the dashboard. Sometimes it won’t be explicit how the plugin interacts with your personal site, so it’s important to make sure you’ve read the documentation available on the plugin’s website.

[comment]: # (feedback link here)

### 4.1.10.Site Privacy #

WordPress is a platform intended to allow you to share your thoughts and ideas freely and easily with the world. However, there are options to publish to a more limited audience.

The first way is to limit who can find your website. That is done by keeping search engines, like Google, from seeing (known as indexing) your site.

1.  To do this, we’ll start at the **Dashboard**.![Screen shot of WordPress Dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
2.  Navigate to **Settings > Reading**. Normally the box next to **Search Engine Visibility** is unchecked. If you decide to check the box, it will “Discourage search engines from indexing this site.” It will depend on the search engine to honor your “request”. Some search engines will simply ignore it. Obviously, this is not a sure-fire way of keeping your blog private.![reading menu--search engine setting](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-reading-menu-privacy-setting.gif)
3.  You also have options on individual posts to keep them private, so that only people who are logged in to your site can view a given post. You can also password protect posts with a password you supply. Choose the **Private** radio button to keep a post hidden behind the login, or choose the **Password protected** button and then type in the password you wish to use. Click on **OK** when you are finished. Then be sure you click the **Update** button to save your post with the new settings.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-10.31-AM.png)

[comment]: # (feedback link here)

### 4.1.11.Discussion Settings #

What makes WordPress a powerful platform is that not only can you create a dynamic website, but you can also allow dynamic discussions about the content with your visitors. Comments, the bread and butter of the discussion, can add to the overhead of your website management. You have to keep up with responses to your commenters or they will think you aren’t paying attention. Comments also can come, unfortunately, in the form of Spam. We will give you some additional information about dealing with Spam in another section. For now, here’s how to manage your Discussion Settings.

1.  Start at the **Dashboard**.![Screen shot of WordPress Dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
2.  Navigate to **Settings > Discussion**.![screen shot of discussion settings, part 1](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-discussion-default-article-settings.gif)
    *   The two main forms of discussion on a website are “Allow link notifications from other blogs (pingbacks and trackbacks)” and “Allow people to post comments on new articles”.
    *   Comments are self-explanatory. People come to your website, read an article, and as long as you allow comments, people can write whatever is on their mind. Commenters must leave their name and email address (if you leave that setting checked). You can also require users to be registered to your site to comment. They would then need to be logged in to submit any comments. By default, you will get an email sent to the admin account of the WordPress site when someone posts a comment, or when a comment is held in moderation. You can uncheck those boxes if you do not wish to receive those emails.
    *   A comment will appear on the article (post or page) only after you approve it. If you have approved a comment author once, they will be automatically approved the next time they leave a comment on your site. If you uncheck the box labeled “Comment author must have a previously approved comment”, then all comments will appear automatically. **We don’t recommend this setting**.
    *   You also have some control over comment moderation regarding how many links a comment contains (spammers like to put links in their “comments”). You also can filter out words, URLs, email addresses, to hold them in moderation. You can then approve them, spam them, or trash them.
    *   There are also forms of discussion called link notifications. Spammers like these too. Here’s an article on the [What, Why, and How-To’s of Trackbacks and Pingbacks in WordPress](http://www.wpbeginner.com/beginners-guide/what-why-and-how-tos-of-trackbacks-and-pingbacks-in-wordpress/ "http://www.wpbeginner.com/beginners-guide/what-why-and-how-tos-of-trackbacks-and-pingbacks-in-wordpress/").
3.  Sometimes it’s nice to have visual representations of the people who are commenting on your blog. These are called **Avatars** and can be found under **Settings > Discussion**.![screen shot of discussion settings, part 2](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-discussion-avatar-settings.gif)

WordPress uses a common universal system of avatars called [Gravatars](http://gravatar.com/ "http://gravatar.com/") (Globally Recognized Avatars). The system requires you to sign up with your email address. You can upload a graphical representation of yourself (a picture or other graphic). From then on you are identified with your Gravatar on any blog that you use that email address with.

In the WordPress Discussion Settings, you have a few options. Whether to show Avatars at all, the “rating” allowed to be shown, and what the default Avatar will be if a user does not have a Gravatar.

[comment]: # (feedback link here)

### 4.1.12.Managing Spam: Akismet #

SPAM! Everyone hates it in their email. If you’re new to WordPress and blogging platforms, spam exists in the form of comment spam – people (or vermin) leave comments promoting their services or schemes, on a post or page.

So how do you deal with comment spam when it can come in even more often than email spam? Do you have to delete every comment that comes in? Well, the answer to the second question is “no”, and the answer to the first question is, with a plugin called [Akismet](http://akismet.com/ "http://akismet.com/").

1.  To get started we need to install a plugin. To do this, we’ll start at the **Dashboard**.![Screen shot of WordPress Dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-f.gif)
2.  Navigate to **Plugins > Installed Plugins**.![Screen shot of Akismet on plugins menu](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-q.gif)
3.  At or near the top of the list of plugins that are automatically installed in a new WordPress installation, is [Akismet](http://wordpress.org/plugins/akismet/ "http://wordpress.org/plugins/akismet/"). It is not activated, so part of the process of getting Akismet is **Activating** the plugin. Before you activate it, however, you need to get something that will be somewhat strange for most people. It’s called an API key. API stands for Application Programming Interface, and it’s a way for programs and services to “talk” to each other. The Akismet plugin requires you to get an **Akismet API Key**, which is simply a “code” that you supply when activating the plugin. The key is free if you use it on a personal WordPress installation, and it’s [available on the Akismet website](http://akismet.com/wordpress/ "http://akismet.com/wordpress/").![screen shot after activating Akismet](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-r.gif)
4.  Once you arrive on the Akismet for WordPress site, click the **Get an Akismet API key** button.![Screen shot of Akismet web site where you get key](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-s.gif)
5.  If you have an account at [WordPress.com](https://wordpress.com/ "http://wordpress.com/") you can sign in with that login and get your key. Otherwise, fill in an email address, a username, and a password to use for a new account. Click the **Sign up** button to proceed.  
    ![create a wordpress.com account, if you don't already have one](http://sites.haverford.edu/docs/wp-content/uploads/2017/11/4.1-t.gif)
6.  Type in the URL of the site you’ll use Akismet on and click on the **Sign Up** button under the Personal plan (that is if you want it to be the free version).![Select desired Akismet plan](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-v.gif)
7.  When you get to the next page, the recommended contribution is $36. You can adjust the slider down to $0. The smiley face will begin to frown, but at least your key will be free. Lastly, fill in your name and click **Continue**.  
    ![](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-w.gif)
8.  You’re finished with the sign-up process for your key, and it will be displayed on the page for you (we’ve blurred ours out).![Akismet key](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-x.gif)
9.  Now follow the steps that they show you for using your new key. You will enter the key in either the Akismet area under Plugins or JetPack (if you have that installed).![Akismet key](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-z.gif)

[comment]: # (feedback link here)

### 4.1.13.iOS & Android App #

You can download the WordPress app from the [iOS App Store](https://itunes.apple.com/us/app/wordpress/id335703880?mt=8 "https://itunes.apple.com/us/app/wordpress/id335703880?mt=8") or the [Google Play Store](https://play.google.com/store/apps/details?id=org.wordpress.android&hl=en "https://play.google.com/store/apps/details?id=org.wordpress.android&hl=en") for your mobile device.

#### Screenshot Setup Tutorial:

1.  When you open the WordPress app, tap on **Add Self-Hosted Site**:  
    ![log into your WordPress site from your smartphone](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-smartphone-app.gif)
2.  Then, you will be able to enter your WordPress site credentials:  
    These credentials come from your Installatron page of WordPress. To access these credentials, first find the applications you added with Installatron by clicking on the **My Apps** icon.![My apps icon](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-installatron-my-apps.gif)
3.  Next, click the title of your installed instance of WordPress:  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-10.49-AM.png)
4.  From here, under the **overview** tab, you can access your WordPress site credentials. You may change your user password by filling in the field next to **password**, scrolling down, and clicking the **Save all** button. Note that this sometimes takes a few minutes, so even if it doesn’t look like anything is happening, do not refresh your page after clicking save.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-10.54-AM.png)
5.  With these credentials, enter them into the WordPress App along with the url for your WordPress website and select **Next.**
6.  On the next page, you will see all of the WordPress websites you have added to the WordPress App. Continue to the site you just added.
7.  To start a new post, tap on the **Pencil Icon**:  
    ![pencil icon lets your create/edit blog post](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-app5.gif)
8.  On this page, add your **Title** and **Content.** You can edit the properties of text by selecting the text and the different **Text Property Buttons**:  
    ![Screen shot of Text Property options](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-smartphone-format-options.gif)
9.  To view the progress of your post, select “**…”** on the top right of the screen and select **Preview**:  
    ![](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-app7.gif)
10.  When finished, select **Publish**:  
    ![Publish post](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.1-app8.gif)

Now when you visit your WordPress webpage, you will see your new blog post!

[comment]: # (feedback link here)