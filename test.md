# TECHVANNAH WORDPRESS WEBSITE DESIGN GUIDE

## 1. WORDPRESS SETUP
-	Set up the website domain in cPanel.
-	Make the domain secure by installing an SSl certificate. This can be done using Lets Encrypt feature on the cPanel.
-	Enable redirection for all the domain URL from HTTP to HTTPS
-	Install the latest version of the WordPress core software on the server.
-	Update your user profile.
-	Record new domain and database information into tracking software or a document.
-	Remove the WordPress default content like the Hello, World! Post and comment.
-	Delete the wp-config-sample.php file.
-	Install a WordPress theme. – AVADA
-	Install necessary WordPress plugins.

    Plugins we commonly use:Contact Form 7, Buttonizer, Google Site Kit, Lite Speed Cache, RankMath SEO, Coming Soon by Seed Prod, Duplicate Page, Google Tag manger, and Avada related plugins.
-	Delete unnecessary WordPress plugins and avoid using too many plugins.
-	Customize the website to change all the basic information. This includes: the site identity, logo and favicon.
-	Colors selection. The first 4 primary colors in Avada theme should remain unchanged.  Use color palette to come up with the best combination of secondary colors according to the company theme color.
-	Set up a 404-error page. Make sure there is a page for those who get onto your site through a faulty link.



## 2. WEBSITE SECTIONS
-	### Header

    It contains the menu. The menu should have one outstanding item.
    Link header logo back to homepage. Always use correct logo dimensions.
    Page Title Bar: It can be set to look similar on all pages or different.

-	### Footer
    It is divided in to two sections.  It should contain a copyright notice, link to a privacy policy, sitemap, logo, contact information, quick links and social media icons.
    Section 2, the bottom most part of the website, should contain copyright notice and link to TechVannah.com website i.e. (© Copyright TECHVANNAH | All Rights Reserved | Created by [TechVannah IT Solutions](https://techvannah.com))

-	### Content
    - Page content should be created using Avada builder. Use containers in Avada.
    - Reuse of blocks – Save the blocks that you might need to use later. Saved blocks enable you to save a specific block within a template for later usage.

	- Format written content, avoid big blocks of text, use paragraphs, and don’t forget about headings! Proofread - double check all text on the site for mistakes and then check again. Use: [Grammarly](https://grammarly.com/) and [Hemingway](https://hemingwayapp.com/) to check grammatical and readability issues.
    - Examine page links make sure no link is broken, internal links point where they are supposed to, and external links open in a new tab. 
    - Check responsive design, optimize images to reduce image size as much as possible without compromising. tinypng can do this for you. 
    - Preview site in major browsers to check responsive design optimize images to spot cross-browser compatibility problems
    - Replace dummy content check the website for placeholder text (such as lorem ipsum) and make sure the actual (client-approved) content is in place. 
    - Images should be highly optimized, correctly named and should contain keywords.

- ### Themes
    - Avada theme should be the main theme. The website should only have two themes; Avada and another theme like Twenty twenty three that can be used in recovery in case the website is broken.
    - Make use of global containers.
    - Avada themes should be registered.

- ### Plugins

    1. **Contact Form 7**

        This will be used to create the website forms. Ensure that all the information collected on the forms is sent to the correct destination and can be accessed by the authorized person.

    2. **Buttonizer**
    
        This should be used to add dynamic customizable Smart Floating Buttons. The buttons should not be more than three and should be of the same size.
     
    3. **Google Site Kit**
    
        It should be used to connect to different Google products. It gives you insights on how people find and use your site, how to improve and monetize your content, with data from multiple Google tools. ***Site Kit*** shows key metrics and insights from different Google products:
    -	***Search Console:*** Understand how Google Search discovers and displays your pages in Google Search. Track how many people saw your site in Search results, and what query they used to search for your site.
    -	***Analytics:*** Explore how users navigate your site and track goals you’ve set up for your users to complete.
    -	***AdSense:*** Keep track of site earnings
    -	***PageSpeed Insights:*** See how your pages perform compared to other real-world sites. Improve performance with actionable tips from PageSpeed Insights.
    -	***Tag Manager:*** Use to manage your tags.
    -	***Optimize:*** Use Site Kit to easily set up Optimize. Then, set up A/B tests in Optimize.

    4. **Lite Speed Cache**
    - It should be used to optimize and speedup a website. Ensure that you configure it correctly to get the best results.

    5. **RankMath SEO**
    - This should be used for Search Engine Optimization. 

    6. **Coming Soon by Seed Prod**
    - It should be used to let the users know that your page or site is currently unavailable until the website is completed.

    7. **Duplicate Page**
    It should be used to duplicate Posts, Pages and Custom Posts easily in case you need to create similar pages and posts.

    8. **Google Tag manger** 
    9. **Avada related plugins**
    - Avada Builder:  Drag & drop Avada Website Builder.
    - Avada Core: Drag & drop Avada Website Builder.
      
# PAGES

## Homepage
- The first item is usually a slider or an image.
- It should contain call to action with the most important service.
- All the website information should be available on the homepage.

## Contact us
- It should be simple.
- It should contain all the contact information.
- It should have a map if available.

## About Page
-	Tell the story of the company and why it began.
-	Describe the consumers or the cause that the company/business serves.
-	Put a face to the company by presenting the founders or members of the team.
-	Include persuasive content.


## Service Page
-	A list of all the services, laid out in an organized way. This could be in the form of an actual list, a table, or a series of separate sections. What’s vital here is that each service is clearly distinguished from the others.
-	Detailed information about each service. Explain what the services are all about.
-	Links out to supporting information, documentation, and/or examples. Don’t overload it. Therefore, it can be helpful to link out to more details on each service.

## 3. TESTING FUNCTIONALITY 
-	Test drive web forms such as contact, order, survey. ensure that they are submitting data correctly 
-	Check your speed score use a tool like lighthouse, Google Pagespeed Insights, GTMETRIX, and Pingdom. loading time should be below three seconds.
-	Confirm form messages and redirects 
-	Test social sharing functionality check whether social sharing is in place, working properly, and includes the right platforms and profiles. 
-	Test third-party tools for ecommerce, marketing, or something else in case you are using. Double check that they are present on-site and doing what they are meant to do.

## 4. Security and Backup
-	Install an anti-spam solution. Use a solution like Akismet or antispam bee. 
-	Implement login protection
-	Set up a backup solution 
-	verify backups

## 5. SEO
-	Install and configure an SEO plugin. Use RankMath SEO plugin.
-	Set site title and tagline 
-	Configure SEO page and post titles all pages and posts on your site should have unique titles 
-	Implement meta descriptions. Create unique and expressive meta descriptions for all posts and pages that include keywords.
-	Set up permalinks make sure the permalink structure is set to your liking. Each page URL contains its main keyword. 
-	Optimize images also, check image file names, descriptions, and alt tags for keyword inclusion and make sure each image is compressed for quick loading times.
-	Set focus keyword
-	Work through content analysis when you have set the focus keyword for a site, be sure to go through the tips inside the content analysis to achieve the best results. 
-	Set up metadata.

## 6. MARKETING
-	Connect with email marketing tool.
-	Set up social icons for completeness, proper functionality, and check whether they are linking to the correct addresses.

