# PenteMbed
A game of Pente coded in C that is displayed directly on the terminal and controlled using a FRDM-KL25Z

The system consists of a two-player game of pente based on UART communication between a FRDM-KL25Z and a PC terminal. 
The user interacts with the game using 3 push buttons and a proximity sensor. 
When the user grabs the proximity sensor the game starts.
The first push button works as an 'enter' key, while the other two are used to select the X and Y coordinates in which each player wishes to place their piece, respectively.
The coordenates can be visualized in 2 7-segment LED displays and the user must click the push button when the desired coordenate appears. While the display for the X coordinate is displaying the coordenates the other one is paused, and the same thing happens while the display for the Y coordinate is running. 
The sistems also contains a servo motor that indicates who´s turn it is between the two players. 
