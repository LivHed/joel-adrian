# Joel Adrian - Stunt performer
This is Milestone Project 1: User Centric Frontend Development - at Code Institute.


This is a website that functions as a portfolio for Joel Adrian, Stunt Performer. The portfolio enables all of Joels work to be gathered and shown in one place, in form of photos, videos and a resume.
The website have five pages that shows a presentation of Joel, what kind of work he have done and how you can contact him or follow him on social media. 
(One or two paragraphs providing an overview of your project.
Essentially, this part is your sales pitch.)




## UX
After doing research looking at websites from the stunt performer community and interview Joel about his wishes and needs with the portfolio, my goal with the design was set: 
1. That it would be easy to find what you want on the website. 
2. The design would be suitable for the stunt-community with colors that give a feeling of a tough and rough edge, but still with a stylistic and minimal design.

(Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.)


### User stories
(In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure: As a user type, I want to perform an action, so that I can achieve a goal.)
* As a colleague in the business I want to have a look at Joel Adrians work to find out what projects he´s busy on, befriend him on social media to expand my network in the business, and send him a message on the contact page with a collaboration idea.

* As a martial artist or exreme sportsman I want to have a look at Joels videos,  pictures and resume to get inspired and learn about a career in the movie industry. 

* As a coordinator, director or possible employer I want to have a look at his showreel and photos. I also want to read his resume and download it, so that I can hire him for a project. 

* As a fan of Joel Adrian I want to look at pictures and videos of him, so I can get to know more about him. I also want to find out where I can follow him on social media. 


### Wireframes
The wireframes I did as a part of the desin process are linked in a separate directory in the project, called **wireframe**. One is designed for desktop view and the other for mobile view.
(This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.)
**Can I link directly here in the text to the wireframe directory?**


## Features
(In this section, you should go over the different parts of your project, and describe each in a sentence or so.)
### Existing Features
(Feature 1 - allows users X to achieve Y, by having them fill out Z)
* The navbar and the footer have the same color, so every page will give a sense of a familiarity, even though the content is changing.
* I planned for the scrollbar to be discrete. That´s why I chose a background color that is slightly darker than the navbar and the footer. I chose not to have the same color as them, so it won´t give the impression that they float together as one element. 
* The About me page is the landing page and gives a short introduction to Joel Adrian. 
* The My work page show Joels resume directly on the page, and also give the opportunity to click on a link to download the resume and click on another link to get to Joel Adrians IMDB page.
* The Videos page include two videos that shows what kind of stunts Joel is able to to and clips from movies. 
* The Photos page shows images in one row that is clickable and will show in a separate window if clicked on.
* The Contact page include a contact form that gives the opportunity to get in touch with Joel with collaboration ideas or job opportunities. 

* The navbar collapse on smaller screens- which provides with a disrete design and easy user experience with the menu items grouped together.
* The Download my resume link and the Social links is placed in the footer to be easily accessed on every page on the website.
* The contact form is placed with no other content on the page to be easily accessed and also gives instructions that is easily understood so the users can contact Joel. 
* The resume pdf document is also embedded responsilvely in the My work page, to be easily overviewed. Under it it´s also possible to click on a link to be able to download it. 
* A custom scrollbar is added so the users can be able to scroll up and down the pages easy.
* The hover effects is designed with a dark color to suit the users and the transition effect is set to feel smooth.
* The fullwidth background image is suppose to remind the users what Joel is all about, a Stunt Performer with experience in the movie industry. The content scrolls infront of the image and it is the same on all pages to give a sense of familiarity and a recognizable design. 
 

(For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.)

(In addition, you may also use this section to discuss plans for additional features to be implemented in the future:)

### Features Left to Implement
(Another feature idea)

1. In the future I want to add more videos to expand the experience of Joel as an experienced Stunt Performer. Today these videos are the existing that Joel want to share.
2. In the future I also want to change the current image grid to a lightbox, for the users to be able to see the images on the same page they are currently on. I want to test this to see if this technique changes the amount of clicks on the Photos page.

## Technologies Used
**The languages** I have used for this project is HTML and CSS. 
**The libraries** included are Ajax, Popper. And also Fontawesome and Jquery. 
**Frameworks** I have used is Bootstrap 4.3.1
**Other tools** I have used are Cloud9 IDE for writing my code, and then pushed it to Github, where the project is stored and deployed.


(In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
JQuery
The project uses JQuery to simplify DOM manipulation.)

## Testing

As a new visitor to the site as a fan, colleague or coordinator, I want to be able to find everything I need easily. Therefore the navbar have been placed in the conventional position at the top of the page, and each of the page sections are clearly labelled in it.
The footer is also placed in the conventional place in the bottom of the page. Here I have placed links to Social media and a link to download the resume, so the needs for possible employers, coordinators or directors to get the resume information will be able to get this quickly from whatever page they are currently on.

(In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.)

(Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.)

(For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits
### Content
The text for section Y was copied from the Wikipedia article Z

### Media
The photos used in this site were obtained from ...

The photos used in this site were obtained from Joel Adrian, that is allowed to use the images he´s in if it´s not used to sell something. **Ask Joel if there were more reasons, to be sure**
The videos used in this site were linked from Joel Adrians own Vimeo page. Here is [one of them.](https://vimeo.com/339213684)
Here is [the other video](https://vimeo.com/198885890) from Joeal Adrians Vimeo page.

### Acknowledgements
I received inspiration for this project from [this website](https://www.ellettecraddock.com/)
I Copied the code for the contact form from [this page](https://codepen.io/BlackNina/pen/MxoVqv?editors=1000) and then I modified it to how suits my needs.
The original code for the image grid was copied from [this page](https://mdbootstrap.com/docs/jquery/content/images/) and then customized for my one column-idea. 