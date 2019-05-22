# The Beatles

The remit of the assignment was to create a responsive website of around 4-5 pages, or, if using a single scrolling page, a website with clearly defined page areas. In doing this, the use of semantic HTML5 elements were necessary to structure the HTML code better. In addition, the site should made use of CSS frameworks and a wireframe provided the foundation of the page structure prior to development.

## User Experience
 
 The Beatles wanted the website developed to cater for both current and prospective fans, alike. In doing so, they wanted their webpage to be visually appealing whilst allowing visitors an opportunity to listen, and watch, selected songs from their back catalogue. Furthermore, the band wanted to highlight the fact that they are still performing regularly and are available for hire.
 
 I wanted the website to provide a minimalist landscape whilst still allowing the user to access all of the key components with ease and with minimal instruction.
 
 The focus of the website was on the band's artistic flare, to ensure a contrast in colours and tones between segments which, in turn, allowed for ease of identification as well as provide a visually appealing space.
 
 The balsamiq wireframe used for this project can be accessed in the wireframes folder of the project directory.

## Features

- Home
    - I wanted the homepage to provide a striking image of the band, identifying who the band were, and offer clear and simple navigation options to the rest of the site. In addition, I wanted to drawer the user to additional material on the site by making the background image only 90% of the view height.
    - An alternative image is used as screen resolution reduces so as to provide a clear indication of the focus of the website.
- About
    - No heading was used so as to keep with the minimalist theme of the site and a colourful background offered contrast from the black & white homepage image offering an indication that the user was in a new section.
    - An opaque background was used for the 'about' dialogue so as to still allow the user access to the vivid image of the band in the background.
    - As screen size reduces, both the font size and the text area changes to ensure an appropriate delivery of material whilst still offering a visually appealing background.
- Video
    - Again, a black & white background to contrast against the colourful 'about' section background and indicate to the user that they are now in another section.
    - No heading was used again as I wanted the background image to be brought into focus.
    - The video itself was placed centrally so the user could not miss it.
    - The video remains central with a reduction in screen size.
- Music
    - Each of the band's 15 albums are showcased. Upon pressing the play icon, the user is played a song from that album. Pressing the pause icon pauses the playback of that song.
    - With a change in screen size comes a change in both the layout of the album covers and the size of the play & pause icons to better suit smaller screen resolutions.
    - Due to the colourful and diverse nature of the album cover mosaic, there was no requirement for a section background as, with the previous segments, the colours offered suitable contrast to the black & white background image of the 'video' section and therefore provided the user with an indication that they were in a new section.
    - Due to the size of the images and the number of albums, this is the only segment whereby the section is not viewed with 90% of the view height as the continuous flow of albums should encourage the user to scroll further down the page.
- Contact
    - As with all the sections that came before, I wanted a focus to be on the imagery associated with the section. As a result the catch-line alluding to the contact box was kept brief and to the point.
    - Again, an opaque text box was used so as to not detract to much from the background image.
    - The contact box takes up minimal real estate on the page and the submit button is green, paying homage to the colour of the apple that was used as an icon for The Beatles' own record label.
    - The functions of each box work as intended and provide suitable feedback when not completed correctly.
    - Both the catch-line and contact segments adjust accordingly with varying screen sizes.
- Navbar
    - The navigation bar remains fixed when scrolling through the entire webpage allowing easy access to each section.
    - At smaller screen sizes the navigation bar collapses to a burger icon so as to not take up too much room on the screen.
- Footer
    - As with the navigation bar, the footer offers links to each section of the webpage as well as social media sites.
    - Font size, footer content and arrangement alter as screen size reduces allowing for a more user-friendly experience.
- Backgrounds
    -  As well as the black & white / colour contrast between sections, black & white images remain fixed to add a secondary indication that the user is entering or leaving a specific section.

### Existing Features

- Navbar - Links to specific sections of the webpage change colour when hovered (Colour and speed consistent in all site hover elements) and clicking on 'The Beatles' will return to homepage. At small screen sizes, navbar menu collapses, and when accessed, will automatically collapse when links is clicked. Hover elements remain at smaller screen sizes.
- Background - The backgrounds of 'homepage' and 'video' sections change at smaller screen sizes as original picture was not suitable.
- About - The word 'contact' in the 'about' section acts as a link to the 'contact' section of the webpage. However, this feature is not highlighted.
- Music - Pressing the 'play' icon on an album cover will play a song from that album. Pressing the 'pause' button will pause the song that is playing. The layout of the album covers changes as the screen size reduces so as to make it more user friendly. In addition, the size of the 'play' and 'pause' icons reduce to match the resolution.
- Contact - Font-size reduces to match the screen size. Each element is also adjusted to fit various screen sizes well.
- Footer - Each footer sub-heading acts as an anchor to each section of the webpage. These elements also change colour when hovered on. As the screen size reduces the font-size adjusts accordingly for both the sub-headings and text. At small screen sizes, the text is removed and the sub-headings are stacked centrally so as to take up minimal space. The social media links also change colour when hovered and redirect the user to the specific pages.

### Features Left to Implement

- As there are no headings present in any of the sections, a feature that needs adding is an 'active' element to the navbar shortcut when the user is within that section.
- A 'stop' and 'rewind' icon needs adding to each of the album covers without taking up too much space. Alternatively, the 'pause' icon could be replaced by a 'stop' icon that immediately returns the audio file to the start position.
- The video, upon playback being initiated, should increase to occupy more of the available screen. And, conversely, reduce in size once playback has ended or been stopped.

## Technologies Used

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Google Fonts](https://fonts.google.com)
    - The project uses **Google Fonts** as a source text fonts.
- [Bootstrap CDN](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap CDN** to help with webpage structure and visual elements.
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to add content and structure to the webpage.
- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - The project uses **CSS** to add style to the HTML5 elements.

## Testing

Throughout the development of the webpage, there was continuous testing and evaluation to ascertain whether the website functioned as planned.

The website was developed, as previously indicated, with minimalism in mind whilst drawing on the artistic side of the band and using their iconic imagery to appeal to both current and prospective fans.

The 'inspect' tool in Google Chrome was my primary testing aparatus for my website when investigating the functionality and useability of the site at various screen resolutions. Whilst developing all sections of the website I continually reverted back to this tool to ensure the product matched my expectations and make any styling modifications required at various screen resolutions.

In addition to 'inspect' in Google Chrome, I frequented [W3C's HTML validation](https://validator.w3.org/) service as well as [W3C's CSS validation](https://jigsaw.w3.org/css-validator/) service to ensure my code fulfilled the necessary criteria.

Scenarios I was concerned with whilst developing and testing my website have already been indicated in the **features** part of this READMe file.

Whilst working on the project I ran into a number of bugs that I feel have been resolved to my satisfaction. These bugs included:

1. Navbar burger icon at large sizes.
2. background images for homepage and video sections at smaller screen sizes.
3. Text area sizing in about section when reducing the screen size.
4. Preventing an overlap from the video when in smaller screen sizes.
5. Applying the play and pause icons to the album covers.

## Deployment

The site was deployed using GitHub. Throughout the development process, at each key phase, I committed the updated files to GitHub so as to back up my work and also allow me to refer back to previous versions of my work.




This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content

- The music video for the 'Video' section of the website was copied from [YouTube](https://www.youtube.com/watch?v=NCtzkaL2t_Y).
- The music for the 'Music' section of the website was taken from my own collection.

### Media

- The photo used for the 'Home' section of the website was obtained from [Front Porch](https://frontporch.club/galleries/poster-and-beatles-black-white-tumblr.html).
- The photo used for the 'About' section of the website was obtained from [Consequence of Sound](https://consequenceofsound.net/2017/04/previously-unreleased-version-of-the-beatles-sgt-peppers-lonely-hearts-club-band-unearthed-from-the-vaults-listen/).
- The photo used for the 'Video' section of the website was obtained from [SiriusXM](http://blog.siriusxm.com/from-yesterday-to-now-9-beatles-songs-that-are-often-overlooked/).
- The photo used for the 'Music' section of the website was obtained from my own collection.
- The photo used for the 'Contact' section of the website was obtained from [All4Prints](http://all4prints.com/en/portraits-iconic/1604-the-beatles-abbey-road.html).

### Acknowledgements

- I received inspiration for this project from my Father, an avid Beatles fan, who exposed me to they music from a young age. And, as a result, I became a fan, too.
# assignment-one
