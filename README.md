# Journey

Project 1 by Alice Foster

[View live github project](https://foster95.github.io/journey/)

# Journey
This project creates a simple, entry level website for Journey, a community led drama company which provides a series of different classes for different ages in order to bring people together and build confidence in a safe, inclusive, welcoming space. The website is designed to give users an overview of each class that is available to access as well as to sign up to be part of the volunteer effort for Journey. The website uses bright, exciting colours, that are associated with fun, joyy and inclusivity. Across the website there are numerous images that are directly related to the classes that are available, as well as a hero image of the group. Finally the website has contrasting colours for the font to ensure maximum accessibility. 

## About Journey
Journey is a company that is based in London that provides drama classes for all ages, which aims to build confidence and foster relationships between attendees. Journey was created by one woman who stumbled into an improvisation class when she was going through a personal crisis and found a community that championed differences and individuality. She set up Journey the following year with the aim not being to create brlliant actors, but to build confidence and support anyone who is feeling a little lost and alone. 

Journey is directly inspired by [Quest CIC](https://www.questsoultheatre.co.uk/), a community led initiative by my friend, which provides drama workshops to those young and old solely with the aim of bringing together people who do not have any sense of community. 

Journey reached out to me as they required a website which provided an overview of all classes, along with their contact details so that people could reach out to contact the company to sign up for classes. They also wanted to stress the fact that they are driven by commmunity and volunteer efforts, and they wanted to collect and encourage people to sign up to help with Journey's volunteer team.

![amiresponsive](https://github.com/foster95/journey/blob/main/assets/images/am-i-responsive.png)
Image from [amiresponsive](https://ui.dev/amiresponsive?url=https://foster95.github.io/journey)

# Table of Contents
1. [UX](#ux)
   - [User Stories](#user-stories)
2. [Design](#design)
   - [Wireframes](#wireframes)
   - [Brand Colours](#brand-colours)
   - [Typography](#typography)
   - [Images](#images)
3. [Features](#features)
4. [Testing](#testing)
   - [Browser Testing](#browser-testing)
   - [Responsive Testing](#responsive-testing)
   - [Device Format Testing for Mobile and Tablet](#device-format-testing-for-mobile-and-tablet)
   - [Device Format Testing for Laptop and Desktop](#device-format-testing-for-laptop-and-desktop)
5. [Code Validation](#code-validation)
   - [HTML Validation](#html-validation)
   - [CSS Validation](#css-validation)
5. [Lighthouse Testing](#lighthouse-testing)
6. [WAVE Testing](#wave-testing)
7. [Testing Errors and Improvements](#testing-errors-and-improvements)
8. [Deployment](#deployment)
9. [Technologies Used](#technologies-used)
10. [Credits and References](#credits-and-references)
11. [Acknowledgement and thanks](#acknowledgement-and-thanks)

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
All wireframes were created using Balsamiq:

![Mobile Wireframes](https://github.com/foster95/journey/blob/main/assets/images/mobile-wireframes.png)
![Desktop Wireframes](https://github.com/foster95/journey/blob/main/assets/images/desktop-wireframes.png)

## Brand Colours
Journey is an all ages drama group with the aim of creating a safe, inclusive environemnt. They are focussed on bringing joy to members. Whenever I think of joy, I think of the sun and it was therefore crucial that yellow be the primary colour for the website. The project therefore originlly began with a much wider colour palette:

### Initial colour palette:
![Initial Colour Palette](https://github.com/foster95/journey/blob/main/assets/images/initial-colour-palette.png)

On begining the website with this colour palette however, the website quickly ran into a number of issues in regards to contrast, accesibility and user experience, with too many colours causing a disjointed and potentially poor experience.

As a result the colour palette was refined, adjusting the colours to ensure that the website could still keep the yellow as the primary colour, but the other colours in the palette would be complimentary. The final selected colour palette is below.

The colours are not quite complimentary, but sit very close to each other on the colour palette, so continue to provide a satisfactory user experience.

### Refined colour palette:
![(Refined Colour Palette)](https://github.com/foster95/journey/blob/main/assets/images/refined-colour-palette.png)

## Typography
All font came from the Google Font library.

- [Barrio](https://fonts.google.com/specimen/Barrio?preview.text=Journey&categoryFilters=Feeling:%2FExpressive%2FPlayful) - was used for all headers and for the site logo. Bario is one of the first fonts that is suggesed by Google for a playful font that still has good readibility across all platforms.
- [Archivo](https://fonts.google.com/specimen/Archivo?preview.text=Journey&query=Omnibus-Type) - was used for all other secondary text. Archivo is a sans-serif font that is very simple and modern to read which contrasts nicely with the more decorative Bario font.
- [Font Awesome](https://fontawesome.com/icons) - was used for social media icons in the footer

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

![(Footer Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-footer.png)
![(Footer Desktop)](https://github.com/foster95/journey/blob/main/assets/images/desktop-footer.png)

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

# Device Format Testing for Mobile and Tablet
## Index.html
![(Index Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-testing-tablet-index-complete.png)
## Classes.html
![(Classes Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-testing-tablet-classes-complete.png)
## Support.html
![(Support Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-testing-tablet-support-complete.png)
## Success.html
![(Success Format Testing Mobile)](https://github.com/foster95/journey/blob/main/assets/images/mobile-tablet-testing-success.png)


# Device Format Testing for Laptop and Desktop
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
A minor error was discovered on the classes.html where the boxes housing class information were not sitting in allignment on desktop screens and wider. To counter this I placed this element into an individual div, with the class "info-textbox". I wrote a media query for screens 1200px and wider:

```
.info-textbox {
    padding-top: 15px;
    display: flex;
    flex-direction: column;
    position: relative;
  }
  ```

  I then had to follow this up with two further media queries for xxl screens 1600px and 1920px

```
@media screen and (min-width: 1600px) {
  .children .info-textbox {
    padding-top: 37px;
  }

  .adults .info-textbox {
    padding-top: 35px;
  }
}
```
```
@media screen and (min-width: 1920px) {
  .children .info-textbox {
    padding-top: 16px;
  }

  .adults .info-textbox {
    padding-top: 13px;
  }
}
```

This fixed the error.

#### Before the fix:
![(Before Fix)](https://github.com/foster95/journey/blob/main/assets/images/bug-fix-before.png)

#### After the fix:
![(After Fix)](https://github.com/foster95/journey/blob/main/assets/images/bug-fix-after.png)

### Contrast
I also originally came up against contrast issues with my colour palette as there was yellow in the header and different shades of blue as the body. Swapping the yellow for blue around and adopting the darker blue immediately fixed the contrast issue. I also ran into an issue with button contrast, and originally had an issue with readability on buttons. I changed the colours on these again to match the rest of the site and added a hover change in colour for some additional visual interest, as well as to confirm to users they had clicked in the right place. The orignal button and the new button can be found below:

#### Original button (failing contrast)

#### New button (passing contrast)

# Deployment
This project used Github and Github Pages, and was deployed early on in the project, as soon as the structure of the site was created. Whilst using VS Code I used the source control panel to ensure that regular commits were made after every change. 

### Hosting through Github Pages
1. Go to Github, and select repository (Journey)
2. Settings > Pages
3. Ensure the following settings are applied
   - Source: 'Deploy from a branch'
   - Branch: 'Main' and 'Root'
   - Press save
4. Allow Github Pages a few minutes to deploy. This can then be found on the right hand side of the dashboard.

![(Github Repository)](https://github.com/foster95/journey/blob/main/assets/images/github-repo.png)

# Technologies Used
## Languages 
HTML and CSS only

## Technology
Github and Github Pages
Balsamiq
Font Awesome
Visual Studio Code

# Credits and Reference
* Mercades Yearly - The originator of Quest CIC which was a massive inspiration for the entire project
* [Coolors](https://coolors.co/) - For colour palette generation
* [Google Fonts](https://fonts.google.com/) - For importing font families
* [Gemini AI](https://gemini.google.com/app) - For image generation across the project as well as some help on writing the copy
* [W3Schools.com](https://www.w3schools.com/) - For general support, but particularly with regards to the hero image section of the website
* The Love Running Project with Code Institute - For which was an inspiration and for which code was used on a few occasions
* Jaqui_Alumna_lead from Slack - who provided a suggestion for a code snippet on the slack channel when I asked for assistance
* [Favicon.io](https://favicon.io/) - For the favicon design

# Acknowledgement and thanks
* Code Institute Slack Community - For helping me see something that was so bleeding obvious if I hadn't been so code blind
* Spencer Barriball - The greatest mentor in the world, who was endlessly kind, patient and funny and gave me the confidence that I was doing the right thing and who helped me in a true hour of need
* My parents - For being brutal as ever and telling me to crack on with it and get the job done, as well as provide tirimisu and flowers when I needed it
* My fiancee Jon - who stepped up whenever I needed him and told me on more than one occasion that he would body double me till 3am if it meant I got the project done.

I would have been utterly lost without these people and their support x