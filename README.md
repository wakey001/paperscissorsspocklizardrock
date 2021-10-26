# wakey001/Rock Paper Scissors
***
Rock, Paper, Scissors . This game is for adults and children is a  fun , intuitive replayable game that is played against the computer.
## Rock Paper Scissors Game
![ami image to be done](ami-readme.png)
***

## Goals For This Project
 
***



## Table Of Contents
* Ux
    * User Goals
    
    * User Stories
   
    * Site Owner Goals
    
    * User Requirements And Expectations
      * Requirements 
      * Expectations
        
    * Design Choices
      * Fonts
      * Icons
      * Color
      * Structure
     
* Features
    * Existing Features
    * Features To Be Implemented
* Technology Used
    * Languages
    * Tools And Libraries
* Testing
* Deployment
* Credits
***
## Ux
***
### User Goals
* The game should have relevant content
* The game should be easy to use on all platforms
* The game should be intuitive and look modern
* The game should be fun, exciting
* The game should work without fault or glitches 

### User Stories
* As a user I want the game to be easy to navigate
* As a user I want the game to have useful information
* As a user I want the game to be exciting  
* As a user I want the game to be visually stimulating
* As a user I want the game to be current and modern in design

### Site Owners Goals
* To have a working game which is fun to use
* The game sould be easy and fun to use 
* The code should be easy enough to read as to be potentially upgraded or extened to include other weapons such as spock or lizard in the future
***

### User Requirements And Expectations
***
#### Requirements
* Easy to play and understand who is winning
* Relevant quality content
* Clear rules in footer
* Visually appealing
####  Expectations
* The user expects the game to be fun
* The user expects the game to entertain them
* The user expects the game to react smoothly with minimal lag 
* The user expects the game to be visually appealing
***
### Design choices


#### Fonts
Fonts for my website are from [GOOGLE FONTS](https://fonts.google.com/). I have decided to go with FONT HERE as I feel in my opinion this is a modern and current feel and is easy to read.I also chose the same for my header as I feel this contasts well with the main text as when larger its flair is even more noticabe in my opinion.
#### Icons
 Icons for my website are from [FONT AWESOME LIBRARY](https://fontawesome.com/).The icons I have chosen are in fitting with the game type as they provide a little fun whilst giving a visual cue whilst also making the site feel modern and for a young audience.
#### Colors


***

### Features 

#### Existing Features

##### Main Images

The images I have used were borrowed from google images and cropped and flipped in paint to create negatives of each other. I chose these hand guestures over the actutual physical images as imo its makes the game more fun and silly which is what it is really , a simple game that can be played with hands too.

##### Game Area
For the game area I have decided to have apposing images as I feel this gives the game an arcade like vs feel .
 One side for the computer and one for user/player and above this corresponding area is a scoreboard which goes up accordingly depending who wins.


##### Footer 
For the footer i have decided to show a brief description of the rules . This is a black border-box with a width of 100% and text aligned centraly and in white to stand out .

##### Features To Be Implemented
 In the future I wish to add lizard and spock to the game as well as updating the styling to perhaps more of a simple styling as apposed to the arcade like layout of this one.

#### Bugs

* ##### Bug 
An issue I came across was with my win() function being implemented . This fuction was to increment the score. The problem was the numbers on the score board would say NaN . 

 

* ##### Fix 
Could not figure out the problem so turned to slack for help . This put me in the direction of looking at what my variables values were which turned out to be the main problem . I had not declared that the variable for playerScore and computerScore needed to be 0 . 

* ##### Verdict 
After the fix I tested the game thouroughly to find It now works perfectly with the scoreboard working fluently.

#### Mobile device

* #### Bug 
When on smaller devices under 350px  , the div expands when scissors is chosen making one side lop-sided


* #### Fix 
I decided the best option was to decrease the font size using a media query for screens under 350px. I targeted divs with h2 headings and played around with different sizes before settling at 70% .

* ##### Verdict 
After implementing the fix the mobile devices under 350px now display constant sizes reliably and does not increase or decrease the size of the div.

#### images
* ##### Bug 
When uploading my images of rock paper scissors . They load vertically by default and were both to the left of there div containers. This looked terrible so neede to be fixed. 

*  ##### Fix
I fixed them in css using display:flex , flex-direction: column , and align-items: center .
  
 
* ##### Verdict
This made them sit perfect in the middle of their div container whilst still retaining the vertical image layout.
 

***
### Technologies Used

#### Languages
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)
* [JS](https://en.wikipedia.org/wiki/JS)
#### Libraries And Frameworks
* [FONT AWESOME](https://fontawesome.com/)
* [GOOGLE FONTS](https://fonts.google.com/)
#### Tools
* [GIT HUB](https://github.com/)
* [GIT POD](https://www.gitpod.io/docs/configure/)
* [W3C HTML VALIDATION SERVICE](https://validator.w3.org/)
* [W3C CSS VALIDATION SERVICE](https://jigsaw.w3.org/css-validator/)
* []
***

### Testing 

* I tested playing this game on different browsers : Chrome, firefox, Safari.
* I confirmed the game always works correctly.
* I confirmed the header, instructions, options are al readable and easy to understand.
*  I confirmed that all colours and fonts chosen are easy to read and accessable by running it through lighthouse in devtools.
![]


***
### Deployment
This project was deployed using github using the following method:

1.After logging into github.com open repository
2.Click on settings then on the left find the pages section 
3.Once in pages click on master branch and then save 
4.Now a link should appear and in a few moments be able to be clicked 
5.This is now a live website than can be viewed from any device

To run it locally on gitpod follow this method:

1.Assuming you have gitpod as an add on . Click on which repository you want to run .
2.Click on gitpod this should then take a few moments 
3.Once loaded find the terminal section and type python3 -m http.server
4.This will open a port 8000 ,click yes to open
5.A new tab should appear with your work ,although sometimes needs to be refreshed 


***

### Credits
#### Content-Media-Inspiration
My inspiration was a mixture of codeinstitute, youtube two youtubers inparticular and my personal view on how I wanted it to look.

#### Images 

#### Acknowledgements
I'd like to firstly acknowledge my mentor Simen D , his guidence helped me structure the project to meet deadlines for our meetings which helped immensley .Id also like to thank the members of slack who helped me with some issues I had . Nameley JavaScript parseInt.






