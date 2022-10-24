# animated-octo-couscous
This is the Repository for the Module 1 Challenge for the Full Stack Coding BootCamp at UTA Online! This is where you can find the code to the completed web application for our module 1 challenge.

::--------------------------------------::

//  In this Challenge, a marketing agency has hired you to refactor an existing site to make it more accessible. //

//  AS A marketing agency
    I WANT a codebase that follows accessibility standards
    SO THAT our own site is optimized for search engines. //

# Improvements/Revisions Made
  //  First off I added a bit more meta to the existing code (html) in order to optimize it for general search engines to find it easier. //

//  Next I capitalized [SEO] in the name to make it look more pronouced from the Hori since it is clearly trying to be different and stick out from the entire website title. SEO being some of the services that the HoriSEOn offers. So that people can easily tell that this site is built for SEO purposes. //

//  I also began editing the look of the site. So that the Header stays fixed at the top of the screen while you scroll. I added the [fixed] position. To make it act as kind of a header navigation. //

//  Then I added a [width] to the .hero element which is clearly supposed to be the page's header.  //

//  Now I simply had to move the background image so that the header didn't overtake it at the top. I did this by moving the .hero [background-position-y] to 90 pixels. //

//  But after reviewing the assignment's Acceptance Criteria, and going over the terms that I did not understand (looking them up if neccessary), I decided to finish up just a little more of the looks before focusing solely on the code. //

//  This began with editing the header marked .seo so that the letters were capitalized. I added some [text-transform:uppercase;] in order to achieve this. //

// At this point I knew well in advance that I was going to have to change the header names and a few of the element titles to be a little more accessable to other coders. However, I figured I could go over each element one at a time after I had it looking like I wanted. And change it both in the HTML and the CSS stylesheet. //

//  Once I had the page looking like I felt it should, I switched my attention over to the actual code itself. To begin the refactoring...//

// The first thing I started working on from the top to the bottom was the <div> elements. I started with the navigation links at the top. I gave them all the div id of [header.navigation] so that they would be a little more specific, but still remain unordered as list items. //

// Next I changed the div class for the main image on the homepage to be a little more specific. Also, since the term 'hero' actually reffers to "a large image with text, often placed at the top of a webpage:" - W3schools.com, (and the text is usually overlapping the image...) I decided to take that out of the class description and just make it ["main-homepage-image"] since it does not have any words over the image itself. Rather than putting words there... //

// Next I changed the div class="content" to ["main-content"] in order to specify that it is the main site's content. The largest section of the body. //

//  Now I've changed the div class below the div class [main-content] to div id and changed the stylesheet to match the change from a class to an id using the [#]. //

// And continued to add [alt] data to each of the individual id's images...With a unique description of each image. //

// Right away I began to realize that specifics are important to keep in line with your refactoring format, you need to not only change the elements/targets type, but also the images that go along with them... ie: [id=search-engine-optimization] & [search-engine-optimization_img] both needed to be changed from class . to ids [#] //

//  I had to use a live preview to continue on with the changes, as I could not tell if I was altering the CSS and HTML in the right way in order for it to still show up on the page correctly. So I downloaded and installed the [Live-View-Server--Extension] in order to complete the rest of the code refactoring. //

// After Changing everything, I went back through to ensure that all of the id elements matched their corressponding header titles. Ex. ["cost-management"] and the title text ["Cost_Management"] To ensure it would be easier to locate within the code and easier to find on the webpage. //

//  Double checked the changes to make sure that all of the images had [alt] text. //

// Another large change that I made, was to the side part. Originally labled: [div_class="benefits"]  .  I gave it the id of "side-bar" and added a section to cover all of the side-bar code under the tag <aside> which also made it easier to keep together to the right. //

//  Another huge change was that I added <sections> tags to each of the main parts of the body section of the page. In order to separate these sections and keep them so. But still get an idea as to where they go. //

//  I also added a bottom border to each of the side-bar sections using CSS. And spaced them apart to make it easier to distingish them on the page. While still keeping the new changes made to the groupings and the names. //

//  Lastly, I went through the entire (body) section of the code, and carefully aligned all of the different selectors, elements, and tags according to their respecting parent tags. This made the code look more uniform to me. And also easier to read in general. //

//  Which I also made sure to space everything apart that I felt needed to be spaced better in order to see the different sections. They are much more easier to spot now, as you scroll through the code. //

//  There were a few last minute tweaks as well to the overall layout of the page also. Like the header had to have the padding removed completely from it. Except on the left side. And the padding had to be removed from the header-navigation section list, in order for it to still allow the links to work and look uniform. Otherwise the sticky header would overlap the page's content when you click the links at the top. And so the entire heading had to shrink. Which resulted in adding a new position attribute to the main-homepage-image element. Added: [background-position-y:50px;] to it. //

# Project's Finished Screenshot:
    https://github.com/CLynnC/animated-octo-couscous/blob/b05c02c3295741f4b2ea6d3494d617080287da16/Module-1-Challenge-Screenshot.jpg
    ![image](https://user-images.githubusercontent.com/116032409/197429439-580b238e-3225-4a1d-9ff4-bbb80a94d413.png)


# Project's Finished Deployment URL


