Everett Houston
Project: 'Tic Tac Toe' using React
'Weekend Project'



This game is held on a 3x3 board, the first move by default is 'X', upon clicking on the block your respective move will show and be saved to the state of that prop within the board. Being that if you place a 'X' in the upper right block, and then the next played selects the block beneath that with 'O' this will be saved to the state, until there is a winner which is acheived by lining three of your pieces, 'X' or 'O' or if the board fills up with no winner. 
A user is able to step through the moves as the game holds the history of all plays, however if you were to go back to step or move 2 from step 5 and then create a new move 3 then history of the board will change as you are playing new moves. 


Objective: Become more familiar with React & the syntax used. Subjects covered include elements,
components, props and state.


Components: Rather than separating technologies by putting markup and logic into separate files,
	    React loosely couples these units into components. For this project I had used Jsx 
	    which allowed React to show more useful warning and error messages.

	    Components are like Js functions, they accept arbitrary inputs ("props") and return
	    React elements describing what should appear on the screen. The simpliest way to 
	    define a component is to write a Js function.

Props:	    Are Read-Only


Elements:   React Elements are immutable, once created you are unable to change its children or
	    attributes. An element represents the UI at a certain point in time. The only way to
	    update the UI is to create a new element and pass it to ReactDom.render()
