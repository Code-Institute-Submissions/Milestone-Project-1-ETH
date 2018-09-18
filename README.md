# Ethereum | Eco-system Overview
![ethereum logo](https://john-e5.github.io/Milestone-Project-1-ETH/assets/images/main-img.png) 


This Website was developed for Code Institute's User Centic Front End Development Project 1 and is based on the **Ethereum Blockchain App Platform**.
It's a one page responsive website that gives a brief overview of the ethereum eco-system and related services.



 
## UX
I decided to develop this website with a focus on new users to ethereum and blockchain technology and also focus on existing users looking to find more information on the ethereum eco-system.
 

### Topic's include:
* _Ethereum_
* _Blockchain_
* _Smart Contracts_
* _Decentralized Applications_
* _Mining_

In the initial stages of development the 5 planes of activity were used to design a user focused mobile first one page website with simple navigation and a brief overview of related topics with relevent external linking used to expand on topics and provide valuable resources for the user.

### Style:
The color pallette and Logo I chose came from the offical [Ethereum visual identity guidelines](https://john-e5.github.io/Milestone-Project-1-ETH/Docs/Ethereum_Visual_Identity_1.0.0.pdf)
The font i used was Roboto and was imported from google fonts via CSS.
apart from the home section I decided to use full color backgrounds to highlight the different sections.


### User Stories:
- As a new user to ethereum and blockchain technology, I want to find infomation on what ethereum is about and how it works.

- As an existing user, I want to source information on ethereum and learn more about smart contracts and decentralized apps and see the current price of ethereum, find and download a wallet.

#### New and Existing Users

##### Home Section

1. Go to [Homepage](https://john-e5.github.io/Milestone-Project-1-ETH/)
2. Click a section tab in the navigation bar or scroll down

##### About Section

1. Read about ethereum
2. Watch short explainer video
3. Click available text links to learn more
    * _Decentralized Applications_
    * _Blockchain_
    * _Coinmarketcap(price info)_


##### How it Works Section

1. Scroll to How it Works or toggle the menu icon to reveal the navigation and click how it works
2. Read how it works
3. View how it works infographic
4. Click text link to learn more
    * _solving complex mathematical problems(Mining)_

##### Smart contract Section

1. Navigate to smart contracts
2. Read about Smart Contracts
3. Watch smart contracts explainer video
4. Read about use cases
5. Click text link to learn more
    * _Smart contracts_

##### About Dapps
1. Navigate to About DApps 
2. Read about DApps
3. View DApps infographic
4. Click text link to learn more
    * _decentralized autonomous organization(DAO)_

##### Resources Section

1. Navigate to Resources
2. Check additional info for links to external resources
3. Check wallets to download or use a wallet
4. Click play on podcasts to hear content
    * _Podcast 1: An Ethereum Podcast: Episode #12_
    * _Podcast 2: Dose of Ether #1: Keeping Up DAppearances_

##### Footer Section

1. Navigate to Footer
2. Fill out contact form to request more info
3. View Coinmarketcap ETH price widget
4. Click social icons to follow and view ethereum social media channels

##### Contact Us Section

1. Click Contact Us tab
2. when modal opens 
    * View contact details(Phone Number, Address)
    * Enter Name, Email Address and a short message
        (N.B Email doesn't currently work as it is beyond the scope of the project)



View the [Wireframes](/Milestone-Project-1-ETH/Docs/Milestone-Project-1-ETH-Wireframes.pdf/Docs/Milestone-Project-1-ETH-Wireframes.pdf)

## Features

### Mobile and Tablet View

The **Home** section features a fixed top navigation bar thats set at transparent for the home section, 
The navigation bar has a hamburger style menu icon, When clicked it displays 7 section tabs:

1. Home
2. About
3. How it Works
4. Smart Contracts
5. About DApps
6. Resources
7. Contact Us

Once Clicked the user is taken directly to the relevent section, I decided not to use a smooth scroll for this as i felt the user might get distracted as it scrolls down.
The Main logo features an SVG which is rotated to put the shadow on the left side and i styled the background of the SVG with a color and blur to give the effect of the sun shining from the background image which is to the right.

The **About** section features an Embeded Youtube Video which explains briefly to the user what ethereum is, It also features links to external resources so the user can expand on the linked topic.

The **How it Works** section features a large detailed infographic about how the process works.

The **Smart Contracts** section features an Embeded Youtube Video that briefly explains smart contracts the section also has links to external resources.

The **About DApps** section features a small infographic about DApps to give the user a rough idea of how dapps comunicate.

The **Resources** section features a list of external resource links to aid the user in learning more about the ethereum platform.
It also features links to wallets from various providers and 2 podcasts to let the user hear some recent opinions from the ethereum community.

The **Contact Us** section features a modal that contains contact information for the site and name and email form that includes a message area to allow the user to leave a comment.

The **Footer** section features a contact form so the user can request more info, it also features a price ticker widget from [Coinmarketcap](Https://coinmarketcap.com) that displays real-time price and market cap info for Ethereum.
Social links are placed in the footer and feature a hover effect.

### Desktop View

The _Desktop_ view also has a transparent navigation bar but differs in that there is no hamburger style menu icon instead the menu items are displayed across the top right of the screen and feature hover effects to highlight the different section tabs.

The navigation bar background changes from transparent to colored on scroll to make it visable to the user for easier navigation.
I added a back to top feature to aid in easier navigation after the user has scrolled down the page, its a small icon that auto hides when not scrolling, when clicked it scrolls the page back up to the home section.
The site uses Jquery scripts to control some navigaton features and smooth scrolling for the back to top feature.
The site also features SEO Metatags and a favicon to display in the browser tab.

### Features Left to Implement

- Implement form features to control email responses
- Add new sections for other features in the eco-system eg. Sharding, Swarm, Solidity, Whisper.
- Add more Development focused content to give more value for experienced users

## Technologies Used

For this project I used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to structure the content in line with modern semantic html5.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)
    - The project uses **CSS3** to style the html content.

- [Bootstrap3](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap3** to Layout the html content on different screen sizes, I used a simple layout with a single column for mobile and 2-3 columns on desktop and tablets.

- [FontAwesome](https://fontawesome.com/)
    - The project uses **FontAwesome** to add icons for social media and contact forms.

- [Animate.css](https://github.com/daneden/animate.css)
    - The project uses **Animate.css** to add easy to use and smooth animations.

- [GoogleFonts](https://fonts.google.com/?selection.family=Roboto)
    - The project uses **GoogleFonts** to add the font Roboto to site.

- [Normalise.css](http://necolas.github.io/normalize.css/)
    - The project uses **Normalise.css** to perform a css reset.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to control scrolling and toggle features.


## Testing

Testing for this project was done with several browsers and devices.

### Browsers

#### Mobile
- Firefox
- Chrome
- Safari
- Opera

#### Desktop
- Firefox
- Chrome
- Opera
- Edge

### Devices
- Hp Laptop 
- Lenovo Laptop
- Huawei Nexus 6P android phone
- Samsung Galaxy Tab 4
- Samsung Galaxy J3
- Iphone 6s
- Iphone 7
- Ipad AIR  

During testing i used Firefox Developer tools to test the responsive design and features of the page using different preset device templates in Firefox, I also used actual devices for testing, pushing changes to git and then testing the site on devies.

While testing on actual devices I noticed the main background image didn't load on IOS devices running mobile safari, I was unsure what was causing the issue and researched the bug online which gave a few suggestions for fixes which I implemented and resolved the issue after a few attempts. 

#### To Test
1. IOS Image Test:
    1. Go to the "Home" page on mobile safari device
    2. View main Background Image

While testing and resolving this issue i learned that it would have been more productive and efficent to do testing on a feature branch and merge the changes once fixed.

### Animation Testing

For the text animations i started using animista.com at first but changed to use the animate.css framework because during testing i noticed the animista animations were causing page load issue's and the animations weren't smooth and i felt it gave a bad user experience when first viewing the page.

1. Animation Testing:
    1. Go to the "Home" page
    2. View title animation
    3. See smooth text animations

For the page scroll animation i tested using firefox developer tools to adjust the timing of when the animation would be triggered i chose a sooner value to help the transition to begin earlier

1. Animation scroll Testing:
    1. Go to the "Home" page
    2. Scroll down the page
    3. See Navbar background color change

### Navigation Testing

The navigation was tested on different screen sizes to make sure all elements aligned correctly, while testing i noticed the navigation items were getting pushed down on tablet screens so i adjusted the break point with media queries to allow the navbar to collapse upto a screen size of 1160px.

1. Navigation Testing:
    1. View the homepage on tablet screen 
    2. Click Hamburger style icon
    3. View Dropdown menu

### Validation Testing

For _HTML_ validation testing I used [W3 Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjohn-e5.github.io%2FMilestone-Project-1-ETH%2F) which shows the html document to be valid.

For _CSS_ validation testing I used [W3 CSS Validator](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjohn-e5.github.io%2FMilestone-Project-1-ETH%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=) which shows the stylesheet to be valid CSS3.



## Deployment

This page has been deployed to [Github Pages](https://john-e5.github.io/Milestone-Project-1-ETH/)


## Credits

### Content
- The text content was sourced from ethereum.org, blockgeeks.com and the ethereum wiki

### Media
- The Infographics were sourced from blockgeeks
- The videos were sourced from youtube
- The podcasts were sourced from the bitcoin podcast network

See [credits.md](/Milestone-Project-1-ETH/Docs/credits.md) for full credits.

### Acknowledgements

- I received inspiration for this project from X
