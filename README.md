# super-space-blasters
DESIGN DOCUMENT - Team 13

Project Name:	Super Planet Blasters
Contact Information:	Phone #	
E-mail

Sponsor	Camden Cornwall	
661-992-5625	
camdenc.cornwall@gmail.com

Team Member	
Adam Gehring	
435-828-3303	
gehringadam@byui.edu

Team Member	
Tyler Hanson	
714-881-9771	
han15002@byui.edu

Team Member	
Bill Willden	
704-978-8647	
wil11075@byui.edu
			

Core Features:
_______________________________
A Top Down endless forward scrolling shooter for the android phones and tablets.
Some features include:

•	Stationary and moving enemies
•	 power ups
•	levels of difficulty 
•	start screen
Advanced Features:
Some extra things we hope to be able to include
•	boss battles
•	Skins or themes
•	“Character Dialogue”

An overview of the design / approach:
___________________________________________
The application will need to create a GUI menu on the startup. 
1.	It will display the game logo/Title and background image
2.	Play theme music
3.	Display buttons
The GUI interface will wait for user input. It will create a new game instance on start,
mute the sound if the sound off button is pressed. 
Once the game starts It will begin the game music and the background scrolling.
We will have patterns and rules set up for each level of gameplay. Small enemies that spawn from the top and top sides and
large enemies that spawn and move slowly to appear stationary. This continues until the user ship is destroyed and the new “game over”
intent will start. From that screen the process can start again or go to the main menu activity. 
Gameplay itself will consist of the main ship constantly firing as the user moves it around by touch (stretch goal could be 
gyro if the device allows). Waves of small ships will come in on the predesigned patterns randomly and shoot lasers that can 
kill the main user ship. On intervals, bigger ships that are meant to appear stationary will appear and shoot as well. 
For a stretch, we would also make big guns on planets target the user for a few seconds and give a warning before firing a 
laser in the direction of the last position of the user ship. As the game progresses, we will have a type of timer increment 
the level counter of the game which will increase the difficulty, causing more ships to appear or shoot faster. We hope to get 
the core parts completed so that we can add “bosses” at certain level increments which will stay at the top of the screen and
shoot many bullets until “dead” or until the user is “dead”. Music and simple sound effects will play throughout the game.
Most of these different objects react while the game is progressing. We are using a framework called libGDX which handles 
things such as game sprites and music and positioning. The more we rely on this framework and collaborate as a team the
more enjoyable this final product can be. 

UML Doc 

