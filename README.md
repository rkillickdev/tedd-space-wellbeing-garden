# **Tedd-Space Wellbeing Garden Website**
The Tedd-Space website has been designed to provide visitors with the opportunity to gather information about a fictional community wellbeing garden based in Teddington, TW11.  The goal of the site owner is to create an online presence to give greater exposure to the garden and increase the user base within the TW11 community. There is a particular emphasis on the positive impact of horticulture and nature on our wellbeing and mental health.

Site users can learn about the ethos and vision of the garden, gain better understanding of the links between nature and wellbeing, gather information about how the garden engages the local community, and easily find the details they need to visit.   They can also learn about volunteering opportunities and register their interest in getting involved.
___

# **CONTENTS**

* User Experience (UX)
    * Strategy
    * Scope
    * Structure
    * Skeleton
    * Surface
* Technologies Used
    * Languages Used
    * Frameworks, Libraries & Programs Used
* Deployment & Local Development
    * How to Fork
    * How to Clone
* Testing
* Credits
    * Code Used
    * Content
    * Media
    * Acknowledgements

# **User Experience (UX)**

## **STRATEGY**
___

### **Why build this site?**
<br>
The wellbeing garden was completed in April 2022. Market research carried out by Richmond Council within the local community has highlighted that many residents of TW11 do not know about the garden. So a core goal of the website will be to increase exposure in the hope of attracting a new diverse user base.

<br>

Research has highlighted the toll that the pandemic had on wellbeing and mental health.  So another core goal of the website will be to emphasise how the benefits of the garden can be two fold. Time spent outside engaging with nature along with the opportunity to reduce isolation by connecting with the community.

<br>

### **What is needed?**

<br>

The website will be an online resource where users will go to understand more about the garden, how they can visit and how it could improve their lives.

<br>

___

## **User Stories**
<br>

### Client Goals:

<br>

* As the client, I want to boost the profile of the garden by creating an online presence.
* As the client, I want to increase accessibility of the garden by promoting the location and opening hours.
* As the client, I want to encourage positive mental health in the community by promoting the benefits of the garden for emotional wellbeing.
* As the client, I want to make users aware of how the garden can help them connect with the community through a range of organised events/ classes/ activities.
* As the client, I want to increase the number of active volunteers
* As the client, I want to make sure the site can be viwed on a range of different sized devices

<br>

### First Time Visitor Goals:

<br>

* As a first time user, I want to know more about how the garden was created and it’s vision for the community.
* As a first time visitor, I want to know how the garden could have a positive impact on my wellbeing, so I can decide whether I could use it.
* As a first time visitor, I want to view address details and opening hours, so that I know where to visit and when.
* As a first time visitor, I want to be able to find out more about volunteering, so I can decide whether this could be for me.
* As a first time visitor, I want to learn more about the activities that run in partnership with the garden, to decide whether these would be of any interest to me.

<br>

### Return Visitor Goals:

<br>

* As a return visitor, I want to make contact to offer my time as a volunteer, so I can feel connected with the community.
* As a return visitor, I want to learn **more** about how horticulture and being surrounded by nature can improve our mental health.

<br>

### Repeat Visitor Goals:

<br>

* As a repeat visitor, I want to be kept up to date with Tedd-Space news, updates and future events, so I can stay informed and feel connected.

<br>

## **SCOPE**
___

<br>

| Opportunity/ Problem                                       | Importance | Viability/ Feasibility |
| :--------------------------------------------------------- | :--------: | :--------------------: |                         
| Create online presence to increase awareness of the garden | 5          | 5                      |
| Promote benefits of gardens for wellbeing                  | 4          | 5                      |      
| Provide news/updates about garden.Promote upcoming events  | 3          | 1                      | 
| Encourage volunteers to get involved                       | 4          | 4                      |
| Promote community aspect of the garden                     | 3          | 4                      |
| Start a blog. Horticulture/ Wellbeing etc                  | 2          | 1                      |



<br>



### **Features To Be Included:**

<br>

* An About section that makes the user aware of what the garden is and its primary goals and objectives.

* A Wellbeing section that explains some of the design features used in the garden to promote positive mental health.

* A Community section where the user can learn ways in which the garden can be used to stay active, interact with others and educate future generations.

* A Visit section where users can obtain the information they need to visit the garden - address details, opening hours.

* A Volunteer section where users can find out more about the volunteers that help run the garden.  If interested there is an opportunity for the user to make contact via a form.

<br>

### **Future Implementations:**

<br>

* Addition of a news, updates and upcoming events section.  For now this information can be accessed externally by clicking social media links, but it would nice to eventually integrate a live feed into the site.

* Addition of a blog page with varied topics covered.  This would give the user the chance to find out more detailed information about the core goals of the site owner, for example in depth features and articles about how gardens and horticulture can improve our physical and mental wellbeing.  This would be a neater solution than simply adding links for articles on external sites.

<br>

## **STRUCTURE**

___

<br>

### **Common Features**

<br>

* A favicon is displayed in each browser tab.  The image is a squared off version of the logo used in the header. It is a 16px X 16px ico file generated on the [Favicon.ico & App Icon Generator](https://www.favicon-generator.org/) 

* The header will feature at the top of each page with the site name and logo to the left and a responsive navigation bar will be positioned to the right.  This header will remain fixed as you scroll down the page, always allowing the user to easily jump to the section they are interested in.  Clicking on the Tedd-Space name and logo wil always take the user back to the about page.  Clicking on the navigation links will jump the user to the relevant section. Following the principles of information architecture,  as these links are all closely tied to the core user needs and owner objectives they are positioned at the highest level of the site.  Hovering over any of the navigation menu links transforms the font size to 120% and the cursor changes to a hand pointer, indicating that clicking will take the user to a new page, therefore making the experience intuitive.  The current page link in the menu shows as bold to always inform the user where they are within the site.   

* To ensure a good user experience in all situations, a media query is used to prevent the naviagtion bar looking squashed and cluttered on mobile devices with smaller screen sizes.  The navigation bar is replaced with a burger menu toggler at 950px and under.  For screens at 450px and under, a further media query is used to reduce the overall size of these header items to give everything space.  When the burger icon is selected, the header expands vertically with the navigation menu displayed. I have chosen this method of using the burger icon as it follows convention and is immediately recognisable.  It therefore aligns with user expectation, providing them with an intuitive experience as they navigate the sight.  A recognisable cross icon is used to indicate to the user that clicking will close the menu.

* The footer will feature at the bottom of each page, with social media links to the Tedd-Space Facebook, Twitter and Instagram pages opening in new browser tabs when clicked.  Font awesome icons are used as they are universally recognisable for the user without the need for text.  A hover effect which transforms the icon size to 110% and changes the colour to a lighter green indicates to the user that these links are clickable.  A secondary navigation menu is positioned in the centre of the footer, incase the user is ever at the bottom of the page and wants to naviage to a new location.  A hover effect increasing the font size to 120% indicates that these links are clickable. To ensure that the Tedd-Space brand is visible throughout, the name appears on the left of the footer and clicking on this will always direct the user back to the home page.

<br>

### **About Page**

<br>

* The aim of the owner is that the purpose of the site should be immediately evident to the user when they land on the home page.  This is achieved by using a hero image of a close up leaf that instantly indicates to the user that the site relates to nature and the dark green colour aims to achieve an emotional response of calmness.  The user is then provided with two core pieces of information as the hero text fades in, to make clear that Tedd-Space is a wellbeing garden and it is located in the TW11 postcode.

* The user is then provided with a concise welcome section where they can understand exactly what Tedd-Space is and what it aims to achieve. This is accompanied by an image which hopes to envoke a positive emotional response ( "this is somewhere I would like to spend time" ) and draws them to learning more about the wellbeing garden.

* The core goals of Tedd-Space are laid out next, to demonstrate to the user 3 different ways the garden could benefit them.  Icons are used above each goal as hints, so the user understands the core aims of Tedd-Space before they have even read the etxt.  Under each goal, an explore button makes it intuitive for the user to learn more about each topic without even having to use the top navigation menu.  This is an example of using progressive disclosure, to engage the user and gradually present them with more content as they navigate the website.  For consistency of user experience, the explore buttons feature the same transform effect on hovering as experienced in the header and footer.

<br>

### **Wellbeing Page**

<br>

* This page provides the user with further information about how the Tedd-Space garden can improve wellbeing.  To ensure consitency of user experience, the page layout is similar in format to the about page. There is a concise intro, a calm image to convey the theme of wellbeing and then 3 design features to look out for.

<br>

### **Community Page**

<br>

* This provides the user with information about the community aspect of Tedd-Space.  The timetable of activities is prominent and features the same background leaf image used on the landing page.  The follow us button makes it easy for the user to find social media links, and there is a link to direct them back  to the timetable if they have scrolled past this but then want to find out more.  

* The slide show provides the user with an opportunity to interact with the site and build an understanding of how the garden could be used.

* Descriptions of 3 different types of community engagement are detailed in the familiar 3 column layout (collapses to single column on mobile devices below 950px).  Font awesome icons ensure that there is continuity and familiarity between pages.

<br>

### **Visit Page**

<br>

* Now that the user has been presented with information about the garden and it's benefits, it is important to provide them with the information needed to visit.  An interactive embedded Google Map shows location and if zoomed out, can give the user context about surrounding areas.  Also core information with full address and opening hours, makes the opportunity to use the garden as simple as possible.  The site owner hopes that this will result in an increase in the user base.

<br>

### **Volunteer Page**

<br>

* Users are presented with some information about the volunteering opportunities.  They will also have the opportunity to interact with a form by submitting their name, email address, using a drop down menu to signal their availability and a text field for any further details.  A send button with familiar consistent hover effect allows users to submit this information.  Feedback will be give to the user throughout the form interaction, with each input field highlighted when in focus and tooltip alerts if a required field has not been filled in correctly.

<br>

### **Thankyou Page**

* Once the form has been submitted successfully, feedback will given to the user by directing them to a thankyou page.  Here they will be thanked for their interest and told that someone from Tedd-Space will be in touch as soon as possible.  The keep exploring button allows users to be guided back to the website home page. 

<br>



## **SKELETON**

___

<br>

### **Wireframes**

<br>

Wireframes for desktop, tablet and mobile:

* Index Wireframe
* Wellbeing Wireframe
* Community Wireframe
* Visit Wireframe
* Volunteer Wireframe
* Thankyou Wireframe

<br>

## **SURFACE**

___

<br>

## **Colour Palette**

<br>

The website aims to use a calming colour palette to align with the Tedd-Space ethos of promoting calm minds.  The user should get the same sense of calmness and wellbeing when navigating the site as they would when visiting the garden.  Green is known to be a soothing colour and also gives the user a sense of being surrounded by nature.  The palette is limited to keep the site looking clean, simple and spacious.  Colours from the [close up leaf](docs/leaf-hero-ref.webp) hero image were extracted using the generator tool on the [coolors](https://coolors.co/) website.  This is the basis for the dark green text that is used consistently throughout the site and the occassional lighter green that is used to give user feedback when hovering over buttons.  The white smoke colour is used against a pure white backdrop to structure the website in a simple clean way, highlighting columns,text boxes and the footer. 

<br>

![Tedd-Space colour palette](docs/tedd-space-colour-palette-resize.png)


<br>

## **Contrast**

<br>

The simple colour palette means that there is good contrast between the background and text.  I used the WebAim [contrast checker](https://webaim.org/resources/contrastchecker/) to investigate contrasts.

<br>

![Tedd-Space colour palette contrast check](docs/tedd-space-contrast-check.png)

<br>

To ensure that the contrast between the hero background image and hero text was optimal, I applied a linear gradient on the image as a CSS rule to make it darker and help the white text stand out more.

<br>

## **Typography**

<br>

Spacing and typography will remain consistent throughout the site to give the user a sense of familiarity wherever they navigate to another page.  Icons will be used alongside informational headings to hint at content.  The following fonts have been selected from Google Fonts:

* Headings:  Montserrat.  This is a sans-serif font.
* Body:  Source Sans Pro.  This is a sans-serif font.
* Hero text and Summer Timetable:  Amatic SC.  This is a cursive font.

Inspiration for the font combination came from this [article](https://www.thedenizenco.com/journal/clean-minimal-font-pairings) about clean minimal font pairings. 

<br>

## **Images**

<br>

## **Accessibility**

___

<br>

To enusure that the website is as accessible as possible for all users and compatible with screen readers, I have done the following:

* Semantic markup has been used to structure the HTML code.
* Check that the colour contrast ratio across the website meets acceptable standards.
* Descriptive alt attributes have been given to all images.
* Aria labels have been used for interactive elements where no accessible name is provided. For example the hamburger menu icon I have used for smaller screen sizes or the social media links in the footer.
* The aria hidden attribute has been added to icons that are purely decorative. 


# **Technologies Used**

<br>

## **Languages Used**

<br>

HTML and CSS were used to create the website.

<br>

## **Frameworks, Libraries & Programs Used**

<br>

* Git -  Version control.
* GitHub - All files for the website stored and saved in a repository.
* GitHub Pages - Used to deploy the final version of the website.
* Balsamiq - Used to create wireframes.
* Font Awesome - Used for all icons throughout the website.
* Google Fonts - Used to import required fonts for the website via the css style page.
* Google Developer Tools - Used throughout build of website for debugging and trialing new features/ styling.
* Google Lighthouse - Used at testing stage to show statistics for performance, accessibility,  best practices and SEO.
* TinyPNG - For compression of image files to improve website performance.
* Birme - For resizing and reformatting images to make them suitable for use on the website.
* Am I Responsive? - For displaying images of how the website looks across a range of devices.

<br>

# **Deployment & Local Development**

<br> 

## **Deployment**

<br>

The live website has been deployed using GitHub Pages, following the steps below:

1. Log in (or sign up) to GitHub.
2. Click on the required repository, in this case: rkillickdev/tedd-space-wellbeing-garden
3. Go to the "Settings" menu.
4. Select the "Pages" tab in the left hand menu - this will jump you to a section called "GitHub Pages".
5. Under the Build and deployment section, select "main" from the select branch menu.  Select "root" from the dropdown select folder menu.
6. Click save.  The URL for your live site which has been deployed on GitHub pages is shown at the top of the GitHub pages section.  This sometimes does not display immediately or may require a browser refresh.

<br>

## **Local Development**

<br>

### **How to fork:**

<br>

1. Login to GitHub.
2. Find the required repository, in this case: rkillickdev/tedd-space-wellbeing-garden
3. Click on the "fork" button at the top right of the page.

<br>

### **How to clone**

<br>









# **Credits**

## **Code Used**

* [Tutorial for setting base CSS and setting up CSS Grid/ Flexbox](https://www.youtube.com/watch?v=p0bGHP-PXD4)
* [Inspiration for navbar box shadow from Tails.com website](https://tails.com/gb/)
* [Solution for creating fixed navbar with content scrolling underneath](https://stackoverflow.com/questions/40772841/how-to-position-fixed-the-navbar-when-using-flexbox)
* [Tutorial for creating picture slideshow on community page](https://www.youtube.com/watch?v=McPdzhLRzCg)
* [Inspiration for linear gradient on hero background image](https://www.w3schools.com/howto/howto_css_hero_image.asp)
* [Hero image text fade in animation](https://blog.hubspot.com/website/css-fade-in)
* [Tutorial for creating hamburger nav menu for mobile devices](https://www.youtube.com/watch?v=SIzi9z8mrTk)
* [How to style placeholder text](https://www.samanthaming.com/tidbits/57-styling-css-placeholder/)
* [Emeddding google maps on visit page](https://blog.hubspot.com/website/how-to-embed-google-map-in-html)
* [Adding a favicon to the browser tab](https://www.w3schools.com/html/html_favicon.asp)
* [Meta Tags IO for improving site visual appearance on social media](https://metatags.io/)
## **Content**

* [Inspiration for Typography](https://www.thedenizenco.com/journal/clean-minimal-font-pairings)

## **Media**

* [Free Logo Maker Website used for Tedd-Space logo](https://logomakr.com/app)

## **Acknowledgements**


