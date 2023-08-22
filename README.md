# Anime Nite

This web page is *not* business related. It was created for a house gathering to help our friends vote for their favorite movie to watch that night! A voting link is provided at the bottom of the page (which uses a Google Sheet document to count votes and display them in a chart). It features a minimalist design and utilizing DOM and mimicking a databse for a clean and maintainable code.

## DOM
The web page is not completely static. The movies section (which is nitially a mere empty container on the HTML page) gets populated by a JavaScript script. The data is pulled from an array of objects (mimicking an actual database), selecting the properties that we're interested in. This also includes using the fileName field as part of the image path when we add its src attribute. Likewise, the hover text is also pulled from the array as an object property.

## Styling
Styling of this page is mostly vanilla CSS. However, the page is linked to a Bootstrap style sheet, which is used for the button only.

## Screen Compatibility
The web page has responsive styling and should adapt well to different screen sizes, including cell phone and tablet screens.

## Live Link
The web page can be accessed [here](https://haridira.github.io/portfolio/featured/23-02-01-animeNite/).
