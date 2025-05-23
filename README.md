# Journey

Project 1 by Alice Foster

[View live github project](hhttps://foster95.github.io/journey/)

# Journey
This project creates a simple, entry level website for Journey, a community led drama company which provides a series of different classes for different ages in order to bring people together and build confidence in a safe, inclusive, welcoming space. The website is designed to give users an overview of each class that is available to access as well as to sign up to be part of the volunteer effort for Journey. The website uses bright, exciting colours, that are associated with fun, joyy and inclusivity. Across the website there are numerous images that are directly related to the classes that are available, as well as a hero image of the group. Finally the website has contrasting colours for the font to ensure maximum accessibility. 

## About Journey
Journey is a company that is based in London that provides drama classes for all ages, which aims to build confidence and foster relationships between attendees. Journey was created by one woman who stumbled into an improvisation class when she was going through a personal crisis and found a community that championed differences and individuality. She set up Journey the following year with the aim not being to create brlliant actors, but to build confidence and support anyone who is feeling a little lost and alone. 

Journey is directly inspired by Quest CIC, a community led initiative by my friend, which provides drama workshops to those young and old solely with the aim of bringing together people who do not have any sense of community. 

Journey reached out to me as they required a website which provided an overview of all classes, along with their contact details so that people could reach out to contact the company to sign up for classes. They also wanted to stress the fact that they are driven by commmunity and volunteer efforts, and they wanted to collect and encourage people to sign up to help with Journey's volunteer team.

# Table of Contents
1. UX
* User Stories
2. Design
* Wireframes
* Brand Colours
* Typography
* Images
3. Features
4. Testing
* Browser Testing
* Responsive Testing
* Device Format Testing - Mobile and Tablet
* Device Format Testing - Laptop and Desktop
5. Code Validation
* HTML Validation
* CSS Validation
5. Lighthouse Testing
6. WAVE Testing
7. Testing Errors and Bugs
8. Deployment
9. Technologies Used
10. Credits and References
11. Final Acknowledgements 

# UX
## User Stories
In order to prepare for the project a series of user stories were created to help steer and guide all the development stages. These can be found below:

1. As a community member, I want to find out detailed class information so I can  decide which class to attend
2. As a parent looking to enrol my child in classes, I want to find out the recommended age range for each class, so I can ensure I place them in the correct group.
3. As a potential Journey volunteer, I want to subscribe to a newsletter so I can be informed about upcoming volunteer opportunities
4. As a potential community member I want to understand the aims and goals of Journey, so I can decide if I allign with them.
5. As a potential attendee of the classes, I want to read testimonials from other members, so that I can find out people's personal opinions of the classes.

# Design
The website has been created across three distinct pages, covering seperate aspects of the company. All of the pages are linked by a simple navigation bar which sits in the centre of the page. All of these pages have been designed with a mobile first outlook and have then been adapted to ensure they are responsive across multiple devices.

Every page follows the same page structure and brand colours ensuring a positive user experience across every page with easy access to return to the homepage.

## Wireframes
All wireframes were generated using Balsamiq:

![Mobile Wireframes](https://github.com/foster95/journey/blob/main/assets/images/mobile-wireframes.png)

![Desktop Wireframes](https://github.com/foster95/journey/blob/main/assets/images/desktop-wireframes.png)

## Brand Colours
Journey is an all ages drama group with the aim of creating a safe, inclusive environemnt. They are focussed on bringing joy to members. Whenever I think of joy, I think of the sun and it was therefore crucial that yellow be the primary colour for the website. The project therefore originlly began with a much wider colour palette:

**Initial colour palette:**
![Initial Colour Palette](https://github.com/foster95/journey/blob/main/assets/images/initial-colour-palette.png)

On begining the website with this colour palette however, the website quickly ran into a number of issues in regards to contrast, accesibility and user experience, with too many colours causing a disjointed and potentially poor experience.

As a result the colour palette was refined, adjusting the colours to ensure that the website could still keep the yellow as the primary colour, but the other colours in the palette would be complimentary. The final selected colour palette is below.

The colours are not quite complimentary, but sit very close to each other on the colour palette, so continue to provide a satisfactory user experience.

**Refined colour palette:**
![(Refined Colour Palette)](https://github.com/foster95/journey/blob/main/assets/images/refined-colour-palette.png)

## Typography
All font came from the Google Font library.

Barrio - was used for all headers and for the site logo. Bario is one of the first fonts that is suggesed by Google for a playful font that still has good readibility across all platforms.

Archivo - was used for all other secondary text. Archivo is a sans-serif font that is very simple and modern to read which contrasts nicely with the more decorative Bario font.

## Images
All images used across the site were generated using Gemini AI through Google, with various prompts such as: 

"create me an image of a drama group of all ages rehearsing"

"create me an image of an informal adults drama group"

"change the group to children"

# Features
Every feature across the website wad chosen for the simplest possible user experience allowing all information to be easily accessible to any user, regardless of the device they were accessing the site on.

## Navigation bar
The navigation bar is always at the top of the screen and houses the Journey logo, which adjusts to a range of screen sizes.

At all times the navigation system can be seen, showing the three pages available.

The header and the navigation bar are fixed so that they are always at the top of the screen regardless of the screen size.

![(Navigation Bar Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-navbar.png)

![(Navigation Bar Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-navbar.png)

## Hero Image
The home page utilises a hero image which spans the screen and reacts responsively depending on the screen size. The hero image has a layer of opacity over the top to avoid distracting from the bulk of the text further down the page. The image looks like it is part of the website, rather than simply sitting on top of the page.

![(Hero Image Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-hero-image.png)

![(Hero Image Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-hero-image.png)

## Who are we and Journey's mission
As you scroll down the page, the user find a section which is a short summary of the company, giving any new user an overview of who the company is and why they should join journey. This is complimented by Journey's three ethos mission statement.

The misson statement sits in a flex box, allowing it to react responsively depending on the screen, moving from stacking to three columns on one page. The font size adapts slightly depending on which screen is used, but the h3 is always slightly larger than the small paragraphs underneath in order to draw visual interest.

![(Mission Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-mission.png)

![(Mission Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-mission.png)

## Classes section
This section provides a brief overview of all ofl the classes available. It had a photo which matches the class and a small section of text which provides some copy to sell each class to a prospective class attendee. Undeneath the text there is a smaller text box which contains the age range for each group and the days of the week the sessions are run. These sections are housed in boxes which model the click boxes used in the navigation bar to provide a cohesive feel acrosss the website.

In order to make this section responsive to different screens, the image size widens and expands for larger screens and shrinks for smaller screens. The text boxes are styled with flex boxes, allowing them to stack on smaller screens and expand into three individual columns on larger screens. 

## Classes information form
Underneath the classes section, there is a form which requires the user to provide their details (name, email, phone number) so that a member of the Journey team can contact them about each relevant class. All of the fields must be filled to allow submission, and on submit takes the user to a success page. This is the same success page as is used for the volunteer form page. The form is styled with the brand colours, and continue to use rounded borders to provide a sympathetic experience across the site. The submission button has styling to change colour when a user highlights over the submit button, further confirming they have submitted correctly.

![(Classes Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-classes.jpg)

![(Classes Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-classes.png)

![(Classes Information Form Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-classes-form.png)

![(Button Stasis)](https://github.com/foster95/journey/blob/main/assets/images/button-stasis.png)

## Support section
This section provides a brief overview of the volunteer opportunities that are available within Journey. As a community driven group, the majority of support for Journey comes from volunteers and therefore this was a crucial addition for the website. This section includes an unorderered list of all of the different volunteer opportunities available and is followed by a volunteer form

## Get involved form
Underneath the support section there is a form which requires the user to provide their details. Unlike the classes information form, this form does not require a phone number. This is because Journey want to talk to everyone who is potentially thinking of joining their classes, but they are more keen to simply gather information for the volunteers so they can contact them via email. All of the fields must be filled to allow submission and on submit takes the user to a success page. This is the same sucess page as is used on the class information page. The form has identical styling to the classes information form, to ensure a cohesive look.

![(Support Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-support.jpg)

![(Support Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-support.png)

## Success page
On completion of either form, a user is taken to this success page. This success page allows the user to know the information has been entered correctly and recorded by the Journey team. It features a button to return the user to the main homepage. This button has the same styling as the other submit buttons on the class information form and the volunteer form.

![(Success Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-success.png)

![(Success Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-success.png)

## Footer
The footer is consistent across every page. It has the same colour palette as the header and navbar to ensure cohesian and includes the address for Journey and Journey's social media platforms. All of the social links have an ARIA label and open in a new page.

# Future Features
* Testimonials section - due to limitations with the project and that I wanted to build solely with vanilla html and not use Bootstrap, I was unable to build a carousel of testimonials. This would be the first immediate update once I have learned Javascript

# Testing

## Browser Testing
I used testingbot to check cross compatability across multiple browsers
Browser | Device | Home | Classes | Support | Success 
--- | --- | --- | --- | --- | --- 
Chrome  | Windows 10 & Android Pixel 9 | No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected 
Edge | Windows 10 |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected 
Firefox | Windows 10 & Galaxy S21 |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |
Opera | Windows 10 & Galaxy S9 |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |  No scaling issues, showing as expected |

## Responsive Testing
I used Devtools and Blisk to test for responsive scaling across multiple screen sizes.
Device | Home | Classes | Support | Success | Notes
--- | --- | --- | --- | --- | ---
Galaxy S20 | Hero image scaling correctly, image with correct amount of padding and displaying cleanly. Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Journey mission points stack on screen and are spaced correctly | Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Images displaying and scaling correctly. Form scales correctly, submit button is centre of page, padding is correct across all paragraphs and images. | Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Padding is correct across all paragraphs. Form scales correctly, submit button is in centre of page. | Mobile navbar is fixed to top of screen, footer is fixed to bottom of page. Paragraphs are padded correctly and return button sits centrally on page. | All correct across all pages as expected and built.
iPhone 14 Pro Max | Hero image scaling correctly, image with correct amount of padding and displaying cleanly. Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Journey mission points stack on screen and are spaced correctly | Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Images displaying and scaling correctly. Form scales correctly, submit button is centre of page, padding is correct across all paragraphs and images. | Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Padding is correct across all paragraphs. Form scales correctly, submit button is in centre of page. | Mobile navbar is fixed to top of screen, footer is fixed to bottom of page. Paragraphs are padded correctly and return button sits centrally on page. | All correct across all pages as expected and built.
iPad Pro 10 | Hero image scaling correctly, image with correct amount of padding and displaying cleanly. Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Journey mission points expand to sit in three columns due to Flexbox properties centrally on the page. | Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Images displaying and scaling correctly. Form scales correctly, submit button is centre of page, padding is correct across all paragraphs and images. | Mobile navbar is fixed to top of screen regardless of scroll, footer is fixed to bottom of page. Padding is correct across all paragraphs. Form scales correctly, submit button is in centre of page. | Mobile navbar is fixed to top of screen, footer is fixed to bottom of page. Paragraphs are padded correctly and return button sits centrally on page. | All correct across all pages as expected and built. 
MacBook | Hero image scales correctly, image with correct amount of padding and displaying cleanly. Navbar is fixed to the top of the screen and displays correctly, footer sits at bottom of page. Journey mission points expand to sit in three columns due to Flexbox properties centrally on the page. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of the page. All images load correctly. Class information expands into three columns due to flexbox properties with equal padding in display. Padding is correct across all paragraphs. Form underneath scales to fill screen better, submit button stays central and fixed. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of page. Padding is correct across all paragraphs, form underneath scales to fill screen better, submit button stays central and fixed. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of page. Padding is correct across all paragraphs, return to home button sits centrally and is fixed. | All correct across all pages as expected and built.
Desktop | Hero image scales correctly, image with correct amount of padding and displaying cleanly. Navbar is fixed to the top of the screen and displays correctly, footer sits at bottom of page. Journey mission points expand to sit in three columns due to Flexbox properties centrally on the page. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of the page. All images load correctly. Class information expands into three columns due to flexbox properties with equal padding in display. Padding is not correct across all paragraphs - padding on bottom sends class information boxes out of allignment and requires individual media query to fix. Form underneath scales to fill screen better, submit button stays central and fixed. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of page. Padding is correct across all paragraphs, form underneath scales to fill screen better, submit button stays central and fixed. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of page. Padding is correct across all paragraphs, return to home button sits centrally and is fixed. | Minor padding issue on Classes page sending boxes housing class days information out of alignment Bug has since been fixed - 23/05. All other pages behaving as expected and built.
Desktop XL | Hero image scales correctly, image with correct amount of padding and displaying cleanly. Navbar is fixed to the top of the screen and displays correctly, footer sits at bottom of page. Journey mission points expand to sit in three columns due to Flexbox properties centrally on the page. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of the page. All images load correctly. Class information expands into three columns due to flexbox properties with equal padding in display. Padding is correct across all paragraphs. Form underneath scales to fill screen better, submit button stays central and fixed. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of page. Padding is correct across all paragraphs, form underneath scales to fill screen better, submit button stays central and fixed. | Navbar is fixed to top of the screen and displays correctly, footer sits at bottom of page. Padding is correct across all paragraphs, return to home button sits centrally and is fixed. | All correct across all pages as expected and built.

# Device Format Testing - Mobile and Tablet
## Index.html
![(Index Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-testing-tablet-index-complete.png)
## Classes.html
![(Classes Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-testing-tablet-classes-complete.png)
## Support.html
![(Support Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-testing-tablet-support-complete.png)
## Success.html
![(Success Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-tablet-testing-success.png)


# Device Format Testing - Laptop and Desktop
## Index.html
![(Index Format Testing Laptop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-testing-index.png)
## Classes.html
![(Classes Format Testing Laptop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-testing-classes.png)
![(Classes Form Format Testing Laptop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-testing-classes-form.png)
## Support.html
![(Support Format Testing Laptop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-testing-support.png)
## Success.html
![(Success Format Testing Laptop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-testing-success.png)

# Code Validation
# HTML Validation
## Index.html
![(Index Validation)](https://github.com/foster95/journey/blob/main/assets/images/index-html-validation.png)
## Classes.html
![(Classes Validation)](https://github.com/foster95/journey/blob/main/assets/images/classes-html-validation.png)
## Support.html
![(Support Validation)](https://github.com/foster95/journey/blob/main/assets/images/support-html-validation.png)
## Success.html
![(Success Validation)](https://github.com/foster95/journey/blob/main/assets/images/success-html-validation.png)

# CSS Validation
![(CSS Validation)](https://github.com/foster95/journey/blob/main/assets/images/css-validation.png)

# Lighthouse Testing
## Index.html - Mobile
![(Index Mobile)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-mobile-index.png)
## Index.html - Desktop
![(Index Desktop)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-desktop-index.png)
## Classes.html - Mobile
![(Classes Mobile)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-mobile-classes.png)
## Classes.html - Desktop
![(Classes Desktop)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-desktop-classes.png)
## Support.html - Mobile
![(Support Mobile)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-mobile-support.png)
## Support.html - Desktop
![(Support Desktop)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-desktop-support.png)
## Success.html - Mobile
![(Success Mobile)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-mobile-success.png)
## Success.html - Desktop
![(Sucess Desktop)](https://github.com/foster95/journey/blob/main/assets/images/lighthouse-desktop-success.png)

# WAVE Testing
## Index.html
![(WAVE Index)](https://github.com/foster95/journey/blob/main/assets/images/wave-index.png)
## Classes.html
![(WAVE Classes)](https://github.com/foster95/journey/blob/main/assets/images/wave-classes.png)
## Support.html
![(WAVE Support)](https://github.com/foster95/journey/blob/main/assets/images/wave-support.png)
## Success.html
![(WAVE Success)](https://github.com/foster95/journey/blob/main/assets/images/wave-success.png)

## Testing Errors and Improvements
### Classes.html
A minor error was discovered on the classes.html where the boxes were not sitting in allignment on desktop screens and wider. To counter this I placed this element into an individual div, with the class "info-textbox". I wrote a media query for screens 1200px and wider:

  .info-textbox {
    padding-top: 15px;
    display: flex;
    flex-direction: column;
    position: relative;
  }

This fixed the error.

Before the fix:

After the fix:

### Contrast
I also originally came up against contrast issues with my colour palette as I yellow in the header and blue as the body, but by swapping this around the contrast issue was immediately minimised. The one place where I have not made a contrast change is for the buttons on the forms and the return home button on success.html. The only way I could ensure 0 contrast issues was to break the colour palette across the rest of the website. Instead I made the text bold, and I added a hover colour which was an inversion with a higher contrast score. This did not minimise the contrast warning, but I feel is a suitable compromise that does not affect website readability, and only affects a very small portion of the website.

# Deployment

# Technologies Used
## Languages 
HTML and CSS only

## Technology
Github and Gitpod
Balsamiq
Font Awesome

# Credits and Reference
* Mercades Yearly - The originator of Quest CIC which was a massive inspiration for the entire project
* Coolors - For colour palette generation
* Gemini AI - For image generation across the project as well as some help on writing the copy
* W3Schools.com - For general support, but particularly with regards to the hero image section of the website
* The Love Running Project with Code Institute - 
* Jaqui_Alumna_lead from Slack - who provided a suggestion for a code snippet on the slack channel when I asked for assistance
* Favicon.io - For the favicon design

# Acknowledgement and thanks
* Code Institute Slack Community - For helping me see something that was so bleeding obvious if I hadn't been so code blind
* Spencer Baribal - The greatest mentor in the world, who was endlessly kind, patient and funny and gave me the confidence that I was doing the right thing and who helped me in a true hour of need
* My parents - For being brutal as ever and telling me to crack on with it and get the job done, as well as provide tirimisu and flowers when I needed it
* My fiancee Jon - who stepped up whenever I needed him and told me on more than one occasion that he would body double me till 3am if it meant I got the project done.

I would have been utterly lost without these people and their support x