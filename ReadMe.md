# TheMonkees Website

A fully responsive website for a legendary Band called 'TheMonkees'. The website acts as a hub for the Band to reach out to their adoring fans.

## UX

From the brief: "The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.
Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.
Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties."

From the above project brief, I have come up with the following user stories:

- As a fan I would like Look at Band Pictures/Artwork
- As a fan I would like to Listen to the Band's music
- As a fan I would like to be able to contact the Band regarding performing at events i.e. Weddings, Christmas parties etc.
- Provide links to Band social media: Facebook, Twitter & YouTube Pages.

### Mockups

Initial mockups were made using **Balsamiq** software to aid in the creation of the website; a basic mockup was made of each web page. 
- The mockups can be found in the **Mockups** folder. 

## Features
- Music - allow Fans to listen to Band music, by navigating to the 'Listen' page.
- Pictures/Artwork - allow fans to look at Band pictures/artwork, by navigating to the 'Look' page.
- Booking Enquiries - allow fans to contact the Band regarding bookings for private events. This is done by navigating to the 'Book' page and filling out the contact form.
  - Also, this is advertised in the footer of the 'Home', 'Look' and 'Listen' pages. 
- Social Media links - allow fans to access links to Band social media by providing links on all Website pages. Links have been provided at the bottom of every single page under the 'OUR SOCIALS' section in the footer.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap v3](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap** to simplify the web page design and to maintain consistency across multiple browsers and screen resolutions.
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to aid with the Bootstrap navigation; the navigation will not work without JQuery.
- [Font Awesome](https://getbootstrap.com/docs/3.3/)
    - The project uses **Font Awesome** to provide icons for the 'OUR SOCIALS' links. 
- [Roboto Font](https://fonts.google.com/specimen/Roboto)
    - The website uses **Roboto** as the main font for all typography. 
- [Balsamiq](https://fonts.google.com/specimen/Roboto)
    - This tool was used to create the mockups of the website at the beginning of the project. 

## Testing

Testing scenarios run:

1. Navigation:
    1. Click on all main navigation buttons i.e. 'Home', 'Look', 'Listen' and 'Book'. Verify that each button takes you to the correct page.
    2. Click onto the 'TheMonkees' brand name in the top-left of each page and verify that it takes you to the 'Home' page.

2. Looking at pictures:
    1. Go to the "Look" page.
    2. Observe if all images display correctly.
    3. Observe images are positioned correctly i.e. no overlapping of images etc.
	4. Follow steps 2 - 3 again, however, this time for different screen sizes i.e. Phone, Tablet, Desktop etc.

3. Listening to Music:
    1. Go to the "Listen" page.
    2. Navigate your mouse cursor to the play button of your chosen song and click the play button. Music should play fine.
	3. Click the mute (speaker) button and observe if song successfully mutes.
    4. Click the play and then the pause button and observe if the song stops playing.
	5. Repeat steps 2 - 4 for all listed songs.

4. Booking form:
    1. Go to the "Book" page.
    2. Try to submit the empty form and verify that an error message about the required fields appears.
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears.
    4. Try to submit the form with all valid inputs and verify that a success message appears.

5. Typography:
	1. Go to the *Home* page.
	2. Have a look at the text and observe if all text is clearly visible i.e. is it too small, too big.
	3. Follow step 2 again, however, this time do the same for different screen sizes i.e. Phone, Tablet, Desktop etc.
	4. Follow steps 2 - 3 for all pages. Is the the typography consistent across all pages? Is it readable on small screen devices?

### Screen Size & Different Browsers

#### Screen Sizes

Using the Debugger tools on Google Chrome I was able to view the website in different screen sizes. The following screen sizes were verified:
- 360px X 640px (WxH)
- 768px X 1024px (WxH)
- 1024px X 1366px (WxH)

Test's were run for various screen sizes, these are listed in the above **Testing** section.

On smaller screen sizes i.e. when the width is 768px or less, the website switches to a stacked view to maintain a consistent look.

#### Multi Browser Testing

Multi browser testing was carried out to ensure there is consistency across different Browsers. The following Browsers were tested:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Internet Explorer v11 - The 'Listen' page doesn't work well with IE v11; the audio doesn't seem to load and throws an error. A note has been made to let users know to avoid using this browser.

## Deployment

The website was deployed using GitHub pages. 

To view the project in action, visit the following link:

https://ezat-r.github.io/theMonkees/


## Credits

### Content
- Information on the Band was obtained from [Wikipedia article](https://en.wikipedia.org/wiki/The_Monkees)

### Media
- The three .SVG pictures that are used in the 'Home' page, were obtained from the following website: https://www.flaticon.com 
- The remainder of the media was provided with this project.