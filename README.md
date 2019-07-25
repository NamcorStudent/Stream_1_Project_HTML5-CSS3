
# Milestone 1 Project - Music Band Website (The Bambi Molesters - The best surf-rock band in the world)

Requirement of the project was creation of the website for established music band. Website should target fans and potential fans. Showcase media of the band (photos, audio, video) and promote availability for arranging concerts/gigs.
In addition to photos, videos and audio website have to provide users with an easy access to band social links.
## UX
Project was guided with pre-set requierments.
- 4 to 5 pages or separate page areas
- Navigation and grid system present
- Semantic html5 where possible
- Responsive site
- Social links present
- Showcase of previous work
- Option for conntact and gig arrangment.
 
Therfore we may say that site was developed to provide fans with options to engage further on with band over social pages (FB, Twitter, instagram...) and also through subscription.
Potential fans are provided with audio-visual material that may make them emgage with the band.
Anyone interested in arranging the gig is empowered/wellcomomed to contact the band to check availability. 

List of User Stories, with the following general structure:
- As a fan I wish to visit "my" band's website to see what is their official social presence so I can track them more often.
- As a fan I wish to be able to check band's tour and be able to buy a ticket for particular concert without much hassle. 
- As a fan I would like to read a bit about band and its members to get more familiar with it. 
- As a fan I would like to recieve regular updates on band's activities. 
- As a fan I would like to have access to band's products.
- As a fan I want an option to ask a question to band or comment their performance (note that is also possible over FB and Twitter)
- As a potential fan I would like to be exposed to sound of the band, as well as see some videos and photos of the members withoud need to subscribe to spotify for example. 
- As a potential fan I also want to check social activities of the band and descover official chanels and see band's presence around the world. 
- As a potential client I enjoy seent some qoutes from official crititique to see would band be sutable for my event. 
- As a potential client I want easy access to initial contact with band. I wish to give them concert proposal wihtout much complication. 

Note that wireframe is deployed to github in its own wireframe directory.

## Features

Home:
Project is developed accross 5 different pages for which we use navigation bar to navigate between.
Home page is just a simple page that indicates bands name and main photo of the band. Photo is not coverin the screen as background is acting as a frame to the photo.
It is introduction to the common theme of the website. Photo also acts as and link to home page accross the website.
Alert on top is calling user for subscription on bands newsletter and it is common motive as well as call for action over the photo that encourages user to hire the band for their occasion.
On the top left social links are dominating the view by offering user to visit band's official FB, Spotify, twitter, Instagram and YouTube channels. There is also a link to the shop in case someone wants to buy some of the band's products. 
Once alert is activated modal is triggered to subscribe. Once on mobile view that option is hidden from the screen and is prosented as a part of the collapse navigation dropdown "hamburger button."
(*NOTE that shop website was not developed for the purpose of this project as it was outside of the scope and no band products were available. Instead link is provided to generic website with some of the bands albums.)

About:
Familiar layout form the landing (home) page. Instead of band name we have "About" written on a side signaling to user current page.
New is small menu under the page name that offers user an opportunity to skip through content and see parts of text he/she is more interested about. 
Text is under the main photo and as user scrolls through it, under each section is a button for quick return to the menu.
On mobile view that menu is under the photo for increased readablility. 
It is worth noting that text about band and its members is taking two thirds of the page width and is floated to the right. One third left on the left is used to present user with quotes about band from different relevant sources.
On mobile view quotes are following menu and only small selection is rendered while about text is presented whole as it is more important content to user. On mobile quotes and biography take full width.
(*NOTE that bio about band mambers would have been biggeer in real life project as they could have provide website-developer with more data)

Media:
Faliliar layout of name, menu, photo, alert and call out contuinues. On Desktop, content is presented with a small offset that brings material (video, music, gallery) into the front plane. And makes it easy to navigate. 
On mobile content is taking 100% of te width with familiar position of sub-menu and buttons to scroll to the top of the page. 
(*NOTE that real website product would have had more interesting photos and music content and/or video as it would be provided by band. Section was more developed to present a layout of the content and its representation.)

Gigs:
Simple page with familiar layout. 
Page provides user with a dates and locations of concerts as well as with button that connects them to the page where they are able to buy tickets.
While on desktop info about concert is presented linearly for increased readablility on mobile individual info data (date, location, city, ticket link) comes one over another. 
User still may sellect particular concert period per month through sub-menu but "Return to the top" button is deliberatly omitted between periods so user would get a chance to see as many concert locations as possible which increase profil of the band. 

Contact:
Last page. That is presenting users with simple contact form. Complicated forms might discurrage users from writing to the band.
Biggest change in layout is presence of alternative subscribe form as additional encouragment to the ones that might be untroustful to the alerts. 

### Existing Features
- Feature Alert - allows user to subscribe to band's newsletter by filling up modal form.
- Feature Call out -  allows user to contact band if they are interested in hireing it.
- Feature Social links - allows user to follow band's social activites (Facebook, Twitter) by clicking on it or access to extended media content (Spotify, YouTube, Instagram)
- Feature Shop - Allowas user to visit website with band's products by clicking the link button present together with social content. 
- Feature Navigation bar allows user to navigate the website by sellecting content they are interested in.
- Feature collapse nav allows for navigation bar to collapse into "hamburger" button once page is looked at on mobile phone that improves layout and user experience.
- Feature of submenu on (About, Media and Gigs pages) for user to navigate by click to the desired page content.
- Feature of the "Return to the top" button to navigate to the top of the page by click so user does not need to go trough known or undesired content (quick user friendly navigation option).
- Feature of the responsive embeded video on media page to showcase band's music video on user's click.
- Fetarue of the music player on media page to showcase band's music on user's click without leaving the websit.
- Feature of responsive lightbox gallery to showcase band's photos with easy navigation for user on his/hers click.
- Feature of "Ticket" button on gigs page for user to be re-dirrected to the site selling the tickets for the event on click. 
- Feature of subscribe on contact page for user to subscribe by submitting its email address.
- Feature of contact form for communication with band by submmiting your querey.
- Feature of re-dirrecting to home page by user clicking the main page photo.


### Features Left to Implement
- Maybe modal for "Hire Us" call to action would be better solution. User's usage data should be collectod once page is up and running. 
- Better responsivness of music player which could include whole discography. 
- News section with differen promotional content about gigs that are comming and other band's activities. 
- Feature of the video blog with band members having a laugh and comment on last gig/city.
- FQA sections including fan and clients questions and answers

## Technologies Used

- [AWS Cloud9](https://aws.amazon.com/cloud9/)
    - Cloud-based integrated development environment (IDE) used to write, run, and debug code for this project. 

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - Programing language used for creation of the website's content

- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - Programing language used for creation of unique styling of the website

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
    - Scripting language used to ensure functionality of certain elements of the project (Dropdown, Gallery overlay, Modal, Music player, Form...) 

- [Bootstrap 4](https://getbootstrap.com/)
    - Library used for simplification of website responsivness in respect to HTML. CSS and JS elements

- [Poppers.js](https://popper.js.org/)
    - JavaScript library used to ensure functionality of Bootstrap components (Dropdown of the nav-bar)

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.

- [Lightbox](https://lokeshdhakar.com/projects/lightbox2/)
    - This project uses **Lightbox** script to overlay images on gallery page

- [Google Fonts](https://fonts.google.com/)
    - Used for improved typography of the website and readablility by selection of appropriate (Fit for purpose) fonts.

- [Font Awesome](https://fontawesome.com/)
    - Icon set used for user friendly styling

- [YouTube](https://www.youtube.com/)
    - Video sharing website that is hosting videos embedded in the project's website

- [Ticketmaster](https://www.ticketmaster.ie/)
    - Ticket sales website used for mock demonstration of project's "Tickets" button functionality

- [Viagogo](https://www.viagogo.ie/)
    - Ticket resale website used for mock demonstration of project's "Tickets" button functionality

- [GitHub](https://github.com/)
    - Distributed version-control platform where that is hosting the repository for this project so other users can collaborate, fork code, share ideas and more.

- [Git](https://git-scm.com/)
    -  Open source distributed version control system used for storage and pushing project's code to its repository

## Testing
1. Navigation
    - Navigation links are displyed by convention and functional
    - On smaller screen they collapse into a user familiar button
    - They are reactive on hoovering and signal when active
    - Submenus are active and functional
    - Submenus change position on mobile to increase user experience
    - On long pages buttons are provided for quick return to the top
    - Main image is link to the home page

2. Social Links (Checking band's social presence/profile)
    - Easy to acces and functional
    - Keeping its position across pages and different devices
    - Font Awesome icons used to highlite each link by brand logo

3. Checking gigs dates
    - Page clearly named (Gigs) as a part of navigation bar. Sucesseful intuitive design/naming
    - Sub menu indicates months
    - Concerts are listed plain for easy navigation and location of important data (Date and day, Venue and Location)
    - Easy to notice button that links to ticket sales
    - Button is responsive
    - Layout changes over different devices to suit user

4. Getting familiar with the band
    - Info under About page (Intuitive navigation)
    - Submenu as well continues the practice of intuitive navigation Links from general band bio to individual ones which have member's function attached (eg, drum player) in case user doesn't know members by name.
    - Buttons provided for quick return to the top of the page

5. Receiving updates
    - Alert is present on the top of all pages calling users to subscribe for updates
    - Link is functional and of differnt color 
    - Subscribe modal is activated when the link is clicked and gives nice page overlay
    - When on mobile link is moved at the bottom of collapsed navigation 
    - On mobile easy to spot as it is shown on green background and activates same modal
    - In case user doesn't like alerts he/she may access classic subscribe form on contact page that is also functional

6. Access to products
    - Via easy to notice and ever-present "Shop" button in line with social links
    - Button racts on hover and click
    - Links to outside website with bands discography where user may buy some albums. Due to lack of currently existing product special unique shop page has not been created

7. Write to band
    - Possible through form conviniently located on "contact" page that may be accessed through navigation
    - Form is easy to fill in and is active on different screen sizes
    - Short empowerment title supporting user to write to the band
    
8. Hearing and Seeing the band
    - Navigate to Media page through navigation
    - Easy to access self-explainatory sub-menu links (Video, Music, Gallery)
    - Access to the section user is interested in
    - Reminder under the Sub-title to visit outside channel for more content which includes functional link to it
    - Functional music player deploying one full music albums
    - Functional and responsive embedded videos from YouTube website
    - Functional gallery. On click photo is zoomed in and gives an overlay and carousell option of viewing the gallery. Exit by the click anywhere outside the selected photo
    - Buttons at the end of section to return to the top of the page
    - Everything looks neat on mobile

9. Judging band's appropriatness to clients occasion
    - Functional Call to action button that empowers the client to contact the band
    - About page is providing relevant quotes
    - Showcase of audio-visual media material 
    - Contact form that encourages communication
     
Google developer tools were used to confirm responsivness of the project across different devices. 
Buttons and links functionality were confirmed by clicking.
Forms were tested by submitting unvalid and valid data before submitting them. 

### Issues with testing
- Resposivnes across different devices was ensured through combination of Bootstrap grid, sizing of elements through "viewport width" and "Viewport height" values and by using "em" and "rem" values for font sizing.
- Navbar collapse was not working due to lack of script that has to be included. Thanks to the tutor service for poining that out
- Paths in music player script had to be updated to ensure functionality of the feature
- Once gallery was introduced, dropdown menu lost its position and functionality. Developer tools pointed to the scripts that were causing issues with "hamburger" button. Once scripts were removed, functionality has restored. 
- Font Awesome icons were planned to be used in about sub-menu. Icons were not rendered due to differnce between version of FA linked to the html and FA Tags which match later version. Writing of the members function in the italic was found as better solution so link has not been updated. 
- Once tested over different sizes often the vertical space was found to be lacking so it would be adjusted to improve readablility.
- Gigs page information reandering was found to be un-pleasing on sizes between mobile and desktop so bootstrap display classes were readjusted tackle the issue.  

## Deployment

The Project was developed in AWS Cloud9 IDE. it was then committed to git and pushed to GitHub using the terminal in Cloud9.
Its Git commitments were pushed to its [GitHub repository](https://github.com/NamcorStudent/Stream_1_Project_HTML5-CSS3) by usage of The Terminal.

Over the above linked Github Repository by the usage of GitHub pages "website" is created that you may see with one click on https://namcorstudent.github.io/Stream_1_Project_HTML5-CSS3/

If you would like to **run project's code localy** you are provided with link to GitHub help page with [description of the steps to take](https://help.github.com/en/articles/cloning-a-repository).
In addition to that you may use a handy beginners [YouTube tutorial](https://www.youtube.com/watch?v=bKuE-afbRLU) on how to clone and run the code locally together with instalation of necessary tools and packages to do so. 


## Credits
Project in this form and shape would not be possible without usage of open source codes develped by following good human beings:
1. Music Player created by **Brad Traversy** whose code may be located on https://github.com/bradtraversy/html5audioplayer
2. Lightbox gallery created by **Soumyajit Nayak** whose code may be located on https://gist.github.com/shrestharikesh/f4d094e0a64f10aa991733506fd9d791


### Content
- Majority of the text for About section was copied from the real official website of music band [The Bambi Molesters](https://www.thebambimolesters.com/)
- **Note** that majority of content all together as for example quotes and gigs locations and dates are made up for the purpose of the project and to showcase functionality and page layout. 

### Media
- The photos used in this site were obtained from official The Bambi Molester releases.

### Acknowledgements
- I received inspiration for this project from awesome music played by The Bambi Molesters