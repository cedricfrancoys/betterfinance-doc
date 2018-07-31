# User Manual
This documentation presents the main elements the user has to deal with and details how to create new ones or update existing ones.  

Here below, the syntax `Menu > {item}` refers to the menu within the Admin area, which is accessible through [http://www.betterfinance.eu/wp-admin](http://www.betterfinance.eu/wp-admin).

## Highlights
Highlights are the items that are used by the slider at the top of the content part of the **Home page**.  
Each highlight item consists of the following fields:  

* Featured Image: should always be present and have a ratio of 3:2 (e.g. 500 x 333);
* Title: should be short enought to fit on 2 lines (approx. max 35 chars.);
* Content: should not exceed 95 chars. (will be anchored with link);
* Link: direct link to the highlighted resource (publication, article, event, ...);  
 
## Members
Members are displayed using a map of Europe. When hovering a country, a popup indicates how many members originate from that country, and clicking the popup displays a list of members.  

Individual members are accessible through URL following this canevas: http://www.betterfinance.eu/organisation/who-we-are/member-organisations/member/{name-of-the-member}

## Articles
Articles are accessible through the **Communication** section.  
Each article consists of the following fields:

* Featured Image: for better user experience, it should always be present;
* Title: the full title of the article;
* Content: the article itself (can be HTML formated), you should prefer using the featured image over embedded images in the content;
* Category : the category the publication belongs to (see below for more details);
* Brand : a meta category to attach a publication to one the BF brands (EuroShareHolders, EuroInvestors, EuroFinUse);
* Type : the type of the article, according to the **Communication** section ("Blog entry", "News", "Press coverage");
* Author : the author of the article ("Better Finance" is set by default);
  

On the website, articles can be accessed through the **Communication** section or using the following URL: [http://www.betterfinance.eu/articles/](http://www.betterfinance.eu/articles/) (full list of articles with filter and search).

Individual articles are accessible through URL following this canevas: http://www.betterfinance.eu/article/{title-of-the-article}

## Publications
Publications are documents that are accessible through the **Publications** section.    
Each publication consists of the following fields:  

* Title: the full title of the publication;
* Content: a presentation of the publication and its content (can be HTML formated);
* Category : the category the publication belongs to (see below for more details);
* Brand : a meta category to attach a publication to one the BF brands (EuroShareHolders, EuroInvestors, EuroFinUSe);
* Type : the type of the publication, according to the names listed under the **Publications** section ("Position Papers & Consultations", "Research Papers", "Press Releases", "Public Letters", "Presentations");
* Author : the author of the publication ("Better Finance" is set by default);
* Document (en) : english version of the document;
* Document (fr) : french version of the document, if any
* Document (de) : deutch version of the document, if any


Listing of existing publications is available through `Menu > Publications > All publications`, which can be filtered by date, category, type or brand; or searched by keywords.

On the website, publications can be accessed through the `Publications` section or using the following URL: [http://www.betterfinance.eu/publications/](http://www.betterfinance.eu/publications/) (full list of articles with filter and search).

Individual publications are accessible through URL following this canevas: http://www.betterfinance.eu/publication/{title-of-the-publication}

## Categories
Most contents allow to be assigned to one or more categories.  
**Articles** and **Publications** share the same list of available categories (`Menu > Publications > Categories` or `Menu > Articles > Categories`) while **Events** use a distinct event-related list of categories (`Menu > Events > Event Categories`).

## Pages

### Excerpts
In addition with the title, Campaigns pages and pages from the main menu (root level "the organisation", "publications", "events", "communication", "project & campaign"), use an "excerpt" field as a short description to be displayed on the menus when applicable. Just remember to fill it in if appropriate.

### Templates
Most of the time, pages use the default template. Existing pages have the template set accordingly with their location within the site structure.
When creating a new page, it might be necessary to select the appropriate template if it differs from the default one.

## Menus
In order to add/change/remove entries from the main menu, go to `Menu > Appearance > Menus` and edit the menu structure as desired.  

To add a link to a page into the menu structure:  

* On the left column, select the "Pages" drop-down 
* Under the "View All" or "search" tab, select the targeted page
* Click the "Add to Menu" button
* On the right column ("Menu Structure"), you can drag-and-drop the newly added page to the desired position 

## Pictures Galleries

### Create a new Picture Gallery

* Under the [admin interface](https://www.betterfinance.eu/wp-admin), go to `Menu > Photo Gallery > Add Galleries/Images`
* Next to the "Galleries" header, click the "Add new" button
* Enter the "Gallery Title" in the related input field
* Click "Add images" button
* Create a new folder, dedicated for the new Gallery: toolbar > "Make a directory" (use only alpha chars, use underscores instead of spaces)
* Double-click on the newly created directory to update the current path
* Click the "Upload files" button in the toolbar 
* Follow the instructions to pload the desired files (only picture formats are allowed: jpg,jpeg,png,gif)
* Click on the "select all" button (on the left side of the footer)
* Click on the "+ Add selected images to the gallery" button (closes the dialog)
* Under the "Basic" section, click the "Add" button (under "preview image")
* Go the the newly created directory and click once on the desired image to select it
* Click on the "+ Add" button
* Optionally, you can also add titles and descriptions to each picture of the gallery
* To save/publish the new gallery, click on the "Publish" button (opposite to the Gallery title)


### Add a gallery to the Pictures&Video page

* Under the [admin interface](https://www.betterfinance.eu/wp-admin), go to `Menu > Photo Gallery > Gallery Groups`
* Within the list of groups, click on "Main Pictures Gallery" group to open it
* Under the "Galleries and Gallery Groups" section, click the "Add" button
* Select the newly created gallery
* Click the "Add to Gallery Group" button
* To save/publish the changes, click on the "Update" button (opposite to the Gallery Group title) 
* To see the changes, go to http://www.betterfinance.eu/communication/videos-pictures/


## Template parts updates

### Update email, address, phone number
* `Menu > Appearance > Widgets > Footer Sidebar > Financepress Contact Info`
* `Menu > Appearance > FinancePress Options > Header settings`

### Update Copyright mention
* `Menu > Appearance > FinancePress Options > Footer settings`

### Update Social links in header&footer
* `Menu > Appearance > FinancePress Options > Social medias`

### Update "Terms & conditions" or Privacy & Security" links 
* `Menu > Appearance > FinancePress Options > Footer settings`