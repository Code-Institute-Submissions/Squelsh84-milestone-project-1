# Maide Connemara

Please click [here for a live demo of the website.](https://squelsh84.github.io/milestone-project-1/). 

My First Milestone Project for Code Institute is a website idea for a real business. My father has been making Handcrafted walking sticks for years but has only ever given them away for free or people have bought them when calling to the house. 
This is a fully responsive website designed to create a funnel to create first contact with potential customers.

# UX
 
#### Who is the target audience?  
- A person who is interested in hiking.
- Uses Walking sticks for hiking or everyday walking.
- Looking for a unique piece that can't be bought in a store.

#### Why is this the best way to target the audience?
The website is designed to lead the customer down through the page to create the initial contact. As the person makes their way down the page the learn about the person to build a rapport.
Next, they learn about the types of wood used and a video of the workshop. Following this the see some sticks that have been made and the different types of woods used. This helps the potential customer to have an idea of what they want.
At the end they will be able to make contact through the simple contact form provided at the bottom.

## User Stories

1. As a user, I want to know where the material was sourced.
2. As a user, I want to know what wood is used.
3. As a user, I want to see previous work.
4. As a user, I want to be able to make contact easily.




### Wireframe

- [Link to my Wireframe on Figma](https://www.figma.com/file/ejZ5n3XOZiFXWCiDn8KqzQPg/Milestone-Project-1?node-id=0%3A1)
	- I decided to use figma to create my wireframe because it gave me a real visual of what I wanted to implement. It took some time as I found it challenging but was worth it.

# Technologies

- Html
- CSS
- [Cloud9](https://c9.io) - Used for a development and testing area.
- [Bootstrap](https://www.bootstrapcdn.com/) - Bootstrap framework to create responsive design and fontawesome for social icon.
- [fancybox](https://fancyapps.com/fancybox/3/) - Creates a gallery modal popup.
- [Google Fonts](https://fonts.google.com/) - Used to style the fonts of the website.
- [Vimeo](https://vimeo.com) - Used to host video used in walking in time area.
- [jQuery](https://jquery.com/) - To make certain features function on the page.
- [Cloudinary](https://cloudinary.com/) - To host large images.
- [git](https://github.com)- Used as a repository.


## Features

#### Feature 1 – Scroll spy Navigation Bar
The navigation bar changes colour as you scroll down the page. This allows the user to know easily where they are on the page.
This collapses into a 'burger icon' dropdown menu in mobile screen sizes to reduce over-crowding and improve user experience.

#### Feature 2 – Jumbotron with Find out more button
This feature brings the potential customer to the embedded video to find out more about the sticks and how they’re made.

#### Feature 3 – Cards with Images
Gives the customer a brief description of types of woods used with buttons to more information.

#### Feature 4 – Embedded Video
Lets the person feel that they know who they are dealing with and helps create a bond with the customer.

#### Feature 5 – Gallery with Fancybox viewer
Customers can see how previous pieces of work have turned out and when clicked can get a closer look at the craftsman work.

#### Feature 6 – Contact Form
Allows potential customers to ask questions about pieces in the gallery or to start the process of ordering a piece.

#### Feature 7 – Social media icons in footer
Allows the customer to connect and follow the craftsman’s other pages.



### Features Left to Implement
- Add a payment feature for sticks available.
- A map of forests for best walks
- Create a blog section to share information about the art of Stick making and some walks around Ireland.
- GDPR compliant pop-up screen to make sure the website complies with European law.


## Testing 
- Used Google Chrome developer tools to test website responsiveness across multiple devices such as Tablets and Mobiles.
- Tested the contact form for the required attribute. With this attribute it will not let you submit the form with the required 
  information. To test this i tried to send the form without the required information but was not let until all information was given correctly. 
- Tested that the smooth scroll worked when clicking on the links in the Navbar. This had to be done on all on tablets and phones too. 
- Tested the link buttons to ensure they responded correctly. I tested these to make sure they open in a new page on devices.
- Used [W3c validator](https://validator.w3.org/) to validate both HTML and CSS. I copied my code and pasted it into the validator to check for errors and warnings.
- Used [Browserling](https://www.browserling.com/) to test the website across multiple browsers. I used this to test my site on opera and safari as I don't have these browsers available.

### Issues when Testing
- On certain screen sizes the padding on the sides of the about us section were creating a long text. this was making the page seem longer and wasn't pleasant on the eye.
  To fix this I reduced the padding to create a larger area for the text and this reduced the length of the text too on smaller screens.
- The navbar menu was taking up too much screen space on the iPad. It stretched across almost all of the top of the screen. To get around this and to create a more pleasing visual
  experience, I changed it to become a 'hamburger menu' from lg down.
- The type of woods cards were leaking over into the next container and stretching passed their container. After trying to create blocks and trying different rules, I created media queries to fix this issue.
- When testing on different browser I found the code had not been optimised and used [Autoprefixer](https://autoprefixer.github.io/) to optimize it. I copied and pasted the code and it added the neccessary code to fix this.
- Page was loading very slowly and images were slow if not loading up. I discovered that my image files were too large and after using [Shortpixel](https://shortpixel.com/) the images were reduced in size and the page loaded much faster.
- A major issue was that my Gallery was opening up multiple tabs after going to the contact us section and back to gallery. After searching on line and not finding any solution I decided to re-write the code again and add the scripts again. Also my original id was Gallery for this section
  and I changed it to gal. After making all these changes it has worked perfectly since.  


## Deployment

The website was developed using Cloud9 IDE, it was then committed to git and pushed to GitHub using the terminal in Cloud9.

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

- Log into GitHub.
- Select the repository **Squelsh84/milestone_project_1**.
- At the top of the page, select **Settings**.
- Scroll down to the GitHub Pages section.
- Under Source, select **Master Branch**
- The live link for the website will now appear beneath the **GitHub Pages** header.
- Click the link and a live website will open in a new tab.


### How to run this project locally
If you wish to clone this project from GitHub:

- Click on this [link](https://github.com/Squelsh84/milestone_project_1) to the GitHub repository.
- There is a green button saying "Clone or download" on the right-hand side, click on this.
- Next copy the clone URL for the repository that is provided.
- Open Git Bash in your local IDE.
- Change the current working directory to the location where you want the cloned directory to be created.
- Type ```git clone```, and then paste the URL copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
````
- Press Enter to create your local clone.

## Credits

### Content
All content on the page was written by me. 

### Media
Photos for the types of woods were sourced using google images.
All the photos in the gallery and video in this website were provided by Mark Walsh and Benjamin Walsh. His work can be found [here]( https://www.benjaminwalsh.ie/)
,Favicon was created using [Canva](https://www.canva.com/)
Footer social icons were taken from the "rosie cv" module.

### Acknowledgements

Big thank you to my mentor Seun Owonikoko who guided me through this project. Also thank you to Anna Greaves who provides a wealth of information and material on slack.

**This is for educational use.** 

