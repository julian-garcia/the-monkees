# The Monkees Website
This is a promotional website for "The Monkees" whereby fans and potential fans can experience multimedia clips, purchase music and browse an image gallery. As well as showcasing the band, it publicises their availability to perform at events such as weddings and Christmas parties. The site was built using **HTML**, **CSS** and **Bootstrap** using a mobile first approach. Visit the site at this address:
[julian-garcia.github.io/the-monkees](https://julian-garcia.github.io/the-monkees/)

## Site Design
Pre development wireframes were created using [Balsamiq](https://balsamiq.com) (see [wireframes.pdf](resources/wireframes.pdf)). Website [coolors.co](https://coolors.co) was used to determine a colour
scheme that uses complementary colours (see [palette.pdf](resources/palette.pdf)). 
### Accessibility
To ensure content readability, sufficient colour contrast of text against the background has been verified using the [WebAIM colour contrast checker](https://webaim.org/resources/contrastchecker/). According to the WCAG (Web Content Accessibility Guidelines) the contrast for this site is rated level AAA for normal and large text. For the navigation and page title sections the contrast ratio is 9.24:1 (it needs to be least 7:1 for normal text and 4.5:1 for large text).

## Features
**Album time line** - designed using custom CSS to complement bootstrap CSS.

**Image Gallery** - makes use of bootstrap modals, displaying each picture in its own container.

**Event Listing & Booking form** - Simple contact form to book a date time for a gig. Includes CSS styled event listing using bootstrap components.

**Media Gallery** - video and audio elements to enable the user to play popular videos and songs 

## Technologies Used
- HTML5/CSS3
- [Bootstrap v4.1.1](http://getbootstrap.com)
  - Define site structure and pre-defined components
- [Fontawesome v5.0.10](https://fontawesome.com)
  - Icons throughout various sections
- [Google Fonts](https://fonts.google.com)
  - Title and body fonts (Dosis and Crimson Text)
- [Balsamiq](https://balsamiq.com)
  - Wireframing software
- [Coolors](https://coolors.co)
  - Definition of a colour scheme

## Testing
Used [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjulian-garcia.github.io%2Fthe-monkees%2Findex.html) to identify HTML errors which were  resolved. To test for site responsiveness, browser responsive mode was used to render the site simulating various screen widths. Tested across various browsers including: Safari, Firefox, Chrome and Internet Explorer. Cross browser compatibility can be confirmed by visiting [browsershots.org](http://browsershots.org/) and feeding in the URL `https://julian-garcia.github.io/the-monkees/index.html`. Visual checks were also performed on an Apple iPhone SE and Apple Macbook Pro.
### Visual user interface checks
Various manual checks were carried out to ensure proper website functionality and responsiveness:
Element | Viewport Size | Test | Outcome
--------|:-------------:|------|:------:
Links | All | Visit all links to verify that there are no broken internal links and no broken external links to social media pages and album purchase pages | Pass 
Window | All | Browser width enlarged and reduced to check that the structure of each page adjusts gracefully according to the viewport size | Pass
Images | All | Home page: Ensure that the images of the 4 band members scale up and down from mobile through to tablet and desktop. Image proportions  should be maintained and faces remain main focus | Pass
Media | All | Music page: Clicked play on each song and the video to ensure that only one track is played at any one time | Pass
Navigation links | Desktop | Current state: The user should be aware of their current position on the site at all times. Check that each navigation menu item is highlighted as active on the relevant page. | Pass
Grid | Desktop| Book us page: The booking form is displayed after the event listing (to the right). | Pass
Navigation | Desktop | Menu items retain contrast on hover as well as highlighted links that indicate the currently active page | Pass
Grid| Mobile | Book us page: On mobile the booking form must be stacked on top of the event list as it is more important so should appear above the fold. | Pass
Window | Mobile | User must be unable to scroll horizontally and all content is accessible through vertical scrolling | Pass
Header | Mobile | Accessibility: Header image is only visible on desktop but not on mobile so as to ensure that page content starts appearing before the fold on mobile | Pass
Navigation | Mobile | Navigation menu item text to background contrast ratio should be consistent on every page. The ratio should be high for readability. | Pass

## Deployment & Contributions
The site was deployed using the [Github Pages](https://pages.github.com) feature of Github which provides a server side address hosed by GitHub in order to render a static website. To contribute to this you'll need to do the following:
- create your own Github repository on GitHub
- create a local project directory on your PC, 
- navigate to that directory on the command line (for command line I use [iTerm2](https://www.iterm2.com) on my mac), 
- clone this github repository by entering: `git clone https://github.com/julian-garcia/the-monkees.git`. 
Then use any text editor to make your changes to the CSS, HTML and/or content. To test, simply open index.html or the other html files locally in any web browser. Having finished development and testing:
- Navigate to your project directory on the command line and enter `git add .` 
- Enter `git commit -m 'My changes'` - replace 'my changes' with a brief overview of your changes
- Finally deploy using `git push -u origin master`
- To set up the static website, go to the settings of your github repository and select "master branch" from the source dropdown in the Github pages section
  
## Credits
Images were obtained from [commons.wikimedia.org](https://commons.wikimedia.org/wiki/Main_Page) and [Pixabay](https://pixabay.com). Usage rights permit the general public to use them.
