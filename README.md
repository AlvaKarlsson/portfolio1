# Towards Ironman
Towards Ironman is a website for people that want to challenge themselves to complete an Ironman, no matter the distance. Together with one of the coaches, a personal training program is produced to suit the user and their goals. No prices are written out because pricing varies depending on length of the program, if the client wants a nutrition guide, help the days following up to the race with packing, nutrition during the race and other things. The absolute pricing is presented when the client and the coach has had a first meeting and talked about how extensive the programme will be.

The site is designed to be intriguing and set a spark of interest for the user to challenge themselves to a bigger goal. They have access to different ways to engage contact to the coaches and a section of thorough information about the programmes and the general structure.

![Screenshot of the different webpages depending on screensize](https://user-images.githubusercontent.com/114992573/198244274-22ce7a4d-4e79-46db-80b2-1b9a5090eaba.png)

## Features
**Navigation**
- Easy to access navigation at the top right corner of the page. Links to the different sections of the page.
- The font is easy to read and follows along further down in the page. The dark background with the white text makes it easy to read. With clear directions to where the links lead makes it even more easy to navigate throughout the site.

**Big motivational picture**
- Draws attention to the user and has a motivational quote on top of the picture for a big statement as a first view of the page.
- The color scheme in the picture fits in with the rest of the page and makes it cohesive.

![Navigation bar and big motivational picture](https://user-images.githubusercontent.com/114992573/198257692-7d0ff21b-fcad-40cc-968f-cc543b75d8e1.png)

**Introduction of the page**
- Gives the reader a short introduction to what the site is all about.

**Information section**
- To the left: A short presentation of the coaches that run the site and what history they have in triathlon and personal training.
- To the right: Basic but clear information about how it works and what the programmes usually include.

![Information section](https://user-images.githubusercontent.com/114992573/198264826-fe0f1adb-79b7-4662-aa0d-fac79eeab79f.png)

**The sign up form**
- If the user wants to get a personalized program, they fill in the form further down the page. All it asks for is for a name (first and last name) and a phone number so the coaches can contact the person about the program. 

**Footer with contact information and social media**
- If the user instead is a bit more insecure and wants to have some answers before they sign up for an interest in a programme, they can contact the company through phone or email.
- The user can also check out the coaches social media pages to see more about what they do and get to know them a bit more as well.

![The form and the footer](https://user-images.githubusercontent.com/114992573/198264959-45411b46-4a57-432d-bd9b-476606825ebb.png)

## Testing
- The website has been tested and works in various web browsers. The ones tested are: Google Chrome, Microsoft Edge and Mozilla Firefox.
- The website is responsive and works on both mobile, tablet and computer sizes. Tested via Devtools Device Toolbar and on my own phone.
- All the navigation links work as they should.
- The form works as planned and cannot submit before all the information that's asked for is in place.

### Bugs
- When the site was deployed via GitHub Pages, I discovered that the style.css-file and images did not communicate to the index.html-file.
- After some testing I later found out that it was because I had an absolute file path in the code.
```
<link href="/assets/css/style.css" rel="stylesheet" type="text/css"/>
```
- To fix the problem, I deleted the first `/` in the `href=/assets/` and that fixed the bug.

### Validator Testing
- HTML (W3C HTML)
  - No errors when code was checked via [W3C HTML Validator](https://validator.w3.org/#validate_by_input).
  
- CSS (CSS Jigsaw)
  - No errors when code was checked via [W3C CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/).

- Accessibility (Lighthouse)
  - The Lighthouse function in devtools confirmed that the site had good accessibility and that it performed good.
  - I tested for both mobile devices and for computers. The top picture is the result for mobile devices and the bottom picture is for computers.
  
![Accessibility on phones](https://user-images.githubusercontent.com/114992573/198268865-87690c80-ffeb-46a7-bd2e-d3fc63032ea9.png)

![Accessibility om computers](https://user-images.githubusercontent.com/114992573/198268928-eca24236-2e53-4564-8b1d-c5fc05cc306e.png)

### Unfixed Bugs
- No unfixed bugs that I have found.
  
## Deployment
- To deploy the web page, I used the GitHub pages. Here is how I deployed the web page:
  - In the GitHub repository on my project page, I clicked the settings menu.
  - To the left in the settings menu, I searched for the section called Pages.
  - There I chose what branch source I wanted to use, and chose main in the dropdown menu.
  - After some minutes I refreshed the page using F5 and the site was deployed.

To come to the page, click [here](https://alvakarlsson.github.io/portfolio1/).

## Credits
- The coding I wrote to make the floating text box on the big main picture, I used a lot of guidance from the [Love Running Project](https://alvakarlsson.github.io/love-running/).

- The big main picture is downloaded from the website [Pexels](https://www.pexels.com/).
