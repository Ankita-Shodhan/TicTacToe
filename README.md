TicTacToe
=========

While using the concepts of sockets, the traditional Tic Tac Toe game has been implemented. 

List of programs developed:

•  Server.c – The server will ‘host’ the game. It will check the validity of the input and also will maintain the current playing board. It also checks for the winners and will send the signal and will handle reading and writing to the client.


•	Client.c – There will be two instances of client running, one entering ‘X’ and the other one ‘Y’. The client will receive the array of the current playing board and display it to the player. It also receives input from the users and will send it to the 

Features of the code:

•	Two players play against each other hosted by the client
•	The players are assigned a “X” and an “O” according to the order in which they join the game. 
•	One after another they will input positions where they want to place their assigned characters.
•	The server will keep checking the playing board and will declare a winner accordingly and the result will be displayed on the screens of both of the clients.
