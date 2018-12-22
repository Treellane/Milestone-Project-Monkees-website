# Milestone Project - The Monkees website

This is the website (frontend) for the band The Monkees. The site is ment to be  a portal to the band; for
fans to listen to the bands music and get more information on them, and for event orginisers to contact 
the band regrading bookingv them for events. 

the website will include...:
- video clips from the bands back cataloge and new material
- bio's of the band members
- a timeline of the band career path
- a discography
- a gallery
- an events page 
- links to the bands social media accounts (Facebook, Twitter and Youtube)
- contact form so potential clients can contact the band regarding book them for events
- news page; with a sign up feature the keep fans up to date with news of the band via email


## User Experience

The website is for fans of the band - to help them find out more about the band (through upcoming event info, 
events videos, bios and discography) and for potential clients (event orginisers) who want the hire/book 
the band for events so they can get a feel for who the band are and their music.

### Example: 
- For a fan, they might want the check for upcoming event dates to see where and when the band 
  will be performing; the Events page will help them achieve this. The fans can also use the News page to see
  any information redrading event announcments (they can also sign up for news updates here!)
- Also for fans, they want to check out the bands album catalogue, 
  to see what albums they don't have, and be able to follow links to buy them; the discograpghy page with help here.
- A fan might also like to download photos of the band; the Gallery page will fit the bill.

- As an event orginiser, looking to book the band for a gig; the Bio page will help the user learn more 
  about the band, the Video page will give them a taste of their music, and the contact form will allow 
  exactly that - contact with the band, with details of the event you'd like to book them for.


## Mockups

A mockup of the site layout was done in Balsamiq.
The mockups themsleves are in a directory called 'Balsamiq Mockups' in the project itself and .png files.
(I hope they are uploaded/saved correctly as I have not tried this before!!!)

## Features

This website will have 9 pages: Home, Biographies, Gallery, Discography, Videos, News, Timeline,
and Events. Also a Contact page (accessed via the footer)

- Home 
    The home page. This page will have an 'About the Band' section with some photos, and a link
    to sign up for updates on news and events. This page, along with all others with have a common
    header and footer (the header with the band logo and menu bar, the footer with a link to
    the bands social media accounts and an contact form for event bookings).
- Bios 
    Brief biographys of the band members, with a link to external sites for more 
    detailed bio information. 
- Gallery
    Images of the band and band members.
- Discography
    The bands album catalogue, with links to external sites to purchase/download the music.
- Videos
    Video links to a selection of the bands bands hits and new material.
-News 
    This is a page for news related to the band: announcments of gig dates, tv appearances/interviews etc.
- Timeline
    This page will give a timeline of the main events of the bands history through the years.
- Events
    An event guide, show the bands upcoming events (dates and venues). Also a link to allow fans to
    sign up the bands newsletter, allowing them to keep up to date with the news on the band.
- Contact 
    This page is to allow users to contact the band regarding event bookings.

### Future Features...
- Adding more social network platrorms!
- Adding a Fan Page (where fans can post comments/photos about the bands gigs they were at)
- Adding a forum for fans, a place where likeminded fans can get together  (maybe band members
  can get involved and answer fans questions in scheduled Q and A sessions!)

## Technologies used

- Balsamiq

    Balsamiq was used to do mock up layovers of the sites pages.

- style.css (../stlye.css)

    My own style sheet for the project
          
- Bootstrap (https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css)

    Bootstrap is used in this project to help with the structure and layout of the website pages.

- Hover.CSS (found at www.cdnjs.com)

    Hover.CSS command library is used to add effects the the menu buttons.

- Fonts (https://fonts.google.com)

    Fonts used in this project are from Google fonts.
    
- jQuery (https://code.jquery.com/jquery-3.3.1.min.js) 

    This was recommend to be added to the bottom of your code in a Code Institute tutorial.
    May not be totally necessary for this site, but it is added for completness.

- JavaScript (https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js)

    This was recommend to be added to the bottom of your code in a Code Institute tutorial. 
    (I believe this makes the modal on the News Page work!)

- GitHub (https://github.com/Treellane/Milestone-Project-Monkees-website)

  GitHub was used to backup the project along the way, as suggested by Code Institute as a
  good habit to get in ot! 
  
  Git deployment address : https://treellane.github.io/Milestone-Project-Monkees-website/
    
     
## Testing

Testing was mainly a case of checking/clicking all the links on all the pages to see if they worked and 
they took you to were they were ment to.

(all links work except the Purchase/Download music links which do not take you anywhere as the project is
only supposed to be a front-end only project!)

Also tested was the responsivemenss of the different pages; this was tested by simply opening each page and 
resizing the browser window.

### Testing Issues

There was quiet a few issues to begin with, which one by hope got sorted!
##### Menu
The original idea for the main menu was to split it either side of a centerally placed logo, but 
at smaller screen sizes it did not look great (with half the menu above and half below the logo). So this 
layout idea was drapped in favor of a left-placed logo and one longer menu bar to the right.

Also with the Menu, getting the side images to position well was the different sizes (and for one to disappear
when the screen got too small) wsa something that needed to be looked at.

##### Videos
Getting the videos ion the Video Page to resize took time to figure out, but eventually I got there. 
Puttting them in iframes instead of divs helped! (i'd forgotten about iframes!). Simple really!

##### Bootstrap columns
This is the first time I coded unsupervised (ie: not had a Code Inst. video tutorial to follow), so I spent
a lot of time playing around with the bootstrap column codes (eg: col-sm-9, hidden-xs) to try to get the layout
looking good at different screensizes; but in time, I got layouts at small screen sizes that I was happy with.

##### Timeline
Getting the timeline to look good when resized smaller took some time too. This was mainly just a case of 
tweeking the padding around the timeline and the outer divs, as well as, again, playing around with the 
bootstrap column sizes.


## Deployment

The code was written in CLoud9 and saved to GitHub.
During the process, regualr saves/uploads were made to GitHub (as suggested by Code Institute as being good coding practice).
During this stage, ideas for extra website pages were coded straight into the Cloud9 (bypassing Balsamiq).
In GitHub, within the settings menu, the site was launched on GitHub Pages by selecting the appropriate setting.
At this point the site appear active, but images are not visable!!! 


### Version Differences
The main difference between the deployed version and the development version is that the original page menu had one logo
in the center with a menu at each side, and the final version has the menu in the center and logos on each side.

Also, extra pages were added from the original website idea (Timeline News, and Events).

## Credits

### Content
All text content was written my me (David Kelly), 
with some being an edited/arranged version of text from Wikipedia.

### Media
All video links are copeid from Youtube.

All Biography and Discography links are taken from Wikipedia.

Some images were provided by Code Institute. All other photos were taken from Google, 
except for the studio album images which were taken from Wikipedia, and the 
'sold-out' News page image, with was taken from Google and edited my me (David Kelly).

### Acknowledgements

A thank you to Code Institute for re-introducing me to my childhood through The Monkees!

Some elements were inspired by coding from the 'Whiskey Website' from a Code Institute tutorial video.  

Timeline layout/code on the Timeline page taken from a W3Schools sample code.

Thank you to The Monkees for the memories. Davy Jones, RIP.


