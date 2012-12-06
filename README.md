TicTacToe
=========

While using the concepts of sockets, the traditional Tic Tac Toe game has been implemented. 

List of programs developed:
===========================

• Server.c – The server will ‘host’ the game. It will check the validity of the input and also will maintain the 
current playing board. It checks for the winner and notifies the players about the same with thier score. 
It keeps a handle tp read and write on the client side.

•	Client.c – There are two instances of client running, one entering ‘X’ and the other one ‘O’. The client receives
an array of the current playing board and then it is displayed to the player. 

Features of the code:
=====================

•	Two players play against each other hosted by the server.

•	The players are assigned a “X” and an “O” according to the order in which they join the game. 

•	One after another they will input positions where they want to place their assigned characters.

•	The server will keep checking the playing board and will declare a winner accordingly and the result will be displayed on the screens of both of the clients.
