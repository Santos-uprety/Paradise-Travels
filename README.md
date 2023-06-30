# PARADISE TRAVELS Responsive Website
![Website Mock Up](assets/images/screenshot%20res.png)
The live website can be found [here](https://santos-uprety.github.io/Paradise-Travels/)


## Purpose
This project was created for the purpose of First Project Portfolio for The Code Institute's Full Stack Development course.


## Table of Contents
* [User Experience Design (UX)](#User-Experience-Design)
    * [The Strategy Plane](#The-Strategy-Plane)
    * [User stories](#User-Stories)
    * [The Scope Plane](#The-Scope-Plane)
    * [The Structure Plane](#The-Structure-Plane)
    * [The Surface Plane](#The-Surface-Plane)
    * [Design](#Design)

            * [Colour Scheme](#Colour-Scheme)
            * [Typography](#Typography)
            * [Imagery](#Imagery)
    * [Differences to Design](#Differences-to-Design)
- [Features](#Features)
    * [Existing Features](#Existing-Features)
    * [Features Left to Implement](#Features-Left-to-Implement)
* [Technologies](#Technologies)
* [Testing](#Testing)

    * [Test Strategy](#Test-Strategy)
    * [Test Results](#Test-Results)
    * [Issues and Resolutions](#Issues-and-Resolutions-to-issues-found-during-testing)
*   [Deployment](#Deployment)

    * [Project Creation](#Project-Creation)
    * [GitHub Pages](#Using-Github-Pages)

* [Credits](#Credits)
  * [Acknowledgements](#Acknowledgements)

****

## User Experience Design
### **The Strategy Plane**
This website was created to test my  knowledge of HTMLand CSS and to offer users some experience with the website that is purely focused on trekking trips.

Objectives of the sites:
* To implement the basic skills I have learnt in HTML and CSS.
* To create interactive site with enough information and simple layouts that is easy to navigate.

#### User stories
* As a user, I want to grasp the site's main purpose quickly.
* As a user, I want to be able to navigate through the pages easily.
* As a user, I want to see high resolution images.
* As a user, I want this website to be responsive. 
* As a user, I want to be able to submit enquiry form.
* As a user, I want to have enough details about trekking packages offered on the website.
* As a user, I want to get detailed information about the tour provider.
* As a user, I want to be able to navigate to the social sites easily.
* As a user, I want to see great collection of images from various locations.


### **The Scope Plane**
Features planned:
* Page Heading - A page title that summarizes the page content.
* Paradise Travels.
* Home - Main content of the page.
* About us - Short description of service provider.
* We offer - A list of offered trek packages.
* Album - Photo gallery containing pictures from different locations.
* Enquiry - Enquiry form to get in touch with provider.
* Footer Items - Contact information and links to social sites.


### **The Structure Plane**

User Story:
> As a user, I want to grasp the site's main purpose quickly.
 
 Acceptance Criteria:
* Page heading displayed with text 'Paradise Travels'.
* Sub heading displayed with text 'Explore The Majestic World Of Himalaya'.

Description:<br>
The website will display a large title saying 'Paradise Travels' and a subtitle saying 'Explore The Majestic World Of Himalaya'. This will help the visitors understand the purpose of the site right away.

User Story:
> As a user, I want to be able to navigate through the pages easily.

 Acceptance Criteria:
 * Navigation bar is visible throughout all the pages.

Description:<br>
I used the float property to align the elements on the web page. I also adjusted the margin values to create some space between them. This way, I achieved a clean and balanced layout for the design.
 


User Story:
> As a user, I want to see high resolution images.
 
 Acceptance Criteria:
 * The images should be clear, sharp and not blurry or pixelated.
 * The images should be relevant to the content and the theme of the website.
 * The images should be optimized for fast loading and minimal bandwidth usage.
    

Description:<br>
My website requires high quality images, which I source from pixels.com. I reduce their dimensions using Adobe express, which optimizes them for web display.

User Story:
> As a user, I want this website to be responsive. 
 
 Acceptance Criteria:
 * The website should adapt to different screen sizes and orientations.
 * The website should load quickly and smoothly on various devices and browsers.

Description:<br>
My web design approach relies on media queries and flex properties to achieve responsiveness. This means that the layout can adapt to different screen sizes and orientations without compromising the user experience.

User Story:
> As a user, I want to be able to submit enquiry form.
 
 Acceptance Criteria:
 * The user interface should allow the user to input the required information and submit it with a simple click. The acceptance criteria for this feature are the input fields are clear and intuitive and the submit button is visible and responsive.

Description:<br>
To center an element horizontally and vertically, I applied the following CSS properties to it: position: absolute, which removes the element from the normal document flow and allows me to position it relative to its closest positioned ancestor; and transform: translate(-50%, -50%), which shifts the element by half of its own width and height in the opposite direction. This way, the element's center is aligned with its parent's center.

User Story:
> As a user, I want to have enough details about trekking packages offered on the website.
 
 Acceptance Criteria:
 * The website should display the name and location of each trekking package.
 * The website should provide a brief description of the itinerary, highlights and inclusions of each trekking package.

Description:<br>
To access the full details of the available offers, users need to select the view deals button. The view deals button is designed to help users compare different options and find the best deal for their needs.

User Story:
> As a user, I want to get detailed information about the tour provider.
 
 Acceptance Criteria:
 * The tour provider's name, location, motivation and background are clearly displayed on the page.

Description:<br>
I applied the flex property to create a responsive layout for the content. The flex property allows me to control how the elements are arranged and aligned within a container. I used flex-direction, justify-content and align-items to display the text and image in the center of the screen. I also added a read more button below the text.

User Story:
> As a user, I want to be able to navigate to the social sites easily.
 
 Acceptance Criteria:
 * The footer should have a menu bar with icons for different social sites, such as Facebook, Twitter, Instagram, etc.

Description:<br>
I wanted to add some social media icons to my website, so I decided to use font-awesome. To use them, I just had to include a link to the font-awesome CDN in the head section of my HTML file, and then add the appropriate class names to the elements I wanted to display as icons. 

User Story:
> As a user, I want to see great collection of images from various locations.
 
 Acceptance Criteria:
 * The images should be high-quality and relevant to the locations.

Description:<br>
 I decided to use Mason design to create a dynamic and responsive gallery album that adapts to different screen sizes and devices. It also gives me the flexibility to customize the appearance and spacing of the photos.




### **The Surface Plane**
### Design

#### Colour Scheme
Body colour: Grey<br>
Header and navigation colour: Brown [#36455C]<br> 
Hover background colour: Lightpink, Hotpink, Whitesmoke, Blue, [#0084ff]<br>
H2 colour: [#111]<br>
H2 span colour: Burlywood<br>
Paragraph colour: Black, [#666]<br>
Social links icons background colour: Blueviolet<br>

#### Typography
The headers and body on all pages throughout the Website are using the [https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;700&family=Roboto:wght@100;300;400;500;700&display=swap]

#### Imagery
I would like to acknowledge that all the images in the website are extracted from pixels.com.

#### Differences to Design

All aspects specified in the Structure Plane were executed according to plan.

****
## Features

### Existing Features

Home

* Heading
* Navigation bar
* Subheading
* Let's explore button
![Features](assets/images/nav%20section.png)
* About us with Read more button
![Features](assets/images/about%20section.png)
* We offer (packages with details and View deals button)
![features](assets/images/offer%20section.png)
* Footer with social links icons
![Features](assets/images/New%20footer.png)


Album
![Features](assets/images/image%20section.png)

* Heading
* Navigation bar
* Images
* Footer with social links icons

Enquiry
![Features](assets/images/enquiry%20section.png)

* Heading
* Navigation bar
* Enquiry form
* Footer with social links icons

### Features Left to Implement
* To make the Explore button and the View Deals buttons more functional, I need to add an anchor tag to each of them. The anchor tag should link to the relevant page or section that provides more information about the destination or the offer. Explore button could link to a page that shows the attractions, culture and history of the place, while the View Deals button could link to a page that shows the prices, itinerary and duration of the trip. Additionally, I could add a hover effect to the images in the Album page, so that when the user moves the cursor over them, they can see a brief caption or description of the image. This will make the Album page more interactive and engaging for the user.

****
## Technologies
* [Fontawesome](https://fontawesome.com/)
     * Font awesome are used for the social links icons in the footer.
* [HTML](https://en.wikipedia.org/wiki/HTML)
	* This project uses HTML as the main language used to complete the structure of the Website.
* [CSS](https://en.wikipedia.org/wiki/CSS)
	* This project uses custom written CSS to style the Website.
* [Google Fonts](https://fonts.google.com/)
	* Google fonts are used throughout the project to import the *Poppins* and *Roboto* fonts.
* [GitHub](https://github.com/)
	* GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [Git](https://gitpod.io/)
	* Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.   
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
	* Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
* [Techsini](http://techsini.com/multi-mockup/index.php)
    * Techsini.com Multi Device Website Mockup Generator was used to create the Mock up image in this README.

****
## Testing

### Test Strategy

#### **Summary**

Testing is done to validate HTML and CSS codes.

HTML code must pass through the [W3C HTML Validator](https://validator.w3.org/).

CSS code must pass through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).

![Results](assets/images/css%20pic1.png)<br>

Accessibility

Home desktop

![Results](assets/images/Home%20desktop.png)<br>

Home mobile

![Results](assets/images/Home%20mobile%20.png)<br>

Album desktop

![Results](assets/images/Album%20desktop.png)<br>

Album mobile

![Results](assets/images/Album%20mobile.png)<br>

Enquiry desktop

![Results](assets/images/Enquiry%20desktop.png)<br>

Enquiry mobile

![Results](assets/images/Enquiry%20mobile.png)<br>



### Test Results

![Results](assets/images/testing%20table.PNG)<br>

### Issues and Resolutions

* Subheading is not aligning as the screen size goes down.


## Deployment

### Project Creation
The first step in this project was to set up a new repository using the Gitpod full template from Code Institute. I gave the repository a name and made it public. Then I clicked on the button to create a new repository from the template. Next, I opened the Gitpod editor and selected the repository I had just created. I added an index.html file and a folder called assets that contained a Css folder. Inside the css folder, I created a style.css file.

The following commands were used for version control throughout the project:
* git add filename - This command was used to add files to the staging area before committing.
* git commit -m "commit message explaining the updates" - This command was used to to commit changes to the local repository.
* git push - This command is used to push all committed changes to the GitHub repository.

### GitHub Pages
1. Navigate to the GitHub [Repository:](https://santos-uprety.github.io/Paradise-Travels/)
1. Click the 'Settings' Tab.
1. Scroll Down to the Git Hub Pages Heading.
1. Select 'Main Branch' as the source.
1. Click the Save button.
1. Click on the link to go to the live deployed page.


****
## Credits
Credit to https://www.w3schools.com/, https://developer.mozilla.org/ and Code Institute Love Running project.


### Acknowledgements
I would like to thank my tutor Ronan for his support and insights.
****
