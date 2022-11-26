# The Aqua Pool

The Aqua Pool is a website for anyone who is interested in swimming. The Aqua Pool offers a variety of sessions available. A user will be able to find all the relevant information on the website. From information about the site, to checking timetables for what is on at a certain time of the day, prices for adults/juniors and 60+. The option to join a membership program and a form so the user can contact the venue with any questions. This site is targeted to all ages and abilities who are interested in swimming.

![Responsive Design](/assets/images/device-responsive.PNG)

# Features

## Home Page Features

### . Navigation

![Navigation Links](/assets/images/home-navigation.PNG)
* At the top left of the page sits the, The Aqua Pool is the name of the swimming centre. When this is clicked on any other page it will return the user to the home page.
* Positioned across from The Aqua Centre logo to the right is the navigation links for Home/Timetable/Price List/Contact Us these link to other pages. 
* The font and colour chosen contrasts well with the background. 
* The navigation links are clear and easy to understand. It is clear what the name of the swimming centre is and makes the different sections of the website easy to see and to find.

## . Hero-Image
* The main image is positioned behind the pool name and navigation bar. It stretches across the width of the page while maintaining its quality. It gives the user that extra information about what this website is. 

![Home Headings](/assets/images/home-heading.PNG)
## . Heading (Welcome to The Aqua Pool/Benefits) Section
* The heading welcomes users to learn more about the centre.
* Underneath the heading is a paragraph which explains to the user all the information they would need about that centre. From how big the pool is to how many lanes they can accommodate for. 
* Underneath the paragraph is another heading which is for the benefits of swimming. This gives the user that extra information on why swimming is such a good form of exercise mentally and physically.

![Information Sections](/assets/images/home-open-social-map-footer.PNG)
## . Opening Times/Social Links Section
* In this section are the opening times and social media links for the centre. The opening times are clear and gives valuble information to the user on when the centre is open.
* Also included are the social media links which allow the user to find the centre on Facebook, Twitter and Instagram. These all open up into seperate web pages. 

## .Google Map Section
* In this section is the map which highlights Essex. Where this fictional swimming center is based. The map is spread across the width of the page, the same as the hero image. So there is consistancy in how the site looks.

## . Footer (Copy Right)
*The footer consits of the copy right information for the centre. This like the hero image and the map, is spread across the width of the page to give conisistancy to the page. The copy right information is positioned to the center.

## .Timetable Page Features
![Timetable Page](/assets/images/timetable%20page.PNG)
![The Footer](/assets/images/the-footer.PNG)

* Consists of the same structure as the Home page with the heading and navagation links, the main image (which has changed) and the footer which hold the same positions across the width of the page to keep consistany. 
* The heading highlights that the user is on the timetable page and below is where the timetable will be.

![Timetable](/assets/images/timetable-table.PNG)
# .Timetable Section
* The timetable section consists of all the relavant infomation the user would need to see what class is on, at what specific time, on each day of the week. 
* There is a hover element to this table so when the user hovers over the class the background color will change. The idea was to link the classes so that the user would be sent to another page to fill in a form to book a class, however due to time constraints I was unable to achieve this. 


## Price List Features
![Price Page](/assets/images/price-list-page.PNG)
* Consists of the same structure as the Home page with the heading and navagation links, the main image (which has changed) and the footer which hold the same positions across the width of the page to keep consistany. 

* Heading of price list tells the user to expect information on the pricing for the centre and below is where the price list will be.

## Price Table Section
![Price Table](/assets/images/price-table.PNG)
* The user gets a clear understading of pricing for all age groups. 

## Membership Section
![Membership](/assets/images/join-us.PNG)
* The heading of Join us will make the user aware of the option to join the centre.
* The user is then invited to join a membership club with the centre. Highlighting the various benefits of joining. 


## Join Us Section
![Join Us Form](/assets/images/join-now-form.PNG)
* The user can enter their details in this join us form section. The form work correctly and I have included the required entries in all fields so for example an email address is required in the email address box and nothing else will be accepted so it must have the correct @ value included. The form sends the user back to the Home page.

# Contact Us Features
![Join Us Form](/assets/images/contact-page.PNG)
* Consists of the same structure as the Home page with the heading and navagation links, the main image (which has changed) and the footer which hold the same positions across the width of the page to keep consistany. 
* The heading of contact us will tell the user to expect a way to contact the centre. 

## Contact Us Form Section

![Join Us Form](/assets/images/contact.PNG)
![Join Us Form](/assets/images/contact-us-form.PNG)

The contact us form works correctly and I have included the required entries in all fields so for example an email address is required in the email address box and nothing else will be accepted so it must have the correct @ value included. This contact us form will send the user to a seperate page that is the thank you page. 

# Thank You Features
![Join Us Form](/assets/images/thank-you-page.PNG)
* Consists of the same structure as the Home page with the heading and navagation links, the main image (which has changed) and the footer which hold the same positions across the width of the page to keep consistany. 

## Thank You Message Section
![Join Us Form](/assets/images/thank-you-message.PNG)
* Once the user has completed the contact us form they will be sent to this thank you page which there is a thank you message, telling the user thank you for their message and that the centre will respond in a certain time period. The user can then click on the navagation links to go to any page they wish for example if they want to go back to the home page they click on home or even The Aqua Pool logo. This page is seperate from the rest and can only be accessed by filling in the contact us form. 

# TESTING
.Testing the website works in different browsers. Chrome.
.The navigation bar works and takes the user to the correct page.
.The navigation is easy to read and understand.
.Forms work correctly and I have included the required entries in all fields so for example an email address is required in the email address box and nothing else will be accepted so it must have the correct @ value included.  


### BUGS
* When testing my website on lighthouse for all screen sizes I had low performance because the jpg images were to large even though my jpg image was already compressed once.
* When trying to add screenshot images to readme.md the image wasn't showing.
* Google maps wasn't responding to any of the sizes I was entering into my style.css file.





### Solved
* By looking below at the issue that lighthouse had found, I clicked on the learn more section and through that I found out that that webp would be a better for my images than jpg. I also decided to compress the image again to make it smaller. Once the images had been converted to webp and I tested again the score went up.
* The file path I had entered didn't have a / at the beginning. /assets was needed to make the path work.
* When looking at my html document in the iframe I could see that the height and width for the map was already written in. So in my style.css file I just needed to enter 100% for the width for the map to stretch across the page. 



### Unsolved Bugs
. Even though I have changed my images from jpg to webp. The only issue I have left is that for mobile screens my performance has only increased a small amount and when last tested it had a performance rating of 80 (all other scores are at 100). The message "Serve static assets with an efficient cache policy" comes up and I unfortunately have no time left to fix this before this project is due.


# Validator Testing

* html 
I used the official W3C markup validation service to check all my HTML.
* css
I used the official W3C markup validation service (Jigsaw) to check all of my CSS styling.

* accessibility
I used lighthouse through devtools to test the accessibilty of the site. Performance, accessibility,best practaces and seo all scored highly in all tests apart from for mobile in which performance was the only section not in green, but of a score of 80. 
I can confirm that colours and fonts used are easy to read and accessable by running the site through lighthouse. 

Testing for desktop
![Mobile Performance](/assets/images/lighthouse-desktop.PNG)
Testing for laptop
![Mobile Performance](/assets/images/lighthouse-laptop.PNG)
Testing for tablet
![Mobile Performance](/assets/images/lighthouse-tablet.PNG)
Testing for mobile
![Mobile Performance](/assets/images/lighthouse-mobile.PNG)

# Deployment

The site was deployed to GitHub pages, the steps to deploy are as follows.
Start in the GitHub repository and navigate to settings tab.
From the settings tab scroll down to the pages tab.
From source select deploy from a branch, then from branch select main branch.
Once selected click save. The page will now provide the link to the complete website.

The live website link can be found here -[The Aqua Pool]()

# Credits 

. Content

using GitHub docs to figure out how to enter a screenshot to readme file
(https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#uploading-assets)

Love Running Nav Bar- some elements taken from this to create my own.

. Media - All images were taken from [Pexels](https://www.pexels.com/).
