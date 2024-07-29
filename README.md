# Dice-or-Die

Section 1 - Project Description

1.1 Project
Dice or Die

1.2 Description
Dice or Die is a mini-game in which the player must chop (click) on the correct fruit or vegetable before time runs out! The win/lose points depending on their speed and accuracy. This game is designed for English-learners as a way to improve the reaction-speed to food-related vocabulary. 
This mini-game takes place inside a larger application that I am developing, called “Anglophoria,” which is a site that offers a wide variety of mini-games for English-language learners. 

1.3 Revision History
Not applicable (nothing to revise yet)

	
		
Section 2 - Overview

2.1 Purpose
The intended audience is English-language learners. The initial version of Dice or Die that I am creating is specifically for low-level learners (A2). However, theoretically, the user should be able to change the difficulty of the game before playing, so it could also appeal to high-level learners (B2, C1, etc.). 

2.2 Scope
As mentioned earlier, this mini-game is just one part of a larger application called “Anglophoria,” a site for English-language leaners to practice their English skills (specifically for improving their speed and confidence through fun games, rather than really “teaching” them grammar rules, etc.). 

2.3 Requirements
For the purposes of this assignment, I want to ensure that the game has:
1.	Seamless gameplay, including flawless button controls (start game, replay, see instructions, etc.), accurate countdowns (60 seconds for the whole game, 5 seconds for each turn), and general functionality (clicking on the correct item earns points, clicking on the wrong item loses points, etc.)
2.	Visually appealing hand-drawn elements
   
2.3.1 Functional Requirements
•	R1: The game first allows the user to click “start game” or “instructions”
•	R2: clicking “instructions” opens up an appropriate description of the game, that the user can exit out of to return to the main start screen
•	R3: clicking “start game” correctly initializes the game
•	R4: the game has simple, intuitive UI, allowing a first-time player to start the game with no confusion. 
•	R5: There are three displays at the top of the screen: time remaining for the game (counting down from 60 seconds), time remaining in the turn (5 seconds), and total points earned
•	R6: There should be about 20 fruit and veggie icons displayed. 
•	R7: There should be a “chef” in the bottom right of the screen, who tells the user which fruit or veggie to click (either orally or just in a speech bubble)
•	R8: The basic game functionality should be flawless: clicking the correct fruit/veggie earns the user 10 points, and they move on immediately to the next turn; clicking the wrong fruit/veggie loses the user 5 points; if the user fails to pass the turn, there should be a “waiting time” of a few seconds before they can start the next turn
•	R9: This logic should be made clear to the user through intuitive visual elements (e.g. when points are lost, the points should turn red momentarily, as 5 points are subtracted; when the turn is lose, the turn countdown should also turn red, etc.)
•	R10: When the game is over (60 seconds have passed), the game should display some sort of message to the user, either congratulating them or not, and ask them if they want to play again.

2.3.2 Non-Functional Requirements
The game should only allow one user at a time. It should not crash or lag for any reason. It should run smoothly on any browser (hosted on github pages). 

2.3.3 Technical Requirements
Standard technical requirements (for a web app) apply. It should run flawlessly on any computer or laptop. My project is a web app (in javascript, html, css) so I don’t think there is no specific requirements for the hardware, etc.

2.3.4 Security Requirements
My app is a simple web app, so there are no specific security requirements. 

2.3.5 Estimates
It's hard for me to give estimated for each individual part of the game. My estimate for total completion of the game is 15 hours. If completed earlier, I might spend additional time implementing client-server architecture. 

2.3.6 Traceability Matrix
Omitted - I don't understand this part. 
	
	
Section 3 - System Architecture

Omitted - not relevant to my project.
