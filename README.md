SURFING IN BUNDORAN WEBSITE
View live project here: https://misstechy.github.io/Surfing-in-Bundoran/
This website is user friendly and interactive for surf lovers. It is predictable, clear, responsive and accesible.
| <img src="assets/css/images/largescreen.png" width="250"> | <img src="assets/css/images/ipad.png" width="250"> | <img src="assets/css/images/phone.png" width="250"> 

I loved the atmosphere, scenary and diversity of people so much that I helped them with organising some trips and also DJ-ing for everyone.

Surfing in Bundoran will forever remain a good memory and here I am trying to represent them in my project.

UX
I had a look over Bundoran's Surfing website :https://bundoransurfco.com/welcome-to-bundoran-surf-mobile/ . It looked crowded and unorganized.

Having the chance to experience their services I build an easy, predictable and user friendly website.

I built my wireframes manually using old fashioned pen and papper. And I highlighted the following:
-user friendly and responsive menu;
-gallery pictures to tease the user;
-jumbotron with large social media icons for the user to be tempted to follow and subscribe;
-short introduction about Surfing team in Bundoran and their motivation;
-reviews and feedback as they are extremly important to have on the website;
-packages and services offered had to be visible and user-interactive as well as the prices;
-and of course the footer that has the same details on each page;

As a sales person and also a consummer I always look for the design, content, understanding the information, social media for proof of fun/services, phone number and address.

I believe that the entire project offers enough information to make the user make a choice. And those are photos, links to social media, shop and Sea Sessions Festival, as well as a sign up page.

Tools used:
-Bootstrap:menu, carousel images, sticky jumbotron, grid, gallery interactive images, cards (for reviews and prices) and sign up/sign in;
-Debbugging with: https://validator.w3.org/#validate_by_input;
-Beautifying with: https://webformatter.com/html;
-Image compression so they can load faster: https://tinypng.com;
-Icons taken from:https://fontawesome.com/icons?d=gallery&q=surf;
-Images, logos and package prices taken from: https://bundoransurfco.com;


Features
Menu, Carousel img, Jumbotron, About Us and Footer - Menu Page
-I thought this 3 work nicely together. 
The Menu expands when the screen is large and all pages get inside the Menu square whn the screen size is small. I was looking for a minimalist approach in this case.

Carousel Images -Menu Page
I added 3 images to encapsulate and tease the viewar, such as:how cool people can look with the surf boards, the surf shop, and Sea Sessions Festival Poster that Bundoran Surf partnered with. Also to tease more The button on the first page directs the user to a youtube Intro for Bundoran Surf CO.
All seams statc but the links redirect users to emotional trigers and that was my aim.

Jumbotron - Menu Page
The large icons suppose to encourage the user to click on them and find more proof of fun after clicking on the video button. The Jumbotron bar remains the same size on each page so the user can interact with it antime he wants. Large enaough to not miss it.

About Us - Menu Page
Is a short introduction about Bundoran Surf team acompanied by a Sea Sessions link which takes the user to the Festival's website.

Footer - Menu Page
Encapsulates the partners, opening hours and address and it is present in the same format on all the pages. From a UX perspective it looks predictable in case the user wants to search for the information. The partner logos are actually links to the relevant websites, which also can be seen as proof of Bundoran Surf CO. activities and reviews over the years.

Menu, Carousel img, Jumbotron,Footer - Gallery Page
All of website's parts are sesponsive to different devices and they have the same scope above mentioned. The only difference is that the gallery has more than 3 pictures. From a UX point of view this can be catching for the user alongside with the links from Home. As all know human brain needs a pause from reading and searching, therefore that pause would be glancing over the gallery's slide show.

Menu, View our shop bar, Image gallery, Price cards, Jumbotron,Footer - Services Page
Menu, Jumbotron and Footer is the same and has the same role as in the first 2 pages. 
View our shop bar was intended to be black and abstract from the light colors of the website. Of corse another opton would have been to add another carousel images with some items from the shop. However that would made the page crowded so I figured out that a noticeable suggestion would be a black bar just in case there are surf equipment fanatics.

The image gallery is suggestive for all that Bundoran Surf Co offers as packages and services. If you hover over each image the title and text are suggesting a short and concise description of the services free from discrimination of gender, age, nationality and the quality of free time. Naturally, users look for what they would enjoy to do then they ask about the price. Therefore under the moving gallery images comes the section with the prices with extra info.

Menu, sign in & sign up, Jumbotron,Footer - Sign in Page
Menu, Jumbotron and Footer is the same and has the same role as in the first 3 pages.
For sign in & sign in I used bootstrap the input from user will be white as well as the existing guiding text for what to input. The construction of this page it is quite simple seasoned with a background image with a scenary from Sleaves League, which is 1h from Bundoran.
Sign in & sign in encourages the users to add themselves to clients list so they would be able to have access to more info and the freedom of choosing a package by tickingone of the price cards.

In conclusion the logic behind this website is to get any user interested to sign in and sign up for more information for themselves. Also from a sales and marketing point ov view this website is aiming to build a large list of prospects, for building study cases, reviews, improve services, offer support, mass services sale. The website answers to the following questions: what is this?; how does it work?; how can I find more people like me who does this?; where I can find the location and contact details?; are their services flexible and what is the price?; is it simple and predictable?; is it pleasant to the eye?; would it be easy to find the information if I came back on this website?; where can I leave reviews/complaints?; can I sign up?; can I follow them on social media?;


Contact form:
Submiting the empty form from sign up page has no link attached to it. It is innert.

I used validator to find errors and the most frequent ones were adding extra or wrong attributes, as well as forgeting commas and closed brackets.

Website is working without any problems on FireFox, Internet Explorer and Chrome. Also it is responsive for small, medium, large and extra large devices.

Deployment
My workspace is called Visual Studio. And my steps of deployment are the following:
1.Created my project folder called Bundoran Surfing on the local machine and arranged the folders according to the requiremants: 1st project "Surfing in Bundoran" ->folder assets->folder css->file style.css->folder images; under assets folder the following files are created: index.html,gallery.html,services.htmls,signup.html.
2.I created an account on GITHUB and created a repository for my project. Steps followed:
hithub account->create new repository->name repository-> set it as public->thick box for initialising the repository with README->click on create repository->Surfing-in -Bundoran repository was created.
3.Once I created the HTML and CSS files in Visual Studio I used the following steps to push them to GITHUB through my local machine VSC terminal: git status->git add index.html->git commit -m "new commit"->git push. For each new file I used same commands. 
4.For each changes made in files I used the following commands: git status->git add file name->git commit -m "modified file"->git push.
5.To make the website live through GITHUB I used the following steps:Surfing in Bundoran repository->settings->scroll down to GITHUB Pages->under source selected master branch from dropdown list->waited for 5min for the background of the link under GITHUB Pages to turn green->green means the website is live and others can see it.


Credits
Content
One review, services, packages and prices were copied from Bundoran Surf website. The first 2 reviews are from a friend and from me.
Media
Most of photos are taken from Bundoran instagram and website, as well as from my own instagram. All the links are to be found in the begining of README.md.

Acknowledgements for technical hiccups.
(Idea for project theme and subject was mine)
Mentor:Akshat Garg
Student Support
Tutor: Simen Daehli, Anna_ci, Claire_ci
Alumni:Marcel777,
