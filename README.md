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



View the [Wireframes](https://john-e5.github.io/Milestone-Project-1-ETH/Docs/Milestone-Project-1-ETH-Wireframes.pdf)

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

### Features Left to Implement

- Implement form features to control email responses
- Add new sections for other features in the eco-system eg. Sharding, Swarm, Solidity, Whisper.
- Add more Development focused content to give more value for experienced users

## Technologies Used

For this project i used

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

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
