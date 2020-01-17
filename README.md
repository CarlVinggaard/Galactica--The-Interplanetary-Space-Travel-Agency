# Galactica - the Interplanetary Space Travelling Agency

This is a user-centric frontend development assignment, done as part of the full-stack developer course at Code Institute. The purpose of the project 
is to implement and display what I have learned about responsive design and web development so far.

The project is a website for Galactica, an imaginary future travelling agency that sells trips into space. The purpose of the website is to advertise the travels 
and persuade the customer to purchase a trip. This is done mainly by large images and catchy headlines. The style of the page is colorful and exciting. The website 
displays three products (package trips) that are listed on the front page, described in detail on the 'journey catalogue' page, and can be purchased on the 'order' 
page.

The website is written in HTML5 and CSS3, and more advanced features are created with Javascript libraries. In order to make the website fully responsive,
the frontend component library Bootstrap 4 has been used extensively. The code was written in the Gitpod IDE.

## User Experience

The target audience is people who want to travel into space. Maybe they already know where they want to go or maybe they want to explore the differnet options for space travel.

The functional and usability requirements for the site include:
- Showcase large images related to the target destinations
- Showcase practical information about the user
- Showcase contact information and social media links
- Enable the user to order a trip
- Enable seamless navigation within the site

### User Flow

User flow 1: The user wants to buy a specific package trip to space. The user can go directly into the 'Journey Catalogue' in the navigation bar and find more information about 
the trip. The user can then click 'Order' to go to the order page.

- 1. Front page -> 2. Journey Catalogue -> 3. Order

User flow 2: The user wants to know more about his/her options for space travel. The user can see the images on the front page, and scroll down and read about the company and 
about its technology and safety record. If the user is convinced to purchase a trip, there is a call-to-action at the bottom of the front page.

- 1. Front page -> 2. Scroll down on front page -> 3. Order

### Style and Design

The website style is colorful to make it interesting, but also to make it seem more futuristic. The idea was to try to make something that did not look too minimalistic
or 'modern', but without it being too much. The navbar is a purple-red gradient which has been reused as background for certain headings. The secondary colors are orange
and blue, which can be seen in the footer or most of the buttons.

The style is heavily influenced by the 'cards', used to present single pieces of information. These have round corners and a wide box-shadow that elevate them above the
background.

### Clickable Prototype

Before writing the website, a prototype model was created to display the structure and style of the site. The prototype is made in Figma, a standard but powerful 
interface design tool. It is clickable (if you click the 'play' button in the top right corner you can interact with it). The prototype can be accessed in Figma 
in the browser with the link: https://www.figma.com/file/Ok4u5aJeHJXPGIh0Y2h9iw/Prototype?node-id=0%3A1.

## Features

### Existing Features

- Navbar - Allows the user to navigate the site seamlessly. Implemented with Bootstrap's navbar component which is responsive.
- Slider/Carousel - Displays the journeys on the front page with large images and makes the front page more dynamic. Implemented using the javascript library Glide.js. 
- Company information - Informs the user about the companys reputation and principles.
- Technology information - Informs the user about the technology and safety record of the company.
- CTA - Informs the user about insurance and allows the user to go directly to the order page.
- Footer - Displays contact information and social media links.
- Journeys page - Contains more in-depth information about each journey. Can be found in the file journeys.html.
- Form - Allows the user to fill out their details to start the ordering process. Includes two datepickers, which were implemented with the javascript library Pikaday.

## Technologies Used

- HTML5
    - Defines the structure of the site.

- CSS3
    - Defines custom styles of the components on the site.
    - All CSS code written as part of this project is contained in assets/css/style.css.

- Bootstrap 4.4.1
    - Used extensively to produce responsive layout, padding, margins, sizing etc.
    - Resource: https://getbootstrap.com
    - CDN: https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css

- Font Awesome
    - Used to easily embed high quality icons.
    - Resource: https://fontawesome.com
    - https://kit.fontawesome.com/d9c8a97a10.js

- Glide.js carousel
    - Used to create the carousel at the top of the front page.
    - Resource: https://glidejs.com
    - CDN: https://cdn.jsdelivr.net/npm/@glidejs/glide


- Pikaday
    - Used to create the two datepicker input fields in the order form.
    - Resource: https://pikaday.com
    - CDN: https://cdn.jsdelivr.net/npm/pikaday/pikaday.js

- Git
    - Used for version control during the project.
    - Files are stored on Github.

## Testing

- Testing was done along the development process mainly using the devTools in Google Chrome. 
    - Responsiveness was tested using the device toolbar.
    - Troubleshooting CSS was done using the styles section of devTools.

- The code was tested in the HTML and CSS code validator (https://validator.w3.org/).

- Tests were done on different devices:
    - Desktop computer with wide monitor (Windows)
    - Smartphone (OnePlus 6/Android)
    - Tablet (iPad/iOS)
    - Laptop (Acer/Windows)

- Tests were done in different browsers:
    - Mozilla Firefox
    - Google Chrome
    - Safari

- Important tests are:
    - Test that the content is displayed properly on small and large screens (all three pages)
    - Test that the navbar menu collapses on small screens
    - Test that the collapsed navbar works correctly

    - Index.html:
        - Check that the slider/carousel changes image every 8 seconds
        - Test that the buttons on the slider link to the correct section of the journeys.html page
        - Test that the buttons in the 'journeys' section of the front page redirect correctly

    - Journeys.html:
        - Test that the buttons redirect to the order.html page

    - Order.html:
        - Test that the input fields are all required by submitting an incomplete form
        - Test that the e-mail field requirement works correctly, by submitting an invalid e-mail address (e.g. one that lacks '@')
        - Test that the datepicker works correctly by filling out the 'From' and 'To' fields without typing the numbers


## Deployment

The website is deployed to GitHub pages and can be accessed at: https://carlvinggaard.github.io/Galactica--The-Interplanetary-Space-Travel-Agency/.

- The process of deployment:
    1. Go to 'Settings' in the Github repository
    2. Under section 'Github Pages', select Source: 'master branch' in the dropdown menu
    3. Use the link provided to access the website

- Local deployment:
    1. Clone the git repository with the command: git clone https://github.com/CarlVinggaard/Galactica--The-Interplanetary-Space-Travel-Agency.git.
    2. This will create a folder where the files can be accessed.

The development and deployment versions are identical.

## Credits

Images used on the website are taken from:

- Greetings From Mars photo series by Julien Mauve (http://www.julienmauve.com/greetings-from-mars)
- NASA (https://nasa.gov)