# The A-Team - Testing Information

[Website deployed on GitHub Pages](https://devtoguk.github.io/milestone-1-THE-A-TEAM/index.html)  

[Back to main README.md file](/README.md)

## Testing
- [W3C - Markup Validation Service](https://validator.w3.org/) - used to check the markup validity of the HTML documents.
- [W3C - CSS Validation Service](https://jigsaw.w3.org/css-validator/) - used to check the validity of the Cascading Style Sheets (CSS).
- [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) - used to help check the responsiveness of the site and also use of Audits to test for performance, accessibility, best practices & SEO
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - used for further performance check.  

## User stories testing (UX section of README.md)

### 1. Potential client: 

1. I need to be able to easily navigate the site to find what I need. 

    1. Whatever page a potential client lands on they are easily able to find and use the site navigation menu.
    2. The A-Team logo on all pages also leads the client back to the Home page. 

2. I want to find out how the team could help me.  

    1. After the call to action message on the Home page the arrows encourage the user to scroll down where they can find key information about how the A-Team can help.
    2. By choosing 'The Team' option on the navigation bar a client can see the abilities of each member of the team.
    3. By choosing 'Our News' option on the navigation bar a client can see news information about some previous A-Team missions. 

3. I would like to know what abilities the team have. 

    1. By choosing 'The Team' option on the navigation bar a client can see the key abilities of each member of the team. 

4. I want to see what other missions the team has done. 

    1. By choosing 'Our News' option on the navigation bar a client can get an idea of what other missions have been completed recently. 

5. I would like to read what others have said about your services. 

    1. The Testimonials part of the Home page gives a potential client some statements from satisfied customers. 

6. I wish to follow you on social media. 

    1. The footer links at the bottom of every page allow a client to go to the A-Team's social media pages and follow them.

### 2. An interested client:
1. I am interested in finding out more about how you can help me, how do I contact you?
    1. From any page the client can choose the 'Contact Us' option on the navigation bar.
    2. On the Home page the client can also click the 'Get in Touch' button.

### 3. For a fan of the A-Team:
1. I need to be able to easily navigate the site to find what I need. 

    1. Whatever page a fan lands on they are easily able to find and use the site navigation menu.
    2. The A-Team logo on all pages also leads the fan back to the Home page. 

2. I would like to find out more info & news about the team. 

    1. By choosing the 'Our News' option on the navigation bar a fan can see news information about the team and missions. 

3. I would like to see what other A-Team fans have been up to. 

    1. By choosing the 'Fan Zone' option on the navigation bar a fan can see all the photos and artwork that other fans have sent in. 

4. I want to send a photo or artwork to you. 

    1. By choosing the 'Fan Zone' option on the navigation bar and clicking the 'Upload Fan Image' button a fan can send in their own 
    photo/artwork. 

5. I wish to follow you on social media. 

    1. The footer links at the bottom of every page allow a fan to go to the A-Team's social media pages and follow them.

## Testing elements and functionality of all site pages (manual tested)

### General

- Check that all titles are consistent in size.
- Make sure that the colours of text have good contrast with their backgrounds.

### Home page 

1. Navigation bar 

    1. Ensure that alt/title text appears when hovering over the image.
    2. When the logo is clicked confirm that it links to the Home page.
    3. Alter the screen size to ensure that the navigation bar is responsive and displays the burger-icon dropdown menu at the 
    correct time, also check for any navbar overflow due to the responsive changes.
    4. Ensure that the hover transition effects work for each navbar item.
    5. Confirm that each navbar item when clicked links to the correct page and the background colour changes to indicate the 
    current page. 

2. Hero-image / Call out message

    1. Make sure the hero-image is responsive as the browser width is changed.
    (problem found on Apple device - see Errors Found section below)
    2. Ensure the hero-image remains fixed while the content below scrolls over the top.
    (problem found on Apple device - see Errors Found section below)
    3. Does the call-out message display clearly? 
    (problem found on IE11 - see Errors section below)

3. We Can Help section 

    1. Change the browser width to ensure that the 3 icons and paragraphs arrange responsively.
    2. Ensure the 'Get in Touch' button hover effect works. 
    3. Check that the 'Get in Touch' button links through to the 'Contact Us' page. 

4. Testimonials 

    1. Change the browser width to ensure that the 2 testimonials photos and statements are responsive. 
    2. Make sure the quote-marks are in the correct place.

5. Footer 

    1. Ensure that the hover transistion effects work for each social link.
    2. Confirm that when clicked each social link opens a new browser window/tab. 

6. Check all the above steps on phone and tablet. 

### The Team page 

1. Navigation bar 

    1. Already tested in the Home page section above. (as the code is the same). 

2. Team Profile Cards 
    1. Make sure that when clicked the card transition effect is working to see the stats and click to rotate back to the team member image. 
    (problem found on IE11 - see Errors Found section below)
    2. Change the browser width to ensure that the 6 cards are arranged responsively depending on the screen size.
    3. Ensure that the stat information displays correctly.
    4. Check that on smaller screens the 'CLICK TO VIEW' text appears in the top-right of each card. 

3. Footer 
    1. Already tested in the Home page section above. (as the code is the same). 

4. Check all the above steps on phone and tablet. 

### Our News page 

1. Navigation bar 

    1. Already tested in the Home page section above. (as the code is the same). 

2. Our News
    1. Change the browser width to ensure that the news stories display correctly. On smaller screens the news-line should
    move to the left and all the news stories display to the right of the line. On larger screens the news stories display 
    on alternate sides of a centered news-line. 

3. Footer 
    1. Already tested in the Home page section above. (as the code is the same). 

4. Check all the above steps on phone and tablet. 

### Fan Zone page 

1. Navigation bar 

    1. Already tested in the Home page section above. (as the code is the same). 

2. Fan Zone images 

    1. Check that the images display in the correct number of columns depending on screen width. 
    2. Ensure the 'Upload Fan Image' button hover effect works. 
    3. Check that the 'Upload Fan Image' button opens the upload modal window.
        1. Does the upload modal display ok on smaller screen sizes.
        2. The upload form should check for required fields. (this was not working: missed form tags and required)
        3. Confirm that javascript code displays the selected filename.
        4. Check the hover effect on the 'Upload' and 'Close' buttons. 

3. Footer 
    1. Already tested in the Home page section above. (as the code is the same). 

4. Check all the above steps on phone and tablet. 

### Contact Us page 

1. Navigation bar 

    1. Already tested in the Home page section above. (as the code is the same). 

2. Contact Us form 

    1. Check that the form displays on all screen sizes.
    2. Attempt to submit an empty form, check that each field displays an error when the field is required.
    3. Check that an error appears if you try to use an invalid email address.

3. Footer 
    1. Already tested in the Home page section above. (as the code is the same). 

4. Check all the above steps on phone and tablet. 

## Additional Testing  
1. Asked friends and family to check the site on their phone, tablets and desktops where possible and let me know
any issues. Got good feedback, the main changes made from this were spelling and grammar changes.
2. I have tested the site on a desktop using the following browsers: Chrome, Firefox, Edge and Internet Explorer 11. As well as testing on Android and Apple 
phones and tablets.

## Errors Found
(only includes main errors rather than small typos/alignment which caused the minor issues)  

1. **Home page - Hero-image**  

    When testing on an actual Apple device the hero-image did not size correctly and also scrolled out the way rather than content
    scrolling over it.  

    **FIX:** 
    Styling looked ok. However, found a Webflow thread with a reply by [CyberDave](https://forum.webflow.com/t/ios-fixed-background-image-not-fixed/42895) 
    which helped solve the problem by moving the hero-image into it's own DIV below the container and changing the original 
    styling slightly. 

2. **Home page - Call-out message**  

    When testing on Internet Explorer 11 the call-out message was not formatted correctly and just squashed into a thin column.  

    **FIX:** 
    Worked fine on all other browsers, it seemed that IE11 was not sizing the jumbotron correctly, but all the styling looked ok. 
    As IE11 is so old, thought it may have bootstrap issues so tried adding xs to the end of the DIV's col-12 and this worked. 

3. **Team page - Profile cards**  

    When testing on Internet Explorer 11, the profile cards when clicked to flip just displayed the reverse image of the front 
    of the card.  

    **FIX:** 
    It appeared that the backface-visibilty was an issue in some way.  After some research it appeared that indeed IE does 
    have a few issues, however I did stumble across a site using a different flip method which did work on IE11. But to use 
    this alternate method I would have to compromise on how the flip worked, unless I added a lot of Javascript. So, in the 
    end I opted to use a little Javascript to help display a version of the team stats without the flip functionality, but 
    at the same time without adding any extra content apart from a sub-text change and a message about using Internet Explorer.
    A JavaScript code snippet by [Ryan Wilson](https://stackoverflow.com/questions/49986720/how-to-detect-internet-explorer-11-and-below-versions) was used to help me detect the IE11 browser.
