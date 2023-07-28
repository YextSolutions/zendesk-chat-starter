# **Help Center Template**


## Preconfigured Yext resources to build a Help Center 


# **Overview**

_Use the Help Center Starter Template to jumpstart your next Yext project. It includes everything you need to begin building your support site on Yext including Yext Content configuration, sample data, search configuration, and frontend resources._


# **What’s Included**


## Content


### Entity types & entities


#### Help Articles

This template uses the built in **Help Article** entity type and includes 5 sample help articles. See the Fields section below for a full list of fields included.


#### FAQ

This template uses the built in **FAQ** entity type and includes four sample FAQs posts (related to COVID). See the Fields section below for a full list of fields included.


#### Home Page

This template includes a custom **Home Page** entity type as well as one sample Home Page entity. This entity is used to store information that is referenced on the home page of the included help site. This makes it easy to edit the information displayed on the site directly from within the Yext CMS. 

See the Fields section below for a full list of fields included.


### Fields


#### Help Articles

The Home Page entity type makes use of several built-in fields available within Yext Content including the Name, Slug, Vote Count, Vote Sum, External Article Post Date, and External Article Update Date. It also makes use of the following custom fields included with the template:



* Help Article Body Markdown
* Category


#### FAQ Fields

The FAQ entity type makes use of several built-in fields available within Yext Content including the Question field. It also makes use of the FAQ Answer Markdown field included with the template.


#### Home Page Fields

The Home Page entity type makes use of several built-in fields available within Yext Content including the Name and Slug. It also makes use of the following custom fields included with the template:



* Cover Photo
* Heading
* Sub Heading
* Featured Articles


## Search


### Backend

Both JAMBO theme and react search experiences are powered by a single search configuration. This search configuration searches both FAQs and Help Articles. It leverages document search against help article bodies, and FAQ answers. Help article categories are configured for facets. There are starter synonyms and universal prompts included. Vertical prompts are keyed off entity names.


### JAMBO Theme

The theme frontend includes a help article search experience.


### React

The included react frontend is not yet fully studio compatible. The search frontend includes universal search, as well as vertical search for FAQs and help articles. The help article vertical includes categories. The help article cards include the article post and update date. The FAQ accordion cards render markdown when expanded.


## Pages

This includes a statically generated help site built on Yext Pages and powered by the Yext Content configuration described above.


### Templates

The repo includes two streams templates: one for the home page and one for individual article pages. Article bodies are rendered in markdown. These templates are used to statically generate pages for each entity defined in the Content section above. Read more about templates in Pages [here](https://hitchhikers.yext.com/docs/pages/templates/).


# **Installation Guide**


## Pre-requisites

This template requires access to the following Yext products:



* Content
* Pages
* Search


## How to Install



1. In the Yext platform, navigate to **Apps > Solutions**.
2. Select the **Help Site Starter Template**.
3. Click **View Solution**. This will open up the Admin Console, an account configuration tool that will allow you to add all of the resources mentioned above to your account. 
4. In the upper right corner, click **Apply**.
5. A modal window will open and prompt you to **enter your Account ID**. You can quickly find this in the URL of your Yext account, which takes the form of “[www.yext.com/s/{accountId}/…](http://www.yext.com/s/{accountId}/…)”. Enter the ID and click **Continue**.
6. In the new modal, click **Start authorization flow**. This will open a new window. When prompted, click **Authorize**. Once you receive authorization confirmation, navigate back to the Admin Console window and click **Continue**.
7. Enter your Account ID as the value for the **businessId** variable you are prompted for, then click **Save**.
8. A modal window will pop up showing all of the resources that will be added / edited within your account. Click **Continue** and, when prompted, click **Confirm**.
9. In the Console, you’ll see the message “Applying resources…”. Wait while the resources are applied. You’ll see messages in the console for each resource that is applied and will eventually receive a message saying “Successfully applied resources”.  
10. You’re done! All of the template’s resources have been added to your account. Jump back into your Yext account and explore your new resources!
