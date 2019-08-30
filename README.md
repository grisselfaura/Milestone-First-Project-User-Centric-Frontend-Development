# Agronut Perú

Welcome to my Stream One Project: User-Centric Frontend Development - Code Institute!

Agronut Perú is an website which interacts with Farmers and influence agriculture productivity in a susteinable and responsible way. 
It provides information and convinient solution about specific crops fertilizers which can be requested online without going to a far away physical shop. 

This website is part of my portfolio to present to prospective employers and also a demo-version for Agronut Perú (as it's potential website).

## Demo

You can check out the website [here]( https://grisselfaura.github.io/Milestone-First-Project-User-Centric-Frontend-Development/)!
![Responsive mockup](https://raw.githubusercontent.com/grisselfaura/Milestone-First-Project-User-Centric-Frontend-Development/master/assets/images/read-mockups/Mock-up-responsive-test.PNG "Responsive mockup")

 
## UX

- My goal on the website design was to make it as easy as possible for the potential customers to access the information on the site while striving for a simple layout approach. 

- The design color scheme was chosen by a local graphic designer with further insight to the peruvian marketing trends to create a colorful visual impact and straighforward easy-to-use feeling. 

- For the buyers, I wanted to provide them with a brief overview of the company, the product's categories and a contact form to request such product via a user friendly design.
  This way, they would be able to get a glimpse of Agronut Perú, the products catalog and an easy-reliable option to contact Agronut Perú if they choose to obtain such product or simply information. 
  In the 'Contact us' section, I wanted them to be able to quickly reach Agronut Perú customer service and sales using a safely approach to avoid potential local internet scams. 
  A google map link in the footer showing the company address was also provided for their information. 

- For potential partnerships, I wanted to provide them with a brief overview of the company oppportunities in the 'Join us' section and corresponding subsections. 
  [Subsections with corresponding information will be further developed upon company request}.

- Wireframes available.

## Features

- ### Existing Features
- This site uses the Scrolling Nav feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. 
- The navbar is fixed to the top that collapses on scroll. The Navbar also uses the scrollSpy feature that highlights active page sections.
- Each section contains an arrow icon at the end of each section to inform the user that there is further reading below. The last arrow will bring the user back to the landing page.
- Buttons are named after corresponding section to promote user friendly approach. In addition hover feature has been added all buttons to highlight user interaction with potential action.

- ### Features Left to Implement
* In the future i would like to add a quality section (depending on client desire to add certifications for its products and service) to be link to the Quality item in the NavBar.
* In addition the readmore button from each product category needs to be link to each individual product caracteristics and its product code.
* Furthermore the links to the subsections buttons in the join us sections (depending on client's layout desire) needs to be added.
* Lastly, I would like to add a blog section with videos and tips regarding susteinable farming. 

## Technologies Used

1. HTML
2. CSS
3. Bootstrap (4.3.1)
3.1. Scrolling Nav
3.2. Bootstrap Footers with map
4. Font-awesome (4.7.0)<!--********would u call this a technology********-->
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
5. [JQuery](https://jquery.com) The project uses **JQuery** to simplify DOM manipulation.


## Testing
HTML and CSS code checked for coding errors.
CSS prefixes were checked against https://autoprefixer.github.io/

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar. 

In the about us section, they can read a bit about the organization background.
They can view both the general products category in the "Product" section and specific information of the each product by clicking on the Readmore buttons (website under construction). 

1. Contact form:
-Go to the "Contact Us" page
-If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. 
-If you try to to enter text in the mobile and dni field, it would only allow numbers in these fields.
-Furthermore, the 'required' attribute is added to all the fields, so if those fields are not filled in, the form will not submit.
-If all field are valid, the page will reload. If an potential buyer is interested in contacting Agronut Perú, they will have to fill out all fields in order for the form to go through.

In addition other-interested people are able to see colaboration posibilities with the Agronut Perú via the buttons-sections in the "Join us" section. 
They are also able to view the address location of the company via clicking on the map in the footer. 

All links will open in a new tab using 'target="_blank" to an under construction page (currently). 
All links have been manually tested to ensure that they are pointing to the correct destination.

-This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that ```background-attachment: fixed``` was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the ```background-attachment: scroll``` property value was added in a media query.
In addition, the site  was tested via  http://ami.responsivedesign.is/ to review how the project looks and works on different screen sizes.

Section with interesting bugs or problems discovered during testing:
- sections not empalming with each others.
- about us icon losing configuration during responsive (fixed)
- H1 tittle does not fit screen on iphone 4 even with media query (fixed).
- background header images for sections reponsive for >md screens (fixed) not yet debugged to scale down for <sm screens.

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. 
The deployed site will update automatically upon new commits to the master branch.
In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting
```
 `git clone  https://github.com/grisselfaura/User-Centric-Frontend-Development-Milestone-Project.git` into your terminal. 
```
To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

## Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Credits

- ### Content
The original text for the entired site was provided by Franco Faura Tellez and translated to english by me.

- ### Media
The photos used in this site were provided by Franco Faura Tellez and obtained from istock.


### Acknowledgements

I received inspiration and mockup for this project from graphic designer Franco Faura Tellez.

The Bootstrap Nav tutorial was found through this tutorial [here](https://startbootstrap.com/templates/scrolling-nav/).
The Bootstrap Footers with map was found through this tutorial [here](https://tutorialzine.com/2016/10/freebie-5-fantastic-bootstrap-footers).


## License
[MIT](https://choosealicense.com/licenses/mit/)