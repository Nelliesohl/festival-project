
# Sohl Music Festival

Project introduction... 

![Web Screenshit](/assets/images/mock-up.png)

# Features

## Existing Features


__Navigation bar__

The navigation bar offers the user fast and easy navigation to their section of interest.

- Internal links to the different sections of the page
- External link to the festival’s ticket partner
- The external link will open in a new browser tab
- Hover effect on links for extra clarity and improved user experience 
- Fully responsive on all screen sizes

![Web Screenshot](/assets/images/menu.png)

__Hero image__

The animated hero image grabs the user's attention. The cover text informs the user about when and where the festival is being held.

- The hero image features an eye-catching zoom animation
- Text overlay including logo, dates, and location of the festival
- Fully responsive on all screen sizes

![Web Screenshot](/assets/images/hero-section.png)

__Ticket banner__

The ticket banner notifies users that tickets have been released and offers fast and easy navigation to the festival's ticket partner for purchase.

- External link to the festivals ticket partner
- The external link opens in a new browser tab
- Hover effect for clarity and improved user experience 
- Fully responsive on all screen sizes

![Web Screenshot](/assets/images/ticket-banner.png)

__About section__

Provides the user with information about what the festival offers and its purpose.

- This section is intended to:
  - Increase the user’s interest 
  - Build brand confidence
- Fully responsive on all screen sizes

![Web Screenshot](/assets/images/about-section.png)

__Artist sections__

Introduces users to the festival’s lineup and allows users to see what day their favorite artist will perform.

- Artist cards with names, images, and embedded external links to the artist’s websites
- External links open in a new browser tab
- Hover effect to make the user aware of the embedded link
- Fully responsive on all screen sizes

![Web Screenshot](/assets/images/first-artist-section.png)

![Web Screenshot](/assets/images/second-artist-section.png)

![Web Screenshot](/assets/images/third-artist-section.png)

 __FAQ__

This section gives users a central place to find the answers they need and provides additional information about the festival.

- This section is intended to:
  - Improve the user experience
  - Establish trust
  - Overcome user obstacles and create conversions
- Fully responsive on all screen sizes

![Web Screenshot](/assets/images/faq-section.png)

__Contact form__

This section contains a form in which the user can contact the festival directly.

- The user will be asked to submit their full name, email address, and message
- All inputs are required to submit the form
- When the form is submitted button inverts colors

![Web Screenshot](/assets/images/contact-section.png)

__Footer__

The footer section encourages the user to keep connected and updated through the festival's social media channels. 

- External links to social media channels
- External links open in a new browser tab

![Web Screenshot](/assets/images/footer-section.png)

## Features Left to Implement

- Ideas for future implementation:
  - Drop-down text for FAQ
  - Redirect user to internal artist page instead of external artist site
  - Update artist images with properly sized images to improve performance score in Light House test
  - Update artist images with correct aspects ratio to improve performance score in Light House test 


## Testing

__Validator Testing__

![HTML Test Screenshot](/assets/images/html-checker.png)
 * HTML
    * No errors were returned when passing through the official W3C validator

![CSS Test Screenshot](/assets/images/css-validator.png)
* CSS
    * No errors were found when passing through the official (Jigsaw) validator

![Light House Screenshot](/assets/images/light-house.png)
* Light house
    * Best possible accessibility score

---

Using dev tools and Safari’s user-agent I’ve been able to test the website on multiple devices and browsers. 

I found two bugs 

- Bug 1
  - Browser: Safari
  - Device: iPhone 12 
  - Bug: Text on submit button did not display
  - Fix: Added color: #000; to submit-button class in CSS stylesheet which fixed the problem 

- Bug 2
  - Browser: Safari 
  - Device: iPad iOS 14.0
  - Bug: Social media icons did not show up in the footer
  - Fix: After a lot of troubleshooting I asked my sister that works in an Apple store to double-check on different iPad devices and she found no bugs, so I considered it resolved.
____
The [Sohl Music Festival](https://nelliesohl.github.io/festival-project/) website works like intended across Chrome, Safari, Mozilla, and Firefox on the following devices:

Chrome: iPhone SE, iPhone XR, iPhone 12 Pro, Pixel 5, Samsung Galaxy S8+ Samsung Galaxy S20 Ultra, iPad Air, iPad Mini, Surface Pro 7, Surface Duo, Samsung Galaxy A51/71, Nest Hub, Nest Hub Max, Galaxy S5 


Safari: Safari 15.3, iPhone iOS 14.0, iPad iOS 14.0, iPhone iOS 13.1.3, iPod touch iOS 13.1.3, iPad Mini iOS 13.1.3, iPad iOS 13.1.3 


Mozilla: Fully responsive in browser


Firefox: Fully responsive in browser
___

What I’ve tested other than responsiveness: 
- Internal links in nav bar is connected to the right sections and works 
- External links in nav bar opens in a new tab
- External ticket banner link opens in a new tab 
- External artist links opens in a new tab 
- All inputs are required to submit form
- Submitting form works
- External social media links opens in a new tab
- Hero image and artist card zoom animation works
- Hover effects applied to links in nav bar, ticket banner, artist cards, and submit button works

(No bugs found)

__Unfixed Bugs__

N/A

## Deployment

The site was deployed to GitHub pages. 

- The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://nelliesohl.github.io/festival-project/ 

## Technologies used

__HTML5__ -
As a structure language.

__CSS__ -
As a style language.

__Font Awesome__ -
As an icon library for a social links.

__Google fonts__ -
As a font resource.

__GitHub__ -
As a software hosting platform to keep project in a remote location.

__Git__ -
As a version-control system tracking.

__Gitpod__ -
As a development hosting platform.

## Credits

__Text content__
* The first sentence in the about section was taken from https://www.thecarousal.com/about
* FAQ content was taken from these three websites https://festival.liquicity.com/faq/, https://paradisecity.be/faq/, https://www.fleshfestival.com/faq 


__Fonts__
* Fonts used were imported from: [Google Fonts](https://fonts.google.com/)
* The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

__Media__
* Hero image: https://www.pexels.com/photo/people-having-a-concert-1190297/
* Artist images: 
  - [David Guetta](https://open.spotify.com/artist/1Cs0zKBU1kc0i8ypK3B9ai)
  - [Marshmello](https://imageio.forbes.com/specials-images/imageserve/5be1e2a3a7ea437059163919/0x0.jpg?format=jpg&crop=1999,1999,x0,y0,safe&height=1999&width=1999)
  - [DJ Khaled](https://cdn.smehost.net/2020sonymusiccouk-ukprod/wp-content/uploads/2019/10/16a2066d261a38a5ba3bff2e101acb93.jpg)   
  - [Martin Garrix](https://www.billboard.com/wp-content/uploads/media/martin-garrix-press-2018-cr-Louis-van-Baar-billboard-1548.jpg?w=875&h=583&crop=1)
  - [Deadmau5](https://www.meldaproduction.com/webtemp/imagecache/art_image/6f/deadmau5.640x640-exact.v1.jpg)
  - [Daft Punk](https://lastfm.freetls.fastly.net/i/u/ar0/80623b58659c416b8751f06a4edceb83.jpg) 
  - [Carl Cox](https://d3vhc53cl8e8km.cloudfront.net/hello-staging/wp-content/uploads/2014/05/06230831/IrTtlwPsIH5tlLqWWonPMsbBlWNb2ggeh7XdAMiR-972x597.jpeg)
  - [Oliver Heldens](https://i.pinimg.com/originals/6f/07/56/6f0756b53886965d2dfb5e2474e3855a.jpg)
  - [Adam Beyer](https://drumcode.se/artist/adam-beyer)
  - [Diplo](https://edm.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cq_auto:good%2Cw_1200/MTc2MjYzNjMxOTI5ODc3Njk0/diplo-press-photo-by-shane-lopeges-2018-billboard-1548-1.png)
  - [Nervo](https://protocol-recordings.com/wp-content/uploads/nervo.jpg)
  - [Justin Bieber](https://i.pinimg.com/originals/48/35/41/483541f14d25c81b01b2e687459154c3.jpg)
  - [Don Diablo](https://media.resources.festicket.com/www/artists/DonDiablo.jpeg)
  - [Steve Aoki](AOKIPRESSAUG20-12_square2.jpg)

(Copied image addresses from google searches instead of finding the rightful owner of the images. In future projects, I would like to do this part differently. For this project, I will credit all of the artists as the rightful owners).

__Code__
* To complete this project I used Code Institute student template: https://github.com/Code-Institute-Org/gitpod-full-template
* For artist card positioning I’ve used code from https://flexboxfroggy.com/
* To clean up my html formatting I’ve used https://webformatter.com/html
* For vendor prefixes, I’ve used https://autoprefixer.github.io/
* The [Code Institute’s](https://learn.codeinstitute.net/) course material and projects are where I’ve taken my code inspiration from 


I would like to thank and give credit to Lejla Delic that has contributed to this project with the majority of the text content in the about section.


I would like to share my enormous gratitude to my mentor Akshat Garg who has been amazing support along this journey and made a lot of things click for me. 

Akshat Garg has also introduced me to the [Flexboxfroggy](https://flexboxfroggy.com/) code, the [HTML formatter](https://webformatter.com/html), the [Mockup site](http://techsini.com/multi-mockup/index.php), and the [Material Design - Color tool](https://material.io/resources/color/#!). 
