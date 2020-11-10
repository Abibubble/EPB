COMMENT MY CODE (WHAT THINGS DO AND WHY)
EXPLAIN WHY I MADE CERTAIN CHOICES - I.E. RESPONSIVE, WHY I MOVED SOME THINGS, WHY I HID SOME THINGS, ETC.

<h1 align="center">Escape Pool Bar Website</h1>

<img src="https://i.imgur.com/eBmDfEK.jpg" alt="Escape Pool Bar Logo" align="center">

[Here is a link to the final project](https://abibubble.github.io/milestone1-escape-pool-bar/index.html)

This is the website for Escape Pool Bar, designed to be responsive and accessible on a range of devices, making it easy to access any information that their customers could need.

![Final project image](assets/images/wireframes/project.jpg)

---
## Initial discussion
In the initial planning meeting with the bar manager of Escape Pool Bar, he requested a website that would easily provide information to customers.
The staff were spending a lot of time at the bar explaining the details of how their pool bar works to customers, which was wasting time that the staff could be doing other duties.

Their target demographic is mainly male with an age range of 16 - 65 years old. 

The main information that customers ask for are as follows:
* Pricing (table rates, guest fees)
* How their table pricing works
* Membership information
* Deals and discounts
* Parking
* Opening hours
* Contact information
* How to book a table
---
## User Experience (UX)
### User stories
#### Client Goals
* We want to have the information that customers often ask for displayed in an easy to find way.
* We want to make it easier for our customers to understand how our pricing works
* We want to make it easy for customers to find us

#### First Time Visitor Goals
* I want to easily learn more about the bar.
* I want to be able to easily navigate throughout the site to find information.
* I want to locate their social media links to see their social media prescence.

#### Returning Visitor Goals
* I want to find current information about Covid-19.
* I want to find the best way to get in contact with the organisation with any questions I may have.

#### Frequent User Goals
* I want to submit a booking request.
---
## Design
### Colour Scheme
The main colours used are white and green, to correlate with English Pool colours (green cloth, white cue ball).

### Typography
The Poppins font is the main font used throughout the whole website with Sans Serif as the fallback font in case the Poppins font isn't being imported into the site correctly.

### Imagery
The large background hero image is designed to be striking and catch the user's attention, making it clear at first glance what the company does. It has a modern aesthetic, and directly correlates to the company.

### Wireframes
[Here is a link to the Wireframes and User Navigation Map](assets/epb-wireframes.pdf)

### Features
* Text information
* Images
* PDF download
* Embedded Google Maps box
* Images carousel
* Responsive on all device sizes
---
## Technologies Used
### Languages Used
* HTML5
* CSS3

### Frameworks, Libraries & Programs Used
#### Bootstrap 4.5.2:
Bootstrap was used to help with the responsiveness and styling of the website.
#### Hover.css:
Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
#### Google Fonts:
Google fonts was used to import the 'Poppins' font into the style.css file which is used on all pages throughout the project.
#### Google Maps:
Google maps embed code was used to add the map.
#### Font Awesome:
Font Awesome was used on all pages tto add social media icons and the copyright icon.
#### jQuery:
jQuery came with Bootstrap which makes the navbar responsive.
#### Git:
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
#### GitHub:
GitHub is used to store the projects code after being pushed from Git.
#### Balsamiq:
Balsamiq was used to create the wireframes during the design process.

## Deployment
### Initial Deployment
This site was deployed to GitHub Pages by following these steps:
1. Login or Sign Up to GitHub.
2. Create a new repository named "milestone1-escape-pool-bar".
3. Once created, click on "Settings" on the main navigation bar under the repository title.
4. Scroll down to "GitHub Pages".
5. Under "Source", choose which branch to deploy (I chose "master", which can also be named "main").
6. Choose which folder to deploy from, usually "/root".
7. Click "Save", then wait for it to be deployed.
8. Your URL will be displayed above "Source". It can take some time for the page to be fully deployed.

### How to fork it
1. Login or Sign Up to GitHub.
2. On GitHub, go to Abibubble/milestone1-escape-pool-bar.
3. In the top right, click "Fork".

### How to clone it
1. Login or Sign Up to GitHub
2. Fork the repository Abibubble/milestone1-escape-pool-bar.
3. Above the file list, click "Code".
4. Choose if you want to clone using HTTPS, SSH, or GitHub CLI, then click the copy button to the right.
5. Open Git Bash.
6. Change the directory to where you want your clone to go.
7. Type gitclone and then paste the URL you copied in step 4.
8. Press Enter to create your clone.

---
## Testing
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
* [W3C Markup Validator - Results](link) <--LINKS-->
* [W3C CSS Validator - Results](link) <--LINKS-->

### Testing User Stories from User Experience (UX) Section
#### First Time Visitor Goals
##### I want to easily learn more about the bar.
Upon entering the site, users are greeted with a navigation bar that is clean and easy to read to take them to the information that they need. 
Underneath this, there is a hero image of a game of pool, making it obvious at first glance what the website is for. 
The user then has two options - click in the navbar to navigate to another page, or scroll down. 
Scrolling down leads to more information about the bar.

##### I want to be able to easily navigate throughout the site to find information.
At the top of each page there is a clean and easy to read navigation bar, with each link describing what the page they will end up at clearly. 
The logo in the top left of each page also links to the homepage, following standard convention.

##### I want to locate their social media links to see their social media prescence.
In the footer of each page, there is a link to their Facebook site. 
In the Contact Us page, there is a link to their Twitter page, and two links to their Facebook site (one to the Facebook in general, and one to prompt to book a table). 
Any links that they click to an external site will open up in a new tab to ensure the user can easily get back to the website.

#### Returning Visitor Goals
##### I want to find current information about Covid-19.
On the homepage, there is a bright yellow scrolling banner that is eye-catching and bold, directly under the navbar that explains the current situation with Covid-19.

##### I want to find the best way to get in contact with the bar with any questions I may have.
The navigation bar has a clear link called 'Contact Us', where all the contact details are visible. 
The user can also scroll to the bottom of any page on the site to locate contact details and a Facebook link in the footer.

#### Frequent User Goals
##### I want to submit a booking request
Scrolling down on the Contact Us page gives a form on tablet and desktop that cal be filled in to submit a table booking request. 
There is also an alternative link to their Facebook page, where a table booking can also be submitted.

### Full Testing
On every device and browser, I tested the following:
* Click the top left logo to take us to Homepage from Homepage
* Click the top left logo to take us to Homepage from Membership
* Click the top left logo to take us to Homepage from How It Works
* Click the top left logo to take us to Homepage from Gallery
* Click the top left logo to take us to Homepage from Contact Us

* Click the Home button in the navbar to take us to Homepage from Homepage
* Click the Home button in the navbar to take us to Homepage from Membership
* Click the Home button in the navbar to take us to Homepage from How It Works
* Click the Home button in the navbar to take us to Homepage from Gallery
* Click the Home button in the navbar to take us to Homepage from Contact Us

* Click the Membership button in the navbar to take us to Membership from Homepage
* Click the Membership button in the navbar to take us to Membership from Membership
* Click the Membership button in the navbar to take us to Membership from How It Works
* Click the Membership button in the navbar to take us to Membership from Gallery
* Click the Membership button in the navbar to take us to Membership from Contact Us

* Click the How It Works button in the navbar to take us to How It Works from Homepage
* Click the How It Works button in the navbar to take us to How It Works from Membership
* Click the How It Works button in the navbar to take us to How It Works from How It Works
* Click the How It Works button in the navbar to take us to How It Works from Gallery
* Click the How It Works button in the navbar to take us to How It Works from Contact Us

* Click the Gallery button in the navbar to take us to Gallery from Homepage
* Click the Gallery button in the navbar to take us to Gallery from Membership
* Click the Gallery button in the navbar to take us to Gallery from How It Works
* Click the Gallery button in the navbar to take us to Gallery from Gallery
* Click the Gallery button in the navbar to take us to Gallery from Contact Us

* Click the Contact Us button in the navbar to take us to Contact Us from Homepage
* Click the Contact Us button in the navbar to take us to Contact Us from Membership
* Click the Contact Us button in the navbar to take us to Contact Us from How It Works
* Click the Contact Us button in the navbar to take us to Contact Us from Gallery
* Click the Contact Us button in the navbar to take us to Contact Us from Contact Us

* Click the Facebook link in the footer to take us to their Facebook page in a separate tab from Homepage
* Click the Facebook link in the footer to take us to their Facebook page in a separate tab from Membership
* Click the Facebook link in the footer to take us to their Facebook page in a separate tab from How It Works
* Click the Facebook link in the footer to take us to their Facebook page in a separate tab from Gallery
* Click the Facebook link in the footer to take us to their Facebook page in a separate tab from Contact Us

* Click the Facebook link in the main body of the page to take us to their Facebook page in a separate tab from Contact Us
* Click the Twitter link in the main body of the page to take us to their Twitter page in a separate tab from Contact Us

* Click the Download Membership form to open a PDF membership form in a separate tab from Membership page

* Attempt to submit the form on Contact Us without a full name
* Attempt to submit the form on Contact Us without an email address
* Attempt to submit the form on Contact Us without a date
* Attempt to submit the form on Contact Us without a start time
* Attempt to submit the form on Contact Us without an end time
* Attempt to submit the form on Contact Us without a table type

* Click to drop down the answers to each FAQ on the Contact Us page
* Click to scroll backwards and forwards through each image on the Gallery page

#### Desktop / Laptop
1. Chrome
* 

2. Edge
* 

3. Firefox
* 

4. Internet Explorer
* 

#### Tablet
1. Chrome
* 

#### Mobile
1. Chrome
* 

2. Safari
* 

3. Samsung Internet
* 

EXPLAIN FULLY EVERY TEST I DO, SO SOMEONE ELSE COULD REPLICATE THE TEST
SCREENSHOTS ARE GOOD WHEN BUGS ARE FOUND
LIGHTHOUSE IN DEVTOOLS, PLUS SCREENSHOTS

### Further Testing
The website was tested on Google Chrome, Firefox, Internet Explorer, Microsoft Edge, Safari and Samsung Internet browsers.
The website was viewed on a variety of devices, including:
* Desktop
* Laptop
* iPad
* Amazon Fire tablet
* iPhone 7
* iPhone X
* iPhone 12
* OPPO Find X2 Lite
* Samsung Galaxy A70
* Samsung Galaxy S9
* Samsung Galaxy S10+
* Samsung A20

A large amount of testing was done to ensure that all pages were linking correctly, all buttons worked as they should, and the form .
Friends, family members, members of staff and 13 customers were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Solved Bugs

### Known Bugs
On mobile, the nav bar moves slightly behind the URL area upon scrolling down.

---
## Credits
### Code
* Bootstrap4: Bootstrap Library used throughout to make site responsive using the Bootstrap Grid System.
* https://dev.to/ryandsouza13: For help with the code to make a marquee effect without the outdated marquee tag

### Content
* All text content written by Andrew Chubb, Conor Nye, and the developer.
* All other code was written by the developer.

### Media
* Logo designed and created by Andrew Chubb, Owner of Escape Pool Bar.
* All photos were taken by Conor Nye, Bar Manager at Escape Pool Bar.

### Acknowledgements
* My mentor, Antonio Rodriguez, for continuous helpful feedback and support.
* The team at Escape Pool Bar, for giving me the opportunity to create their website.
* Eve Crabb and Tom Crabb, for their support and help through my learning.
* JimLynx_lead on Slack, for his continuous support and guidance.
* The team at Code Institute, for teaching me the necessary skills to create this site.