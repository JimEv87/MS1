# Testing

## Code Validation

All HTML code has passed [HTML Validation](https://validator.w3.org/#validate_by_input) 

![Image of validated code for index page](https://github.com/JimEv87/MS1/blob/master/testing/HTMLCheckerIndex.PNG)
![Image of validated code for about page](https://github.com/JimEv87/MS1/blob/master/testing/HTMLCheckerAbout.PNG)
![Image of validated code for tour page](https://github.com/JimEv87/MS1/blob/master/testing/HTMLCheckerTour.PNG)
![Image of validated code for music page](https://github.com/JimEv87/MS1/blob/master/testing/HTMLCheckerMusic.PNG)
![Image of validated code for gallery page](https://github.com/JimEv87/MS1/blob/master/testing/HTMLCheckerGallery.PNG)
![Image of validated code for contact page](https://github.com/JimEv87/MS1/blob/master/testing/HTMLCheckerContact.PNG)

CSS code passed [CSS Validation](https://jigsaw.w3.org/css-validator/)

![Image of validated CSS](https://github.com/JimEv87/MS1/blob/master/testing/CSSChecker.PNG)

## Browser Testing

The website has been tested for compatibility on five different browsers.  

![Image of browser compatability testing](https://github.com/JimEv87/MS1/blob/master/testing/browsertesting.PNG)

Note - All testing covers functionalities and appearance

## Responsiveness Testing

The website has been tested for responsiveness on several devices.  All pages render as expected, all images display correctly and all links work.

![Image of responsiveness testing](https://github.com/JimEv87/MS1/blob/master/testing/restesting.PNG)

Note - when displayed in landscape mode on mobile the footer is slightly impeded 

## Bugs

- Initial valdiation highlighted sections that were missing H tags. I found that although they are not required, it is best practice to include a 
heading tag on every section so I adjust my code accordingly.
- Images were displaying correctly when viewed locally but not on the deployed site.  This was a simple bug to fix as I had included an extra / in 
the filepath
- The footer was not displaying correctly in mobile view.  This was resolved by adjusting the padding and using the align-self-center class from
Bootstrap
- The image on the tour page was stetched and ugly when viewed in mobile view. I wanted to retain this image as it assits the user in understanding
the website's styling so instead of removing or replacing the image I used a media query to resize it in mobile view

## User Story Testing

- As a user, I want to be able to navigate the website easily
  - the fixed header and footer makes navigation easy
- As a music lover, I want to find out who The Snuts are (where are they from? What kind of music do the play? How long have they been together?)
  - the about page informs the user of the key facts about the band
- As a music lover, I want to find out about their songs and where to listen to them?
  - the music page displays the artwork for the band's singles and gives direct links to listen/view on Spotify, Apple and YouTube
- As a Snuts fan, I want to find out when and where they are playing and how can I purchase tickets?
  - the tour page gives details of the upcoming tour with handy links to ticketing websites and location maps
- As a Snuts fan, I want to be able to view pictures of the band and of gigs they’ve done
  - the gallery shows off lots of pictures of the band in action
- As a Snuts fan, I want to find out if they have any merchandise for sale
  - the Shop link in the footer opens the band's merchandise website in a new tab
- As a Snuts fan, I want to find out how to connect with them and follow them on social media
  - the social media links in the footer direct the user to the band's Facebook, Twitter, Instagram and YouTube pages
- As a music promotor and venue owner, I want to find out about the band’s popularity, fan following and reputation
  - the reviews in the index page and the content of the about page describe the band's popularity and growing reputation. The charity links on the 
 index page also promote the band's ethics.
- As a music promotor and venue owner, I want to be able to contact the band to enquire about bookings
  - the contact page (although non-functioning at this time) allows contact to the band/band's management