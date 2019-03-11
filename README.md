 # The Muppet Clicky Game 


The Muppet Clicky game is a web game application where users click images of Muppets in order to earn points. You win the game when you have clicked all 9 of the Muppets. The only catch is that the muppets change locations with every click...

 ## Technologies Used:
React.js- UI

 ## About the Code:

Getting Started

First thing I did was create the React Client-side boilerplate by typing create-react-app clicky-game-app in the command line. Next, I changed into that directory by typing 'cd clicky-game-app' in the terminal. After that I typed yarn start to open the app in the browser.

Starting to Code
Create-react-app gives you a public folder with a basic index.html page, some basic css for the react template, an App.js file, index.js file, and some other boilerplate files. The bulk of the code for this app was done in the src/components directory. 

### Components

#### ClickItem
handles the clickItems and their corresponding Muppet images. 

#### Header
handles the header and the greeting.

#### Game
Creates and manages and executes the core functionality of the game and its scoring. 


#### Nav
The Nav component is where the score is displayed as well as displaying th rendered game playing messages.

#### Container
The Container component wraps the ClickItem component.

#### NavMessage

The NavMessage is where the scoring and the rendering messages are created with JavaScript(ES6). 
#### Footer

Footer also holds the App name as well as the React logo.

The Muppet Clicky Game can be found on Heroku [here](https://limitless-bayou-59747.herokuapp.com/)
The Muppet Clicky Game Designer and Programmer: Erin Kenney 