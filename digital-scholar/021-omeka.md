### 4.2.Omeka #

[Omeka](https://omeka.org/classic/ "http://omeka.org/about/") is an open-source web application that can be used to create and display online digital collections. Developed by programmers at George Mason University, Omeka was designed to be user-friendly, both during installation and setup and during daily usage.

You can learn how to use this application in the official [Omeka Support Documentation](https://omeka.org/codex/Documentation). This support guide will help you get started and begin creating your Omeka site.

[comment]: # (feedback link here)

### 4.2.1.Installing Omeka #

To get started you’ll need to login to your control panel ([https://digitalscholar.rochester.edu/dashboard](https://digitalscholar.rochester.edu/dashboard "https://digitalscholar.rochester.edu/dashboard")) using your University of Rochester username and password.

1.  Once logged in you’ll be on the homepage of your cPanel. Navigate to the **Web Applications** section of the cPanel and find **Featured Applications**. Then select **Omeka**.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/4.2-a.png)
2.  This page gives you more information about the Omeka software. To begin the install, click **install this application** in the upper-righthand corner.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/4.2-b.png)
3.  On the next page, the installer will ask for some information about this install. The first thing you’ll want to do is decide where to install it. If you’re wanting to install Omeka on your main domain, you can leave the directory area empty. If you created a subdomain, you can select it from the drop-down menu. You also have the option of installing Omeka in a subfolder by typing in the folder name in the **Directory** field. Click here for more information about [subdomains and subfolders](http://stateu.org/docs/uncategorized/subdomains-vs-subdirectories/ "https://digitalscholar.rochester.edu/support/cpanel/subdomains-vs-subfolders").  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/Screen-Shot-2018-04-02-at-12.44.10-PM.png)
4.  Scroll down to the next Setting section. Set an Administrator Username and Administrator Password. You will need this again shortly.
5.  By default the installer will automatically backup your website and update it anytime a new version comes out. While we recommend you keep this option, it is possible to only do minor updates, or turn them off completely. The installer will also create a database for you automatically, but if you’ve already created one for this website you can choose **Let me manage the database settings** and enter the details. Click **Install** to continue.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-12.16-PM.png)
6.  The installer will take just a few moments to install Omeka and a progress bar will keep you updated. When it is complete you will see a link to your new Omeka site as well as a link to the backend administrative section for your Omeka site. Click the **Omeka Admin** link to configure your new Omeka installation.  
    ![](http://www.stateu.org/docs/wp-content/uploads/2018/03/2018-04-02-at-12.19-PM.png)
7.  When you visit your new Omeka Admin link, you are asked for the admin username and password. Enter the **Username** and **Password** that you set for the administrative superuser (i.e. yourself).  
    ![Omeka login screen](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.2-Omeka-super-user-account.gif)
8.  Begin adding content in the **Admin Dashboard**. You’ll find lots of instructions, tips, and ideas on the [Omeka.org documentation site](http://omeka.org/codex/Documentation).  
    ![Omeka dashboard](http://sites.haverford.edu/docs/wp-content/uploads/2017/10/4.3-Omeka-dashboard.gif)

[comment]: # (feedback link here)

### 4.2.2.Installing Plugins #

As you begin to use your Omeka install on Reclaim Hosting you may wish to add additional functionality by way of the various open source plugins available at [http://omeka.org/add-ons/plugins/](http://omeka.org/add-ons/plugins/). Although Omeka doesn’t currently include an automated installer for plugins, the process of uploading them to your space is outlined here.

To get started you’ll want to log into your cPanel:

![](http://www.stateu.org/docs/wp-content/uploads/2018/03/login.png)

In cPanel you’ll access the File Manager located under the Files section.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/563bd572c43ae0aa3626e18d4a332951870eed30_1_690x172.png)

In the File Manager you’ll navigate on the lefthand sidebar down to your plugins folder which should be one of several folders within your Omeka install (your root directory for your domain is **public\_html**).

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/c575d3f00fb0066b3a8c817b4503b26934455103_1_690x327.png)

Here you will see all plugins currently in your Omeka install. To add a new one you want to have downloaded the zip file locally to your computer from Omeka’s website first. Then click the Upload button to upload the file.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/d3d270966f9b8e525e68db1cce383f236e3a4d92_1_690x361.png)

The interface will allow you to drag and drop or select from your computer one or more zip files for the plugins you wish to upload. Once the upload has completed you can return to the previous screen using the link at the bottom of the page.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/33f32b69be00f9e0ce0c5869c8200da0cc6b23ed_1_690x313.png)

You should now see a zip file for your plugin in the plugins folder. The last step is to extract the contents of the zip file to the same folder. To do this select your file and click the Extract button.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/7b425f46c6fe79ffb8bf9134e725a72112429554_1_690x310.png)

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/e4d280c945807fab80dfe3e9d800db052787dfea_1_690x328.png)

Once the plugin is extracted you can delete the zip file and the plugin will now be available for activation within your Omeka administration interface.

[comment]: # (feedback link here)

### 4.2.3.Installing Themes #

Just as you would [install plugins](https://www.stateu.org/docs/uncategorized/installing-plugins/), installing themes to Omeka is very similar. Omeka has a few themes installed automatically that you have access to. But there are more themes available at [http://omeka.org/add-ons/themes](http://omeka.org/add-ons/themes/). There is no automatic installer so you would need to upload the theme to your File Manager in cPanel.

Start by finding the the theme you’d like to install. Download the theme by clicking on the red button.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/80c8c4acda589801c0a8431dc7337c6489de6064_1_690x445.png)

Note that the file should be in .zip format.  
![](https://community.reclaimhosting.com/uploads/default/original/1X/a441ff866a31a1092d945bbd64d8dc2bcc82fb76.png)

Then open your file manager in cPanel.  
![](https://community.reclaimhosting.com/uploads/default/original/1X/3b8d71c57846caed1cc50d2c6a4eb3916c757e8f.png)

After, you’ll go to your specific Omeka install. Click on **themes**.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/d8878d8b0aae193f2c5dd5aa8a55784fabc01b4b_1_690x327.png)

Click **Upload**.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/c32f724cc26577e7b8b44d4943ec73bc2a4f6bfa_1_690x327.png)

You can drag and drop the .zip file into the window or you can click select a file.  
![](https://community.reclaimhosting.com/uploads/default/original/1X/4f49ff8cb69ab5f08fd7828fac20679651367a18.png)

Once your file is uploaded to the themes folder you need to go in and extract the files from the .zip folder. Click on the theme file you just uploaded then click on extract.

![](https://community.reclaimhosting.com/uploads/default/optimized/1X/3f6b61b0f3ea705e5f09869270399ca4e0b14376_1_690x327.png)

You’ll need to confirm that you want to extract the files. Click extract files. ![](https://community.reclaimhosting.com/uploads/default/original/1X/0b004d3db81cf8ff0b27031b2cb9d57364436b89.png)

Once the theme is extracted you can delete the .zip file and the theme will now be available for activation within your Omeka administration interface.

[comment]: # (feedback link here)

### 4.2.4.Neatline Plugin #

### Building an interactive map using Omeka’s Neatline plugin

Neatline is a plugin for Omeka that allows for the creation of interactive maps and timelines. Neatline allows the user to plot points on geospatial layers that, when clicked, reveal text and media. Users may create records from scratch and add them to their Neatline exhibits, or import existing items from Omeka. See [Neatline.org](http://neatline.org/) for demos of this tool in action and more documentation.

Before using this tool, you’ll need to **install the Neatline plugin to Omeka**. If you’ve already installed the Escher plugin, you can use it to install Neatline. If not, follow the instructions on [the “Installing Plugins” section of this support page](https://www.stateu.org/docs/#installing-plugins).

### Vocabulary

**Item**: Omeka’s basic building block, containing text, media, and/or metadata.  
**Collection**: A group of items, typically sharing a common theme.  
**Record**: Neatline’s version of items. Can be created on their own, or imported from an existing item in Omeka.  
**Exhibit**: A Neatline map or timeline; contains your records.  
**Widget**: An add-on tool for Neatline, such as Waypoints.  
**Spatial layer**: A navigable map that Neatline can use, typically pulled from Google Maps. The various options Neatline offers have different aesthetics.

### Setting up (first time only)

1\. Install the Neatline plugin (see above). Install any additional supporting plugins you’d like, such as Neatline Waypoints.

2\. Go to your Plugins page in Omeka. Then, click “Configure” to the right of Neatline. On the configuration page, click the link to [developers.google.com/maps/web](https://developers.google.com/maps/web). If possible, open this link in a new tab, since you’ll soon need to return to the configuration page.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.12-PM.png)

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.19-PM.png)

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.20-PM.png)

3\. On the Google page that opens, click the “GET A KEY” button at top right. Follow the prompts in the pop-up window to create a new project, named whatever you’d like (this title won’t matter for your Neatline projects). When you’re given a long string of characters, copy it. This is your Google Maps API Key. You’ll only need it once.

![](https://docs.emerson.build/wp-content/uploads/2018/01/04-API-step2-getkey.jpeg)

4\. Return to the Neatline configuration page from step 2. Paste your API Key into the text box. Then click the green “Save Changes” button. Neatline is now connected to Google Maps.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.21-PM.png)

5\. Click Settings at top right of your Omeka dashboard. In the text box to the right of “ImageMagick Directory Path,” enter this exact text without the quotation marks: “/usr/bin”. Then click the green Save Changes button at top right. This will allow Omeka to handle your images properly.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.22-PM.png)

Neatline is now ready to go!

### Laying the foundation

**1\. Optional: create one or more collections.** This is an organizational tool: by creating collections now, you’ll be able to sort your items or bulk import them to Neatline more easily later. To create a collection, click “Collections” on your lefthand Omeka dashboard menu. Then, click the green Add a Collection button. On the Add a Collection page, give your collection a Title (you can leave all other boxes blank). If you want to add formatting to your text such as bolding or italics, check the box next to “Use HTML,” and more editing options will appear.

When you’re done, check the box next to “Public” and then click the green Add Collection button.

**NOTE**: You’ll see many fields when creating collections or items, but there’s no need to panic: almost all are optional and exist for archival purposes. Only fields with a \* after them are required.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.24-PM.png)

**2\. Begin creating items.** Omeka is a tool for curating artifacts. In this step, you’ll begin this curation by creating items. To create an item, click “Items” on your lefthand Omeka dashboard menu. Then, click the green Add an Item button. On the Add an Item page, give your item a Title and a Description (you can leave all other boxes blank). This is the text that will ultimately appear to viewers of this record on your Neatline map. If you want to add formatting to your text such as bolding or italics, check the box next to “Use HTML,” and more editing options will appear.

Check the box next to “Public.” If you wish to add this item to a collection, select it from the dropdown menu under “Collection.”

If you wish to add images to your item, click the “Files” tab, then click “Choose File.” Follow the prompts to upload an image. To upload more images, click the green Add Another File button. These images will be displayed alongside your text when a viewer clicks the relevant point on your map.

If you wish to add tags to your item, click the “Tags” tab, then enter all desired tags in the text box, separated by commas. Remember to click Add Tag afterward.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.26-PM.png)

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.27-PM.png)

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.29-PM.png)

When you’re done adding text, files, and tags, click the green Add Item (or Save Changes if you’re editing) button.

You can always find your list of items, with the option to edit each one, by clicking Items on your Omeka dashboard. From the Items page, you can also use the blue Search Items button to filter items by user or tag.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.30-PM.png)

Clicking “Tags” on the Omeka dashboard will bring you to a list of all your tags. Click a tag’s name to edit it, or click the number to its left to view all items with that tag.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.33-PM.png)

### Managing Neatline exhibits and using the editor

**1\. Create an exhibit.** Your Neatline map will be known as an exhibit. It’s now time to create this map. Click Neatline on the lefthand dashboard menu, which brings you to the Browse Exhibits page. Then click the green Create an Exhibit button.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/10-neatline-exhibits.jpg)

On the Create an Exhibit page: give your exhibit a Title, Narrative (optional but recommended), and Widgets (if you’d like to use Waypoints or another add-on you’ve previously installed). The Narrative is the exhibit’s primary textual description, and it will appear alongside your map.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/11-create-exhibit-1.jpg)

Scroll down and select a Default Spatial Layer from the drop-down menu. The Default Spatial Layer is the default map style your exhibit will display. You can edit this any time, so try out a few and see which aesthetic you like best. You can also optionally use the Embed Spatial Layers field to allow your viewers to toggle between various map styles.

The only other setting you need to change here (eventually) is Public: when you check this box, your exhibit will be live. When you’re done, click the green Save Exhibit button at the bottom of the form.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/12-create-exhibit-2.jpg)

**2\. Access the Neatline editor.** Return to the Browse Exhibits page from step 1. To access the editor, click your exhibit’s title. Clicking Public View or Fullscreen View will let you preview how your exhibit will look to visitors.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/13-access-editor.jpg)

Here is what the editor looks like. Notice the Records, Styles, and Plugins tabs, and the list of records below the blue New Record button (there won’t be any records until you add some):

![](https://docs.emerson.build/wp-content/uploads/2018/01/14-editor.jpeg)

**3\. Set the default focus.** This is the latitude/longitude and zoom that viewers will see when they first open your map (they’ll then be able to move it however they’d like). In the editor, click the Styles tab. Click and drag on your map to move it around, and use the + and – symbols at top left to zoom in and out. When you’re satisfied with the current view of the map, click the Use Current Viewport as Default button. This will automatically fill-in coordinates and the depth of zoom. You can also manually add these. When you’re done, click the blue Save button.

![](https://docs.emerson.build/wp-content/uploads/2018/01/15-default-focus.jpeg)

**4\. Import items into your exhibit**, which then become records. First, click the Records tab in the editor. Then, click the large blue New Record button.

![](https://docs.emerson.build/wp-content/uploads/2018/01/16-new-record.jpeg)

New tabs will appear. Click the Item tab. You’ll see a drop-down menu called “Search Omeka items.” This will list all the Omeka items you’ve previously created. Find the item you wish to add to the map and select it. The item’s content appears below the drop-down menu. If it looks correct, click the blue Save button. If not, click “View the item in Omeka,” edit the item, and try again.

**NOTE**: If you edit an item in Omeka that you’ve already imported into your Neatline exhibit, its record in the exhibit will be automatically updated.

**NOTE #2**: You can also create records from scratch using the New Record button and the Text tab (without making an Omeka item first). However, this isn’t recommended if you wish to include images or other media in your record, since that media would require additional HTML formatting.

![](https://docs.emerson.build/wp-content/uploads/2018/01/17-link-to-omeka.jpeg)

**5\. Pin your records to the map.** You can access any of your records from the list of records on the editor’s main page (see the screenshot in step 2 of this section, looking under the New Record button). Once you’re in a record, you can place it on the map. If you’ve just created a record using the Item tab from the previous step, then you’re already in that record.

Once in the record, click the Map tab. You can draw many different shapes here (and feel free to experiment!), but for our purposes, we’ll look at two buttons: “Navigate” and “Draw Point.”

When “Navigate” is selected, you can move your map around without adding anything. When “Draw Point” is selected, you can click on the map to place a blue pin. When a viewer clicks this pin, she’ll see the record associated with it. When you’re done, click Save.

For example: I have a record containing text and images about Shakespeare’s first performance of _Henry V_ in London. I can go into my Henry V record and use “Draw Point” to place a pin on London. Now, the viewer can click the blue dot on London to bring up this record.

![](https://docs.emerson.build/wp-content/uploads/2018/01/18-draw-point.jpeg)

Optionally, you can use the Style tab in a record (to the right of the Map tab) to change the appearance of points and shapes for that record.

You can add as many interactive points or shapes as you’d like.

**6\. Add widgets to your record (optional).** If you’re using the Waypoints widget, select it by clicking in the Widgets field. See the next step for more information about Waypoints.

When you’re done, click Save. Then, you can exit out of the record and back to the editor’s main page by clicking the X above the Style tab. You can return to Omeka by clicking “Return to Omeka.”

![](https://docs.emerson.build/wp-content/uploads/2018/01/19-style.jpeg)

**7\. Adding Waypoints: a table of contents for your map.** The following guide from Neatline.org explains how to add a list of clickable records to your map, so viewers can jump from point to point without searching the map for them:  
[http://docs.neatline.org/working-with-the-waypoints-plugin.html](http://docs.neatline.org/working-with-the-waypoints-plugin.html)

![](https://docs.emerson.build/wp-content/uploads/2018/01/20-waypoints.jpeg)

### Linking your maps to your Omeka home page

**1\. Choose what links you’d like to display on your home page’s navigation menu.** This menu may appear in a slightly different place on your homepage depending on your theme. Here’s what it looks like in one of Omeka’s built-in themes (“Thanks, Roy”):

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/21-frontpage-default.jpg)

**To edit this menu**: from your Omeka dashboard, click Appearance in the black bar at the top of the screen. Then click the Navigation tab.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/2018-04-04-at-12.42-PM.png)

This takes you to a checklist of links. Each checked link will appear on your home page’s menu. To edit a link’s label (name) or URL, click the small black arrow to its right.

**To add a new link**: fill in the Label and URL fields at the bottom of this page, and then click Add Link. You can reorder the menu by clicking and dragging the links. When you’re done, click the green Save Changes button.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/23-appearance-navigation2.jpg)

By default, there will be a link called “Neatline” which takes your viewer to a list of your Neatline exhibits. This is called the Browse Exhibits page, and looks like this:

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/24-frontpage-browse-exhibits.jpg)

If you’d rather have links on your menu to one or more specific exhibits, first pull up that exhibit’s public or full-screen view (see the screenshot for step 2 under _Managing Neatline exhibits and using the editor_ above). Copy the URL from the address bar at the top of your browser. Paste it into the URL field on Appearance > Navigation, give it a label, click Add Link, and then Save Changes.

**2\. OR, choose a different default home page.**

_To use a list of your Neatline exhibits as your home page_:  
On Appearance > Navigation, click on the drop-down menu under “Select a Homepage” (to the right of the link checklist). Select “Neatline” (or whatever you’ve renamed it). Click Save Changes to finish.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/25-appearance-navigation3.jpg)

_To use a specific exhibit as your home page (taking your viewer directly to the map)_:  
On Appearance > Navigation, add a link to the public or fullscreen view of the map you wish to be the homepage (see the previous step). Then, click on the drop-down menu under “Select a Homepage” (to the right of the link checklist). Select the link you’ve just added. Click Save Changes to finish.

![](http://www.stateu.org/docs/wp-content/uploads/2018/04/26-appearance-navigation4.jpg)

Now you can share your Omeka site’s address with whomever you’d like, and they’ll be able to explore your interactive map!

[comment]: # (feedback link here)

### 4.2.5.Working with Omeka Classic #

Here are a few tips and tricks that can help make sure you get the most out of the Omeka software.

ImageMagick
-----------

Omeka requires the ImageMagick library in order to resize and generate thumbnails for your images. University of Rochester provides ImageMagic for all accounts, but occasionally you will need to manually enter the server path to the utility. The setting for this is located under the **Settings** > **General** tab and the path to ImageMagick is **/usr/bin**

![image](https://community.reclaimhosting.com/uploads/default/original/1X/a5cd299aad7a8a3f74f461474ca93b27316ebcb4.png)

PHP-CLI
-------

Some plugins including [**CSV Import**](https://omeka.org/classic/plugins/CsvImport/) and [**Neatline**](https://omeka.org/classic/plugins/Neatline/) may need to execute code using the command-line version of PHP. If your plugin requires this it can be enabled by editing the **config.ini** file in your File Manager under **application>config**.

Navigate to the line that reads:

background.php.path = “”

Change it to the following:

background.php.path = "/usr/bin/php-cli"

[comment]: # (feedback link here)