# Memory Game
Here is a very popular game called memory game. It's a fun game for both adults and children. Great exercise for memory and concentration and can make the time more pleasant. 

[View the live project here](https://mariaarnesson.github.io/project_memory/)


![responsive](assets/images/responsive.png)

# Features
## User Experience 
### User stories:

- The user should be able to read the instructions of the game by reading the instructions on the homepage.
- The user should be able to see all 16 double-sided cards random selected.
- The user should be able to change the background color.
- The user should be able to see the tab by clicking on it to match it with another card.
- The user should activate the timer by clicking on button: "Game Start".
- The user should activate the move counting by pressing on the first two cards.
- The user should be able to stop the game at any time during the game by pressing "Stop Game".
- The user should receive a message when all cards have been matched and how many moves have been made at the end of the game.
- The user should be able to play again after finishing the game by pressing: "Play Game"

## The Memory Game Logo:


- When the user open the page the first thing the user can see is the Memory Games logo as well as options to start the game or read the game instructions:


![home_page](assets/images/homepage1.png)
![home_page2](assets/images/homepage2.png)

- The Game Area:
    - By pressing on "Play Game" the user will continue to the other side with the game area. 
    - The Timer starts and moves are counted each time the user selects two cards.
    - The user can choose any cards and match them together:

         ![game_area](assets/images/game_area.png)    



    - This is what all pairs of cards look like:
![game_page](assets/images/game_page.png)
    - This is what the different background colors of the game look like:
![yellow_background](assets/images/yellow_background.png)
![blue_background](assets/images/blue_background.png)
![gray_background](assets/images/gray_background.png)    

    - The final message looks like this:
![game_over](assets/images/Game_over.png)


## Features Left to Implement

 - I would like to add a sound animation to the game so that the sound effects can be played every time a card flip is clicked.
 - I would like to add a time in which the user has to fit in order to finish the game quickly.
 - I would like that the user has access to difficulty levels.

# Design

## Wireframe:

![wireframe_home](assets/images/wireframe_home_page.png)
![wireframe_instruction](assets/images/wireframe_instruction.png)
![wireframes_memory_game](assets/images/wireframe_memory_game.png)
![wireframes_ipad](assets/images/wireframe_ipad.png)
![wireframe_iphone](assets/images/wireframe_iphone.png)


## Colour Adobe

![colors_home_page](assets/images/colors_home_psge.png)
![colors_message_page](assets/images/colors_massage_page.png)
![colors_yellow_background](assets/images/colors_yellow_background.png)
![colors_blue_background](assets/images/colors_blue_background.png)
![colors_grey_background](assets/images/colors_gray_background.png)

# Testing

## Validator Testing

- HTML
    - No errors were returned when passing through the officialW3C validator.
    ![validator_html](assets/images/validator_html.png)
- CSS
    - No errors were found when passing through the official (Jigsaw) validator.
    ![validator_css](assets/images/validator_css.png)
- JavaScript 
    - No errors were found when passing through the official Jshint validator.
    ![validator_js](assets/images/validator_js.png)

## Lighthouse Testing

### Lighthouse Mobile:

![lighthouse_mobile](assets/images/lighthouse_mobile.png)

### Lighthouse Desktop: 

![lighthouse_desktop](assets/images/lighthouse.png)

# Problems Encountered:

- Because I added <script src="assets/js/script.js"></script> in the <head> element on the html page, none of the functions wanted to work for me after the page was onload, so I had to move the script at the bottom of the body element.

- I couldn't create a function changeBackground() because instead of writing const wrapper = document.getElementByClassName("wrapper) I should have used: const wrapper = document.querySelector(".wrapper"); After typing it correctly everything worked as it should.

# Deployment:
- The site was deployed to GitHub pages. The steps to deploy are as follows:
    - In the GitHub repository, navigated to the Settings tab.
    - From the tab in the left hand side sidebar, select Pages.
    - Afrerword select main under branch. 
    - Click the save button.
    - The page had updated. 
    - The live link can be found here - https://mariaarnesson.github.io/project_memory/



# Technologies Used
## Languages Used
- [HTML](https://sv.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)
- [Javascript](https://sv.wikipedia.org/wiki/Javascript)



# Credits

## Content:
 - [Memory game JavaScript](https://www.youtube.com/watch?v=dqqxkrKhfS4&t=2s) this tutorial was followed and some JavaScript code was taken and adapted to my game.
 - [Adobe color](https://color.adobe.com/sv/create/image) this page was used to explain what colors I used to designe my game.
 - [Memory game](https://www.codingnepalweb.com/build-memory-card-game-html-javascript/) this page was used and a code which makes a animation to shake cards was taken.
 - [w3schools](https://www.w3schools.com/js/tryit.asp?filename=tryjs_setinterval3) My codes were based on information from that site
 
 ## Media:
 - [Freepik](https://www.freepik.com/search?format=search&query=memory%20game%20logo) All the pictures in my project were downloaded from this site


