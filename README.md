![Friendly Bet Logo](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/fblogo1.jpg "Friendly bet Logo")

This is the README.md file for the project to develop a static, informational website for 'Friendly Bet'. 

## Description

This project is based on a company specialising in 'friendly betting' games, that is; games where users play various
games against each other for money, but mainly for fun and enjoyment. This format is also known as 'pooled betting'. 
It is more similar to a lottery format than traditional sports betting/gambling, which is betting against bookmakers.  

The project and website's aim is to give users an understanding of the purpose of the platform, the games available, how 
they can play each game and the rules. There is also a section explaining the various sports covered where sports fans can 
check which sports are covered on the website.    

Users can navigate by Game Type or Sport. The following three pages make up the website project:
 - index.html
 - gametypes.html
 - sports.html

## User Stories

External users of the site have the following 5 **User Goals** (including relevant section of website where users reach goal):
1.	**Discover the purpose of the website** (navbar throughout)
    ![Friendly Bet Navigation](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USnav1.jpg "Friendly Bet Navigation")
2.	**Find out about the games and how to play them** (Game Types page)
    ![Game Types](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USgametypes.jpg "Game Types")
3.	**Determine whether the games will be fun / enjoyable** (Enjoyable features on Home page)
    ![Why Play](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USwhyplayFBgames.jpg "Why Play")
4.	**Find out the sports covered by the platform** (Sports page)
    ![Sports](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USsports.jpg "Sports")
5.	**Understand the rules** (Modals in Game Types page for specific game rules)
    ![Rules](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USrules.jpg "Rules")

The site owner has the following goals (brackets include the relevant area of website goals are achieved):
1.	**Generate user interest in playing the games** (Home page introduction, benefits and navbar)
    ![Why Play](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USwhyplayFBgames.jpg "Why Play")
2.	**Allow users to easily understand the games and why they are fun** (Game Types page and how to play)
    ![Game Types](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USgametypes.jpg "Game Types")
3.	**Make them likely to tell their friends about the games and share them** (index.html/why us?)
4.	**Users associate upcoming sporting events with the games themselves e.g. Premier League, Masters Golf, Grand National etc** 
(Sports page links and info about official tournaments)
    ![Sports Events](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/USsportseventsGN.jpg "Sports Events")


## User Experience (UX)

The brand colours of Friendly Bet are blue and orange, with a hint of white. The reason for the colour choice is 
that blue denotes trust (important for a site offering social betting games for the first time) and orange 
represents fun. Significantly from a design and UX perspective, blue and orange are complementary pairs on the 
color wheel. The branding colour combination is maintained in the logo and navbar of the header, as well as the 
footer via the branded blue background, white h5 headings and branded orange h4 headings. Users are never far
from branded navigation.

The images on the home page show groups of friends gathering, cheering and coming together to enjoy sport, which is precisely
what the brand is about. The images in the gametypes page are more representative of the games themselves - Last Man Standing
requires the winner to be the only player remaining, Sweepstakes are all about putting money in a kity/pot and watching the
action, while Prediction Competitions are more about studying the form, probabilities etc.

The footer section clearly defines (using branded links) where users can contact the company, keep in
touch via social channels or sign up to the newsletter for updates.

The benefits of playing games offered by 'Friendly Bet' are clearly dipicted with green tick icons, quickly drawing them
to the attention of users in the 'Why us?' section of index.html.

## Testing

For testing, acceptance criteria was driven by the user stories (which include the navbar/header testing) and footer testing.
Manual testing was carried out on the following five **User Stories**:

1.	**Discover the purpose of the website.**  <br>
Tests completed and outcomes:  
- Users land on the home page index.html which displays a content introduction to the website.
- Navbar provides easy navigation and the navbar expands and collapses as expected.
- In index.html, all navbar links work to the 'Why Friendly Bet' section, Game Types page and Sports page.
- In gametypes.html and sports.html, all navbar links work to the 'Why Friendly Bet' section, 
Game Types page and Sports page.

2.	**Find out about the games and how to play them.**  <br>
Tests completed and outcomes:
- In gametypes.html, all three accordions for each Game Type (Last Man Standing, Sweepstakes and Prediction Competitions) 
    expand and collapse as required.
    
3.	**Determine whether the games will be fun / enjoyable.**  <br>
Tests completed and outcomes:
- Link to benefits of website in 'Why Friendly Bet' section in index.html works on every page of the site.

4.	**Find out the sports covered by the platform.**  <br>
Tests completed and outcomes:
- In sports.html, all five accordions for each Sport (Football, Horse Racing, Golf, GAA and Rugby) expand 
    and collapse as required.
- For Football, all three external links to websites work correctly.
- For Horse Racing, the two external links to websites work correctly.
- For Golf, the external link works correctly.
- For GAA, the external link works correctly.
- For Rugby, the two external links to websites work correctly.

5.	**Understand the rules.** <br>
Tests completed and outcomes: 
- Modal with Rules for Last Man Standing opens, displays the rules and closes as expected.
- Modal with Rules for Sweepstakes opens, displays the rules and closes as expected.
- Modal with Rules for Last Man Standing opens, displays the rules and closes as expected.

### Footer (Manual Testing)
Tests completed and outcomes:
- All four social links work on index.html, gametypes.html and sports.html.
- In Contact Us, telephone link works in index.html, gametypes.html and sports.html.
- In Contact Us, email form works in index.html, gametypes.html and sports.html.

##### Pingdom (Performance Testing)
Pingdom Performance Grade: B88.
![Pingdom Testing Results](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Pingdom%20Test%20Results.jpg "Pingdom Testing Results")

## Features

The navbar uses a responsive collapseable Javascript plug-in. This allows users to toggle between the navigation
options, while keeping the brand logo at the top of the viewport at all times.

In the gametypes.html file, users are given a brief introdution to each game, details of how a game is played
and a more definitive set of rules for those looking for a deeper understanding. The rules can be accessed from 
a modal - this is the 'less fun', more serious content is not taking up large sections of a page that predominantly
aims to focus on the fun aspects of the games. The button type used from the Bootstrap framework is the button
'info' class which reprents what the users are accessing. The secondary button is used for closing.

Within sports.html, external links to sport fixtures and schedules are displayed with an arrow pointed right
to give clarity to users that they are leaving the site. 'target=_blank' is used to ensure users can easily 
navigate back to the Friendly Bet site.

In both gametypes and sports pages, collapse components are used to allow users to toggle their preferred choice without
having all options open at once. The show class is used to display the first option on each page for visual effect when 
users land on the gametypes/sport page.

## Scalability

Future iterations of the project can have several actual games included for the user. Live games could be added, 
based on the documented formats, which utilise JavaScript to bring the games alive for the user, add backend 
funtionality and manage databases to store customer data, connect to live data API's etc. Features may include
user accounts, live tables, share functionality and ultimately UX driven game development. Fixtures and blogs can
also be incorporated, reducing the need for users to access external websites and increasing 'quality' traffic - 
users already interested in the subject matter.


## Technologies

The Bootstrap framework was frequently used throughout the side. The grid was used to layout the website. Many components
on the site were taken from Bootstrap and subsequently customised.
Jquery, popper and bootstrap cdn js plug-ins were copy and pasted to the site from w3schools.com.
Fontawesome was used for the icons in social links, external links, greens ticks and contact links.
Unsplashed.com was mostly used for the images on the site. Google images was for just one.
Logopony.com was used to generated the logo, a screenshot was subsequently taken of it and uploaded.
Google Fonts was used and plugged-in for the 'Exo 2' font and expolration of other fonts.

## Wireframes
![Wireframe 1](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe1.jpg "Wireframe 1")
![Wireframe 2](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe2.jpg "Wireframe 2")
![Wireframe 3](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe3.jpg "Wireframe 3")
![Wireframe 4](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe4.jpg "Wireframe 4")
![Wireframe 5](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe5.jpg "Wireframe 5")
![Wireframe 6](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe6.jpg "Wireframe 6")
![Wireframe 7](https://github.com/RoyoftheRavers/friendly-bet-games-dev/blob/master/assets/images/Wireframe7.jpg "Wireframe 7")


## Acknowledgements
CI Mentor - Felipe was excellent in giving advice around the planning and execution of the project, including several
useful tips and resources. He was always available for calls, emails or IMs. CI support provided help and guidance throughout.

